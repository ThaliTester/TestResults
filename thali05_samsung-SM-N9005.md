#### Test 50650278b28a87a_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  294): DCD ON
,D/AndroidRuntime( 6192): 
D/AndroidRuntime( 6192): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6192): CheckJNI is OFF
D/AndroidRuntime( 6192): readGMSProperty: start
D/AndroidRuntime( 6192): readGMSProperty: already setted!!
D/AndroidRuntime( 6192): readGMSProperty: end
D/AndroidRuntime( 6192): addProductProperty: start
E/AffinityControl( 6192): AffinityControl: registerfunction enter
D/AndroidRuntime( 6192): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  891): inState():  stateMachine is null !!
I/PersonaManagerService(  891): PersonaId don't exist
I/ActivityManager(  891): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  891): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  891): mDVFSHelper.acquire()
D/FocusedStackFrame(  891): Set to : 0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  891): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6208 uid=10273 gids={50273, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6192): Shutting down VM
E/Zygote  ( 6208): MountEmulatedStorage()
D/PointerIcon(  891): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  891): setMouseCustomIcon IconType is same.101
D/PointerIcon(  891): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  891): setHoveringSpenCustomIcon IconType is same.1
E/Zygote  ( 6208): v2
I/libpersona( 6208): KNOX_SDCARD checking this for 10273
I/libpersona( 6208): KNOX_SDCARD not a persona
I/SELinux ( 6208): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6208): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6208): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6208): TimaSignature is unavailable
D/ActivityThread( 6208): Added TimaKeyStore provider
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  891): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/SurfaceWidgetView( 1439): destroyHardwareResources():220442251
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6208): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1777): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1439): updateVisibility : ActivityRecord{2c99cbd0 token=android.os.BinderProxy@a4f7a45 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1439): onTrimMemory. Level: 20
,I/WebViewFactory( 6208): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6208): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6208): Loading: webviewchromium
,I/LibraryLoader( 6208): Time to load native libraries: 5 ms (timestamps 6027-6032)
I/LibraryLoader( 6208): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6208): Binding Chromium to main looper Looper (main, tid 1) {1be13402}
,I/LibraryLoader( 6208): Expected native library version number "",actual native library version number ""
,I/chromium( 6208): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6208): Initializing chromium process, renderers=0
,W/art     ( 6208): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6208): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6208): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6208): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
,I/chromium( 6208): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,D/BluetoothAdapter( 6208): 944238867: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6208): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6208): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6208): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6208): Local Branch: mybranch5813579
I/Adreno-EGL( 6208): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6208): Local Patches: NONE
I/Adreno-EGL( 6208): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): stay LED for fully charged
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,W/chromium( 6208): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/ActivityManager(  891): Activity pause timeout for ActivityRecord{26148db8 u0 com.test.thalitest/.MainActivity t3}
,W/chromium( 6208): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6208): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6208): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6208): CordovaWebView is running on device made by: samsung
,W/art     ( 6208): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6208): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 6208): performCreate Call secproduct feature valuefalse
D/Activity( 6208): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6208): Render dirty regions requested: true
,D/Atlas   ( 6208): Validating map...
,D/ActivityManager(  891): post active user change for 0
,D/KnoxTimeoutHandler(  891): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  891): handleActiveUserChange for user 0
,V/ActivityThread( 6208): updateVisibility : ActivityRecord{3fe97c80 token=android.os.BinderProxy@2492a1b2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  891): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  891): setMouseCustomIcon IconType is same.101
D/PointerIcon(  891): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  891): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6208): Initialized EGL, version 1.4
,I/OpenGLRenderer( 6208): HWUI protection enabled for context ,  &this =0xafb76038 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6208): Enabling debug mode 0
,D/InputMethodManagerService(  891): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  891): mDVFSHelper.release()
I/Timeline(  891): Timeline: Activity_windows_visible id: ActivityRecord{26148db8 u0 com.test.thalitest/.MainActivity t3} time:156618
,I/art     (  891): Explicit concurrent mark sweep GC freed 242500(16MB) AllocSpace objects, 30(4MB) LOS objects, 17% free, 37MB/45MB, paused 1.751ms total 155.273ms
,W/IInputConnectionWrapper( 6208): showStatusIcon on inactive InputConnection
,I/Timeline( 6208): Timeline: Activity_idle id: android.os.BinderProxy@2492a1b2 time:156767
,I/SamsungIME( 1721): getCurrentCandidateView
,D/SamsungIME( 1721): Dismiss ExpandCandiate
,I/chromium( 6208): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6208): 
,D/JsMessageQueue( 6208): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1721): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1721): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1721): KeybaordView init() : load resources
,D/jxcore_app_log( 6208): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1360967808
D/JX-Cordova( 6208): jxcore cordova android initializing
,I/SamsungIME( 1721): getCurrentKeyboard
I/SamsungIME( 1721): getTextKeyboard
,D/SamsungIME( 1721): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/SamsungIME( 1721): [SwiftkeyWrapper] currentLangauge : 1701729619
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/jxcore-log( 6208): Initializing JXcore engine
,W/jxcore-log( 6208): JXcore engine is ready
,W/jxcore-log( 6208): Starting JXcore engine
,E/auditd  ( 1811): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  891): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  891): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6283): MountEmulatedStorage()
,E/Zygote  ( 6283): v2
I/libpersona( 6283): KNOX_SDCARD checking this for 1000
I/libpersona( 6283): KNOX_SDCARD not a persona
I/ActivityManager(  891): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6283 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  330): Explicit concurrent mark sweep GC freed 8764(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 295us total 18.604ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 266us total 9.384ms
,I/SELinux ( 6283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6283): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 265us total 9.565ms
,D/TimaKeyStoreProvider( 6283): TimaSignature is unavailable
,D/ActivityThread( 6283): Added TimaKeyStore provider
,D/ResourcesManager( 6283): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 6208): Platform android
W/jxcore-log( 6208): 
,W/jxcore-log( 6208): Process ARCH arm
W/jxcore-log( 6208): 
,D/SecurityLogAgent( 6283):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6283):  SeDenialReceiver : File path = null
I/ActivityManager(  891): Killing 5279:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/jxcore-log( 6208): JXcore Cordova bridge is ready!
I/jxcore-log( 6208): 
,W/jxcore-log( 6208): JXcore engine is started
,D/SSRM:n  (  891): SIOP:: AP = 330, PST = 326, CUR = 450
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/jxcore-log( 6208): Toggling radios to true
I/jxcore-log( 6208): 
,D/BluetoothAdapter( 6208): enable()
,W/ActivityManager(  891): Permission Denial: getCurrentUser() from pid=6208, uid=10273 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  891): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  891): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6208, uid=10273 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  891): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/BluetoothManagerService(  891): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2141)
W/BluetoothManagerService(  891): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService(  891): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  891): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService(  891): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  891): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider(  891): name = bluetooth_on
,E/DevicePolicyManagerService(  891): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  891): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,I/WifiManager( 6208): packageName : com.test.thalitest
,D/SecContentProvider(  891): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  891): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  891): mCursor = null
,D/WifiService(  891): setWifiEnabled: true pid=6208, uid=10273
W/ActivityManager(  891): Permission Denial: getCurrentUser() from pid=6208, uid=10273 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  891): Failed getting userId using ActivityManagerNative
W/WifiService(  891): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6208, uid=10273 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  891): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  891): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  891): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  891): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  891): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  891): name = wifi_on
,I/WifiService(  891): disconnect: pid=6208, uid=10273
,I/jxcore-log( 6208): Radios toggled
I/jxcore-log( 6208): 
,E/WifiHW  (  891): ##################### set firmware type 0 #####################
,I/WifiHW  (  288): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,I/WifiHW  (  288): module is semco
E/WifiHW  (  288): ==========[WIFI] SEMCO MODULE ===========
I/WifiHW  (  288): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  (  288): TEMP_FAILURE_RETRY complete
D/SoftapController(  288): Softap fwReload - Ok
,D/CommandListener(  288): Setting iface cfg
D/CommandListener(  288): Trying to bring down wlan0
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,E/WifiHW  (  891): supplicant_name : p2p_supplicant
,E/Zygote  ( 6310): MountEmulatedStorage()
,E/Zygote  ( 6310): v2
I/libpersona( 6310): KNOX_SDCARD checking this for 1002
I/libpersona( 6310): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6310 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 6208): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 6208): 
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
D/WifiMonitor(  891): startMonitoring(wlan0) with mConnected = false
,I/jxcore-log( 6208): Perf Test app loaded loaded
I/jxcore-log( 6208): 
,I/jxcore-log( 6208): check test folder
I/jxcore-log( 6208): 
,E/Zygote  ( 6316): MountEmulatedStorage()
E/Zygote  ( 6316): v2
I/libpersona( 6316): KNOX_SDCARD checking this for 10152
I/libpersona( 6316): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6316 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 6310): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6310): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6310): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/HotspotTile( 1182): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1182): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-WifiQuickSettingButton( 1182): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1182): Wifi onReceive(2)
,D/STATUSBAR-QSTileView( 1182): onStateChanged: Wi-Fi
,I/wpa_supplicant( 6309): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6309): Successfully initialized wpa_supplicant
,D/SmartBondingService(  891): getNetworkEnabled : wifi : false mobile : true
,I/SecureStorage( 6309): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6309): [INFO]: SPID(0x00000000)This device supports Secure Storage
,D/WifiCredService( 1303): Action received :android.net.wifi.WIFI_STATE_CHANGED
,I/jxcore-log( 6208): found test : ./testFindPeers.js
I/jxcore-log( 6208): 
,I/SecureStorage(  424): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6309
I/SecureStorage(  424): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 6309): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6309): ssSupport state is = 1
,I/wpa_supplicant( 6309): >>>>> GET KEY, IV <<<<<
,I/SecureStorage( 6309): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  424): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6309
I/SecureStorage(  424): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,I/SELinux ( 6316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/HotspotTile( 1182): onReceive : 2, 0
,E/SELinux ( 6316): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6316): TimaSignature is unavailable
I/jxcore-log( 6208): found test : ./testSendData.js
I/jxcore-log( 6208): 
,D/ActivityThread( 6316): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6310): TimaSignature is unavailable
,D/ActivityThread( 6310): Added TimaKeyStore provider
,D/ResourcesManager( 6310): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager( 6310): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6310): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 6316): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,I/BluetoothA2dpSinkServiceJni( 6310): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 6310): Adding GattService
,D/BtSettings.ProfileConfig( 6310): Adding HeadsetService
D/BtSettings.ProfileConfig( 6310): Adding A2dpService
D/BtSettings.ProfileConfig( 6310): Adding HidService
D/BtSettings.ProfileConfig( 6310): Adding HealthService
,D/BtSettings.ProfileConfig( 6310): Adding PanService
D/BtSettings.ProfileConfig( 6310): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 6310): Adding SapService
D/BtSettings.ProfileConfig( 6310): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 6310): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 6310): Adding SapClientService
D/BtSettings.ProfileConfig( 6310): Adding HidDevService
I/BtSettings.ProfileConfig( 6310): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider(  891): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,I/Choreographer( 6208): Skipped 76 frames!  The application may be doing too much work on its main thread.
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  891): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  891): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  891): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/chromium( 6208): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/SettingsProvider(  891): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  891): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/chromium( 6208): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SettingsProvider(  891): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
,D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  891): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  891): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  891): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  891): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  891): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/WebViewFactory( 6316): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6316): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6316): Loading: webviewchromium
,I/LibraryLoader( 6316): Time to load native libraries: 7 ms (timestamps 810-817)
,I/LibraryLoader( 6316): Expected native library version number "",actual native library version number ""
,D/BluetoothAdapterState( 6310): make
,I/bluedroid( 6310): init
,I/BluetoothAdapterState( 6310): Entering OffState
,I/bte_conf( 6310): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6310): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6310): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6310): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 6310): btif_fetch_local_ble_random_bdaddr
I/bluedroid( 6310): get_profile_interface socket
I/bluedroid( 6310): get_profile_interface map_client
I/GKI_LINUX( 6310): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterService( 6310): checkAddrForIOP: Loading from conf
,D/BluetoothAdapterProperties( 6310): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6310): populateRssiValuesNative
I/bluedroid( 6310): getModelRssiValues
E/BluetoothServiceJni( 6310): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/BluetoothAdapterProperties( 6310): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6310): Name is: Note3-1
D/SettingsProvider(  891): name = bluetooth_name
,I/bluedroid( 6310): config_hci_snoop_log
,D/BluetoothManagerService(  891): Broadcasting onBluetoothServiceUp() to 11 receivers.
,E/DevicePolicyManagerService(  891): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService(  891): getAllowBluetoothMode - value retunrs : 2
V/WebViewChromiumFactoryProvider( 6316): Binding Chromium to main looper Looper (main, tid 1) {29c79f50}
I/LibraryLoader( 6316): Expected native library version number "",actual native library version number ""
D/SecContentProvider(  891): uri = 3 selection = isBluetoothEnabled
I/chromium( 6316): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/BluetoothAdapterState( 6310): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties( 6310): Setting state to 11
I/BluetoothAdapterState( 6310): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 6310): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6310): updateAdapterState state is 11
D/BluetoothAdapterService( 6310): Autoconnection is available 
D/BluetoothAdapterService( 6310): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 6310): getInstant: null
,D/BluetoothSecureManager( 6310): calling getMethod for getService
D/BluetoothSecureManager( 6310): calling getService
,D/BluetoothSecureManager( 6310): getService return binder: android.os.BinderProxy@33ca6f8b
D/BluetoothSecureManagerService(  891): isSecureModeEnabled
D/BluetoothSecureManagerService(  891): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 6310): isSecureModeOn:false
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/InputMethodManagerService(  891): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
W/BluetoothAdapterService( 6310): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
I/InputMethodManagerService(  891): [BT Setting State] State =11
W/BluetoothAdapterService( 6310): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 6310): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6310): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6310): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6310): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothTile( 1182):  onBluetoothPairedDevicesChanged:
W/BluetoothAdapterService( 6310): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6310): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BluetoothTile( 1182): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6310): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6310): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6310): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
I/SamsungIME( 1721): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService( 6310): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 6310): make
,D/StatusBarManagerService(  891): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,W/BluetoothAdapterService( 6310): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6310): Not skipping com.android.bluetooth.gatt.GattService
D/StatusBarManagerService(  891): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 1182): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/STATUSBAR-QSTileView( 1182): onStateChanged: Bluetooth
,D/PhoneStatusBar( 1182): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
W/BluetoothAdapterService( 6310): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6310): Not skipping com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6310): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 6310): Not skipping com.android.bluetooth.a2dp.A2dpService
,I/BluetoothBondStateMachine( 6310): StableState(): Entering Off State
,I/BtGatt.JNI( 6310): classInitNative(L890): classInitNative: Success!
W/BluetoothAdapterService( 6310): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6310): Not skipping com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6310): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6310): Not skipping com.android.bluetooth.hdp.HealthService
D/BtGatt.DebugUtils( 6310): handleDebugAction() action=null
D/BtGatt.GattService( 6310): Received start request. Starting profile...
D/BtGatt.GattService( 6310): start()
I/bluedroid( 6310): get_profile_interface gatt
D/BluetoothAdapterService( 6310): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3847f113
D/BtGatt.AdvertiseManager( 6310): advertise manager created
I/SecureStorage(  424): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
W/BluetoothAdapterService( 6310): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6310): Not skipping com.android.bluetooth.pan.PanService
I/BrowserStartupController( 6316): Initializing chromium process, renderers=0
W/BluetoothAdapterService( 6310): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6310): Not skipping com.android.bluetooth.map.BluetoothMapService
W/art     ( 6316): Attempt to remove local handle scope entry from IRT, ignoring
W/BluetoothAdapterService( 6310): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6310): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 6310): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3847f113
W/BluetoothAdapterService( 6310): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6310): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6310): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6310): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6310): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6310): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6310): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 6310): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6310): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 6310): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetService( 6310): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 6310): classInitNative: succeeds
D/HeadsetStateMachine( 6310): make
W/chromium( 6316): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
E/HeadsetStateMachine( 6310): # of Max HF connection is 2
W/chromium( 6316): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6316): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46780 len=2953
I/chromium( 6316): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229536 len:643667
I/bluedroid( 6310): get_profile_interface handsfree
I/DualScoManager( 6310): Instantiating Dual Sco Manager
I/DualScoManager( 6310): Set HeadsetServiceHelper
D/BluetoothAtMessage( 6310): createCMTIContentObservers
,D/SettingsProvider(  891): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 6310): Enter Disconnected: -2
,D/BluetoothAdapterService( 6310): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3847f113
E/HeadsetStateMachine( 6310): set to mRemoteBrsf = 0
D/BluetoothA2dp(  891): Proxy object connected
D/HeadsetStateMachine( 6310): map size, before remove : 0
D/HeadsetStateMachine( 6310): map size, after remove: 0
D/HeadsetStateMachine( 6310): mNextConnectingDevice : null
D/A2dpService( 6310): Received start request. Starting profile...
D/BluetoothA2dp( 2950): Proxy object connected
I/BluetoothAvrcpServiceJni( 6310): classInitNative: succeeds
V/Avrcp   ( 6310): make
V/Avrcp   ( 6310): Avrcp
I/bluedroid( 6310): get_profile_interface avrcp
,V/Avrcp   ( 6310): start
,I/Adreno-EGL( 6316): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6316): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6316): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6316): Local Branch: mybranch5813579
I/Adreno-EGL( 6316): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6316): Local Patches: NONE
I/Adreno-EGL( 6316): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,E/RemoteController( 6310): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   ( 6310): ++registerMediaPlayers++
,I/Avrcp   ( 6310): No of Audio players :: 2
I/Avrcp   ( 6310): App Package name is com.google.android.music
,D/ResourcesManager( 6310): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   ( 6310): App pkg name is Google Play Music
,I/Avrcp   ( 6310): Name::Google Play Music
V/Avrcp   ( 6310): MediaPlayerInfo: mPlayerId=1
I/Avrcp   ( 6310): App Package name is com.sec.android.app.music
,D/ResourcesManager( 6310): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   ( 6310): App pkg name is Music
I/Avrcp   ( 6310): Name::Music
V/Avrcp   ( 6310): MediaPlayerInfo: mPlayerId=2
I/Avrcp   ( 6310):  set player publishabilty with player id::2 toBePublished ::true
I/Avrcp   ( 6310): No of Video players :: 1
I/Avrcp   ( 6310): Video App Package name is com.sec.android.app.videoplayer
D/ResourcesManager( 6310): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/Avrcp   ( 6310): Video App pkg name is Video Player
I/Avrcp   ( 6310): Name::Video Player
V/Avrcp   ( 6310): MediaPlayerInfo: mPlayerId=3
I/Avrcp   ( 6310): Add tempPlayer
V/Avrcp   ( 6310): MediaPlayerInfo: mPlayerId=4
I/Avrcp   ( 6310): Total no of players: 4
V/Avrcp   ( 6310): swapping the samsung player with 1st player
I/Avrcp   ( 6310):  Updating now playing list upon AVRCP Start
V/Avrcp   ( 6310): handleMessage, msg=207
,D/BluetoothMediaBrowser( 6310):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
I/BluetoothA2dpServiceJni( 6310): classInitNative: succeeds
D/A2dpStateMachine( 6310): make
,I/bluedroid( 6310): get_profile_interface a2dp
,I/GKI_LINUX( 6310): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 6310): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService( 6310): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3847f113
,I/BluetoothHidServiceJni( 6310): classInitNative: succeeds
,D/A2dpStateMachine( 6310): Enter Disconnected: -2
,D/HidService( 6310): Received start request. Starting profile...
,I/bluedroid( 6310): get_profile_interface hidhost
D/HidService( 6310): setHidService(): set to: null
D/BluetoothAdapterService( 6310): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3847f113
,I/BluetoothHealthServiceJni( 6310): classInitNative: succeeds
D/BluetoothMediaBrowser( 6310): no now playing list
D/BluetoothMediaBrowser( 6310):  getNowPlayingId now playing id : -1
D/Avrcp   ( 6310):  checkNowPlayingList start
,D/HealthService( 6310): Received start request. Starting profile...
,I/bluedroid( 6310): get_profile_interface health
,D/BluetoothAdapterService( 6310): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3847f113
,I/BluetoothPanServiceJni( 6310): classInitNative(L105): succeeds
,D/BluetoothPan(  891): BluetoothPAN Proxy object connected
,D/PanService( 6310): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6310): initializeNative(L110): pan
I/bluedroid( 6310): get_profile_interface pan
,D/BluetoothAdapterService( 6310): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3847f113
,D/BluetoothMapService( 6310): Received start request. Starting profile...
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6384): MountEmulatedStorage()
E/Zygote  ( 6384): v2
I/libpersona( 6384): KNOX_SDCARD checking this for 10186
I/libpersona( 6384): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6384 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6384): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6384): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6384): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6384): TimaSignature is unavailable
,D/ActivityThread( 6384): Added TimaKeyStore provider
,W/chromium( 6316): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6316): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/ResourcesManager( 6384): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 6384): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6384): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6384): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6384): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6384): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/art     ( 6316): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6316): onDetachedFromWindow called when already detached. Ignoring
,I/SecureStorage( 6309): [INFO]: SPID(0x00000000)Processing data has been completed
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,I/SecureStorage( 6309): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 6309): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  424): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6309
I/SecureStorage(  424): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6309): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6309): ssSupport state is = 1
I/wpa_supplicant( 6309): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 6309): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6309): SIM READ ERROR
I/wpa_supplicant( 6309): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6309): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6309): SIM READ ERROR
I/wpa_supplicant( 6309): Blacklist: Clear (all) 
,I/wpa_supplicant( 6309): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6309): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 6309): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6309): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 6309): rfkill: Cannot open RFKILL control device
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/BluetoothAdapterService( 6310): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3847f113
,E/BluetoothAdapterService(944238867)( 6310): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,I/BluetoothSAPServiceJni( 6310): classInitNative(L204): succeeds
,D/SapService( 6310): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 6310): initializeNative(L209): sap
I/bluedroid( 6310): get_profile_interface sap
D/BluetoothAdapterService( 6310): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3847f113
,D/HeadsetStateMachine( 6310): Try to query the phonestate on bind
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,I/Telecom ( 1395): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1395): BluetoothPhoneService: updateHeadsetWithCallState
,E/SMD     (  294): DCD ON
,I/Telecom ( 1395): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1395): Proxy not attached to service
,D/HeadsetStateMachine( 6310): Proxy object connected
D/HeadsetPhoneState( 6310): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 6310): sendDeviceDataStateChanged
D/HeadsetPhoneState( 6310): Signal level : previous=0 curr=0
E/BluetoothAdapterService(944238867)( 6310): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 6310): Proxy object connected
D/BluetoothAdapterService( 6310): Bluetooth A2dp source service connected
E/BluetoothAdapterService(944238867)( 6310): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(944238867)( 6310): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,D/HeadsetStateMachine( 6310): Disconnected process message: 11
D/HeadsetStateMachine( 6310): Disconnected process message: 18
D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/HeadsetPhoneState( 6310): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6310): Disconnected process message: 11
,E/Zygote  ( 6414): MountEmulatedStorage()
I/libpersona( 6414): KNOX_SDCARD checking this for 10092
E/Zygote  ( 6414): v2
I/libpersona( 6414): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6414 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,I/SELinux ( 6414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/RCPManagerService(  891): exchangeData() failure , invalid userId
,E/BluetoothAdapterService(944238867)( 6310): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(944238867)( 6310): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
I/SELinux ( 6414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6414): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/lowmemorykiller(  251): Error writing /proc/4454/oom_score_adj; errno=22
I/ActivityManager(  891): Killing 4454:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,E/BluetoothAdapterService(944238867)( 6310): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(944238867)( 6310): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/BluetoothAdapterState( 6310): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 6310): enable
,I/bt_hci_bdroid( 6310): init
,I/GKI_LINUX( 6310): gki_task_entry task_id=0 [BTU] starting
,E/SignOutReceiver( 4305): WIFI_STATE_CHANGED_ACTION
,I/bt_vendor( 6310): init
,I/bt_vnd_conf( 6310): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6310): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6310): userial_init
D/bt_vendor( 6310): op for 5
,D/bt_vendor( 6310): op for 0
,D/bt_upio ( 6310): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6310): is_emulator_context : 0
,D/bt_upio ( 6310): is_rfkill_disabled ? [0]
D/bt_upio ( 6310): is_rfkill_disabled ? [0]
,D/bt_vendor( 6310): op for 0
,D/bt_upio ( 6310): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6310): is_emulator_context : 0
D/bt_upio ( 6310): is_rfkill_disabled ? [0]
,D/bt_vendor( 6310): op for 3
I/bt_userial_vendor( 6310): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 6310): userial_vendor_open():UART is setup
I/bt_userial_vendor( 6310): device fd = 65 open
D/bt_vendor( 6310): op for 1
E/bt_hwcfg( 6310): Start CFG HW, HCI reset
,D/bt_userial( 6310): Entering userial_read_thread()
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6283): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6283): KnoxConfiguration : Current State Mapping Found 
D/TimaKeyStoreProvider( 6414): TimaSignature is unavailable
D/SecurityLogAgent( 6283): StateMachine : Current State = 1
,D/ActivityThread( 6414): Added TimaKeyStore provider
,D/SecurityLogAgent( 6283): StateMachine : Changed Current State = 1
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,I/ActivityManager(  891): Killing 5110:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,I/ActivityManager(  891): Killing 5377:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,D/ResourcesManager( 6414): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider( 6414): onCreate
D/BadgeProvider( 6414): DatabaseHelper
,E/bt_hwcfg( 6310): Read Local Name after HCI reset
,D/BluetoothNotiBroadcastReceiver( 1303): onReceive
,D/bt_hwcfg( 6310): Chipset BCM4335C0
D/bt_hwcfg( 6310): Target name = [BCM4335C0]
,I/bt_hwcfg( 6310): module_type[semco].
I/bt_hwcfg( 6310): not ZERO...
I/bt_hwcfg( 6310): module_type[semco] is invalid.
E/bt_hwcfg( 6310): patchram path ORG . BCM4335C0
E/bt_hwcfg( 6310): patchram path ORG .. BCM4335C0
E/bt_hwcfg( 6310): patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
E/bt_hwcfg( 6310): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6310): patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
E/bt_hwcfg( 6310): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6310): patchram path ORG bcm4335_V0093.0399.hcd BCM4335C0
E/bt_hwcfg( 6310): patchram path ORG bcm4335_V0093.0399_wisol.hcd BCM4335C0
E/bt_hwcfg( 6310): fw ver (org)0.0
E/bt_hwcfg( 6310): vendor lib preload failed to locate firmware patch file
E/bt_hwcfg( 6310): Remove module rev, try again BCM4335
D/bt_hwcfg( 6310): Target name = [BCM4335]
I/bt_hwcfg( 6310): module_type[semco].
I/bt_hwcfg( 6310): not ZERO...
I/bt_hwcfg( 6310): module_type[semco] is invalid.
E/bt_hwcfg( 6310): patchram path ORG . BCM4335
E/bt_hwcfg( 6310): patchram path ORG .. BCM4335
E/bt_hwcfg( 6310): patchram path ORG bcm2079xB4_firmware.ncd BCM4335
E/bt_hwcfg( 6310): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6310): patchram path ORG bcm2079xB5_firmware.ncd BCM4335
E/bt_hwcfg( 6310): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6310): patchram path ORG bcm4335_V0093.0399.hcd BCM4335
I/bt_hwcfg( 6310): patch(org) : bcm4335_V0093.0399.hcd
I/bt_hwcfg( 6310): Found patchfile: /vendor/firmware/bcm4335_V0093.0399.hcd
E/bt_hwcfg( 6310): ORG patchram base 0093
E/bt_hwcfg( 6310): ORG patchram minor 0399
E/bt_hwcfg( 6310): fw ver (org)93.399
E/bt_hwcfg( 6310): Final Patchram is /vendor/firmware/bcm4335_V0093.0399.hcd
,I/bt_hwcfg( 6310): Axi patch failure or not include AXI patching
I/bt_hwcfg( 6310): bt vendor lib: set UART baud 3000000
D/BadgeProvider( 6414): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/AuthorizationBluetoothService( 1572): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BadgeProvider( 6414): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6414): sendNotify, [notify] : null
,D/BadgeProvider( 6414): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6414): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6414): update, [UpdateCount] : 1
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/Launcher.Model( 1439): reloadBadges entered.
,W/ActivityManager(  891): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/bt_hwcfg( 6310): bt vendor lib: set UART baud 115200
,I/bt_hwcfg( 6310): FW Download delta = 543364
D/bt_hwcfg( 6310): Settlement delay -- 100 ms
I/bt_hwcfg( 6310): Setting fw settlement delay to 100 
,E/Tethering(  891): No numeric data
,D/Tethering(  891): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  891): forceRefresh() from cache miss
,D/HotspotTile( 1182): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1182): updateTetherState():false, false
,D/NtpTrustedTime(  891): forceRefresh Fail.
,V/NetworkStats(  891): performPollLocked(flags=0x1)
,I/wpa_supplicant( 6309): wlan0: Setting scan request: 0 sec 100000 usec
D/NetworkStatsFactory(  891): UpdateStatsForKnox
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  891): performPollLocked() took 11ms
,D/NtpTrustedTime(  891): forceRefresh() from cache miss
,D/NtpTrustedTime(  891): forceRefresh Fail.
,I/wpa_supplicant( 6309): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 6309): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6309): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  424): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6309
I/SecureStorage(  424): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6309): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6309): ssSupport state is = 1
,I/SecureStorage( 6309): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6309): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  424): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6309
I/SecureStorage(  424): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6309): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6309): ssSupport state is = 1
I/wpa_supplicant( 6309): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6309): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6309): SIM READ ERROR
I/wpa_supplicant( 6309): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 6309): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 6309): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/bt_hwcfg( 6310): bt vendor lib: set UART baud 3000000
,I/wpa_supplicant( 6309): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 6309): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  891): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-HAL(  891): callSECApiBoolean - ID [21]
I/wpa_supplicant( 6309): HOTSPOT20_ENABLE called
I/wpa_supplicant( 6309): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6309): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6309): SIM READ ERROR
I/wpa_supplicant( 6309): Blacklist: Clear (all) 
,I/bt_hwcfg( 6310): vendor lib fwcfg completed
,I/wpa_supplicant( 6309): Skip scan - bUseNetwork false
,I/        ( 6310): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6310): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6310): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6310): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6310): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6310): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6310): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6310): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6310): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6310): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6310): BTE_InitTraceLevels -- TRC_SAP
I/        ( 6310): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6310): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6310): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6310): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6310): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 6310): BTE_InitTraceLevels -- TRC_PROTOCOL
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1182): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1182): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 1182): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1182): Wifi onReceive(3)
D/HotspotTile( 1182): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1182): onStateChanged: Wi-Fi
,D/HotspotTile( 1182): onReceive : 3, 0
,D/WifiCredService( 1303): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/WifiNative-HAL(  891): callSECApiInt - ID [210]
,D/SmartBondingService(  891): getNetworkEnabled : wifi : true mobile : true
,D/WifiConfigStore(  891): Loading config and enabling all networks 
,E/SignOutReceiver( 4305): WIFI_STATE_CHANGED_ACTION
,E/WifiConfigStore(  891): Not a HS20
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6283): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6283): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6283): StateMachine : Current State = 1
D/SecurityLogAgent( 6283): StateMachine : Changed Current State = 1
,E/WifiConfigStore(  891): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  891): callSECApiInt - ID [65]
,D/WifiNative-HAL(  891): callSECApiBoolean - ID [13]
I/wpa_supplicant( 6309): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6309): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6309): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6309): P2P: Current p2p state = IDLE
I/wpa_supplicant( 6309): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 6309): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6309): First Scan Start
,I/wpa_supplicant( 6309): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL(  891): Setting external_sim to 1
D/WifiStateMachine(  891): Setting OUI to DA-A1-19
I/WifiNative-HAL(  891): startHal
E/wifi    (  891): getStaticLongField sWifiHalHandle 0x9bdec86c
,D/wifi    (  891): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x402202
I/WifiNative-HAL(  891): Could not start hal
,E/native  (  891): do suspend true
,E/WifiStateMachine(  891): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiP2pService(  891): P2pDisabledState{ what=131203 }
,D/WifiScanningService(  891): SCAN_AVAILABLE : 3
D/RttService(  891): SCAN_AVAILABLE : 3
D/WifiScanningService(  891): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  891): startHal
E/wifi    (  891): getStaticLongField sWifiHalHandle 0x94aff99c
D/wifi    (  891): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x102206
I/WifiNative-HAL(  891): Could not start hal
E/WifiScanningService(  891): could not start HAL
,D/CommandListener(  288): Setting iface cfg
D/CommandListener(  288): Trying to bring up p2p0
D/RttService(  891): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  891): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService(  891): P2pEnablingState
D/WifiP2pService(  891): P2pEnablingState{ what=147457 }
D/WifiP2pService(  891): P2p socket connection successful
,D/WifiP2pService(  891): P2pEnabledState
E/WifiStateMachine(  891): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiDisplayController(  891): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  891): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiNative-HAL(  891): callSECStringApiVoid - ID [215]
D/WifiDisplayController(  891): disconnect
E/WifiNative-HAL(  891): invaild command id : 215
D/WifiDisplayController(  891): updateConnection
D/WifiDisplayController(  891): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  891): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService(  891): sending p2p connection changed broadcast: IDLE
,E/WifiStateMachine(  891): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 6309): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/Zygote  ( 6445): MountEmulatedStorage()
E/Zygote  ( 6445): v2
I/libpersona( 6445): KNOX_SDCARD checking this for 10192
I/libpersona( 6445): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6445 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayController(  891): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiP2pService(  891): create mNetworkAgent
,I/SELinux ( 6445): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/AllShareCastTile( 1182): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter(  891): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1182): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
I/SELinux ( 6445): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6445): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 6309): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/ConnectivityService(  891): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  891): Got NetworkAgent Messenger
D/ConnectivityService(  891): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService(  891): updateNetworkInfo()
D/ConnectivityService(  891): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891): NetworkAgent connected
,E/CSLegacyTypeTracker(  891): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,D/WifiNative-HAL(  891): p2pGetDeviceAddress
,D/WifiNative-HAL(  891): p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,D/WifiDisplayController(  891): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
D/WifiDisplayController(  891):  deviceAddress: ea:50:8b:de:28:a3
D/WifiDisplayController(  891):  primary type: 10-0050F204-5
D/WifiDisplayController(  891):  secondary type: null
D/WifiDisplayController(  891):  wps: 0
D/WifiDisplayController(  891):  grpcapab: 0
D/WifiDisplayController(  891):  devcapab: 0
D/WifiDisplayController(  891):  status: 3
D/WifiDisplayController(  891):  wfdInfo: null
D/WifiDisplayController(  891):  groupownerAddress: null
D/WifiDisplayController(  891):  GOdeviceName: null
D/WifiDisplayController(  891):  interfaceAddress: 
D/WifiDisplayController(  891):  SConnectInfo : null
,D/WifiP2pService(  891): DeviceAddress: ea:28:a3
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  891): mCursor = null
,D/WifiP2pService(  891): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  891): InactiveState
D/WifiP2pService(  891): InactiveState{ what=143376 }
D/WifiP2pService(  891): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 6309): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService(  891): updateNetworkInfo()
,D/WifiP2pService(  891): InactiveState{ what=143376 }
D/WifiP2pService(  891): P2pEnabledState{ what=143376 }
D/ConnectivityService(  891): ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
D/TimaKeyStoreProvider( 6445): TimaSignature is unavailable
,D/ActivityThread( 6445): Added TimaKeyStore provider
,D/ResourcesManager( 6445): creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,D/WifiDirectBR( 6445): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager(  891): Killing 5397:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6461): MountEmulatedStorage()
E/Zygote  ( 6461): v2
I/libpersona( 6461): KNOX_SDCARD checking this for 10088
I/libpersona( 6461): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6461 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6461): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,W/bt-l2cap( 6310): l2c_link_processs_ble_num_bufs 15
,I/SELinux ( 6461): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6461): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/bt-btm  ( 6310): BTM_SecRegister:p_cb_info->p_le_callback == 0xb3a42b05 
E/bt-btm  ( 6310): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb3a42b05 
,D/TimaKeyStoreProvider( 6461): TimaSignature is unavailable
,D/ActivityThread( 6461): Added TimaKeyStore provider
,D/ResourcesManager( 6461): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server( 6461): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/WifiDirectBR( 6445): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 6445): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 6445): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/WifiDirectBR( 6445): stopServiceTest : false
,I/ActivityManager(  891): Killing 5454:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BluetoothAdapterProperties( 6310): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 0 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,E/bt-btif ( 6310): BTM_SEC_REG[4]: id 3
,E/bt-btif ( 6310): BTM_SEC_REG[6Register() called for PSM: 0x001b
,D/BluetoothAdapterProperties( 6310): Address is:E0:DB:10:1F:C9:5E
,E/BluetoothServiceJni( 6310): populateRssiValuesNative
I/bluedroid( 6310): getModelRssiValues
,E/BluetoothServiceJni( 6310): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6310): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6310): Name is: Note3-1
D/SettingsProvider(  891): name = bluetooth_name
,D/BluetoothAdapterProperties( 6310): Scan Mode:20
,D/BluetoothAdapterProperties( 6310): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 6310): LE Address is:E0:B7:20:3E:93:BC
,D/bt_vendor( 6310): op for 2
E/bt-btif ( 6310): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
D/bt_vendor( 6310): op for 6
,E/bt-btif ( 6310): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 6310): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 6310): btif_sock_init: !vhci_init
,D/IOP_DB_BT( 6310): db_open: file /etc/bluetooth/iop_bt.db
,D/bt_vendor( 6310): op for 7
,D/bt_upio ( 6310): proc btwrite assertion
,D/IOP_DB_BT( 6310): db_open: db_open : handle 3025575952l, read 14063 bytes onto local cache
D/IOP_DB_BT( 6310): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 6310): db_query: result 1
I/        ( 6310): iop_db_open: iop_db_open status 0
D/bte_conf( 6310): Device ID record 1 : primary
D/bte_conf( 6310):   vendorId            = 0075
D/bte_conf( 6310):   vendorIdSource      = 0001
D/bte_conf( 6310):   product             = 0100
D/bte_conf( 6310):   version             = 0200
D/bte_conf( 6310):   clientExecutableURL = 
D/bte_conf( 6310):   serviceDescription  = 
D/bte_conf( 6310):   documentationURL    = 
D/bte_conf( 6310): bte_load_did_conf no section named DID2.
D/bt_vendor( 6310): op for 7
D/BluetoothAdapterState( 6310): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6310): ScanMode =  20
D/BluetoothAdapterProperties( 6310): State =  11
D/BluetoothPanServiceJni( 6310): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/bt_upio ( 6310): BT_WAKE is asserted already
D/SecContentProvider(  891): uri = 3 selection = isDiscoverableEnabled
D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
D/BluetoothAdapterProperties( 6310): Scan Mode:21
D/BluetoothAdapterProperties( 6310): Discoverable Timeout:120
D/BluetoothAdapterProperties( 6310): Setting state to 12
I/BluetoothAdapterState( 6310): Bluetooth adapter state changed: 11-> 12
,D/SettingsProvider(  891): name = bluetooth_a2dp_sink_mode
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 1002
,D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,W/BackupManagerService(  891): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 6310): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6310): updateAdapterState state is 12
,D/BluetoothAdapterService( 6310): Autoconnection is available 
D/BluetoothAdapterService( 6310): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 6310): starting service from this receiver
,D/BluetoothA2dp( 2950): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 6310): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  891): onBluetoothStateChange: up=true
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,E/bt_h4   ( 6310): vendor lib postload completed
D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
I/BluetoothAdapterState( 6310): Entering On State from state = 11
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,W/InputMethodManagerService(  891): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  891): [BT Setting State] State =12
I/InputMethodManagerService(  891): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/BluetoothTile( 1182):  onBluetoothStateChange:
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/BluetoothHeadset( 1395): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@19c74bae, true
,D/BluetoothHeadset( 1395): registerMessageListener
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
I/SamsungIME( 1721): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/BluetoothTile( 1182):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1182): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/HeadsetService( 6310): registerMessageListener
,D/HeadsetService( 6310): registerMessageListener
D/HeadsetStateMachine( 6310): Disconnected process message: 70
D/HeadsetStateMachine( 6310): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3749f89d
,I/Telecom ( 1395): BluetoothPhoneService: updateHeadsetWithCallState
I/Telecom ( 1395): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/BluetoothTile( 1182):  handleUpdatestate:false name:null
,D/STATUSBAR-QSTileView( 1182): onStateChanged: Bluetooth
,D/StatusBarManagerService(  891): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/StatusBarManagerService(  891): setIconVisibility slot=bluetooth visible=true
,I/BluetoothPbapService( 6310): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/PhoneStatusBar( 1182): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/HeadsetStateMachine( 6310): Disconnected process message: 9
,D/HeadsetStateMachine( 6310): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/audio_hw_primary(  302): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  302): voice_set_parameters: enter: A2dpSuspended=false
W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
V/voice   (  302): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  302): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  302): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  302): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  302): adev_set_parameters: exit
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
I/BluetoothPbapService( 6310): Handler(): got msg=1
E/HeadsetStateMachine( 6310): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothManagerService(  891): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/SecContentProvider(  891): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,V/BluetoothPbapService( 6310): PBAP Service initSocket try: 0
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,W/BluetoothAdapter( 6310): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6310): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket( 6310): bindListen(), new LocalSocket 
D/BluetoothSocket( 6310): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6310): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fc09e55
D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
,D/BluetoothSocket( 6310): channel: 19
D/BluetoothPbapService( 6310): PBAP Socket is BluetoothServerSocket
D/BluetoothMapMasInstance( 6310): set MAP SDP message type : 1
,W/BluetoothAdapter( 6310): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6310): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 6310): bindListen(), new LocalSocket 
D/BluetoothSocket( 6310): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6310): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@fff806a
,D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
D/BluetoothSocket( 6310): channel: 5
,D/LocalBluetoothProfileManager( 1303): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1303): Adding local HEADSET profile
,E/BluetoothHeadset( 1303): BTStateChangeCB is registed
,E/BluetoothHeadset( 1303): BluetoothHeadset service is binded
,W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 1303): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1303): PANU : true
,D/LocalBluetoothProfileManager( 1303): Adding local MAP profile
,D/BluetoothMap( 1303): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 1303): Warning: SAP profile was previously added.
,D/LocalBluetoothProfileManager( 1303): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1303): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1303): onReceive
,D/BluetoothA2dp( 1303): Proxy object connected
,D/BluetoothAdapterService( 6310): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3847f113
D/BtConfig.SecureMode( 6310): isSecureModeOn:false
D/A2dpProfile( 1303): Bluetooth service connected
,D/HeadsetProfile( 1303): Bluetooth service connected
,D/AuthorizationBluetoothService( 1572): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/Bluetoothsap( 1303): BluetoothSAP Proxy object connected
,D/SapProfile( 1303): Bluetooth service connected
D/Bluetoothsap( 1303): getConnectedDevices()
,D/BluetoothInputDevice( 1303): Proxy object connected
,D/HidProfile( 1303): Bluetooth service connected
,D/BluetoothPan( 1303): BluetoothPAN Proxy object connected
,D/PanProfile( 1303): Bluetooth service connected
,D/BluetoothMap( 1303): Proxy object connected
,D/MapProfile( 1303): Bluetooth service connected
D/BluetoothPbap( 1303): Proxy object connected
D/PbapServerProfile( 1303): Bluetooth service connected
,D/SecContentProvider(  891): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/BluetoothAdapter( 6310): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6310): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
D/BluetoothSocket( 6310): bindListen(), new LocalSocket 
D/BluetoothSocket( 6310): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6310): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f5f09a4
D/bt_vendor( 6310): op for 7
D/bt_upio ( 6310): BT_WAKE is asserted already
D/BluetoothSocket( 6310): channel: 12
I/BtOppRfcommListener( 6310): Accept thread started.
,I/wpa_supplicant( 6309): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant( 6309): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6309): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 6309): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 6309): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  891): mCursor = null
,I/wpa_supplicant( 6309): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 6309): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 6309): Associated with C0.AA.4A
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,I/wpa_supplicant( 6309): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 6309): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,I/wpa_supplicant( 6309): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 6309): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 6309): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 6309): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6309): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 6309): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6309): Blacklist: Clear (temp) 
I/wpa_supplicant( 6309): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/WifiNative-HAL(  891): callSECApiVoid - ID [50]
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  891): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  891): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  891): Got NetworkAgent Messenger
E/ConnectivityService(  891): updateNetworkInfo()
D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891): NetworkAgent connected
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1182): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  288): Setting iface cfg
,E/Zygote  ( 6492): MountEmulatedStorage()
,E/Zygote  ( 6492): v2
I/libpersona( 6492): KNOX_SDCARD checking this for 10038
,I/libpersona( 6492): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6492 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/WifiStateMachine(  891): Start Dhcp Watchdog 1
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,I/SELinux ( 6492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1182): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  891): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,I/SELinux ( 6492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6492): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6492): TimaSignature is unavailable
,D/ActivityThread( 6492): Added TimaKeyStore provider
,D/ResourcesManager( 6492): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 6492): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/native  (  891): do suspend false
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  891): InactiveState{ what=143375 }
D/SecContentProvider2(  891): mCursor = null
D/WifiP2pService(  891): P2pEnabledState{ what=143375 }
,I/VlingoApplication( 6492): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/BluetoothHeadset( 6492): BTStateChangeCB is registed
,E/BluetoothHeadset( 6492): BluetoothHeadset service is binded
,E/lowmemorykiller(  251): Error writing /proc/5040/oom_score_adj; errno=22
I/ActivityManager(  891): Killing 5040:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,I/Hs20UtilService( 1303): Starting #2
I/Hs20UtilService( 1303): Message received 5007
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,E/dhcpcd  ( 6512): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6512): version 5.5.6 starting
,E/dhcpcd  ( 6512): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/SettingsProvider(  891): name = driving_mode_on
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 10038
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,D/BluetoothManager( 6492): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 4
,I/dhcpcd  ( 6512): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6512): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6512): if(wlan0) info get Success. (MAC : C0.AA.4A)
,I/dhcpcd  ( 6512): bssid match
,I/dhcpcd  ( 6512): wlan0: rebinding lease of 192.168.1.128
,I/art     (  891): Explicit concurrent mark sweep GC freed 44813(2MB) AllocSpace objects, 5(80KB) LOS objects, 17% free, 36MB/44MB, paused 1.343ms total 107.741ms
,E/SignOutReceiver( 4305): NETWORK_STATE_CHANGED_ACTION
,D/bt_vendor( 6310): op for 7
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  891): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/bt_upio ( 6310): ..proc_btwrite_timeout..
,I/dhcpcd  ( 6512): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/dhcpcd  ( 6512): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  891): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,E/native  (  891): do suspend true
,D/WifiP2pService(  891): InactiveState{ what=143375 }
,D/WifiP2pService(  891): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  891): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1182): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  891): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
,E/WifiStateMachine(  891): VerifyingLinkState enter
,D/WifiNative-HAL(  891): callSECApiInt - ID [210]
,E/ConnectivityService(  891): updateNetworkInfo()
,D/ConnectivityService(  891): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fede:28a3/64,192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  891): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine(  891): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  891): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fede:28a3/64,192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver(  891): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fede:28a3/64,192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker(  891): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fede:28a3/64,192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  891): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fede:28a3/64,192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1182): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  891): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,E/WifiStateMachine(  891): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  891): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  891): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  891): mBoosterFLAG : 0
I/WifiTrafficPoller(  891): current booster mode : FullMode
,D/ConnectivityService(  891): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/WifiNative-HAL(  891): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1182): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  891): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService(  891): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1182): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,E/ConnectivityService(  891): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  891): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  891): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
D/StatusBar.NetworkController( 1182): applyOpen
,D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,V/        (  288): QcRouteController
,I/Hs20UtilService( 1303): Starting #3
,I/Hs20UtilService( 1303): Message received 5007
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,V/        (  288): QcRouteController
,W/NetworkManagementService(  891): route cmd failed: 
W/NetworkManagementService(  891): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '49 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 49 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  891): '
W/NetworkManagementService(  891): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  891): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  891): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  891): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  891): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  891): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  891): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  891): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6197)
W/NetworkManagementService(  891): 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:229)
W/NetworkManagementService(  891): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2395)
W/NetworkManagementService(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  891): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ConnectivityService(  891): updateSourceRoutes : add src route for:192.168.1.128
V/        (  288): QcRouteController
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SignOutReceiver( 4305): NETWORK_STATE_CHANGED_ACTION
V/        (  288): QcRouteController
,I/Hs20UtilService( 1303): Starting #4
,I/Hs20UtilService( 1303): Message received 5007
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 4305): NETWORK_STATE_CHANGED_ACTION
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,I/Hs20UtilService( 1303): Starting #5
,I/Hs20UtilService( 1303): Message received 5007
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  891): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 4305): NETWORK_STATE_CHANGED_ACTION
,V/        (  288): QcRouteController
,I/SurfaceFlinger(  254): id=14 createSurf (1x1),1 flag=4, Uoast
,I/jxcore-log( 6208): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6208): 
,D/PowerManagerService(  891): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=891
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,D/ConnectivityService(  891): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService(  891): LTETest block dns file not exists
,V/Nat464Xlat(  891): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  891): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  891): calling update connectivity
,D/EntConnectivity(  891): Not allowed due to - mEnabled false
E/ConnectivityService(  891): updateNetworkInfo()
D/ConnectivityService(  891): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  891): updateNetworkInfo()
D/ConnectivityService(  891): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  891): calling update connectivity
D/ConnectivityService(  891): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  891):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  891):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  891): currentScore = 0, newScore = 60
D/ConnectivityService(  891):    accepting network in place of null
D/ConnectivityService(  891): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/TelephonyNetworkFactory( 1419): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  891): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fede:28a3/64,192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  891): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/System.out(  891): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  891): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
I/System.out(  891): (HTTPLog)-Static: isShipBuild true
I/System.out(  891): (HTTPLog)-Thread-180-416563465: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(  891): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  891): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fede:28a3/64,192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering(  891): MasterInitialState.processMessage what=3
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkStats(  891): updateIfacesLocked()
V/NetworkStats(  891): performPollLocked(flags=0x1)
,D/SmartBondingService(  891): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/NetworkStatsFactory(  891): UpdateStatsForKnox
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  891): getNetworkEnabled : wifi : true mobile : true
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1182): updateDataNetType()
D/EntConnectivity(  891): Not allowed due to - mEnabled false
D/StatusBar.NetworkController( 1182): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1182): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  891): forceRefresh() from cache miss
,V/NetworkStats(  891): performPollLocked() took 9ms
,D/ConnectivityService(  891): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  891): calling update connectivity
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  891): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1182): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1182): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1182): applyOpen
,D/PackageManager(  891): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/System.out(  891): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NtpTrustedTime(  891): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449671288150 mCachedNtpElapsedRealtime : 165782 mCachedNtpCertainty : 10
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
V/NetworkStats(  891): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 14:28:08 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449671287653], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449671287636]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Validated
,D/ConnectivityService(  891): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  891): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  891):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  891): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  891): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  891): calling update connectivity
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  891): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524290
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/Watchdog(  891): !@Sync 5
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1182): updateDataNetType()
,D/StatusBar.NetworkController( 1182): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1182): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1182): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1182): onWifiSignalChanged enabled=true enabledDesc:"NG7005g",
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  891): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  891): SmartBondingReceiver: wifi is connected
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  891): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  891): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
,D/SmartBondingService(  891): getSBEnabled() enabled =false
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): stay LED for fully charged
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  891): getNetworkEnabled : wifi : true mobile : true
,W/ContextImpl( 1894): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 1894): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/AlarmManagerService(  891): Setting time of day to sec=1449671288
,D/AlarmManagerService(  891): Trying to open a file
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AlarmManagerService(  891): File Open Success
,D/AlarmManagerService(  891): File Close Success
I/AlarmManagerService(  891): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager(  891): waitForAlarm result :65536
,W/AlarmManagerService(  891): Unable to set rtc to 1449671288: Invalid argument
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,I/DBG_DM  ( 3190): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3190): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6310): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PCWCLIENTTRACE_PushUtil( 5845): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5845): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5845): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5845): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3190): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiStateMachine(  891): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_SET
,D/StatusBar-DoNotDistrub( 1182): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 1182): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3190): [llIlIIIIlllIlllllIll(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/accuweather( 1777): [Accuweather J]>>> SWW:64 [0:0] =============== BR act = androidintentactionTIME_SET
D/accuweather( 1777): [Accuweather J]>>> SWW:645 [0:0] renderUpdateAllCondition : [0] = 1
,D/accuweather( 1777): [Accuweather J]>>> WR:452 [0:0] =============== updateAllCondition = 1
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3190): [IIllIIllIIIlllIlIIll(403/llllllIllIlIlllIIlIl)] Check completed.
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3190): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3190): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 4795): type=WIFI subType= reason=null isConnected=true
,E/Zygote  ( 6629): MountEmulatedStorage()
E/Zygote  ( 6629): v2
I/libpersona( 6629): KNOX_SDCARD checking this for 10014
I/libpersona( 6629): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6629 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  891): waitForAlarm result :4
,I/SELinux ( 6629): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6629): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6629): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/Settings(  891): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/StatusBar-DoNotDistrub( 1182): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager(  302): getOutputsForDevice device 0002 -> 0002
I/DBG_DM  ( 3190): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
I/AudioService(  891): getStreamVolume 5 index 0
D/StatusBar-DoNotDistrub( 1182): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,I/DBG_DM  ( 3190): [IIIlllIlIIlllIIIIllI(73/llllIIIllIlIIIIllllI)] 
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1749): Module APK com.google.android.play.games already loaded
,I/DrmEventService(  891):  no response from SecureClock 
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  891): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6644 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6644): MountEmulatedStorage()
E/Zygote  ( 6644): v2
I/libpersona( 6644): KNOX_SDCARD checking this for 10004
I/libpersona( 6644): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3190): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3190): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
,I/SELinux ( 6644): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6644): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/TimaKeyStoreProvider( 6629): TimaSignature is unavailable
E/SELinux ( 6644): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 6629): Added TimaKeyStore provider
,I/DBG_DM  ( 3190): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 3190): [IIllIIllIIIlllIlIIll(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,D/ResourcesManager( 6629): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/DBG_DM  ( 3190): [IIllIIllIIIlllIlIIll(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,D/TimaKeyStoreProvider( 6644): TimaSignature is unavailable
,D/ActivityThread( 6644): Added TimaKeyStore provider
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 6644): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,E/Zygote  ( 6669): MountEmulatedStorage()
E/Zygote  ( 6669): v2
I/libpersona( 6669): KNOX_SDCARD checking this for 10104
I/libpersona( 6669): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6669 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6669): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6669): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6669): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/FOTA_Client( 6629): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/DBG_DM  ( 3190): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
,I/FOTA_Client( 6629): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6669): TimaSignature is unavailable
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 6669): Added TimaKeyStore provider
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3190): [IIllIlIIlIlllIIllIII(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 3190): [llIlIIIIlllIlllllIll(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3190): [llIlIIIIlllIlllllIll(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 3190): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,I/DBG_DM  ( 3190): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3190): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,E/Zygote  ( 6688): MountEmulatedStorage()
E/Zygote  ( 6688): v2
I/libpersona( 6688): KNOX_SDCARD checking this for 10023
I/libpersona( 6688): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6688 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_DM  ( 3190): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/art     (  330): Explicit concurrent mark sweep GC freed 8722(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 302us total 12.944ms
,I/DBG_DM  ( 3190): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,D/ResourcesManager( 6669): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 278us total 9.901ms
,V/AccountUtils( 1749): 0 accounts found with uca feature
,I/DBG_DM  ( 3190): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,D/TimaKeyStoreProvider( 6688): TimaSignature is unavailable
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 271us total 9.648ms
I/GamesSyncAdapter( 1749): Starting sync for 3a3529a
,D/ActivityThread( 6688): Added TimaKeyStore provider
,I/DBG_DM  ( 3190): [IIllIlIIlIlllIIllIII(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 3190): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 3190): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 3190): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@cb9cad1
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_DM  ( 3190): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 6688): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,E/Zygote  ( 6704): MountEmulatedStorage()
E/Zygote  ( 6704): v2
I/libpersona( 6704): KNOX_SDCARD checking this for 1000
I/libpersona( 6704): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6704 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6704): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6704): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/KLMS-2.4.511: ( 6688): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
W/GamesSyncAdapter( 1749): User is not G+ enabled. Aborting sync
,I/GamesSyncAdapter( 1749): Sync duration for 3a3529a: 81
,E/SELinux ( 6704): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3190): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/KLMS-2.4.511: ( 6688): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1449671289151
,I/KLMS-2.4.511: ( 6688): MainReciver(): TIME_CHANGED
,I/KLMS-2.4.511: ( 6688): StateImplV2(): dateTimeChanged().START : Wed Dec 09 15:28:09 GMT+01:00 2015
,I/KLMS-2.4.511: ( 6688): StateImplV2(): dateTimeChanged().END
,I/DBG_DM  ( 3190): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/ActivityManager(  891): Killing 4887:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,W/System.err( 5860): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
W/System.err( 5860): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err( 5860): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err( 5860): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err( 5860): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err( 5860): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
W/System.err( 5860): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 5860): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 5860): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 5860): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5860): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
W/System.err( 5860): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5860): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5860): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
W/System.err( 5860): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6704): TimaSignature is unavailable
,D/ActivityThread( 6704): Added TimaKeyStore provider
,E/Zygote  ( 6722): MountEmulatedStorage()
E/Zygote  ( 6722): v2
I/libpersona( 6722): KNOX_SDCARD checking this for 10042
I/libpersona( 6722): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/com.sec.android.fota.osp.time.ServerTimeReceiver: pid=6722 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6722): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager(  891): showStatusBarByNotification() mOpenByNotification=false
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1749): Module APK com.google.android.play.games already loaded
,D/TimaKeyStoreProvider( 6722): TimaSignature is unavailable
,D/ActivityThread( 6722): Added TimaKeyStore provider
,I/DBG_DM  ( 3190): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3190): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/ResourcesManager( 6704): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/ResourcesManager( 6722): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
E/GpsLocationProvider(  891): No APN found to select.
,D/ResourcesManager( 1182): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3190): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3190): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 3190): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,I/SO_AGENT( 6722): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/SA      ( 5931): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 6704): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,D/KnoxNotification( 1182): ----- inflateViews : modified publicViewLocal -----
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/KnoxNotification( 1182): ----- inflateViews : modified KnoxViewLocal -----
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PersonaManager( 1182): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1182): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@4e08550
D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PersonaManager( 1182): isKioskContainerExistOnDevice
,I/DIAGMON_AGENT( 6704): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6669): Delaying sync.
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 6745): MountEmulatedStorage()
E/Zygote  ( 6745): v2
I/libpersona( 6745): KNOX_SDCARD checking this for 10076
I/libpersona( 6745): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6745 uid=10076 gids={50076, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6745): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6745): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6745): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  891): Killing 4958:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,D/PanelView( 1182): There is/are notification(s) 
,D/PanelView( 1182): There is/are notification(s) 
V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6745): TimaSignature is unavailable
,D/ActivityThread( 6745): Added TimaKeyStore provider
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1749): Module APK com.google.android.play.games already loaded
,D/ResourcesManager( 6745): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 6704): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/ActivityManager(  891): Killing 5527:flipboard.app/u0a125 (adj 15): bgCount ##41
,I/DIAGMON_AGENT( 6704): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6704): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6704): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/Auth.Api.Credentials( 1749): [CredentialSyncAdapter] Unknown sync event.
,E/SMD     (  294): DCD ON
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6764): MountEmulatedStorage()
E/Zygote  ( 6764): v2
I/libpersona( 6764): KNOX_SDCARD checking this for 10106
I/libpersona( 6764): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6764 uid=10106 gids={50106, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 6764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  891): Killing 5730:com.sec.android.widgetapp.digitalclock/u0a109 (adj 15): bgCount ##41
,I/SELinux ( 6764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6764): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ Time Manager ( 6745): Time Difference not stored. TIME_DIFFERENCE
,D/TimaKeyStoreProvider( 6764): TimaSignature is unavailable
,D/ActivityThread( 6764): Added TimaKeyStore provider
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  891): Killing 5754:com.sec.android.widgetapp.dualclockdigital/u0a115 (adj 15): bgCount ##41
,D/ResourcesManager( 6764): creating new AssetManager and set to /system/app/ClockPackage_Osup/ClockPackage_Osup.apk
,I/FOTA_Client( 6629): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,W/ResourcesManager( 6764): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6764): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6764): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6764): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6764): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6764): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/FOTA_Client( 6629): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6629): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6688): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6688): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449671289724
,I/KLMS-2.4.511: ( 6688): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6688): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 6688): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 6688): NetworkChangeOperations(): uploadRequestLog().START 
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6669): Delaying sync.
,D/SettingsProvider(  891): name = next_alarm_formatted
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 10106
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6688): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 6784): MountEmulatedStorage()
E/Zygote  ( 6784): v2
I/libpersona( 6784): KNOX_SDCARD checking this for 10036
I/libpersona( 6784): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=6784 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 6784): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6784): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6784): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 6784): TimaSignature is unavailable
,D/ActivityThread( 6784): Added TimaKeyStore provider
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PicasaService( 4904): start picasa sync
,D/PicasaService( 4904): end picasa sync
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  891): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  891): apparently satisfied.  currentScore=60
,D/ConnectivityService(  891): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,D/ConnectivityManager.CallbackHandler( 1749): CM callback handler got msg 524290
,D/ResourcesManager( 6784): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 6784): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6784): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Killing 5688:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Minikin ( 6784): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,E/Zygote  ( 6803): MountEmulatedStorage()
,E/Zygote  ( 6803): v2
I/libpersona( 6803): KNOX_SDCARD checking this for 10116
I/libpersona( 6803): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6803 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6803): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  891): Killing 5811:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,I/SELinux ( 6803): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SELinux ( 6803): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6803): TimaSignature is unavailable
,D/ActivityThread( 6803): Added TimaKeyStore provider
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6803): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/elm:14491( 6803): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491( 6803): ELMEngine.ELMEngine( context ).
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/elm:14491( 6803): MDMBridge.setEnterpriseBridge()
,I/ActivityManager(  891): Killing 5829:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,D/elm:14491( 6803): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/elm:14491( 6803): ElmAgentService : onCreate()
,D/elm:14491( 6803): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/elm:14491( 6803): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491( 6803): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491( 6803): ModuleBase.ModifySetAlarm()
D/elm:14491( 6803): MDMBridge.getInstance()
D/elm:14491( 6803): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491( 6803): ElmAgentService : onDestroy().
,I/SO_AGENT( 6722): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6828): MountEmulatedStorage()
,E/Zygote  ( 6828): v2
I/libpersona( 6828): KNOX_SDCARD checking this for 10172
I/libpersona( 6828): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6828 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6828): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6828): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6828): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6828): TimaSignature is unavailable
,D/ActivityThread( 6828): Added TimaKeyStore provider
,I/dhcpcd  ( 6512): wlan0: sending IPv6 Router Solicitation
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6828): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
E/SPPClientService( 4612): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,W/ResourcesManager( 6828): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6828): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6828): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SA      ( 5931): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5931): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 5931): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5931): [SLFUCHKMGR] constructor called
,I/PeopleSync( 1749): onPerformSync() [5005f081]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 5931): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5931): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 5931): [SCU] == networkStateCheck == true
,I/SA      ( 5931): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5931): isChinaCountryCode : false
I/SA      ( 5931): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5931): [OR] == networkStateCheck true ==
,I/SA      ( 5931): [OR] GetMyCountryZoneTask
,I/SA      ( 5931): [OR] onReceive END
,I/SA      ( 5931): [SRS] prepareGetMyCountryZone
,D/SecurityLogAgent( 6283): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6283): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6283): StateMachine : Current State = 1
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 5931): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5931): [SSP] query invoked
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 6853): MountEmulatedStorage()
E/Zygote  ( 6853): v2
I/libpersona( 6853): KNOX_SDCARD checking this for 10051
I/libpersona( 6853): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6853 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6853): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6853): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6853): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6853): TimaSignature is unavailable
,D/ActivityThread( 6853): Added TimaKeyStore provider
,I/art     (  891): Explicit concurrent mark sweep GC freed 56961(3MB) AllocSpace objects, 9(144KB) LOS objects, 17% free, 37MB/45MB, paused 1.651ms total 96.339ms
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,I/SA      ( 5931): [TPMU] GetMccFromDB : null
I/SA      ( 5931): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5931): [TPM] isNoProxy(default) : true
,E/File    ( 5931): fail readDirectory() errno=2
,E/Zygote  ( 6869): MountEmulatedStorage()
,E/Zygote  ( 6869): v2
I/libpersona( 6869): KNOX_SDCARD checking this for 1000
I/libpersona( 6869): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6869 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6869): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  891): Killing 5315:sstream.app/u0a25 (adj 15): bgCount ##41
,I/SELinux ( 6869): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6869): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6869): TimaSignature is unavailable
,D/ActivityThread( 6869): Added TimaKeyStore provider
,D/ResourcesManager( 6853): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 6853): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/Zygote  ( 6885): MountEmulatedStorage()
E/Zygote  ( 6885): v2
I/libpersona( 6885): KNOX_SDCARD checking this for 10074
I/libpersona( 6885): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=6885 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6885): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 6869): creating new AssetManager and set to /system/app/TimeService/TimeService.apk
,D/TimeService( 6869): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449671290442
,D/        ( 6869): TimeServiceNative: User Time to be set is 1449671290443
D/QC-time-services( 6869): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6869): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6869): Lib:time_genoff_operation: pargs->ts_val = 1449671290443
,D/QC-time-services(  359): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 6869): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  359): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449671290443
D/QC-time-services(  359): Daemon:genoff_opr: Base = 2, val = 1449671290443, operation = 0
,D/QC-time-services(  359): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/17/70 21:16:36
D/QC-time-services(  359): Daemon:Value read from RTC seconds = 9234996000
D/QC-time-services(  359): Daemon:new time 1449671290443 
D/QC-time-services(  359): Daemon: delta 1440436294443 genoff 1440436294443 
D/QC-time-services(  359): Daemon:genoff_persistent_update: Writing genoff = 1440436294443 to memory
D/QC-time-services(  359): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  359): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/TimaKeyStoreProvider( 6885): TimaSignature is unavailable
,D/ActivityThread( 6885): Added TimaKeyStore provider
,D/QC-time-services(  359): Updating the TOD offset
D/QC-time-services(  359): Daemon:genoff_persistent_update: Writing genoff = 1440436294443 to memory
D/QC-time-services(  359): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  359): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  359): Daemon:Update to modem bit set
D/QC-time-services(  359): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  359): Daemon: Base = 2, Value being sent to MODEM = 1124471494443
,E/QC-time-services( 6869): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,W/ActivityThread( 5880): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/QC-time-services(  359): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  359): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager(  891): Killing 5353:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,D/comdaemonstockapp( 3336): [Daemon_Stock]>>> Stockclock_DaemonService.java:63 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 3336): [Daemon_Stock]>>> Stockclock_DaemonService.java:64 [0:0] appServiceStatus: 0
D/comdaemonstockapp( 3336): [Daemon_Stock]>>> Stockclock_DaemonService.java:65 [0:0] [AR]: 0
,D/comdaemonstockapp( 3336): [Daemon_Stock]>>> Stockclock_DaemonService.java:66 [0:0] [AR]: Next time = 0
,D/daemonapp( 3336): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 3336): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3336): [MSC_Accu_Daemon]>>> daemonapp [Version : 14123102 ] [ 1 ] 
,D/comsamsunglog( 3336): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3336): [MSC_Accu_Daemon]>>> ====================================================================================================================
,D/daemonapp( 3336): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/System.out( 5880): Thread-947(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/daemonapp( 3336): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 3336): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3336): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,I/System.out( 5880): Thread-947(ApacheHTTPLog):isShipBuild true
,I/System.out( 5880): Thread-947(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/daemonapp( 3336): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
D/ResourcesManager( 6885): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,D/daemonapp( 3336): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3336): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,D/daemonapp( 3336): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3336): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
D/daemonapp( 3336): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3336): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,I/CalendarProvider2( 6853): CalendarProvider2.onCreate() called
,I/PeopleDatabaseHelper( 1749): cleanUpNonGplusAccounts done.
,I/CheckinService( 1749): Checkin interval check for package: unspecified last checkin: 1449576540818 min interval config: 0 actual interval: 94749743
,I/sCloudBackupApp( 6885): sCloudBackupApp Version Info : 3.13.7.KK_APP
I/SCloudBackupReceiver( 6885): Other Intent
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,I/art     ( 1572): Explicit concurrent mark sweep GC freed 20625(1152KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 19MB/32MB, paused 511us total 25.985ms
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5880): Thread-947 calls detatch()
,E/Zygote  ( 6907): MountEmulatedStorage()
,E/Zygote  ( 6907): v2
I/libpersona( 6907): KNOX_SDCARD checking this for 1000
I/libpersona( 6907): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=6907 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 5900:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,I/art     (  330): Explicit concurrent mark sweep GC freed 8758(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 325us total 13.299ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 355us total 10.298ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 270us total 10.515ms
,I/SELinux ( 6907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6907): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6907): TimaSignature is unavailable
,D/ActivityThread( 6907): Added TimaKeyStore provider
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/ResourcesManager( 6907): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 6907): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 6907): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,W/DriveInitializer( 1749): Awaiting to be initialized
,I/KnoxUsageLogPro( 6907): premStatus:2
,W/DriveInitializer( 1749): Background init thread started
,I/KnoxUsageLogPro( 6907): isEulaShown : false
I/KnoxUsageLogPro( 6907): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1749): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,E/Zygote  ( 6927): MountEmulatedStorage()
E/Zygote  ( 6927): v2
I/libpersona( 6927): KNOX_SDCARD checking this for 10146
I/libpersona( 6927): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6927 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6927): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  891): Killing 5957:com.sec.android.app.soundalive/u0a64 (adj 13): bgCount ##41
,I/SELinux ( 6927): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6927): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/btif_config_util( 6310): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 6927): TimaSignature is unavailable
,D/ActivityThread( 6927): Added TimaKeyStore provider
,I/ActivityManager(  891): Killing 5095:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##41
,D/ResourcesManager( 6927): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/DriveInitializer( 1749): Background init thread ended
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6927): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/PeopleSync( 1749): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1749): Starting sync, feed=null [5005f081]
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6927): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6927): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6927): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/BaseAppContext( 1749): Using Auth Proxy for data requests.
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/BaseAppContext( 1749): Using Auth Proxy for data requests.
,W/BaseAppContext( 1749): Using Auth Proxy for data requests.
,I/PeopleSync( 1749): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SA      ( 5931): [RC New] Execute method=[GET] start
,I/art     ( 1749): Explicit concurrent mark sweep GC freed 22498(1621KB) AllocSpace objects, 22(352KB) LOS objects, 25% free, 22MB/30MB, paused 767us total 42.452ms
,I/SA      ( 5931): [RC New] Security=[true]
,I/System.out( 5931): Thread-956(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5931): Thread-956(ApacheHTTPLog):isShipBuild true
,I/System.out( 5931): Thread-956(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1572): (HTTPLog)-Static: isSBSettingEnabled false
,I/WebViewFactory( 6927): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6927): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6927): Loading: webviewchromium
,I/LibraryLoader( 6927): Time to load native libraries: 4 ms (timestamps 8894-8898)
,I/LibraryLoader( 6927): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6927): Binding Chromium to main looper Looper (main, tid 1) {2e8517d6}
,I/LibraryLoader( 6927): Expected native library version number "",actual native library version number ""
,I/chromium( 6927): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6927): Initializing chromium process, renderers=0
,W/art     ( 6927): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6927): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6927): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 6927): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 6927): Requires BLUETOOTH permission
,I/System.out( 1572): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1572): Tagging socket 58 with tag 1000040100000000{268436481,0} uid 10015, pid: 1572, getuid(): 10015
,I/Adreno-EGL( 6927): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6927): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6927): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6927): Local Branch: mybranch5813579
I/Adreno-EGL( 6927): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6927): Local Patches: NONE
I/Adreno-EGL( 6927): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,E/WifiStateMachine(  891): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/qtaguid ( 1572): Tagging socket 63 with tag 1000040100000000{268436481,0} uid 10015, pid: 1572, getuid(): 10015
,I/SurfaceFlinger(  254): id=14 Removed Uoast (8/9)
,D/PowerManagerService(  891): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 891) eventTime = 169012
D/PowerManagerService(  891): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=891 (0x0)
,D/PowerManagerService(  891): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=891, ws=WorkSource{10067}) (elapsedTime=3461)
,I/NSApplication( 6927): Starting up...
,D/OpenGLRenderer( 3190): Render dirty regions requested: true
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Atlas   ( 3190): Validating map...
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=4, Uoast
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/PowerManagerService(  891): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=891
,I/Adreno-EGL( 3190): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 3190): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 3190): Build Date: 11/19/14 Wed
I/Adreno-EGL( 3190): Local Branch: mybranch5813579
I/Adreno-EGL( 3190): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 3190): Local Patches: NONE
I/Adreno-EGL( 3190): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/OpenGLRenderer( 3190): Initialized EGL, version 1.4
,E/Zygote  ( 6998): MountEmulatedStorage()
E/Zygote  ( 6998): v2
I/libpersona( 6998): KNOX_SDCARD checking this for 10158
I/libpersona( 6998): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6998 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 5977:com.google.android.apps.docs/u0a112 (adj 13): bgCount ##41
,I/OpenGLRenderer( 3190): HWUI protection enabled for context ,  &this =0xaf422088 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 3190): Enabling debug mode 0
,I/SELinux ( 6998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6998): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6998): TimaSignature is unavailable
,D/ActivityThread( 6998): Added TimaKeyStore provider
,D/ResourcesManager( 6998): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 6998): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6998): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6998): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 6998): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6998): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6998): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6283): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6283): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6283): StateMachine : Current State = 1
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6283): StateMachine : Changed Current State = 1
,I/ActivityManager(  891): Killing 6001:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##41
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7015): MountEmulatedStorage()
E/Zygote  ( 7015): v2
I/libpersona( 7015): KNOX_SDCARD checking this for 10200
I/libpersona( 7015): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7015 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7015): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/UdcCache:FPQuery( 1749): Bootstrapping UDC settings cache for all accounts
,I/VacuumService( 1572): Vacuum at: now=1449671291669 tag=VacuumService
,D/TimaKeyStoreProvider( 7015): TimaSignature is unavailable
,D/ActivityThread( 7015): Added TimaKeyStore provider
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7015): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1749): (HTTPLog)-Static: isShipBuild true
I/System.out( 1749): (HTTPLog)-Thread-185-386661142: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/ActivityManager(  891): Killing 6022:com.samsung.android.app.watchmanagerstub/u0a126 (adj 13): bgCount ##41
,I/CalendarProvider2( 6853): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager(  891): Killing 6041:com.samsung.helphub/1000 (adj 13): bgCount ##41
,I/System.out( 1749): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1749): Tagging socket 112 with tag 1000150000000000{268440832,0} uid 10015, pid: 1749, getuid(): 10015
,I/iu.SyncManager( 1749): SYNC; picasa accounts
,I/qtaguid ( 1749): Tagging socket 120 with tag 1000150000000000{268440832,0} uid 10015, pid: 1749, getuid(): 10015
,D/NetworkLogImpl( 1749): Loaded NetworkSpeedPredictor
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 1749): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.UploadsManager( 1749): num queued entries: 0
,I/iu.UploadsManager( 1749): num updated entries: 0
I/iu.SyncManager( 1749): NEXT; no task
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 5931): [RC New] [v2liruge] api execute + 649
I/SA      ( 5931): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5931): AsyncTask #1 calls detatch()
,I/SA      ( 5931): [TPMU] getNetworkMcc : 
,I/SA      ( 5931): [SCU] saveMccToPreferece Start
I/SA      ( 5931): [SCU] RegionMCC : 260
I/SA      ( 5931): [SSP] query invoked
,I/SA      ( 5931): [TPMU] GetMccFromDB : null
I/SA      ( 5931): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5931): [SCU] saveMccToPreferece End
,I/SA      ( 5931): [RC New] executeRequest [v2liruge] end. 722
I/SA      ( 5931): [RC New] Execute end
I/SA      ( 5931): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5931): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 6082): notifyNetworkActivated
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 6082): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  891): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 1749): Untagging socket 112
,D/GetConfigurationSnapshotOperation( 1572): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1572): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1572): Using platform SSLCertificateSocketFactory
,D/hcjo    ( 6082): AutoUpdateManager:IDLE:execute
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 6082): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6082): exit::IDLE
D/InitializeManagerStateMachine( 6082): entry::NETWORK_CHECK
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 6082): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6082): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6082): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6082): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6082): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6082): entry::SUCCESS
D/hcjo    ( 6082): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6082): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 6082): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6082): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GCM     ( 1572): GCM config loaded
D/InitializeManagerStateMachine( 6082): exit::SUCCESS
D/InitializeManagerStateMachine( 6082): entry::IDLE
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7052): MountEmulatedStorage()
E/Zygote  ( 7052): v2
I/libpersona( 7052): KNOX_SDCARD checking this for 10171
I/libpersona( 7052): KNOX_SDCARD not a persona
,I/SELinux ( 7052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ActivityManager(  891): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7052 uid=10171 gids={50171, 9997} abi=armeabi-v7a
E/SELinux ( 7052): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1749): Tagging socket 112 with tag 1000190000000000{268441856,0} uid 10015, pid: 1749, getuid(): 10015
,D/GetCommittedConfigurationOperation( 1572): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7052): TimaSignature is unavailable
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ActivityThread( 7052): Added TimaKeyStore provider
,I/System.out( 1572): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7052): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7052): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7052): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/System.out( 1572): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1572): Tagging socket 69 with tag 1000120100000000{268440065,0} uid -1, pid: 1572, getuid(): 10015
,I/qtaguid ( 1572): Tagging socket 72 with tag 1000120100000000{268440065,0} uid -1, pid: 1572, getuid(): 10015
,I/qtaguid ( 1749): Untagging socket 112
,D/SSRM:n  (  891): SIOP:: AP = 370, PST = 327, CUR = 450
,I/art     (  891): Explicit concurrent mark sweep GC freed 33942(2MB) AllocSpace objects, 6(96KB) LOS objects, 17% free, 37MB/45MB, paused 1.359ms total 87.248ms
,I/art     ( 1572): Explicit concurrent mark sweep GC freed 58988(3MB) AllocSpace objects, 17(487KB) LOS objects, 39% free, 20MB/33MB, paused 596us total 39.310ms
,I/ActivityManager(  891): Killing 6058:com.sec.kidsplat.installer/u0a189 (adj 13): bgCount ##41
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 112 with tag 1000150000000000{268440832,0} uid 10015, pid: 1749, getuid(): 10015
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GetCommittedConfigurationOperation( 1572): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1572): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1572): Tagging socket 69 with tag 1000120100000000{268440065,0} uid -1, pid: 1572, getuid(): 10015
,I/qtaguid ( 1749): Untagging socket 112
,E/Volley  ( 1749): [186] BasicNetwork.performRequest: Unexpected response code 410 for https://www.googleapis.com/plus/v2whitelisted/people/me/people/all?prettyPrint=false&fields=items(etag,id,names,nicknames,images,urls,sortKeys,taglines,emails,phoneNumbers,addresses,metadata,memberships,legacyFields/mobileOwnerId),nextPageToken,nextSyncToken&customResponseMaskingType=menagerie&includeAffinity=gplusAutocomplete&includeAffinity=chatAutocomplete&includeAffinity=emailAutocomplete&includeOthers=true&maxResults=100&orderBy=modified&syncToken=CNOiz9mXKhIBMRjbEioECAEQAQ
,I/PeopleSync( 1749): Sync Token out of date, syncing all people/gaia-map
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 112 with tag 1000150000000000{268440832,0} uid 10015, pid: 1749, getuid(): 10015
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Uploader( 1572):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1572): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1572): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1572): Tagging socket 69 with tag 1000120100000000{268440065,0} uid -1, pid: 1572, getuid(): 10015
,I/qtaguid ( 1749): Untagging socket 112
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GetCommittedConfigurationOperation( 1572): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,I/System.out( 1572): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1572): Tagging socket 69 with tag 1000120100000000{268440065,0} uid -1, pid: 1572, getuid(): 10015
,I/PeopleSync( 1749): Sync finished, successful=true, took 1448ms
,I/PeopleSync( 1749): ***Sync finished***, duration: 2435 [5005f081]
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1749): Module APK com.google.android.play.games already loaded
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PlaySystemBroadcastReceiver( 1749): Processed handlePeopleChanged at 170242
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1749): Module APK com.google.android.play.games already loaded
,W/DataBroker( 1749): No player ID found and calling context is not the dest app
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GetCommittedConfigurationOperation( 1572): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1572): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1572): Tagging socket 69 with tag 1000120100000000{268440065,0} uid -1, pid: 1572, getuid(): 10015
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1749): (284) automatic index on invitations(external_inviter_id)
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  891): Killing 5596:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 13): bgCount ##41
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5845): mConnectivityHandler : connected
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 5845): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 5845): ================================================
,I/CSTORAGE( 5845):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 5845): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5845): [GetString-S]
E/art     ( 5845): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 5845): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5845): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5845): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5845): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5845): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5845): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 6512): wlan0: sending IPv6 Router Solicitation
,I/SurfaceFlinger(  254): id=15 Removed Uoast (8/9)
I/SurfaceFlinger(  254): id=15 Removed Uoast (-2/9)
D/PowerManagerService(  891): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 891) eventTime = 172540
D/PowerManagerService(  891): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=891 (0x0)
D/PowerManagerService(  891): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=891, ws=WorkSource{1000}) (elapsedTime=3467)
E/SMD     (  294): DCD ON
,I/GAV4    ( 6927): Thread[GAThread,5,main]: No campaign data found.
,I/PowerManagerService(  891): [PWL] Off : 75s ago
,I/dhcpcd  ( 6512): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6512): wlan0: no IPv6 Routers available
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,D/PreloadUpdateManagerStateMachine( 6082): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6082): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6082): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6082): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 6082): RestApi Request Add : 2307
,E/File    ( 6082): fail readDirectory() errno=2
,D/SSRM:n  (  891): SIOP:: AP = 320, PST = 321, CUR = 450
,I/System.out( 6082): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6082): (HTTPLog)-Static: isShipBuild true
I/System.out( 6082): (HTTPLog)-Thread-990-171836488: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6082): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6082): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6082): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 6082, getuid(): 10045
,I/qtaguid ( 6082): Untagging socket 26
,D/hcjo    ( 6082): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 6082): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 6082): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6082): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6082): entry::REQ_UPDATE_CHECK
,I/Volley  ( 6082): RestApi Request Add : 2315
,I/System.out( 6082): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6082): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6082): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 6082, getuid(): 10045
,I/qtaguid ( 6082): Untagging socket -1
,I/qtaguid ( 6082): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid ( 6082): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 6082): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 6082): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine( 6082): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 6082): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 6082): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 6082): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 6082): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 6082): entry::IDLE
,E/SMD     (  294): DCD ON
,I/ActivityManager(  891): Waited long enough for: ServiceRecord{205fafd7 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1482): disconnect managed GoogleApiClient
,D/SSRM:n  (  891): SIOP:: AP = 310, PST = 318, CUR = 450
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 6
,V/AlarmManager(  891): waitForAlarm result :4
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 310, PST = 317, CUR = 450
,E/SMD     (  294): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 105s ago
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 300, PST = 316, CUR = 450
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/Atfwd_Sendcmd(  357): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  357): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 300, PST = 315, CUR = 450
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/Watchdog(  891): !@Sync 7
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  (  891): SIOP:: AP = 300, PST = 314, CUR = 450
,E/SMD     (  294): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): stay LED for fully charged
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1749): Module APK com.google.android.play.games already loaded
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 1749): 0 accounts found with uca feature
,I/GamesSyncAdapter( 1749): Starting sync for 3a3529a
,I/GamesSyncAdapter( 1749): Sync duration for 3a3529a: 3
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1749): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1749): Module APK com.google.android.play.games already loaded
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 140s ago
,D/SSRM:n  (  891): SIOP:: AP = 300, PST = 314, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 300, PST = 314, CUR = 450
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 8
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 300, PST = 311, CUR = 450
,V/AlarmManager(  891): waitForAlarm result :4
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 300, PST = 304, CUR = 450
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 180s ago
,D/SSRM:n  (  891): SIOP:: AP = 300, PST = 302, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 9
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ClearcutLoggerApiImpl( 1749): disconnect managed GoogleApiClient
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 300, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 298, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 297, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  891): initializing...
,I/TLC_TIMA_PKM_initialize(  891): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  891): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  891): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  891): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  891): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  891): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  891): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  891): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  891): App is not loaded in QSEE
,D/QSEECOMAPI: (  891): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  891): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  891): Trustlet response is completed
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 300, PST = 297, CUR = 450
,I/jxcore-log( 6208): Connected to the server!
I/jxcore-log( 6208): 
,I/chromium( 6208): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,I/Atfwd_Sendcmd(  357): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  357): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  891): [PWL] Off : 225s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3378): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 3378): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 296, CUR = 450,
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  891): waitForAlarm result :4
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): stay LED for fully charged
,E/Zygote  ( 7166): MountEmulatedStorage()
,I/ActivityManager(  891): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7166 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,E/Zygote  ( 7166): v2
I/libpersona( 7166): KNOX_SDCARD checking this for 10096
I/libpersona( 7166): KNOX_SDCARD not a persona
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,I/SELinux ( 7166): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
I/SELinux ( 7166): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SELinux ( 7166): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 7166): TimaSignature is unavailable
,D/ActivityThread( 7166): Added TimaKeyStore provider
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager( 7166): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  891): Killing 3378:com.android.vending/u0a33 (adj 13): bgCount ##41
,E/SMD     (  294): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6310): Disconnected process message: 10
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 11
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 294, CUR = 450
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 293, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 292, CUR = 450
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 275s ago
,E/Watchdog(  891): !@Sync 12
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 291, CUR = 450
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 13
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 291, CUR = 450
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 330s ago
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 14
,E/SMD     (  294): DCD ON
,I/Atfwd_Sendcmd(  357): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  357): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 15
,E/SMD     (  294): DCD ON
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1572): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1572): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1572): Tagging socket 66 with tag 1000040100000000{268436481,0} uid 10015, pid: 1572, getuid(): 10015
,I/qtaguid ( 1572): Tagging socket 73 with tag 1000040100000000{268436481,0} uid 10015, pid: 1572, getuid(): 10015
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1749): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/bootchecker(  352): bootchecker wake up!!
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PowerManagerService(  891): [PWL] Off : 390s ago
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 16
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 17
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  357): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  357): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 455s ago
,E/Watchdog(  891): !@Sync 18
,E/SMD     (  294): DCD ON
,I/Atfwd_Sendcmd(  357): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  357): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,I/Atfwd_Daemon(  357): Stop the daemon....
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 19
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 289, CUR = 450
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 289, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  891): [PWL] Off : 525s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 289, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 288, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 21
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 285, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 22
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 283, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 600s ago
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 282, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 23
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 24
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  891): !@Sync 25
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 680s ago
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/LightsService(  891): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  891): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  891): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog(  891): !@Sync 26
,I/EventLogService( 1749): Aggregate from 1449669872045 (log), 1449669872045 (data)
,D/LightsService(  891): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  891): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  891): unregisterListener ::   
,D/LightsService(  891): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 27
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 28
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 765s ago
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): stay LED for fully charged
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 29
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 31
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  891): [PWL] Off : 855s ago
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 32
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 33
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 34
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 950s ago
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 35
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  891): !@Sync 36
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  891): !@Sync 37
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1050s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  891): !@Sync 38
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  891): !@Sync 39
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  891): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  891): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  891): Updating Usage Statistics in DB @ 1449672336138
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  891): Done Updating Usage Statistics in DB @ 1449672336347
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  891): !@Sync 40
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  891): !@Sync 41
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1155s ago
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  294): DCD ON
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  891): !@Sync 42
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  891): !@Sync 43
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  891): !@Sync 44
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1265s ago
,E/Watchdog(  891): !@Sync 45
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 46
,V/AlarmManager(  891): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,D/LightsService(  891): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  891): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  891): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  891): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  891): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  891): unregisterListener ::   
,D/LightsService(  891): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 47
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  294): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 48
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1380s ago
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 49
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,E/SMD     (  294): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog(  891): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 51
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 52
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1500s ago
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 53
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 54
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 55
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 56
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1625s ago
,E/Watchdog(  891): !@Sync 57
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 58
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 59
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/NetworkStatsFactory(  891): UpdateStatsForKnox
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,E/SMD     (  294): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  891): !@Sync 60
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,V/NetworkStats(  891): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  891): UpdateStatsForKnox
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,V/NetworkStats(  891): performPollLocked() took 68ms
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,I/ActivityManager(  891): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=7320 uid=10033 gids={50033, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7320): MountEmulatedStorage()
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
E/Zygote  ( 7320): v2
,I/libpersona( 7320): KNOX_SDCARD checking this for 10033
I/libpersona( 7320): KNOX_SDCARD not a persona
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,I/SELinux ( 7320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,I/SELinux ( 7320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7320): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ProcessStatsService(  891): Prepared write state in 26ms
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,I/ProcessStatsService(  891): Prepared write state in 9ms
D/TimaKeyStoreProvider( 7320): TimaSignature is unavailable
,D/ActivityThread( 7320): Added TimaKeyStore provider
,I/ProcessStatsService(  891): Prepared write state in 9ms
,D/ResourcesManager( 7320): creating new AssetManager and set to /data/app/com.android.vending-2/base.apk
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ProcessStatsService(  891): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-44-05.bin
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1572): (HTTPLog)-Static: isSBSettingEnabled false
,D/Finsky  ( 7320): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/System.out( 1572): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1572): Tagging socket 58 with tag 1000040100000000{268436481,0} uid 10015, pid: 1572, getuid(): 10015
,I/qtaguid ( 1572): Tagging socket 69 with tag 1000040100000000{268436481,0} uid 10015, pid: 1572, getuid(): 10015
,D/Finsky  ( 7320): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 7320): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7320): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7320): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Ads     ( 7320): Skipping gmscore version check
,D/Finsky  ( 7320): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7320): [1] Libraries$2.run: Finished loading 1 libraries.
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7320): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7320): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/System.out( 7320): Thread-1142(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7320): Thread-1142(ApacheHTTPLog):isShipBuild true
,I/System.out( 7320): Thread-1142(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 7320): Tagging socket 44 with tag e8d195d100000000{3906049489,0} uid -1, pid: 7320, getuid(): 10033
,I/qtaguid ( 7320): Tagging socket 48 with tag e8d195d100000000{3906049489,0} uid -1, pid: 7320, getuid(): 10033
,I/qtaguid ( 7320): Untagging socket 44
,I/System.out( 7320): Thread-1142 calls detatch()
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 7320): Untagging socket 44
,I/qtaguid ( 7320): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 7320): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 7320): untagSocket(44) failed with errno -22
,I/System.out( 7320): Thread-1143 calls detatch()
,D/Finsky  ( 7320): [1] SelfUpdateScheduler.checkForSelfUpdate: Starting DFE self-update from local version [80430000] to server version [80430500]
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7411): MountEmulatedStorage()
,E/Zygote  ( 7411): v2
I/libpersona( 7411): KNOX_SDCARD checking this for 10015
I/libpersona( 7411): KNOX_SDCARD not a persona
,I/SELinux ( 7411): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7411): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7411): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager(  891): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7411 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 7411): TimaSignature is unavailable
,I/qtaguid ( 7320): Tagging socket 49 with tag e8d195d100000000{3906049489,0} uid -1, pid: 7320, getuid(): 10033
,D/ActivityThread( 7411): Added TimaKeyStore provider
,V/AlarmManager(  891): waitForAlarm result :4
,I/qtaguid ( 7320): Tagging socket 52 with tag e8d195d100000000{3906049489,0} uid -1, pid: 7320, getuid(): 10033
,D/Finsky  ( 7320): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ResourcesManager( 7411): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/ResourcesManager( 7411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/qtaguid ( 7320): Untagging socket 44
I/qtaguid ( 7320): Failed write_ctrl(u 44) res=-1 errno=22
,I/qtaguid ( 7320): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 7320): untagSocket(44) failed with errno -22
I/System.out( 7320): Thread-1142 calls detatch()
,D/Finsky  ( 7320): [1] DownloadImpl.setState: Duplicate state set for 'com.android.vending' (0). Already in that state
,D/Finsky  ( 7320): [1] DownloadQueueImpl.add: Download com.android.vending added to DownloadQueue
,D/Finsky  ( 7320): [1] DownloadImpl.setState: com.android.vending from 0 to 1.
,D/PackageManager(  891): START FREE STORAGE AND NOTIFY: observer{403549353}
D/PackageManager(  891): freeStorageSize{0}
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageManager(  891): [MSG] FREE_STORAGE_AND_NOTIFY
,I/installd(  308): free_cache(0) avail 25688178688
D/PackageManager(  891): result of freeStorageAndNotify: 0{403549353}
,D/Finsky  ( 7320): [1] StartNextDownloadRunnable.run: Download com.android.vending starting
,I/qtaguid ( 7320): Untagging socket 49
,I/System.out( 7320): Thread-1143 calls detatch()
,I/MultiDex( 7411): VM with version 2.1.0 has multidex support
I/MultiDex( 7411): install
I/MultiDex( 7411): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 7320): [1145] DownloadQueueImpl$7.run: Enqueued com.android.vending as content://downloads/my_downloads/21
D/Finsky  ( 7320): [1] DownloadImpl.setState: com.android.vending from 1 to 2.
,D/Finsky  ( 7320): [1] DownloadQueueImpl.onStart: com.android.vending: onStart
,I/qtaguid ( 7320): Untagging socket 44
,I/qtaguid ( 7320): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 7320): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 7320): untagSocket(44) failed with errno -22
I/System.out( 7320): Thread-1142 calls detatch()
,D/Finsky  ( 7320): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update check as there is an update already queued.
,D/Finsky  ( 7320): [1] DownloadQueueImpl.notifyProgress: com.android.vending: onProgress 0/-1 Status: 190.
,V/JNIHelp ( 7411): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/Finsky  ( 7320): [1] DownloadQueueImpl.notifyProgress: com.android.vending: onProgress 0/-1 Status: 192.
,D/DownloadManager( 1239): [21] Starting com.android.vending
,I/System.out( 1239): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityThread( 1239): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ActivityThread( 7411): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7411): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@163b250c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7411): Installed default security provider GmsCore_OpenSSL
,E/DownloadManager( 1239): SB enabled 
,I/System.out( 1239): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1239): (HTTPLog)-Static: isShipBuild true
I/System.out( 1239): (HTTPLog)-Thread-61-984408338: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1239): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1239): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1239): Tagging socket 56 with tag ffffff0100000000{4294967041,0} uid 10033, pid: 1239, getuid(): 10052
,D/WearableService( 1482): callingUid 10015, callindPid: 1482
,E/MDM     ( 1482): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1572): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/SMD     (  294): DCD ON
,D/AuthorizationBluetoothService( 1572): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1749): Restart initialization of location
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1749): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/art     ( 7411): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/art     ( 7411): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  891): waitForAlarm result :4
,D/NativeLibraryUtils( 7411): Install completed successfully. count=13 extracted=0
,W/GCoreFlp( 1482): No location to return for getLastLocation()
,W/FusedLocationProvider( 1572): location=null
,D/ResourcesManager( 7411): creating new AssetManager and set to /data/app/com.android.vending-2/base.apk
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/Finsky  ( 7320): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/qtaguid ( 1239): Tagging socket 63 with tag ffffff0100000000{4294967041,0} uid 10033, pid: 1239, getuid(): 10052
,I/qtaguid ( 1239): Untagging socket 56
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/DownloadManager( 1239): SB enabled 
,I/System.out( 1239): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1239): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1239): Tagging socket 64 with tag ffffff0100000000{4294967041,0} uid 10033, pid: 1239, getuid(): 10052
,D/Finsky  ( 7320): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 7320): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  891): waitForAlarm result :4
,D/Finsky  ( 7320): [1164] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1482): client connected with version: 8296000
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 7320): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7320): (HTTPLog)-Static: isShipBuild true
I/System.out( 7320): (HTTPLog)-Thread-1153-105891142: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7320): (HTTPLog)-Static: isSBSettingEnabled false
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
V/NetworkStats(  891): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  891): UpdateStatsForKnox
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  891): performPollLocked() took 36ms
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,I/System.out( 7320): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,V/NetworkStats(  891): performPollLocked(flags=0x1)
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  891): UpdateStatsForKnox
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  891): performPollLocked() took 32ms
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,I/ActivityManager(  891): Killing 6414:com.sec.android.provider.badge/u0a92 (adj 15): bgCount ##41
,V/NetworkStats(  891): performPollLocked(flags=0x1)
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  891): UpdateStatsForKnox
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  891): performPollLocked() took 29ms
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,V/NetworkStats(  891): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  891): UpdateStatsForKnox
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  891): performPollLocked() took 32ms
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,I/WifiTrafficPoller(  891): Dynamic booster is mCpuFreqIndex_1. mCpuFreqIndex_1 is 8
,D/CustomFrequencyManagerService(  891): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 883200  uid : 1000  pid : 891  pkgName : WIFI_TP@4
,V/NetworkStats(  891): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  891): UpdateStatsForKnox
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NetworkStats(  891): performPollLocked() took 95ms
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,I/art     (  891): Explicit concurrent mark sweep GC freed 60492(5MB) AllocSpace objects, 141(2MB) LOS objects, 17% free, 37MB/45MB, paused 1.589ms total 117.027ms
,I/qtaguid ( 7320): Untagging socket 44
,I/qtaguid ( 7320): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 7320): Untagging socket 44 failed errno=-22
,W/NetworkManagementSocketTagger( 7320): untagSocket(44) failed with errno -22
I/System.out( 7320): Thread-1142 calls detatch()
,D/DownloadManager( 1239): [21] Finished with status SUCCESS
,V/DownloadManager( 1239): MIME Type = application/vnd.android.package-archive
,I/DownloadManager( 1239): Download 21 finished with status SUCCESS
,D/Finsky  ( 7320): [1] DownloadQueueImpl.notifyProgress: com.android.vending: onProgress 15156597/15156597 Status: 200.
,D/Finsky  ( 7320): [1] DownloadBroadcastReceiver.onReceive: Intent received at DownloadBroadcastReceiver
,D/Finsky  ( 7320): [1] DownloadImpl.setState: com.android.vending from 2 to 3.
,D/Finsky  ( 7320): [1] DownloadQueueImpl.onComplete: com.android.vending: onComplete
D/Finsky  ( 7320): [1] DownloadQueueImpl.remove: Download com.android.vending removed from DownloadQueue
D/PackageManager(  891): START FREE STORAGE AND NOTIFY: observer{326330691}
D/PackageManager(  891): freeStorageSize{0}
,D/PackageManager(  891): [MSG] FREE_STORAGE_AND_NOTIFY
D/Finsky  ( 7320): [1] SelfUpdateScheduler.onComplete: Self-update ready to be installed, waiting for market to close.
I/installd(  308): free_cache(0) avail 25673031680
D/PackageManager(  891): result of freeStorageAndNotify: 0{326330691}
,D/Finsky  ( 7320): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 7320): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  891): waitForAlarm result :4
,D/DeviceConnectionService( 1482): client connected with version: 8296000
,D/Finsky  ( 7320): [1167] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 7320): (HTTPLog)-Static: isSBSettingEnabled false
,V/AlarmManager(  891): waitForAlarm result :8
,I/WifiTrafficPoller(  891): Dynamic booster is mCpuFreqIndex_2. mCpuFreqIndex_2 is 8
,D/CustomFrequencyManagerService(  891): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 883200  uid : 1000  pid : 891  tag : WIFI_TP@4
,D/CustomFrequencyManagerService(  891): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 883200  uid : 1000  pid : 891  pkgName : WIFI_TP@4
,D/SSRM:n  (  891): SIOP:: AP = 300, PST = 282, CUR = 450
,E/SMD     (  294): DCD ON
,D/CustomFrequencyManagerService(  891): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 883200  uid : 1000  pid : 891  tag : WIFI_TP@4
,I/ActivityManager(  891): Killing 6461:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/SQLiteConnectionPool( 1749): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/Watchdog(  891): !@Sync 61
,W/ActivityManager(  891): getRecentTasks: caller 10033 is using old GET_TASKS but privileged; allowing
,E/SMD     (  294): DCD ON
,D/PackageManager(  891): START_PACKAGE_INSTALL: observer{383351447}
D/PackageManager(  891):           originPath{/data/data/com.android.providers.downloads/cache/downloadfile-4.apk}
,D/PackageManager(  891): [MSG] INIT_COPY: observer{383351447}
D/PackageManager(  891):           idx{0}
D/PackageManager(  891):           for_user{UserHandle{0}}
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  891): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7494 uid=10007 gids={50007, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,E/Zygote  ( 7494): MountEmulatedStorage()
E/Zygote  ( 7494): v2
I/libpersona( 7494): KNOX_SDCARD checking this for 10007
I/libpersona( 7494): KNOX_SDCARD not a persona
,I/SELinux ( 7494): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7494): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7494): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7494): TimaSignature is unavailable
,D/ActivityThread( 7494): Added TimaKeyStore provider
,D/ResourcesManager( 7494): creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
,D/PackageManager(  891): [MSG] MCS_BOUND: observer{383351447}
D/PackageManager(  891):           for_user{UserHandle{0}}
,D/PersonaManagerService(  891): needVerificationForPackage  
,D/PersonaManagerService(  891): needVerificationForPackage com.android.vending
D/PersonaManagerService(  891): needVerificationForPackage return true for  at the end com.android.vending
D/PackageManager(  891): Found 1 verifiers for intent Intent { act=android.intent.action.PACKAGE_NEEDS_VERIFICATION dat=file:///data/data/com.android.providers.downloads/cache/downloadfile-4.apk typ=application/vnd.android.package-archive flg=0x1 } with 0 optional verifiers
,D/PackageManager(  891): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 7320): [1] PackageVerificationReceiver.onReceive: Skipping verification because own installation
,D/PackageManager(  891): [MSG] PACKAGE_VERIFIED: observer{383351447}
D/PackageManager(  891):           verificationId{0}
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 7320): [1] PackageVerificationReceiver.onReceive: Verification requested, id = 0
,D/DefContainer( 7494): Copying /data/data/com.android.providers.downloads/cache/downloadfile-4.apk to base.apk
,D/PackageManager(  891): remove MCS_UNBIND and Posting MCS_UNBIND
D/PackageManager(  891): [MSG] PROCESS_PENDING_INSTALL: observer{383351447}
D/PackageManager(  891): currentStatus{1}
D/PackageManager(  891): installPackageLI: path
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 283, CUR = 450
,W/PackageManager(  891): verifying app can be installed or not
,D/ApplicationPolicy(  891): isApplicationInstallationEnabled
D/ApplicationPolicy(  891): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy(  891): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  891): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  891): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy(  891): isApplicationInstallationEnabled :  Checking PKG WL - false
,D/ApplicationPolicy(  891): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  891): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  891): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy(  891): isApplicationInstallationEnabled :  enabled true
I/AASAInstall(  891): product true
,I/AASAUninstall(  891):  com.android.vending not target!
,D/PackageManager(  891): Replace existing pacakge
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.android.vending
,D/PackageManager(  891): Existing package
D/PackageManager(  891): Renaming /data/app/vmdl1886857520.tmp to /data/app/com.android.vending-1
,D/PackageManager(  891): replacePackageLI
,D/PackageManager(  891): !@killApplicatoin: 10033, replace sys pkg
I/ActivityManager(  891): Force stopping com.android.vending appid=10033 user=-1: replace sys pkg
I/ActivityManager(  891): Killing 7320:com.android.vending/u0a33 (adj 9): stop com.android.vending
,W/PackageManager(  891): Trying to update system app code path from /data/app/com.android.vending-2 to /data/app/com.android.vending-1
,I/art     (  891): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.android.vending-1@base.apk@classes.dex' for file location '/data/app/com.android.vending-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     (  891): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.android.vending-1/arm/base.odex' for file location '/data/app/com.android.vending-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager(  891): Running dexopt on: /data/app/com.android.vending-1/base.apk pkg=com.android.vending isa=arm vmSafeMode=false interpret_only=false
,W/ActivityManager(  891): Spurious death for ProcessRecord{32f130d2 7320:com.android.vending/u0a33}, curProc for 7320: null
,I/dex2oat ( 7511): ----------------------------------------------------
,I/dex2oat ( 7511): <SS>: S T A R T I N G . . .
I/dex2oat ( 7511): <SS>: going to process manifest...
,I/        ( 7511): SS_ART_lib [I]: Parsing Manifest for SS stuff
,I/dex2oat ( 7511): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.android.vending-1/base.apk --oat-fd=12 --oat-location=/data/dalvik-cache/arm/data@app@com.android.vending-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/SMD     (  294): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,W/ActivityManager(  891): Unable to start service Intent { flg=0x4 cmp=com.android.vending/com.google.android.finsky.services.ContentSyncService (has extras) } U=0: not found
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4298, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1755s ago
,I/dex2oat ( 7511): dex2oat took 5.441s (threads: 4)
,I/PackageManager(  891): do mInstaller.dexopt : 0
D/PackageManager(  891): Time to dexopt: 5.617 seconds
,D/PackageManager(  891): !@killApplicatoin: 10033, update pkg
I/ActivityManager(  891): Force stopping com.android.vending appid=10033 user=-1: update pkg
,W/PackageManager(  891): Code path for pkg : com.android.vending changing from /data/app/com.android.vending-2 to /data/app/com.android.vending-1
W/PackageManager(  891): Resource path for pkg : com.android.vending changing from /data/app/com.android.vending-2 to /data/app/com.android.vending-1
,W/PackageSettings(  891): Skipping PackageSetting{a31cdb3 com.example.hello/10268} due to missing metadata
,D/PackageManager(  891): New package installed
,I/AASAInstall(  891): shared uid app without token:com.android.providers.userdictionary
I/AASAInstall(  891): shared uid app without token:com.sec.android.app.easylauncher
,I/AASAInstall(  891): shared uid app without token:com.google.android.apps.maps
W/AASAInstall(  891):  mAASATempBlackList  updated  :com.android.contacts  uid=10024
I/AASAInstall(  891): blacklist package=com.android.contacts     pem=android.permission.DEVICE_POWER
I/AASAInstall(  891): blacklist package=com.android.contacts     pem=android.permission.INTERACT_ACROSS_USERS_FULL
I/AASAInstall(  891): shared uid app without token:com.android.contacts
,I/AASAInstall(  891): shared uid app without token:com.samsung.android.providers.context
I/AASAInstall(  891): shared uid app without token:com.android.systemui
I/AASAInstall(  891): shared uid app without token:com.android.providers.calendar
,I/AASAInstall(  891): shared uid app without token:com.android.providers.downloads
I/AASAInstall(  891): shared uid app without token:com.google.android.gsf
I/AASAInstall(  891): shared uid app without token:com.android.providers.contacts
,I/AASAInstall(  891): shared uid app without token:com.samsung.android.scloud.proxy.calendar
I/AASAInstall(  891): shared uid app without token:com.sec.android.widgetapp.easyfavoritescontactswidget
I/AASAInstall(  891): shared uid app without token:com.samsung.android.scloud.proxy.contacts
,W/AASAInstall(  891):  mAASATempBlackList  updated  :com.google.android.gms  uid=10015
I/AASAInstall(  891): blacklist package=com.google.android.gms     pem=android.permission.PACKAGE_USAGE_STATS
I/AASAInstall(  891): blacklist package=com.google.android.gms     pem=android.permission.MODIFY_AUDIO_ROUTING
I/AASAInstall(  891): blacklist package=com.google.android.gms     pem=android.permission.MANAGE_DOCUMENTS
I/AASAInstall(  891): shared uid app without token:com.google.android.gms
,I/AASAInstall(  891): shared uid app without token:com.sec.android.app.launcher
W/AASAInstall(  891):  mAASATempBlackList  updated  :com.google.android.gsf.login  uid=10015
I/AASAInstall(  891): blacklist package=com.google.android.gsf.login     pem=android.permission.CONTROL_KEYGUARD
I/AASAInstall(  891): shared uid app without token:com.google.android.gsf.login
,I/AASAInstall(  891): shared uid app without token:com.android.providers.downloads.ui
I/AASAInstall(  891): shared uid app without token:com.google.android.marvin.talkback
,I/AASAInstall(  891): shared uid app without token:com.sec.android.provider.logsprovider
I/AASAInstall(  891): shared uid app without token:com.samsung.android.scloud.sync
,I/AASAInstall(  891): shared uid app without token:com.samsung.android.scloud.proxy.sbrowser
,I/AASAInstall(  891): shared uid app without token:com.google.android.syncadapters.contacts
I/AASAInstall(  891): shared uid app without token:com.google.android.syncadapters.calendar
I/AASAInstall(  891): shared uid app without token:com.google.android.backuptransport
I/AASAInstall(  891): shared uid app without token:com.android.providers.media
,D/EnterpriseDeviceManagerService(  891): updateAdminPermissions
W/PackageManager(  891): Not granting permission android.permission.REAL_GET_TASKS to package com.android.vending (protectionLevel=18 flags=0x404abec5)
W/PackageManager(  891): Not granting permission android.permission.SEND_DOWNLOAD_COMPLETED_INTENTS to package com.android.vending (protectionLevel=2 flags=0x404abec5)
,W/PackageManager(  891): Unknown permission android.permission.USE_FINGERPRINT in package com.android.vending
W/PackageManager(  891): Unknown permission android.permission.GET_PACKAGE_IMPORTANCE in package com.android.vending
W/PackageManager(  891): Unknown permission android.permission.GET_ACCOUNTS_PRIVILEGED in package com.android.vending
W/PackageManager(  891): Unknown permission android.permission.INSTALL_GRANT_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  891): Unknown permission android.permission.GRANT_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  891): Unknown permission android.permission.REVOKE_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  891): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.android.vending
W/PackageManager(  891): Not granting permission android.permission.BATTERY_STATS to package com.android.vending (protectionLevel=50 flags=0x404abec5)
,W/PackageSettings(  891): Skipping PackageSetting{a31cdb3 com.example.hello/10268} due to missing metadata
,D/PackageManager(  891): doPostInstall for uid{10033}
,D/PackageManager(  891): [MSG] MCS_UNBIND
,D/PackageManager(  891): [MSG] POST_INSTALL: observer{383351447}
D/PackageManager(  891):           Handling post-install for 2
,I/ActivityManager(  891): Force stopping com.android.vending appid=10033 user=0: pkg removed
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
,I/KLMS-2.4.511: ( 6688): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/SamsungIME( 1721): mOCRHelper is null
,I/KLMS-2.4.511: ( 6688): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449672978238
,E/ActivityManager(  891): com.android.vending package replaced
I/KLMS-2.4.511: ( 6688): MainReciver(): PACKAGE_REMOVED
,I/art     ( 3156): Explicit concurrent mark sweep GC freed 36704(2012KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 15MB/26MB, paused 600us total 35.353ms
,I/KLMS-2.4.511: ( 6688): MainReciver(): REPLACING: true | pkgName: com.android.vending
,D/ResourcesManager( 1439): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1721): mOCRHelper is null
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/elm:14491( 6803): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.android.vending flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
,W/Settings(  891): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,D/elm:14491( 6803): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.android.vending flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
,D/DynamicService( 1403): Ignoring package intent due to package being replaced.
,E/Zygote  ( 7540): MountEmulatedStorage()
I/ActivityManager(  891): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7540 uid=10021 gids={50021, 9997} abi=armeabi-v7a
E/Zygote  ( 7540): v2
I/libpersona( 7540): KNOX_SDCARD checking this for 10021
I/libpersona( 7540): KNOX_SDCARD not a persona
,D/elm:14491( 6803): ElmAgentService : onCreate()
D/elm:14491( 6803): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.android.vending flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/SELinux ( 7540): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/elm:14491( 6803): ElmAgentService : onDestroy().
,I/SELinux ( 7540): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7540): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  891): Explicit concurrent mark sweep GC freed 35463(2MB) AllocSpace objects, 8(128KB) LOS objects, 16% free, 40MB/48MB, paused 1.959ms total 172.535ms
,D/RCPManagerService(  891): PackageReceiver onReceive()
I/art     (  891): WaitForGcToComplete blocked for 85.624ms for cause Explicit
,I/HarmonyEASService(  891): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  891): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.android.vending flg=0x4000010 (has extras) }
D/JobSchedulerService(  891): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  891): uID is 10033
V/EnterpriseBillingPolicy(  891): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  891): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  891): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  891): getBillingProfileForVpnEngine - start - com.android.vending
V/EnterpriseBillingPolicyStorage(  891): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/TimaKeyStoreProvider( 7540): TimaSignature is unavailable
D/ActivityThread( 7540): Added TimaKeyStore provider
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 7540): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,I/Launcher.Workspace( 1439): isBadgeUpdate : false
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/SQLiteConnectionPool(  891): exportDB...
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 7540): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7540): onReceive called  PACKAGE_REMOVED package:com.android.vending
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7540): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/DynamicService( 1403): Ignoring package intent due to package being replaced.
,E/Zygote  ( 7556): MountEmulatedStorage()
E/Zygote  ( 7556): v2
I/libpersona( 7556): KNOX_SDCARD checking this for 10025
I/libpersona( 7556): KNOX_SDCARD not a persona
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Books/Books.apk
,I/ActivityManager(  891): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=7556 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6445:com.samsung.shareshot/u0a192 (adj 15): bgCount ##41
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/SQLiteConnectionPool(  891): ...exportDB
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/SELinux ( 7556): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/SELinux ( 7556): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/RegisteredServicesCache( 1403): empty dynamic service
,E/SELinux ( 7556): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EnterpriseDeviceManagerService(  891): onPackageUpdateFinished - packageName: com.android.vending, uid: 10033
,D/EnterpriseDeviceManagerService(  891): Package has changed for user 0
D/EnterpriseDeviceManagerService(  891): Admin package name: com.google.android.gms
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/TimaKeyStoreProvider( 7556): TimaSignature is unavailable
,D/ActivityThread( 7556): Added TimaKeyStore provider
,D/ResourcesManager( 7556): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
,W/ResourcesManager( 7556): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  891): PackageReceiver onReceive()
D/RCPManagerService(  891): App Installed with packageNAme = com.android.vending
D/RCPManagerService(  891):  PackageReceiver onReceive() bundle Bundle[{com.google.android.gms.version=8296000, com.google.android.gms.car.application=2131165184}]
D/RCPManagerService(  891):  PackageReceiver onReceive() proxyName null proxyService null
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.android.vending
D/KnoxMUMContainerPolicy(  891): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.android.vending flg=0x4000010 (has extras) }
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService(  891): Now staging backup of com.android.vending
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,W/linker  ( 7556): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/MVFD_interface( 7556): <<<  caMVFace_FaceInit
,V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy(  891): uID is 10033
V/EnterpriseBillingPolicy(  891): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  891): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  891): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  891): getBillingProfileForVpnEngine - start - com.android.vending
V/EnterpriseBillingPolicyStorage(  891): getBillingProfileForVpnEngine - end - null
,D/PersonaPolicyManagerService(  891): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.android.vending
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/KnoxMUMContainerPolicy(  891): packageInstalledForExternalStorage com.android.vending
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7556): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7556): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,I/art     (  891): Explicit concurrent mark sweep GC freed 60184(3MB) AllocSpace objects, 2(603KB) LOS objects, 17% free, 37MB/45MB, paused 2.930ms total 314.014ms
,D/HockeyApp( 7556): Current handler class = sstream.app.util.Log$1
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager(  891): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  891): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  891): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager(  891): delete codoeFile: 
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/PackageManager(  891): result of install: 1{383351447}
,I/PackageManager(  891): Observer no longer exists.
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
D/ResourcesManager( 7556): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7556): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ApplicationCompatibleReceiver( 7556): com.sec.chaton Already existed in setting table , SKIP!!!
,D/ResourcesManager( 7556): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 7556): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7556): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7556): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7556): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7556): Asset path '/system/framework/videowall.jar' does not exist or contains no resources.
,W/ResourcesManager( 7556): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_PushUtil( 5845): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5845): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5845): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5845): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/ApplicationCompatibleReceiver( 7556): com.sec.android.app.videoplayer Already existed in setting table , SKIP!!!
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7556): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,W/ResourcesManager( 7556): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7556): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7556): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7556): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7556): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7556): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7556): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/ResourcesManager( 7556): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/ApplicationCompatibleReceiver( 7556): com.sec.pcw Already existed in setting table , SKIP!!!
W/ResourcesManager( 7556): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7556): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7556): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7556): Asset path '/system/framework/svi.jar' does not exist or contains no resources.
W/ResourcesManager( 7556): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7556): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 7556): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Books/Books.apk
W/ResourcesManager( 7556): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ApplicationCompatibleReceiver( 7556): com.samsung.android.app.pinboard Already existed in setting table , SKIP!!!
,D/ResourcesManager( 7556): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7556): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7556): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7556): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/SQLiteLog( 7556): (1299) abort at 20 in [INSERT INTO config(selected,category,native_package_names,image_unselected,image_selected,login,application_name,visible,native_app_required,config_id,stream_id,source_icon) VALUES (?,?,?,?,?,?
,E/SQLiteDatabase( 7556): Error inserting selected=1 category=com.android.calendar native_package_names=null image_unselected=2130903040 image_selected=2130903040 login=0 application_name=2131690540 visible=1 native_app_required=0 config_id=com.android.calendar stream_id=null source_icon=0
E/SQLiteDatabase( 7556): android.database.sqlite.SQLiteConstraintException: NOT NULL constraint failed: config.stream_id (code 1299)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1595)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1465)
E/SQLiteDatabase( 7556): 	at sstream.app.provider.StoryProvider.insertOne(StoryProvider.java:352)
E/SQLiteDatabase( 7556): 	at sstream.app.provider.StoryProvider.insert(StoryProvider.java:263)
E/SQLiteDatabase( 7556): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 7556): 	at android.content.ContentResolver.insert(ContentResolver.java:1217)
E/SQLiteDatabase( 7556): 	at sstream.app.provider.DatabaseUtil.storeConfigSetting(DatabaseUtil.java:784)
E/SQLiteDatabase( 7556): 	at sstream.app.receiver.ApplicationCompatibleReceiver.addCompatibleAppsToDB(ApplicationCompatibleReceiver.java:420)
E/SQLiteDatabase( 7556): 	at sstream.app.receiver.ApplicationCompatibleReceiver.getCompatibleApps(ApplicationCompatibleReceiver.java:155)
E/SQLiteDatabase( 7556): 	at sstream.app.StreamManager$1.run(StreamManager.java:177)
,E/Zygote  ( 7590): MountEmulatedStorage()
E/Zygote  ( 7590): v2
I/libpersona( 7590): KNOX_SDCARD checking this for 10039
I/libpersona( 7590): KNOX_SDCARD not a persona
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager(  891): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7590 uid=10039 gids={50039, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 4305:com.samsung.android.snote/u0a168 (adj 15): bgCount ##41
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     (  330): Explicit concurrent mark sweep GC freed 8710(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 4.460ms total 19.632ms
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/CrashAnrDetector(  891): onPackageUpdateFinished : com.android.vending
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 266us total 10.716ms
,I/SELinux ( 7590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7590): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ApplicationCompatibleReceiver( 7556): com.sec.android.gallery3d Already existed in setting table , SKIP!!!
D/ResourcesManager( 7556): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 385us total 10.823ms
,D/ApplicationCompatibleReceiver( 7556): com.sec.android.app.samsungapps Already existed in setting table , SKIP!!!
,D/ApplicationCompatibleReceiver( 7556): com.samsung.android.snote Already existed in setting table , SKIP!!!
,D/TimaKeyStoreProvider( 7590): TimaSignature is unavailable
,D/ActivityThread( 7590): Added TimaKeyStore provider
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig( 7590): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 7590): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/System.out( 7556): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7556): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7556): (HTTPLog)-Static: isShipBuild true
I/System.out( 7556): (HTTPLog)-Static: isShipBuild true
I/System.out( 7556): (HTTPLog)-Thread-1163-636360998: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7556): (HTTPLog)-Thread-1165-636360998: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7556): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7556): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7556): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7556): (HTTPLog)-Static: isShipBuild true
I/System.out( 7556): (HTTPLog)-Thread-1164-191789415: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7556): (HTTPLog)-Static: isSBSettingEnabled false
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/svi.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/videowall.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SMD     (  294): DCD ON
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/System.out( 7556): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/System.out( 7556): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/System.out( 7556): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 7556): Tagging socket 50 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 7556, getuid(): 10025
I/qtaguid ( 7556): Tagging socket 51 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 7556, getuid(): 10025
I/qtaguid ( 7556): Tagging socket 49 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 7556, getuid(): 10025
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7590): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7590): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7612): MountEmulatedStorage()
E/Zygote  ( 7612): v2
I/libpersona( 7612): KNOX_SDCARD checking this for 10043
I/libpersona( 7612): KNOX_SDCARD not a persona
,I/SELinux ( 7612): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7612): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7612): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  891): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7612 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6644:com.sec.android.cloudagent/u0a4 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7612): TimaSignature is unavailable
,D/ActivityThread( 7612): Added TimaKeyStore provider
,D/ResourcesManager( 3156): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager( 7612): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7612): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7612): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7612): PushLog.txt file is not deleted.
,D/SPPClientService( 7612): PushLog.txt file is not deleted.
D/SPPClientService( 7612): ============PushLog. stop!
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7628): MountEmulatedStorage()
E/Zygote  ( 7628): v2
I/libpersona( 7628): KNOX_SDCARD checking this for 10048
I/libpersona( 7628): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7628 uid=10048 gids={50048, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6704:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,I/SELinux ( 7628): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7628): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7628): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7628): TimaSignature is unavailable
,D/ActivityThread( 7628): Added TimaKeyStore provider
,D/ResourcesManager( 7628): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 7628): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7628): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/SL_DEBUG( 7628): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 7628): isLoggable:: SL_DEBUG_EXIST = false
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ActivityThread( 7628): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
,I/qtaguid ( 7556): Untagging socket 49
,I/qtaguid ( 7556): Untagging socket 50
,I/qtaguid ( 7556): Untagging socket 51
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7628): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7628): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,V/Transcoder( 7628): Transcoder(0xafa0d3d0)::constructor
V/Transcoder( 7628): addObitRecipient
V/TMI-JNI ( 7628): Mobile Transcoder JNI version 1.6.0/20131120/4.4
,I/SA      ( 5931): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5931): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:false extra.UID.:10033 extra.DATA_REMOVED.:false extra.REPLACING.:true extra.user_handle.:0 ]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Mms/FreeMessageReceiver( 4824): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/TactileAssist(  891): enable value -1
I/TactileAssist(  891): internal enable value -1
I/TactileAssist(  891): intensity value -1
I/TactileAssist(  891): saveAppList value true
,I/TactileAssist(  891): List of disabled apps :
,D/Mms/FreeMessageReceiverService( 4824): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4824): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/SettingsProvider(  891): name = reading_mode_app_list
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7657): MountEmulatedStorage()
,E/Zygote  ( 7657): v2
I/libpersona( 7657): KNOX_SDCARD checking this for 10064
I/libpersona( 7657): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7657 uid=10064 gids={50064, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 7657): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7657): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7657): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  891): Killing 6745:com.samsung.android.scloud.sync/u0a76 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7657): TimaSignature is unavailable
,D/ActivityThread( 7657): Added TimaKeyStore provider
,D/ResourcesManager( 7657): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 7657): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility( 7657): onReceive() it will make start service
,D/Compatibility( 7657): onHandleIntent()
,D/Compatibility( 7657): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.android.vending flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=false, android.intent.extra.UID=10033, android.intent.extra.DATA_REMOVED=false, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
D/Compatibility( 7657): found: 2
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 7657): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 7657): skipping ResolveInfo{2f912676 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
,D/Compatibility( 7657): considering ResolveInfo{2fc98477 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7657): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 7657): enabling receiver ResolveInfo{2a33d8e4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 7657): enabling receiver ResolveInfo{2881014d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 7657): enabling receiver ResolveInfo{1be13402 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 7657): enabling receiver ResolveInfo{3847f113 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 7657): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/Zygote  ( 7674): MountEmulatedStorage()
,E/Zygote  ( 7674): v2
I/libpersona( 7674): KNOX_SDCARD checking this for 1000
I/libpersona( 7674): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7674 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7674): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7674): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7674): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  891): Killing 6764:com.sec.android.app.clockpackage/u0a106 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7674): TimaSignature is unavailable
,D/ActivityThread( 7674): Added TimaKeyStore provider
,D/ResourcesManager( 7674): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,W/ContextImpl( 7674): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7690): MountEmulatedStorage()
E/Zygote  ( 7690): v2
I/libpersona( 7690): KNOX_SDCARD checking this for 10112
I/libpersona( 7690): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7690 uid=10112 gids={50112, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7690): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7690): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7690): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  891): Killing 6629:com.sec.android.fotaclient/u0a14 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7690): TimaSignature is unavailable
,D/ActivityThread( 7690): Added TimaKeyStore provider
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/DocsApplication( 7690): Installing DEX configuration.
,D/DexInstaller( 7690): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 7690): Provided clientMode=RELEASE, packageInfo=PackageInfo{3b65e138 com.google.android.apps.docs}
,D/TAG     ( 7690): onCreate()
,D/CrossAppStateProvider( 7690): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/PackageManager(  891): [MSG] CHECK_PENDING_VERIFICATION
,D/SSRM:n  (  891): SIOP:: AP = 370, PST = 292, CUR = 450
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7713): MountEmulatedStorage()
E/Zygote  ( 7713): v2
I/libpersona( 7713): KNOX_SDCARD checking this for 1000
I/libpersona( 7713): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7713 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6784:com.samsung.android.app.pinboard:tagService/u0a36 (adj 15): bgCount ##41
,I/SELinux ( 7713): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,W/GAV2    ( 7690): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 7713): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7713): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7713): TimaSignature is unavailable
,D/ActivityThread( 7713): Added TimaKeyStore provider
,D/ResourcesManager( 7713): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,W/ContextImpl( 7713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7733): MountEmulatedStorage()
,E/Zygote  ( 7733): v2
I/libpersona( 7733): KNOX_SDCARD checking this for 10126
I/libpersona( 7733): KNOX_SDCARD not a persona
,I/SELinux ( 7733): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  891): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7733 uid=10126 gids={50126, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7733): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7733): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 7733): TimaSignature is unavailable
,D/ActivityThread( 7733): Added TimaKeyStore provider
,E/Zygote  ( 7746): MountEmulatedStorage()
,E/Zygote  ( 7746): v2
I/libpersona( 7746): KNOX_SDCARD checking this for 10121
I/libpersona( 7746): KNOX_SDCARD not a persona
,I/SELinux ( 7746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  891): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=7746 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 7746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7733): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/TimaKeyStoreProvider( 7746): TimaSignature is unavailable
,D/ActivityThread( 7746): Added TimaKeyStore provider
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7746): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,E/Zygote  ( 7763): MountEmulatedStorage()
,E/Zygote  ( 7763): v2
I/libpersona( 7763): KNOX_SDCARD checking this for 1000
I/libpersona( 7763): KNOX_SDCARD not a persona
,I/SELinux ( 7763): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  891): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7763 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7763): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7763): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 7746): (284) automatic index on titles(filter_id)
,D/TimaKeyStoreProvider( 7763): TimaSignature is unavailable
,D/ActivityThread( 7763): Added TimaKeyStore provider
,D/ResourcesManager( 7763): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/ActivityManager(  891): Killing 6492:com.vlingo.midas/u0a38 (adj 15): bgCount ##41
,W/ContextImpl( 7713): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:44 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:149 android.os.Handler.dispatchMessage:102 
,I/ActivityManager(  891): Killing 6722:com.sec.android.soagent/u0a42 (adj 15): bgCount ##41
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 7690): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7780): MountEmulatedStorage()
,E/Zygote  ( 7780): v2
I/libpersona( 7780): KNOX_SDCARD checking this for 1000
I/libpersona( 7780): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7780 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 5880:com.policydm/1000 (adj 15): bgCount ##41
,I/SELinux ( 7780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7780): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  891): Killing 6869:com.qualcomm.timeservice/1000 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7780): TimaSignature is unavailable
,D/ActivityThread( 7780): Added TimaKeyStore provider
,D/ResourcesManager( 7780): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,W/ContextImpl( 7780): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2991 
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7797): MountEmulatedStorage()
E/Zygote  ( 7797): v2
I/libpersona( 7797): KNOX_SDCARD checking this for 1000
I/libpersona( 7797): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7797 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7797): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7797): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SMD     (  294): DCD ON
E/SELinux ( 7797): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  891): Killing 6885:com.samsung.android.scloud.backup/u0a74 (adj 15): bgCount ##41
,I/art     (  330): Explicit concurrent mark sweep GC freed 8766(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 312us total 14.036ms
,D/TimaKeyStoreProvider( 7797): TimaSignature is unavailable
,D/ActivityThread( 7797): Added TimaKeyStore provider
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 10.725ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 9.735ms
,D/ResourcesManager( 7797): creating new AssetManager and set to /system/app/PopupuiReceiver/PopupuiReceiver.apk
,D/PopupuiReceiver( 7797): onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,D/SecContentProvider2(  891): uri = -1 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,I/PopupuiReceiver_KNOX( 7797): getSealedState : true
,D/SecContentProvider2(  891): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2(  891): mCursor = null
,I/PopupuiReceiver_KNOX( 7797): getSealedHideNotificationMessages : 1
D/SecContentProvider2(  891): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2(  891): mCursor = null
,I/PopupuiReceiver_KNOX( 7797): getCheckCoverPopupState : true
,D/PopupuiReceiver( 7797): Action package removed
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7812): MountEmulatedStorage()
,E/Zygote  ( 7812): v2
I/libpersona( 7812): KNOX_SDCARD checking this for 10168
I/libpersona( 7812): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=7812 uid=10168 gids={50168, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6853:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7812): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7812): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7812): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7812): TimaSignature is unavailable
,D/ActivityThread( 7812): Added TimaKeyStore provider
,D/ResourcesManager( 7812): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager( 7812): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,V/COMMON  ( 7812): getScreenSize 1080 1920
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,I/JAM     ( 7812): Load The ApaService JNI
,I/JAM     ( 7812): version: ProfessionalAudio_v1.0.b5
,I/JAM     ( 7812): Try v1.0.b3 ...
,D/Spen    ( 7812): SpenSdk version level = 55
,D/Spen    ( 7812): SpenSdk jar version = 3.0.216
,D/Spen    ( 7812): SpenSdk apk version = 3.0.216
,D/Spen    ( 7812): Server UPDATE Check
,W/linker  ( 7812): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/SPenError( 7812): JNI_OnLoad
,D/JNI_Bitmap( 7812): Init .. Done
,D/SPenSpiDecoder( 7812): JNI_OnLoad .. Done
D/SPenError( 7812): JNI_OnLoad Success
,D/PluginManager( 7812): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
,D/PluginManager( 7812): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni( 7812): JNI_OnLoad
,D/Init_SPenSdk_Jni( 7812): AndroidSDK: 21
D/Init_SPenSdk_Jni( 7812): JNI_OnLoad .. Done
,E/Zygote  ( 7829): MountEmulatedStorage()
E/Zygote  ( 7829): v2
I/libpersona( 7829): KNOX_SDCARD checking this for 10168
I/libpersona( 7829): KNOX_SDCARD not a persona
,D/Model_ObjectBase_Jni( 7812): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni( 7812): JNI_OnLoad .. Done
,D/Model_ObjectImage_Jni( 7812): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni( 7812): JNI_OnLoad .. Done
,D/Model_ObjectContainer_Jni( 7812): JNI_OnLoad .. Done
,I/ActivityManager(  891): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=7829 uid=10168 gids={50168, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,D/Model_PageDoc_Jni( 7812): JNI_OnLoad .. Done
,D/Model_NoteDoc_Jni( 7812): check build type eng[0]
,D/Model_NoteDoc_Jni( 7812): JNI_OnLoad .. Done
D/Model_NoteFile_Jni( 7812): JNI_OnLoad .. Done
,D/Model_ObjectUtil_Jni( 7812): JNI_OnLoad .. Done
D/Model   ( 7812): OnLoad class Done
,D/spe_log ( 7812): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library( 7812): Draw Engine JNI_OnLoad enter!!
D/SPen_Library( 7812): Canvas JNI_OnLoad enter!!
,D/SPen_Library( 7812): Canvas JNI_OnLoad Success
,D/SPen_Library( 7812): TextView JNI_OnLoad enter!!
,D/SPen_Library( 7812): TextView JNI_OnLoad Success
,D/SPen_Library( 7812): Text JNI_OnLoad enter!!
D/SPen_Library( 7812): Text JNI_OnLoad Success
D/SPen_Library( 7812): FontManager JNI_OnLoad enter!!
,D/SPen_Library( 7812): FontManager JNI_OnLoad Success
D/SPen_Library( 7812): CapturePage JNI_OnLoad enter!!
D/SPen_Library( 7812): CapturePage JNI_OnLoad Success
,D/SPen_Library( 7812): Multi JNI_OnLoad enter!!
,I/SELinux ( 7829): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/SPen_Library( 7812): Multi JNI_OnLoad Success
D/SPen_Library( 7812): Draw Engine JNI_OnLoad Success
,D/SPen_Library( 7812): Brush JNI_OnLoad enter!!
,I/SELinux ( 7829): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7829): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SPen_Library( 7812): Brush JNI_OnLoad Success
,D/SPen_Library( 7812): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library( 7812): ChineseBrush JNI_OnLoad Success
,D/SPen_Library( 7812): InkPen JNI_OnLoad enter!!
,D/SPen_Library( 7812): InkPen JNI_OnLoad Success
,D/SPen_Library( 7812): Marker JNI_OnLoad enter!!
,D/SPen_Library( 7812): Marker JNI_OnLoad Success
,D/SPen_Library( 7812): Pencil JNI_OnLoad enter!!
,D/SPen_Library( 7812): Pencil JNI_OnLoad Success
,D/SPen_Library( 7812): NativePen JNI_OnLoad enter!!
,D/SPen_Library( 7812): NativePen JNI_OnLoad Success
,D/SPen_Library( 7812): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library( 7812): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library( 7812): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library( 7812): MontblancCalligraphyPen JNI_OnLoad Success
,D/TimaKeyStoreProvider( 7829): TimaSignature is unavailable
,D/ActivityThread( 7829): Added TimaKeyStore provider
,D/SPen_Library( 7812): MagicPen JNI_OnLoad enter!!
,D/SPen_Library( 7812): MagicPen JNI_OnLoad Success
,D/SPen_Library( 7812): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library( 7812): ObliquePen JNI_OnLoad Success
,D/SPen_Library( 7812): FountainPen JNI_OnLoad enter!!
,D/SPen_Library( 7812): FountainPen JNI_OnLoad Success
,D/Spen    ( 7812): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni( 7812): SPenSdk_init2
D/Init_SPenSdk( 7812): Init - screen_width = 1080, screen_height = 1920, maxCacheSize = 100 M
,D/Init_SPenSdk( 7812): Total S Pen SDK Directory Size = 0
D/Spen    ( 7812): initialize complete
,W/linker  ( 7812): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/SNoteApp( 7812): SpenSDK was initialized / elapsed time: 87.345574
,D/ResourcesManager( 7829): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager( 7829): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/SNoteProvider( 7829): onCreate enableSnoteSync = true
,E/Zygote  ( 7847): MountEmulatedStorage()
E/Zygote  ( 7847): v2
I/libpersona( 7847): KNOX_SDCARD checking this for 10178
I/libpersona( 7847): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.everglades for broadcast com.sec.everglades/.widget.EvergladesWidgetProvider: pid=7847 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7847): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  891): Killing 6927:com.google.android.apps.magazines/u0a146 (adj 15): bgCount ##41
,I/ActivityManager(  891): Killing 6669:com.android.chrome/u0a104 (adj 15): bgCount ##42
,I/SELinux ( 7847): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7847): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/COMMON  ( 7829): getScreenSize 1080 1920
,D/SNoteProvider( 7829): ===query=== 
,D/TimaKeyStoreProvider( 7847): TimaSignature is unavailable
D/ActivityThread( 7847): Added TimaKeyStore provider
,D/ResourcesManager( 7847): creating new AssetManager and set to /system/app/SamsungHub/SamsungHub.apk
,W/ResourceType( 7847): ResTable_typeSpec entry count inconsistent: given 1, previously 1632
,E/SharedPreferenceProvider( 7847): onCreate
,W/EG1.0.D.EvergladesApplication( 7847): {[9DA925020CE53372A65E446EE35B83FB42B05CFB82F8C72DEFF6EA2A95D60F03]}
,W/EG1.0.D.com.sec.everglades.widget.EvergladesWidgetProvider( 7847): {[7ED70924CFE2E2078BEA0BDB4E4E9EB68FE3579D0CF0C0C71F94E00A4249F3B2]}
,W/EG1.0.D.com.sec.everglades.widget.EvergladesWidgetProvider( 7847): {[A36E55454916D0BE88191A59A715BC94656CD5939242E91AA6EBEC49CA25669BE2D5F1890404ADC7C9CFBDB8632DDA9E5BE00A9A27C278E2F5F6B80FEBC23537]}
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7862): MountEmulatedStorage()
,E/Zygote  ( 7862): v2
I/libpersona( 7862): KNOX_SDCARD checking this for 10189
I/libpersona( 7862): KNOX_SDCARD not a persona
,I/SELinux ( 7862): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  891): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7862 uid=10189 gids={50189, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6316:tv.peel.samsung.app/u0a152 (adj 15): bgCount ##41
,I/SELinux ( 7862): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7862): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SNoteProvider( 7829): ===query=== 
,D/RecentNotesCoverCache( 7812): displayed loading completed 0 / elapsed time: 321.266042
,D/TimaKeyStoreProvider( 7862): TimaSignature is unavailable
,D/ActivityThread( 7862): Added TimaKeyStore provider
,D/ResourcesManager( 7862): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7862): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsModeInstallReceiver( 7862): onReceive intent data =  package:com.android.vending
,D/KidsModeInstallReceiver( 7862): Package not found : com.sec.android.app.kidshome
D/KidsModeInstallReceiver( 7862): checkPackage() : kidsHomeVersion :  -1
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7878): MountEmulatedStorage()
,E/Zygote  ( 7878): v2
I/libpersona( 7878): KNOX_SDCARD checking this for 10201
,I/libpersona( 7878): KNOX_SDCARD not a persona
,I/SELinux ( 7878): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7878): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7878): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  891): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.knoxquickstart.QuickStartReceiver: pid=7878 uid=10201 gids={50201, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6998:com.samsung.android.sconnect/u0a158 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7878): TimaSignature is unavailable
,D/ActivityThread( 7878): Added TimaKeyStore provider
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/UMC:Core( 7878): onCreate(): 
,D/USER_AGENT( 7878): UMC/1.1.40 (SM-N9005) SAFE-5.3 KNOX-2.3
,D/[SAMSUNG SMARCART NATIVE]( 7878): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7878): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/CSTORAGE( 7878): ================================================
I/CSTORAGE( 7878):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7878): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7878): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7878): FINISHED: initialize rv:0
,D/UMC:SecurityUtils( 7878): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7878): Loaded server certificates: 0
D/UMC:SecurityUtils( 7878): timaVersion on the device: 3.0
,D/UMC:CloudMDMSecurity( 7878): New Flow
D/TimaService(  891): TIMA3: in ccmRegisterForDefaultCertificate
I/        (  891): CCM JNI: In ccm_register_for_default_cert
D/TimaService(  891): TIMA: in getTimaVersion
I/        (  891): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  891): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  891): pInitArgs 0x91125814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  891): &ctx = 0x9fca0c1c
I/TLC_TZ_CCM: (  891): creating new ccm context...
I/TLC_TZ_CCM: (  891): initializing ccm context...
I/TLC_TZ_CCM: (  891): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  891): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  891): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  891): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  891): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  891): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  891): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  891): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  891): Client_Server_Open was called
I/TZ: client_server_communication(  891): IClientServer::IClientServer()
I/TZ: client_server_communication(  891): BpClientServer::BpClientServer()
I/TZ_CCM_SERVER( 1095): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1095): OPENSWCONN
I/TZ_CCM_SERVER( 1095): creating new ccm context...
I/TZ_CCM_SERVER( 1095): initializing ccm context...
I/TZ_CCM_SERVER( 1095): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1095): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1095): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1095): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1095): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1095): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1095): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1095): QSEECom_get_handle sb_length = 0x9800
D/QSEECOMAPI: ( 1095): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1095): Loaded image: APP id = 5
,I/TZ: qc_tlc_communication( 1095): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,I/TZ: client_server_communication(  891): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  891): Client_Server_Open succeeded, serverName = CCM
,I/TZ_CCM_C_Initialize: (  891): ctx = 0x9decc830, comm = 0x9c9cc058, sendmsg = 0x8770a000, recvmsg = 0x8770ec00
I/TZ_init: (  891): TZ_init: sending initialization request...
,I/TZ: client_server_communication(  891): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  891): Calling Communicate()
I/TZ_CCM_SERVER( 1095): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1095): COMM
,E/TZ_init: (  891): TZ_init Process: Secure memory is not initialized!,
E/TZ_init: (  891): trustlet initialization failed
,I/TZ_init: (  891): TZ_init_START...
I/TZ_init: (  891): TZ_init_with_data: sending initialization request...
I/TZ: client_server_communication(  891): Cmd id = 2, len = 19456
,I/TZ: client_server_communication(  891): Calling Communicate()
I/TZ_CCM_SERVER( 1095): BnCCM::onTransact(2) 16
,I/TZ_CCM_SERVER( 1095): COMM
I/TZ_init: (  891): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: (  891): Exercising TZ_DB_INIT in TLC
I/TLC_TZ_COMMON: key_db_init: (  891): TZ_COMMON: Installing default certificate for the first time
,D/QSEECOMAPI: (  891): QSEECom_get_handle sb_length = 0x840
D/QSEECOMAPI: (  891): App is already loaded QSEE and app id = 5
,E/CSTORAGE(  891): _kmLockAndLoadTA enter
D/QSEECOMAPI: (  891): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  891): App is not loaded in QSEE
,D/QSEECOMAPI: (  891): Loaded image: APP id = 6
,E/CSTORAGE(  891): _kmLockAndLoadTA leave
,E/CSTORAGE(  891): Application TA reported error code: -9,
E/TZ_VENDOR_TLC: (  891): shareServiceKey failed:-9
,D/QSEECOMAPI: (  891): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  891): QSEECom_shutdown_app, app_id = 6
,D/QSEECOMAPI: (  891): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  891): QSEECom_shutdown_app, app_id = 5
,E/tz_ccm_install_default_cert: (  891): TZ_load_default_cert failed to init SKM! [Return Value] = 65541
E/TLC_TZ_COMMON: key_db_init: (  891): TZ_COMMON: couldn't install default cert-check for DRK
E/TZ_COMMON: tlc_key_db_util: (  891): translate_db_rv_to_ck_rv:Unknown DB error 6
,I/TZ: client_server_communication(  891): Client_Server_Close was called
I/TZ_CCM_SERVER( 1095): BnCCM::onTransact(1) 16
,I/TZ_CCM_SERVER( 1095): CLOSESWCONN
D/QSEECOMAPI: ( 1095): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1095): QSEECom_shutdown_app, app_id = 5
I/TZ: client_server_communication(  891): Client_Server_Close succeeded
,E/        (  891): CCM JNI: In ccm_create_slot - TZ_CCM_C_Initialize failed with error 2147483653
E/        (  891): CCM JNI: In ccm_register_for_default_cert - ccm_create_slot failed
,D/UMC:CloudMDMSecurity( 7878): ccmRegisterForDefaultCertificate: 5
D/UMC:CloudMDMSecurity( 7878): TIMA service call for password change success!!
,D/UMC:AdminManager( 7878): init - start
,D/UMC:AdminManager( 7878): loadAdmins
,D/UMC:AdminManager( 7878): startPolicyHandlers
,I/UMC:TestPolicyHandler( 7878): Setup is called in testpolicyhandler
D/UMC:AdminManager( 7878): init - end
,V/UMC:AlarmHandler( 7878): Enter loadList
,D/GSLBManager( 7878): migrateStoredUrlFromOldPref
,D/GSLBManager( 7878): migrateStoredUrlFromOldPref : Migration Not Needed
,D/UMC:UMCAdmin( 7878): deactivateUMCAdminIfNotRequired : -1
,E/UMC:Utils( 7878): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7878): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7878): isContainer : 0
,W/LicenseLogService(  891): log() failed
,D/EnterpriseDeviceManagerService(  891): isManagedProfileUser(): userId = 0
,E/UMC:UMCAdmin( 7878): No active admin owned by uid 10201
D/UMC:UMCAdmin( 7878): isContainer : 0
,D/UMC:UMCAdmin( 7878): deactivateUMCAdmin - UMC App Admin deactivated
D/QuickStartReceiver( 7878): Intent Action : android.intent.action.PACKAGE_REMOVED
,D/QuickStartReceiver( 7878): Intent Replacing : true
,I/ActivityManager(  891): Killing 6384:com.android.email/u0a186 (adj 15): bgCount ##41
,D/PackageBroadcastService( 1749): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.android.vending
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1749): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1572): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1572): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7899): MountEmulatedStorage()
E/Zygote  ( 7899): v2
I/libpersona( 7899): KNOX_SDCARD checking this for 10033
I/libpersona( 7899): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7899 uid=10033 gids={50033, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7899): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7899): TimaSignature is unavailable
,D/ActivityThread( 7899): Added TimaKeyStore provider
,D/ResourcesManager( 7899): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/Finsky  ( 7899): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7899): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7899): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7899): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  891): Killing 6283:com.samsung.android.securitylogagent/1000 (adj 15): bgCount ##41
,D/Ads     ( 7899): Skipping gmscore version check
,D/Finsky  ( 7899): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7899): [1] Libraries$2.run: Finished loading 1 libraries.
,I/HomeSyncInstallReceiver( 1403): This pkg do not need BT addr. Do nothing
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7938): MountEmulatedStorage()
,E/Zygote  ( 7938): v2
I/libpersona( 7938): KNOX_SDCARD checking this for 10019
I/libpersona( 7938): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=7938 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7938): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7938): TimaSignature is unavailable
,D/Finsky  ( 7899): [1] InstallerImpl.access$500: Attempt recovery of content://downloads/my_downloads/21 200
,D/ActivityThread( 7938): Added TimaKeyStore provider
D/Finsky  ( 7899): [1] InstallerImpl.access$500: Releasing content://downloads/my_downloads/21 200
,D/Finsky  ( 7899): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ResourcesManager( 7938): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
,D/Finsky  ( 7899): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7957): MountEmulatedStorage()
E/Zygote  ( 7957): v2
I/libpersona( 7957): KNOX_SDCARD checking this for 10020
I/libpersona( 7957): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.groupcast for broadcast com.samsung.groupcast/.receiver.SPPReceiver: pid=7957 uid=10020 gids={50020, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7957): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  891): Killing 7015:com.samsung.android.service.travel/u0a200 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7957): TimaSignature is unavailable
,D/ActivityThread( 7957): Added TimaKeyStore provider
,D/ResourcesManager( 7957): creating new AssetManager and set to /system/priv-app/GroupPlay_25/GroupPlay_25.apk
,W/ResourcesManager( 7957): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7957): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/GroupCast_FileTools( 7957): [getDirectoryForImageResized : 333] cleaning!!
,I/PCWCLIENTTRACE_PushUtil( 5845): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5845): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5845): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5845): [onReceive] - android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  891): Killing 7052:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): bgCount ##41
,I/RelayReceiver_PinBoard( 5860): onReceive... android.intent.action.PACKAGE_ADDED
,I/RelayService_PinBoard( 5860): RelayService Started!! : android.intent.action.PACKAGE_ADDED
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7974): MountEmulatedStorage()
,E/Zygote  ( 7974): v2
I/libpersona( 7974): KNOX_SDCARD checking this for 1000
I/libpersona( 7974): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=7974 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7974): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7974): TimaSignature is unavailable
,D/ActivityThread( 7974): Added TimaKeyStore provider
,D/ResourcesManager( 7974): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/SA      ( 5931): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 5931): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5931): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10033 extra.REPLACING.:true extra.user_handle.:0 ]
,I/ActivityManager(  891): Killing 6828:com.android.calendar/u0a172 (adj 15): bgCount ##41
,D/Mms/FreeMessageReceiver( 4824): onReceive, action : android.intent.action.PACKAGE_ADDED
,I/TactileAssist(  891): enable value -1
I/TactileAssist(  891): internal enable value -1
I/TactileAssist(  891): intensity value -1
I/TactileAssist(  891): saveAppList value true
,I/TactileAssist(  891): List of disabled apps :
,D/Mms/FreeMessageReceiverService( 4824): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 4824): onHandleIntent: ACTION_PACKAGE_ADDED
,D/Compatibility( 7657): onReceive() it will make start service
,D/Compatibility( 7657): onHandleIntent()
,D/Compatibility( 7657): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.android.vending flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10033, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 7657): found: 2
D/Compatibility( 7657): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7657): skipping ResolveInfo{3d328e4e com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7657): considering ResolveInfo{14368b6f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7657): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 7657): enabling receiver ResolveInfo{8f607c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Compatibility( 7657): enabling receiver ResolveInfo{85a0d05 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 7657): enabling receiver ResolveInfo{152d415a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/UpdateIcingCorporaServi( 1592): Updating corpora: APPS=com.android.vending, CONTACTS=MAYBE
,D/Compatibility( 7657): enabling receiver ResolveInfo{33ca6f8b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ContextImpl( 7674): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2991 
,D/Compatibility( 7657): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 7713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
,D/PackageIntentReceiver( 7733): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7733): Not GearManger package! 
,D/ResourcesManager( 7713): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,E/FilterInstaller( 7713): installFilters
,E/FilterInstaller( 7713): There is no requred permission
,I/art     (  891): Explicit concurrent mark sweep GC freed 43134(2MB) AllocSpace objects, 7(112KB) LOS objects, 17% free, 37MB/45MB, paused 1.459ms total 96.126ms
,D/ResourcesManager( 7812): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1749): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1749): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.android.vending
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1749): Module APK com.google.android.play.games already loaded
,D/ResourcesManager( 1592): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,I/PeopleContactsSync( 1749): CP2 sync disabled
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1749): Submit a task: h
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/h       ( 1749): Processing package: com.android.vending
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/UpdateIcingCorporaServi( 1592): UpdateCorporaTask done [took 187 ms] updated apps [took 185 ms] 
,D/a       ( 1749): Look up (com.android.vending:80430500) returned no result
,D/h       ( 1749): Starting Hash for package com.android.vending:6.0.5
,D/GCM     ( 1572): GcmService start Intent { act=com.google.android.gms.gcm.PACKAGE_REPLACED cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gms.gcm.PACKAGE_REPLACED
,I/PCWCLIENTTRACE_PushUtil( 5845): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5845): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5845): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5845): [onReceive] - android.intent.action.PACKAGE_REPLACED
D/PCWCLIENTTRACE_SYSTEMReceiver( 5845): ACTION_PACKAGE_REPLACED_START
,I/SA      ( 5931): [PMR] Received action : android.intent.action.PACKAGE_REPLACED
,I/SA      ( 5931): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5931): [SUR] onReceive Intent=[ action_PACKAGE_REPLACED package extra.UID.:10033 extra.REPLACING.:true extra.user_handle.:0 ]
,D/Compatibility( 7657): onReceive() it will make start service
,W/ContextImpl( 7674): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:168 android.app.ActivityThread.handleReceiver:2991 
,D/Compatibility( 7657): onHandleIntent()
,D/Compatibility( 7657): intentservice saw: Intent { act=android.intent.action.PACKAGE_REPLACED dat=package:com.android.vending flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10033, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 7657): found: 2
D/Compatibility( 7657): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 7657): skipping ResolveInfo{25ee1926 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7657): considering ResolveInfo{b6e7967 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7657): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 7657): enabling receiver ResolveInfo{13b14314 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 7657): enabling receiver ResolveInfo{1a61d7bd com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 7657): enabling receiver ResolveInfo{2492a1b2 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 7657): enabling receiver ResolveInfo{15f4503 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 7657): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/Zygote  ( 8009): MountEmulatedStorage()
,E/Zygote  ( 8009): v2
I/libpersona( 8009): KNOX_SDCARD checking this for 10146
I/libpersona( 8009): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=8009 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 8009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 8009): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/h       ( 1749): Package com.android.vending's hash: 8d58d5fed273b866768764e239b5727f4c6e27a8ff1606fe5661974af1a8cca3
,D/a       ( 1749): Look up (com.android.vending:80430500) returned no result
,D/TimaKeyStoreProvider( 8009): TimaSignature is unavailable
,D/ActivityThread( 8009): Added TimaKeyStore provider
,D/h       ( 1749): Saved the app info in cache for package:com.android.vending.
,D/ResourcesManager( 8009): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8009): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8009): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8009): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8009): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 8009): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 8009): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 8009): Loading: webviewchromium
,I/LibraryLoader( 8009): Time to load native libraries: 5 ms (timestamps 2459-2464)
I/LibraryLoader( 8009): Expected native library version number "",actual native library version number ""
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): stay LED for fully charged
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,V/WebViewChromiumFactoryProvider( 8009): Binding Chromium to main looper Looper (main, tid 1) {2e8517d6}
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/LibraryLoader( 8009): Expected native library version number "",actual native library version number ""
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
I/chromium( 8009): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/HeadsetStateMachine( 6310): Disconnected process message: 10
,I/BrowserStartupController( 8009): Initializing chromium process, renderers=0
,W/art     ( 8009): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 8009): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 8009): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 8009): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 8009): Requires BLUETOOTH permission
,I/Adreno-EGL( 8009): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 8009): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8009): Build Date: 11/19/14 Wed
I/Adreno-EGL( 8009): Local Branch: mybranch5813579
I/Adreno-EGL( 8009): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 8009): Local Patches: NONE
I/Adreno-EGL( 8009): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/NSApplication( 8009): Starting up...
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8062): MountEmulatedStorage()
E/Zygote  ( 8062): v2
I/libpersona( 8062): KNOX_SDCARD checking this for 10158
I/libpersona( 8062): KNOX_SDCARD not a persona
,I/SELinux ( 8062): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 8062): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 8062): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  891): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8062 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/SMD     (  294): DCD ON
,D/TimaKeyStoreProvider( 8062): TimaSignature is unavailable
,D/ActivityThread( 8062): Added TimaKeyStore provider
,I/ActivityManager(  891): Killing 7166:com.blurb.checkout/u0a96 (adj 15): bgCount ##41
,I/art     (  330): Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 339us total 31.055ms
,D/ResourcesManager( 8062): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 8062): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8062): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8062): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 300us total 10.839ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 268us total 10.886ms
,D/QuickConnect( 8062): PeriphStartReceiver.onReceive - android.intent.action.PACKAGE_REPLACED
,I/ActivityManager(  891): Killing 7411:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,D/PackageBroadcastService( 1749): Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.android.vending
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1749): Submit a task: h
,I/PeopleContactsSync( 1749): CP2 sync disabled
D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/h       ( 1749): Processing package: com.android.vending
,D/GassUtils( 1749): Found app info for package com.android.vending:80430500. Hash: 8d58d5fed273b866768764e239b5727f4c6e27a8ff1606fe5661974af1a8cca3
,D/h       ( 1749): Found info for package com.android.vending in db.
,D/ChimeraCfgMgr( 1749): Loading module com.google.android.gms.vision from APK com.google.android.gms
,E/NetworkScheduler.SchedulerReceiver( 1572): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1572): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8080): MountEmulatedStorage()
E/Zygote  ( 8080): v2
I/libpersona( 8080): KNOX_SDCARD checking this for 10125
I/libpersona( 8080): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc flipboard.app for broadcast flipboard.app/flipboard.sstream.SstreamBroadcastReceiver: pid=8080 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 8080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 8080): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8080): TimaSignature is unavailable
,D/ActivityThread( 8080): Added TimaKeyStore provider
,D/ResourcesManager( 8080): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,I/MultiDex( 8080): VM with version 2.1.0 has multidex support
,I/MultiDex( 8080): install
I/MultiDex( 8080): VM has multidex support, MultiDex support library is disabled.
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8080): Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8080): Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,I/System.out( 8080): Reading bundled version for config.json
,I/System.out( 8080): Reading bundled version for services.json
,I/System.out( 8080): Reading bundled version for dynamicStrings.json
,I/System.out( 8080): Parsed section Cover Stories, private: false
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Widget  ( 7812): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,D/Widget  ( 7812): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  ( 7812): widgetUpdate 6
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,I/ActivityManager(  891): Killing 7494:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,I/GAV2    ( 7690): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  294): DCD ON,
,I/GAV4    ( 8009): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:n  (  891): SIOP:: AP = 320, PST = 296, CUR = 450,
,E/SMD     (  294): DCD ON
,D/PackageManager(  891): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
,D/RegisteredServicesCache( 1403): empty dynamic service
,I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
,D/RegisteredServicesCache( 1403): empty dynamic service
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/ResourcesManager( 1439): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,W/ResourcesManager( 1439): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1439): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 1439): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 1439): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/ResourcesManager( 1439): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1439): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager( 1439): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,W/ResourcesManager( 1439): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1439): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
,D/ResourcesManager( 1439): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/art     ( 7556): Verification of com.sec.android.touchwiz.widget.TwDndListView sstream.app.activities.StreamActivity.access$1000(sstream.app.activities.StreamActivity) took 117.815ms
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  891): mCursor = null
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,I/UpdateIcingCorporaServi( 1592): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,E/Zygote  ( 8164): MountEmulatedStorage()
I/libpersona( 8164): KNOX_SDCARD checking this for 10088
E/Zygote  ( 8164): v2
I/libpersona( 8164): KNOX_SDCARD not a persona
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager(  891): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8164 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8164): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 8164): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8164): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  891): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  891): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  891): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/TimaKeyStoreProvider( 8164): TimaSignature is unavailable
,D/ActivityThread( 8164): Added TimaKeyStore provider
,V/BackupManagerService(  891): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@31c4b58e
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/ResourcesManager( 8164): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/FileShare-Server( 8164): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,I/UpdateIcingCorporaServi( 1592): UpdateCorporaTask done [took 132 ms] updated apps [took 132 ms] 
,W/ResourcesManager(  891): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  891): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  891): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager(  891): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8180 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6688:com.samsung.klmsagent/u0a23 (adj 15): bgCount ##41
,E/Zygote  ( 8180): MountEmulatedStorage()
I/libpersona( 8180): KNOX_SDCARD checking this for 1000
E/Zygote  ( 8180): v2
I/libpersona( 8180): KNOX_SDCARD not a persona
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/GmsNetworkLocationProvi( 1482): DISABLE
I/SELinux ( 8180): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/GCoreNlp( 1482): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SELinux ( 8180): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 8180): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LocationProviderProxy(  891): applying state to connected service
,D/TimaKeyStoreProvider( 8180): TimaSignature is unavailable
,D/ActivityThread( 8180): Added TimaKeyStore provider
,D/LocationProviderProxy(  891): applying state to connected service
,D/ResourcesManager( 8180): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,E/SMD     (  294): DCD ON
,D/ShortcutReceiver( 8180):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/PackageBroadcastService( 1749): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/PeopleContactsSync( 1749): CP2 sync disabled
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8200): MountEmulatedStorage()
,E/Zygote  ( 8200): v2
I/libpersona( 8200): KNOX_SDCARD checking this for 10131
I/libpersona( 8200): KNOX_SDCARD not a persona
,I/SELinux ( 8200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  891): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8200 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 8200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 8200): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8200): TimaSignature is unavailable
,D/ActivityThread( 8200): Added TimaKeyStore provider
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 8200): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 3156): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/Babel   ( 8200): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 8200): MmsConfig.loadMmsSettings
I/Babel   ( 8200): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,I/Babel   ( 8200): MmsConfig.loadFromDatabase
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/AudioCapabilities( 8200): Unsupported mime audio/evrc
,W/AudioCapabilities( 8200): Unsupported mime audio/qcelp
,E/Babel   ( 8200): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 8200): MmsConfig.loadFromResources
,W/VideoCapabilities( 8200): Unrecognized profile 2130706433 for video/avc
,E/Babel   ( 8200): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 8200): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,W/Settings( 8200): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 8200): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 8200): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 8200): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 8200): Unsupported mime audio/x-ima
W/AudioCapabilities( 8200): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 8200): Unsupported mime audio/qcelp
W/AudioCapabilities( 8200): Unsupported mime audio/evrc
W/VideoCapabilities( 8200): Unsupported mime video/wvc1
W/VideoCapabilities( 8200): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 8200): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 8200): Unsupported mime video/wvc1
W/VideoCapabilities( 8200): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 8200): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 8200): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 8200): Unsupported mime video/mp43
,W/VideoCapabilities( 8200): Unsupported mime video/sorenson
,W/VideoCapabilities( 8200): Unsupported mime video/mp4v-esdp
,I/UpdateIcingCorporaServi( 1592): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/FileShare-Server( 8164): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,I/VideoCapabilities( 8200): Unsupported profile 4 for video/mp4v-es
,D/ShortcutReceiver( 8180):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ResourcesManager( 1749): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/PackageBroadcastService( 1749): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1749): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  891): Killing 6803:com.sec.esdk.elm/u0a116 (adj 15): bgCount ##41
,I/Icing   ( 1749): updateResources: need to parse f{com.google.android.gms}
,D/ResourcesManager( 1592): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/UpdateIcingCorporaServi( 1592): UpdateCorporaTask done [took 448 ms] updated apps [took 448 ms] 
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 62
,V/AlarmManager(  891): waitForAlarm result :4
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 7899): Thread-1252(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7899): Thread-1252(ApacheHTTPLog):isShipBuild true
,I/System.out( 7899): Thread-1252(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 7899): Tagging socket 44 with tag e8d195d100000000{3906049489,0} uid -1, pid: 7899, getuid(): 10033
,I/qtaguid ( 7899): Tagging socket 48 with tag e8d195d100000000{3906049489,0} uid -1, pid: 7899, getuid(): 10033
,I/qtaguid ( 7899): Untagging socket 44
,I/System.out( 7899): Thread-1252 calls detatch()
,D/Finsky  ( 7899): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 1 successful.
,D/Finsky  ( 7899): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  891): Killing 7540:com.sec.android.service.health/u0a21 (adj 15): bgCount ##41
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 310, PST = 299, CUR = 450,
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 300, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 301, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 63
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 302, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 303, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 304, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 64
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 303, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 303, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ClearcutLoggerApiImpl( 1572): disconnect managed GoogleApiClient
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  891): !@Sync 65
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6310): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6310): Disconnected process message: 10
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 291, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8267): 
D/AndroidRuntime( 8267): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8267): CheckJNI is OFF
D/AndroidRuntime( 8267): readGMSProperty: start
D/AndroidRuntime( 8267): readGMSProperty: already setted!!
D/AndroidRuntime( 8267): readGMSProperty: end
D/AndroidRuntime( 8267): addProductProperty: start
E/AffinityControl( 8267): AffinityControl: registerfunction enter
D/AndroidRuntime( 8267): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  891): START PACKAGE DELETE: observer{288281021}
D/PackageManager(  891): pkg{<packageName>}
D/PackageManager(  891): user{0}
D/PackageManager(  891): caller{2000}
D/PackageManager(  891): flags{3}
D/PersonaManagerService(  891): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  891): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  891): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  891): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  891): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  891): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  891): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  891): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  891): getApplicationUninstallationEnabled
D/ApplicationPolicy(  891): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  891): !@killApplicatoin: 10273, uninstall pkg
I/ActivityManager(  891): Force stopping com.test.thalitest appid=10273 user=-1: uninstall pkg
I/ActivityManager(  891): Killing 6208:com.test.thalitest/u0a273 (adj 0): stop com.test.thalitest
W/PackageSettings(  891): Skipping PackageSetting{a31cdb3 com.example.hello/10268} due to missing metadata
I/WindowState(  891): WIN DEATH: Window{1a8b977e u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  254): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  891): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  891): setMouseCustomIcon IconType is same.101
D/PointerIcon(  891): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  891): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  891):   Force finishing activity ActivityRecord{26148db8 u0 com.test.thalitest/.MainActivity t3}
D/FocusedStackFrame(  891): Set to : 0
W/ActivityManager(  891): Spurious death for ProcessRecord{a0513b2 6208:com.test.thalitest/u0a273}, curProc for 6208: null
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  891): Force stopping com.test.thalitest appid=10273 user=0: pkg removed
I/art     ( 1592): Explicit concurrent mark sweep GC freed 33450(2002KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 18MB/31MB, paused 644us total 49.607ms
I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1482): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/SamsungIME( 1721): mOCRHelper is null
I/art     ( 3156): Explicit concurrent mark sweep GC freed 4629(229KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 4.965ms total 52.842ms
E/Zygote  ( 8295): MountEmulatedStorage()
E/Zygote  ( 8295): v2
I/libpersona( 8295): KNOX_SDCARD checking this for 10023
I/libpersona( 8295): KNOX_SDCARD not a persona
I/ActivityManager(  891): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8295 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 8295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8295): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8295): TimaSignature is unavailable
D/ActivityThread( 8295): Added TimaKeyStore provider
D/ResourcesManager( 8295): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/SurfaceWidgetView( 1439): destroyHardwareResources():220442251
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  891): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/Launcher( 1439): onRestart, Launcher: 339118959
D/Launcher( 1439): onStart, Launcher: 339118959
D/Launcher.HomeView( 1439): onStart
I/art     (  891): Explicit concurrent mark sweep GC freed 80895(5MB) AllocSpace objects, 46(736KB) LOS objects, 17% free, 37MB/45MB, paused 1.545ms total 199.653ms
I/art     (  891): WaitForGcToComplete blocked for 117.594ms for cause Explicit
D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1777): [237392/8] Surface widget visibility changed visibility = true on instance = 1
V/ActivityThread( 1439): updateVisibility : ActivityRecord{2c99cbd0 token=android.os.BinderProxy@a4f7a45 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/SurfaceWidget.Renderer( 1777): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1777): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
I/SurfaceFlinger(  254): id=16 createSurf (1080x1920),1 flag=4, Mauncher
D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  891): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  891): setMouseCustomIcon IconType is same.101
D/PointerIcon(  891): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  891): setHoveringSpenCustomIcon IconType is same.1
I/KLMS-2.4.511: ( 8295): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 8295): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449673106724
I/KLMS-2.4.511: ( 8295): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 8295): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/InputMethodManagerService(  891): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  891): Got RemoteException sending setActive(false) notification to pid 6208 uid 10273
W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/Timeline(  891): Timeline: Activity_windows_visible id: ActivityRecord{441464e u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1984435
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/RegisteredServicesCache( 1403): empty dynamic service
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/art     (  891): Explicit concurrent mark sweep GC freed 17636(968KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 37MB/45MB, paused 1.783ms total 248.982ms
I/art     (  891): WaitForGcToComplete blocked for 167.223ms for cause Explicit
D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/RCPManagerService(  891): PackageReceiver onReceive()
I/HarmonyEASService(  891): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  891): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  891): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  891): uID is 10273
V/EnterpriseBillingPolicy(  891): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  891): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  891): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  891): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  891): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  891): removeObsoleteFile: deleting file=3_task.xml
I/art     (  891): Explicit concurrent mark sweep GC freed 5701(310KB) AllocSpace objects, 3(48KB) LOS objects, 17% free, 37MB/45MB, paused 1.526ms total 95.041ms
D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
D/PackageManager(  891): delete codoeFile: 
I/AASAUninstall(  891):  com.test.thalitest not target!
D/PackageManager(  891): result of delete: 1{288281021}
D/AndroidRuntime( 8267): Shutting down VM
E/Zygote  ( 8315): MountEmulatedStorage()
E/Zygote  ( 8315): v2
I/libpersona( 8315): KNOX_SDCARD checking this for 10116
I/libpersona( 8315): KNOX_SDCARD not a persona
I/ActivityManager(  891): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8315 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  891): Killing 7612:com.sec.spp.push:RemoteNotiProcess/u0a43 (adj 15): bgCount ##41
I/SELinux ( 8315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8315): TimaSignature is unavailable
D/ActivityThread( 8315): Added TimaKeyStore provider
D/ResourcesManager( 8315): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/elm:14491( 8315): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 8315): ELMEngine.ELMEngine( context ).
D/elm:14491( 8315): MDMBridge.setEnterpriseBridge()
D/elm:14491( 8315): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
D/elm:14491( 8315): ElmAgentService : onCreate()
D/elm:14491( 8315): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 8315): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 8315): MDMBridge.getInstance()
D/elm:14491( 8315): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 8315): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8332): MountEmulatedStorage()
E/Zygote  ( 8332): v2
I/libpersona( 8332): KNOX_SDCARD checking this for 10021
I/libpersona( 8332): KNOX_SDCARD not a persona
I/ActivityManager(  891): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8332 uid=10021 gids={50021, 9997} abi=armeabi-v7a
I/SELinux ( 8332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/elm:14491( 8315): ElmAgentService : onDestroy().
I/SELinux ( 8332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ActivityManager(  891): Killing 7746:com.samsung.android.provider.filterprovider/u0a121 (adj 15): bgCount ##41
E/SELinux ( 8332): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8332): TimaSignature is unavailable
D/ActivityThread( 8332): Added TimaKeyStore provider
D/ResourcesManager( 8332): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8332): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8332): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8332): onReceive() : package name is not s health. Return !!!
I/PCWCLIENTTRACE_PushUtil( 5845): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5845): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5845): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5845): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8350): MountEmulatedStorage()
E/Zygote  ( 8350): v2
I/libpersona( 8350): KNOX_SDCARD checking this for 10043
I/libpersona( 8350): KNOX_SDCARD not a persona
I/ActivityManager(  891): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8350 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  891): Killing 7780:com.android.keychain/1000 (adj 15): bgCount ##41
I/SELinux ( 8350): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8350): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8350): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8350): TimaSignature is unavailable
D/ActivityThread( 8350): Added TimaKeyStore provider
D/ResourcesManager( 8350): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 8350): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8350): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 8350): PushLog.txt file is not deleted.
D/SPPClientService( 8350): PushLog.txt file is not deleted.
D/SPPClientService( 8350): ============PushLog. stop!
E/SQLiteLog( 8350): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 8350): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 8350): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8350): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8350): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8350): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 8350): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 8350): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 8350): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 8350): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8350): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8350): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8350): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8350): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 8350): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 8350): 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
E/SQLiteDatabase( 8350): 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
E/SQLiteDatabase( 8350): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 8350): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 8350): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 8350): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 8350): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 8350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8350): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8350): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 8350): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8350): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8350): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 8350): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/LNoti   ( 8350): [b] open fail. SQLException occured
I/SA      ( 5931): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
I/SA      ( 5931): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10273 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  891): Killing 7797:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
I/EventHub(  891): Removing device '/dev/input/event6' due to inotify event
E/SharedPreferencesImpl( 4904): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/Mms/FreeMessageReceiver( 4824): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/EnterpriseDeviceManagerService(  891): Package has changed for user 0
D/EnterpriseDeviceManagerService(  891): Admin package name: com.google.android.gms
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Books/Books.apk
I/EventHub(  891): Removing device '/dev/input/event7' due to inotify event
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/TactileAssist(  891): enable value -1
I/TactileAssist(  891): internal enable value -1
I/TactileAssist(  891): intensity value -1
I/TactileAssist(  891): saveAppList value true
I/TactileAssist(  891): List of disabled apps :
D/Mms/FreeMessageReceiverService( 4824): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4824): onHandleIntent: ACTION_PACKAGE_REMOVED
E/SharedPreferencesImpl(  891): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/SettingsProvider(  891): name = reading_mode_app_list
D/Compatibility( 7657): onReceive() it will make start service
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/EventHub(  891): Removing device '/dev/input/event8' due to inotify event
D/Compatibility( 7657): onHandleIntent()
D/Compatibility( 7657): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10273, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 7657): found: 2
D/Compatibility( 7657): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7657): skipping ResolveInfo{88526fe com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7657): considering ResolveInfo{19072e5f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7657): default: com.sec.android.app.soundalive.SAControlPanelActivity
I/UpdateIcingCorporaServi( 1592): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 7657): enabling receiver ResolveInfo{14a9e0ac com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7657): enabling receiver ResolveInfo{3fd14175 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7657): enabling receiver ResolveInfo{388b50a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/ContextImpl( 7674): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
D/RCPManager( 6907):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService(  891):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService(  891): queryAllProviders():  providerCallBack is not register for 0
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/SQLiteLog( 7674): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 7674): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 7674): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 7674): (14) os_unix.c:32503: (2) open(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu) - 
E/SQLiteDatabase( 7674): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 7674): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7674): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 7674): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 7674): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7674): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7674): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7674): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 7674): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 7674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 7674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 7674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err( 7674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err( 7674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 7674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
W/System.err( 7674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 7674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 7674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 7674): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 7674): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 7674): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 7674): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7674): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7674): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Compatibility( 7657): enabling receiver ResolveInfo{381a517b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/EventHub(  891): Removing device '/dev/input/event9' due to inotify event
E/SharedPreferencesImpl( 7657): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
E/SharedPreferencesImpl( 7657): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 7657): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Maps/Maps.apk
E/SQLiteLog( 1592): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1592): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
F/libc    ( 1592): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa04104e1 in tid 8370 (IntentService[U)
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
W/ContextImpl( 7713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
I/EventHub(  891): Removing device '/dev/input/event10' due to inotify event
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/ResourcesManager(  891): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  891): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  891): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}

```
