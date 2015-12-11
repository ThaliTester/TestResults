#### Test 5065027857de7f1_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  294): DCD ON
,D/AndroidRuntime( 6516): 
D/AndroidRuntime( 6516): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6516): CheckJNI is OFF
D/AndroidRuntime( 6516): readGMSProperty: start
D/AndroidRuntime( 6516): readGMSProperty: already setted!!
D/AndroidRuntime( 6516): readGMSProperty: end
D/AndroidRuntime( 6516): addProductProperty: start
E/AffinityControl( 6516): AffinityControl: registerfunction enter
D/AndroidRuntime( 6516): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  758): inState():  stateMachine is null !!
I/PersonaManagerService(  758): PersonaId don't exist
I/ActivityManager(  758): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  758): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  758): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  758): mDVFSHelper.acquire()
D/FocusedStackFrame(  758): Set to : 0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6531 uid=10283 gids={50283, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6516): Shutting down VM
D/PointerIcon(  758): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  758): setMouseCustomIcon IconType is same.101
D/PointerIcon(  758): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  758): setHoveringSpenCustomIcon IconType is same.1
E/Zygote  ( 6531): MountEmulatedStorage()
I/libpersona( 6531): KNOX_SDCARD checking this for 10283
E/Zygote  ( 6531): v2
I/libpersona( 6531): KNOX_SDCARD not a persona
I/SELinux ( 6531): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6531): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6531): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6531): TimaSignature is unavailable
D/ActivityThread( 6531): Added TimaKeyStore provider
V/WindowOrientationListener(  758): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  758): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  758): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  758): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  758): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  758): Display changed displayId=0
D/SurfaceWidgetView( 1444): destroyHardwareResources():705418629
D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/ResourcesManager( 6531): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1771): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1444): updateVisibility : ActivityRecord{2e3e0002 token=android.os.BinderProxy@2c670c2f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1444): onTrimMemory. Level: 20
I/WebViewFactory( 6531): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 6531): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 6531): Loading: webviewchromium
I/LibraryLoader( 6531): Time to load native libraries: 6 ms (timestamps 6941-6947)
I/LibraryLoader( 6531): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6531): Binding Chromium to main looper Looper (main, tid 1) {2afc79f7}
I/LibraryLoader( 6531): Expected native library version number "",actual native library version number ""
I/chromium( 6531): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6531): Initializing chromium process, renderers=0
W/art     ( 6531): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6531): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6531): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6531): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6531): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
I/Adreno-EGL( 6531): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6531): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6531): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6531): Local Branch: mybranch5813579
I/Adreno-EGL( 6531): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6531): Local Patches: NONE
I/Adreno-EGL( 6531): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
D/BluetoothAdapter( 6531): 112418916: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6531): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6531): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6531): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6531): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6531): CordovaWebView is running on device made by: samsung
W/art     ( 6531): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6531): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager(  758): Activity pause timeout for ActivityRecord{1036eb80 u0 com.test.thalitest/.MainActivity t3}
D/Activity( 6531): performCreate Call secproduct feature valuefalse
D/Activity( 6531): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 6531): Render dirty regions requested: true
D/Atlas   ( 6531): Validating map...
D/ActivityManager(  758): post active user change for 0
D/KnoxTimeoutHandler(  758): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  758): handleActiveUserChange for user 0
V/ActivityThread( 6531): updateVisibility : ActivityRecord{3c86e93d token=android.os.BinderProxy@3209cee7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  758): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  758): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  758): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  758): setMouseCustomIcon IconType is same.101
D/PointerIcon(  758): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  758): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6531): Initialized EGL, version 1.4
I/OpenGLRenderer( 6531): HWUI protection enabled for context ,  &this =0xb3a5dad8 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6531): Enabling debug mode 0
D/InputMethodManagerService(  758): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline(  758): Timeline: Activity_windows_visible id: ActivityRecord{1036eb80 u0 com.test.thalitest/.MainActivity t3} time:157407
W/ActivityManager(  758): mDVFSHelper.release()
I/SamsungIME( 1726): getCurrentCandidateView
W/IInputConnectionWrapper( 6531): showStatusIcon on inactive InputConnection
I/Timeline( 6531): Timeline: Activity_idle id: android.os.BinderProxy@3209cee7 time:157418
,D/SamsungIME( 1726): Dismiss ExpandCandiate
,I/chromium( 6531): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6531): 
,D/JsMessageQueue( 6531): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1726): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1726): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1726): KeybaordView init() : load resources
,I/SamsungIME( 1726): getCurrentKeyboard
I/SamsungIME( 1726): getTextKeyboard
D/SamsungIME( 1726): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6531): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258378624
,D/JX-Cordova( 6531): jxcore cordova android initializing
,D/SamsungIME( 1726): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/jxcore-log( 6531): Initializing JXcore engine
,W/jxcore-log( 6531): JXcore engine is ready
,W/jxcore-log( 6531): Starting JXcore engine
,E/auditd  ( 1824): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  758): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  758): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  758): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6607 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6607): MountEmulatedStorage()
E/Zygote  ( 6607): v2
I/libpersona( 6607): KNOX_SDCARD checking this for 1000
I/libpersona( 6607): KNOX_SDCARD not a persona
,I/SELinux ( 6607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6607): TimaSignature is unavailable
,D/ActivityThread( 6607): Added TimaKeyStore provider
,W/jxcore-log( 6531): Platform android
W/jxcore-log( 6531): 
W/jxcore-log( 6531): Process ARCH arm
W/jxcore-log( 6531): 
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/ResourcesManager( 6607): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6607):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6607):  SeDenialReceiver : File path = null
,I/ActivityManager(  758): Killing 4879:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,I/PowerManagerService(  758): [PWL] Off : 50s ago
,I/jxcore-log( 6531): JXcore Cordova bridge is ready!
I/jxcore-log( 6531): 
W/jxcore-log( 6531): JXcore engine is started
,D/SSRM:n  (  758): SIOP:: AP = 330, PST = 325, CUR = 450
,V/AlarmManager(  758): waitForAlarm result :4
,D/NtpTrustedTime(  758): forceRefresh() from cache miss
,D/NtpTrustedTime(  758): forceRefresh Fail.
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  758): stay LED for fully charged
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/NetworkUtils( 1502): OkHttp exception
W/EventLoggerService( 1502): Unable to send logs Error code: 262146
,I/art     (  758): Explicit concurrent mark sweep GC freed 63003(4MB) AllocSpace objects, 34(544KB) LOS objects, 17% free, 37MB/45MB, paused 1.294ms total 96.676ms
,I/art     ( 1480): Explicit concurrent mark sweep GC freed 34163(2003KB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 21MB/28MB, paused 492us total 42.292ms
,V/GLSActivity( 1480): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1480): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/System.out( 1480): (HTTPLog)-Static: isSBSettingEnabled false
,E/Auth    ( 1480): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1502): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1480): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1480): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1480): (HTTPLog)-Static: isSBSettingEnabled false
,E/Auth    ( 1480): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1502): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/jxcore-log( 6531): Toggling radios to true
I/jxcore-log( 6531): 
,D/BluetoothAdapter( 6531): enable()
,W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=6531, uid=10283 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  758): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  758): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6531, uid=10283 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  758): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/BluetoothManagerService(  758): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2141)
W/BluetoothManagerService(  758): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService(  758): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  758): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService(  758): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  758): getAllowBluetoothMode - value retunrs : 2
D/SettingsProvider(  758): name = bluetooth_on
,E/DevicePolicyManagerService(  758): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  758): getAllowBluetoothMode - value retunrs : 2
,E/SMD     (  294): DCD ON
,I/WifiManager( 6531): packageName : com.test.thalitest
,D/SecContentProvider(  758): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  758): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  758): mCursor = null
,D/WifiService(  758): setWifiEnabled: true pid=6531, uid=10283
W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=6531, uid=10283 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  758): Failed getting userId using ActivityManagerNative
W/WifiService(  758): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6531, uid=10283 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  758): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  758): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  758): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  758): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  758): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  758): name = wifi_on
,E/WifiHW  (  758): ##################### set firmware type 0 #####################
,I/WifiService(  758): disconnect: pid=6531, uid=10283
,I/jxcore-log( 6531): Radios toggled
I/jxcore-log( 6531): 
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,I/WifiHW  (  289): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
I/WifiHW  (  289): module is semco
E/WifiHW  (  289): ==========[WIFI] SEMCO MODULE ===========
I/WifiHW  (  289): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  (  289): TEMP_FAILURE_RETRY complete
D/SoftapController(  289): Softap fwReload - Ok
,D/CommandListener(  289): Setting iface cfg
D/CommandListener(  289): Trying to bring down wlan0
,D/CommandListener(  289): Clearing all IP addresses on wlan0
,E/WifiHW  (  758): supplicant_name : p2p_supplicant
,E/Zygote  ( 6648): MountEmulatedStorage()
E/Zygote  ( 6648): v2
,I/ActivityManager(  758): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6648 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 6531): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 6531): 
,D/SmartBondingService(  758): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,I/jxcore-log( 6531): Perf Test app loaded loaded
I/jxcore-log( 6531): 
,I/libpersona( 6648): KNOX_SDCARD checking this for 1002
,I/libpersona( 6648): KNOX_SDCARD not a persona
,I/chromium( 6531): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SmartBondingService(  758): getNetworkEnabled : wifi : false mobile : true
,I/jxcore-log( 6531): check test folder
I/jxcore-log( 6531): 
,I/jxcore-log( 6531): found test : ./testFindPeers.js
I/jxcore-log( 6531): 
,D/WifiMonitor(  758): startMonitoring(wlan0) with mConnected = false
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 6531): found test : ./testSendData.js
I/jxcore-log( 6531): 
,I/wpa_supplicant( 6647): [wpa_supplicant_init]: use SECRIL
,I/wpa_supplicant( 6647): Successfully initialized wpa_supplicant
,E/Zygote  ( 6654): MountEmulatedStorage()
E/Zygote  ( 6654): v2
I/libpersona( 6654): KNOX_SDCARD checking this for 10152
,I/libpersona( 6654): KNOX_SDCARD not a persona
,I/SecureStorage( 6647): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6647): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  387): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6647
I/SecureStorage(  387): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 6647): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6647): ssSupport state is = 1
,I/wpa_supplicant( 6647): >>>>> GET KEY, IV <<<<<
,I/SecureStorage( 6647): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  387): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6647
I/SecureStorage(  387): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,I/SELinux ( 6648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 1191): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1191): Wifi onReceive(2)
,D/HotspotTile( 1191): onReceive : android.net.wifi.WIFI_STATE_CHANGED
I/ActivityManager(  758): Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6654 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/STATUSBAR-QSTileView( 1191): onStateChanged: Wi-Fi
,D/WifiCredService( 1315): Action received :android.net.wifi.WIFI_STATE_CHANGED
,I/SELinux ( 6654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/HotspotTile( 1191): onReceive : 2, 0
,I/SELinux ( 6654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/TimaKeyStoreProvider( 6648): TimaSignature is unavailable
,E/SELinux ( 6654): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityThread( 6648): Added TimaKeyStore provider
,D/ResourcesManager( 6648): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager( 6648): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6648): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6654): TimaSignature is unavailable
,D/ActivityThread( 6654): Added TimaKeyStore provider
,D/ResourcesManager( 6654): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,I/chromium( 6531): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/BluetoothA2dpSinkServiceJni( 6648): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 6648): Adding GattService
,D/BtSettings.ProfileConfig( 6648): Adding HeadsetService
D/BtSettings.ProfileConfig( 6648): Adding A2dpService
D/BtSettings.ProfileConfig( 6648): Adding HidService
,D/BtSettings.ProfileConfig( 6648): Adding HealthService
D/BtSettings.ProfileConfig( 6648): Adding PanService
D/BtSettings.ProfileConfig( 6648): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 6648): Adding SapService
D/BtSettings.ProfileConfig( 6648): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 6648): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 6648): Adding SapClientService
,D/BtSettings.ProfileConfig( 6648): Adding HidDevService
I/BtSettings.ProfileConfig( 6648): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider(  758): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  758): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  758): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
,D/SettingsProvider(  758): selectionArgs: 1002
,D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  758): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  758): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  758): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  758): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  758): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  758): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  758): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  758): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/WebViewFactory( 6654): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6654): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/SettingsProvider(  758): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/LibraryLoader( 6654): Loading: webviewchromium
,I/LibraryLoader( 6654): Time to load native libraries: 6 ms (timestamps 1645-1651)
,I/LibraryLoader( 6654): Expected native library version number "",actual native library version number ""
,D/BluetoothAdapterState( 6648): make
,I/bluedroid( 6648): init
I/BluetoothAdapterState( 6648): Entering OffState
,I/bte_conf( 6648): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6648): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6648): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6648): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 6648): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 6648): get_profile_interface socket
I/bluedroid( 6648): get_profile_interface map_client
I/GKI_LINUX( 6648): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterService( 6648): checkAddrForIOP: Loading from conf
,D/BluetoothAdapterProperties( 6648): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6648): populateRssiValuesNative
I/bluedroid( 6648): getModelRssiValues
E/BluetoothServiceJni( 6648): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6648): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/SettingsProvider(  758): name = bluetooth_name
,D/BluetoothAdapterProperties( 6648): Name is: Note3-1
,I/bluedroid( 6648): config_hci_snoop_log
,D/BluetoothManagerService(  758): Broadcasting onBluetoothServiceUp() to 10 receivers.
,E/DevicePolicyManagerService(  758): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  758): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider(  758): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState( 6648): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties( 6648): Setting state to 11
I/BluetoothAdapterState( 6648): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 6648): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6648): updateAdapterState state is 11
,D/BluetoothAdapterService( 6648): Autoconnection is available 
,D/BluetoothAdapterService( 6648): updateAdapterState prevState = 10newState = 11
,W/InputMethodManagerService(  758): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  758): [BT Setting State] State =11
,D/BluetoothSecureManager( 6648): getInstant: null
,I/SamsungIME( 1726): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothSecureManager( 6648): calling getMethod for getService
,D/BluetoothTile( 1191):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1191): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothSecureManager( 6648): calling getService
,I/SecureStorage(  387): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
D/BluetoothSecureManager( 6648): getService return binder: android.os.BinderProxy@6c46e85
D/BluetoothSecureManagerService(  758): isSecureModeEnabled
D/BluetoothSecureManagerService(  758): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 6648): isSecureModeOn:false
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6648): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 6648): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/STATUSBAR-QSTileView( 1191): onStateChanged: Bluetooth
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 6648): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/StatusBarManagerService(  758): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
W/BluetoothAdapterService( 6648): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 6648): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6648): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/StatusBarManagerService(  758): setIconVisibility slot=bluetooth visible=false
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 6648): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6648): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 6648): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
D/PhoneStatusBar( 1191): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
W/BluetoothAdapterService( 6648): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 6648): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 6648): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 6648): make
,W/BluetoothAdapterService( 6648): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine( 6648): StableState(): Entering Off State
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6648): Not skipping com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6648): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6648): Not skipping com.android.bluetooth.hfp.HeadsetService
V/WebViewChromiumFactoryProvider( 6654): Binding Chromium to main looper Looper (main, tid 1) {3316b2cd}
,I/BtGatt.JNI( 6648): classInitNative(L890): classInitNative: Success!
,W/BluetoothAdapterService( 6648): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 6648): Not skipping com.android.bluetooth.a2dp.A2dpService
I/LibraryLoader( 6654): Expected native library version number "",actual native library version number ""
,I/chromium( 6654): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/BtGatt.DebugUtils( 6648): handleDebugAction() action=null
,D/BtGatt.GattService( 6648): Received start request. Starting profile...
D/BtGatt.GattService( 6648): start()
I/bluedroid( 6648): get_profile_interface gatt
,D/BluetoothAdapterService( 6648): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b36064
D/BtGatt.AdvertiseManager( 6648): advertise manager created
,W/BluetoothAdapterService( 6648): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6648): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 6648): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6648): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 6648): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6648): Not skipping com.android.bluetooth.pan.PanService
,I/BrowserStartupController( 6654): Initializing chromium process, renderers=0
,W/BluetoothAdapterService( 6648): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6648): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/art     ( 6654): Attempt to remove local handle scope entry from IRT, ignoring
,W/BluetoothAdapterService( 6648): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6648): Not skipping com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 6648): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b36064
,W/BluetoothAdapterService( 6648): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6648): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6648): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6648): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6648): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6648): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 6648): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 6648): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6648): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 6648): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetService( 6648): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 6648): classInitNative: succeeds
,D/HeadsetStateMachine( 6648): make
,E/HeadsetStateMachine( 6648): # of Max HF connection is 2
,W/chromium( 6654): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6654): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/bluedroid( 6648): get_profile_interface handsfree
,I/chromium( 6654): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46780 len=2953
,I/chromium( 6654): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229536 len:643667
,I/DualScoManager( 6648): Instantiating Dual Sco Manager
I/DualScoManager( 6648): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 6648): createCMTIContentObservers
D/SettingsProvider(  758): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 6648): Enter Disconnected: -2
,D/BluetoothAdapterService( 6648): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b36064
,E/HeadsetStateMachine( 6648): set to mRemoteBrsf = 0
,D/A2dpService( 6648): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 6648): classInitNative: succeeds
V/Avrcp   ( 6648): make
V/Avrcp   ( 6648): Avrcp
I/bluedroid( 6648): get_profile_interface avrcp
,V/Avrcp   ( 6648): start
,D/BluetoothA2dp(  758): Proxy object connected
D/HeadsetStateMachine( 6648): map size, before remove : 0
D/HeadsetStateMachine( 6648): map size, after remove: 0
D/HeadsetStateMachine( 6648): mNextConnectingDevice : null
,D/BluetoothA2dp( 2929): Proxy object connected
,E/RemoteController( 6648): Cannot set synchronization mode on an unregistered RemoteController
V/Avrcp   ( 6648): ++registerMediaPlayers++
I/Avrcp   ( 6648): No of Audio players :: 2
I/Avrcp   ( 6648): App Package name is com.google.android.music
,D/ResourcesManager( 6648): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   ( 6648): App pkg name is Google Play Music
I/Avrcp   ( 6648): Name::Google Play Music
V/Avrcp   ( 6648): MediaPlayerInfo: mPlayerId=1
I/Avrcp   ( 6648): App Package name is com.sec.android.app.music
D/ResourcesManager( 6648): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
I/Avrcp   ( 6648): App pkg name is Music
I/Avrcp   ( 6648): Name::Music
V/Avrcp   ( 6648): MediaPlayerInfo: mPlayerId=2
I/Avrcp   ( 6648):  set player publishabilty with player id::2 toBePublished ::true
I/Avrcp   ( 6648): No of Video players :: 1
I/Avrcp   ( 6648): Video App Package name is com.sec.android.app.videoplayer
D/ResourcesManager( 6648): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/Adreno-EGL( 6654): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6654): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6654): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6654): Local Branch: mybranch5813579
I/Adreno-EGL( 6654): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6654): Local Patches: NONE
I/Adreno-EGL( 6654): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
I/Avrcp   ( 6648): Video App pkg name is Video Player
I/Avrcp   ( 6648): Name::Video Player
V/Avrcp   ( 6648): MediaPlayerInfo: mPlayerId=3
I/Avrcp   ( 6648): Add tempPlayer
V/Avrcp   ( 6648): MediaPlayerInfo: mPlayerId=4
I/Avrcp   ( 6648): Total no of players: 4
V/Avrcp   ( 6648): swapping the samsung player with 1st player
I/Avrcp   ( 6648):  Updating now playing list upon AVRCP Start
V/Avrcp   ( 6648): handleMessage, msg=207
D/BluetoothMediaBrowser( 6648):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
I/BluetoothA2dpServiceJni( 6648): classInitNative: succeeds
D/A2dpStateMachine( 6648): make
I/bluedroid( 6648): get_profile_interface a2dp
I/GKI_LINUX( 6648): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 6648): warning : media task started media_task_refcnt 1 
D/BluetoothAdapterService( 6648): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b36064
I/BluetoothHidServiceJni( 6648): classInitNative: succeeds
D/A2dpStateMachine( 6648): Enter Disconnected: -2
D/HidService( 6648): Received start request. Starting profile...
I/bluedroid( 6648): get_profile_interface hidhost
D/HidService( 6648): setHidService(): set to: null
D/BluetoothAdapterService( 6648): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b36064
D/BluetoothMediaBrowser( 6648): no now playing list
D/BluetoothMediaBrowser( 6648):  getNowPlayingId now playing id : -1
D/Avrcp   ( 6648):  checkNowPlayingList start
I/BluetoothHealthServiceJni( 6648): classInitNative: succeeds
D/HealthService( 6648): Received start request. Starting profile...
I/bluedroid( 6648): get_profile_interface health
D/BluetoothAdapterService( 6648): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b36064
I/BluetoothPanServiceJni( 6648): classInitNative(L105): succeeds
D/BluetoothPan(  758): BluetoothPAN Proxy object connected
D/PanService( 6648): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6648): initializeNative(L110): pan
I/bluedroid( 6648): get_profile_interface pan
D/BluetoothAdapterService( 6648): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b36064
,D/BluetoothMapService( 6648): Received start request. Starting profile...
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6720): MountEmulatedStorage()
E/Zygote  ( 6720): v2
I/libpersona( 6720): KNOX_SDCARD checking this for 10186
I/libpersona( 6720): KNOX_SDCARD not a persona
,I/SELinux ( 6720): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6720): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6720): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  758): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6720 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6720): TimaSignature is unavailable
,D/ActivityThread( 6720): Added TimaKeyStore provider
,W/chromium( 6654): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6654): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/ResourcesManager( 6720): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 6720): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6720): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6720): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6720): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6720): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/art     ( 6654): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6654): onDetachedFromWindow called when already detached. Ignoring
,I/SecureStorage( 6647): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 6647): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6647): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  387): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6647
I/SecureStorage(  387): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6647): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6647): ssSupport state is = 1
,I/wpa_supplicant( 6647): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 6647): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6647): SIM READ ERROR
I/wpa_supplicant( 6647): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6647): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6647): SIM READ ERROR
I/wpa_supplicant( 6647): Blacklist: Clear (all) 
,I/wpa_supplicant( 6647): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6647): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 6647): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6647): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 6647): rfkill: Cannot open RFKILL control device
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
,D/BluetoothAdapterService( 6648): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b36064
D/RCPManagerService(  758): exchangeData() failure , invalid userId
,E/BluetoothAdapterService(112418916)( 6648): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,I/BluetoothSAPServiceJni( 6648): classInitNative(L204): succeeds
,D/SapService( 6648): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 6648): initializeNative(L209): sap
,I/bluedroid( 6648): get_profile_interface sap
D/BluetoothAdapterService( 6648): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b36064
D/HeadsetStateMachine( 6648): Try to query the phonestate on bind
,I/Telecom ( 1400): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1400): BluetoothPhoneService: updateHeadsetWithCallState
,D/BadgeProvider( 6040): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/Telecom ( 1400): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,E/SignOutReceiver( 6183): WIFI_STATE_CHANGED_ACTION
,W/BluetoothHeadset( 1400): Proxy not attached to service
,D/HeadsetStateMachine( 6648): Proxy object connected
D/HeadsetPhoneState( 6648): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 6648): sendDeviceDataStateChanged
D/HeadsetStateMachine( 6648): Disconnected process message: 11
D/HeadsetStateMachine( 6648): Disconnected process message: 18
D/HeadsetPhoneState( 6648): Signal level : previous=0 curr=0
,E/BluetoothAdapterService(112418916)( 6648): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6648): Disconnected process message: 10
D/BluetoothA2dp( 6648): Proxy object connected
,D/BluetoothAdapterService( 6648): Bluetooth A2dp source service connected
D/HeadsetPhoneState( 6648): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6648): Disconnected process message: 11
E/BluetoothAdapterService(112418916)( 6648): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(112418916)( 6648): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
,E/BluetoothAdapterService(112418916)( 6648): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,E/BluetoothAdapterService(112418916)( 6648): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,I/ActivityManager(  758): Killing 4953:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,E/BluetoothAdapterService(112418916)( 6648): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,E/BluetoothAdapterService(112418916)( 6648): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 6648): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 6648): enable
,D/Launcher.Model( 1444): reloadBadges entered.
,D/BadgeProvider( 6040): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6040): sendNotify, [notify] : null
D/BadgeProvider( 6040): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6040): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6040): update, [UpdateCount] : 1
,I/bt_hci_bdroid( 6648): init
I/GKI_LINUX( 6648): gki_task_entry task_id=0 [BTU] starting
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6607): KnoxConfiguration : Current State = 1
,I/bt_vendor( 6648): init
I/bt_vnd_conf( 6648): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
D/SecurityLogAgent( 6607): KnoxConfiguration : Current State Mapping Found 
,I/bt_vnd_conf( 6648): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6648): userial_init
D/SecurityLogAgent( 6607): StateMachine : Current State = 1
D/bt_vendor( 6648): op for 5
D/bt_vendor( 6648): op for 0
,D/bt_upio ( 6648): upio_set_bluetooth_power(on: 0)
,D/bt_upio ( 6648): is_emulator_context : 0
D/bt_upio ( 6648): is_rfkill_disabled ? [0]
D/bt_upio ( 6648): is_rfkill_disabled ? [0]
,D/bt_vendor( 6648): op for 0
,D/bt_upio ( 6648): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6648): is_emulator_context : 0
D/bt_upio ( 6648): is_rfkill_disabled ? [0]
D/bt_vendor( 6648): op for 3
I/bt_userial_vendor( 6648): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 6648): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 6648): device fd = 65 open
D/bt_vendor( 6648): op for 1
D/bt_userial( 6648): Entering userial_read_thread()
,E/bt_hwcfg( 6648): Start CFG HW, HCI reset
,D/SecurityLogAgent( 6607): StateMachine : Changed Current State = 1
,I/ActivityManager(  758): Killing 5727:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,D/BluetoothNotiBroadcastReceiver( 1315): onReceive
,D/AuthorizationBluetoothService( 1480): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/bt_hwcfg( 6648): Read Local Name after HCI reset
,D/bt_hwcfg( 6648): Chipset BCM4335C0
,D/bt_hwcfg( 6648): Target name = [BCM4335C0]
,I/bt_hwcfg( 6648): module_type[semco].
I/bt_hwcfg( 6648): not ZERO...
I/bt_hwcfg( 6648): module_type[semco] is invalid.
,E/bt_hwcfg( 6648): patchram path ORG . BCM4335C0
E/bt_hwcfg( 6648): patchram path ORG .. BCM4335C0
E/bt_hwcfg( 6648): patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
E/bt_hwcfg( 6648): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6648): patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
E/bt_hwcfg( 6648): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6648): patchram path ORG bcm4335_V0093.0399.hcd BCM4335C0
,E/bt_hwcfg( 6648): patchram path ORG bcm4335_V0093.0399_wisol.hcd BCM4335C0
E/bt_hwcfg( 6648): fw ver (org)0.0
E/bt_hwcfg( 6648): vendor lib preload failed to locate firmware patch file
E/bt_hwcfg( 6648): Remove module rev, try again BCM4335
D/bt_hwcfg( 6648): Target name = [BCM4335]
I/bt_hwcfg( 6648): module_type[semco].
I/bt_hwcfg( 6648): not ZERO...
,I/bt_hwcfg( 6648): module_type[semco] is invalid.
E/bt_hwcfg( 6648): patchram path ORG . BCM4335
E/bt_hwcfg( 6648): patchram path ORG .. BCM4335
E/bt_hwcfg( 6648): patchram path ORG bcm2079xB4_firmware.ncd BCM4335
E/bt_hwcfg( 6648): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6648): patchram path ORG bcm2079xB5_firmware.ncd BCM4335
E/bt_hwcfg( 6648): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
,E/bt_hwcfg( 6648): patchram path ORG bcm4335_V0093.0399.hcd BCM4335
I/bt_hwcfg( 6648): patch(org) : bcm4335_V0093.0399.hcd
I/bt_hwcfg( 6648): Found patchfile: /vendor/firmware/bcm4335_V0093.0399.hcd
E/bt_hwcfg( 6648): ORG patchram base 0093
E/bt_hwcfg( 6648): ORG patchram minor 0399
E/bt_hwcfg( 6648): fw ver (org)93.399
E/bt_hwcfg( 6648): Final Patchram is /vendor/firmware/bcm4335_V0093.0399.hcd
,I/bt_hwcfg( 6648): Axi patch failure or not include AXI patching
,I/bt_hwcfg( 6648): bt vendor lib: set UART baud 3000000
,W/ActivityManager(  758): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/bt_hwcfg( 6648): bt vendor lib: set UART baud 115200
,I/bt_hwcfg( 6648): FW Download delta = 553542
D/bt_hwcfg( 6648): Settlement delay -- 100 ms
I/bt_hwcfg( 6648): Setting fw settlement delay to 100 
,E/Tethering(  758): No numeric data
,D/Tethering(  758): sendTetherStateChangedBroadcast 1, 0, 0
,D/HotspotTile( 1191): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1191): updateTetherState():false, false
D/NtpTrustedTime(  758): forceRefresh() from cache miss
,I/wpa_supplicant( 6647): wlan0: Setting scan request: 0 sec 100000 usec
,D/NtpTrustedTime(  758): forceRefresh Fail.
,V/NetworkStats(  758): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  758): UpdateStatsForKnox
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  758): performPollLocked() took 7ms,
D/NtpTrustedTime(  758): forceRefresh() from cache miss
D/NtpTrustedTime(  758): forceRefresh Fail.
,I/wpa_supplicant( 6647): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 6647): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6647): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  387): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6647
I/SecureStorage(  387): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,I/SecureStorage( 6647): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6647): ssSupport state is = 1
,I/SecureStorage( 6647): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 6647): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  387): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6647
,I/SecureStorage(  387): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6647): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6647): ssSupport state is = 1
,I/wpa_supplicant( 6647): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6647): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6647): SIM READ ERROR
I/wpa_supplicant( 6647): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 6647): p2p0: State: DISCONNECTED -> INACTIVE
,I/wpa_supplicant( 6647): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6647): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 6647): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  758): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-HAL(  758): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 6647): HOTSPOT20_ENABLE called
I/wpa_supplicant( 6647): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6647): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6647): SIM READ ERROR
I/wpa_supplicant( 6647): Blacklist: Clear (all) 
,I/bt_hwcfg( 6648): bt vendor lib: set UART baud 3000000
,I/wpa_supplicant( 6647): Skip scan - bUseNetwork false
,D/SmartBondingService(  758): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/SmartBondingService(  758): getNetworkEnabled : wifi : true mobile : true
D/WifiNative-HAL(  758): callSECApiInt - ID [210]
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/WifiCredService( 1315): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/WifiConfigStore(  758): Loading config and enabling all networks 
D/STATUSBAR-WifiQuickSettingButton( 1191): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1191): Wifi onReceive(3)
,D/HotspotTile( 1191): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1191): onStateChanged: Wi-Fi
,D/HotspotTile( 1191): onReceive : 3, 0
,E/WifiConfigStore(  758): Not a HS20
,E/SignOutReceiver( 6183): WIFI_STATE_CHANGED_ACTION
,I/bt_hwcfg( 6648): vendor lib fwcfg completed
,E/WifiConfigStore(  758): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/        ( 6648): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6648): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6648): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6648): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6648): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6648): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6648): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6648): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6648): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6648): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6648): BTE_InitTraceLevels -- TRC_SAP
I/        ( 6648): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6648): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6648): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6648): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6648): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 6648): BTE_InitTraceLevels -- TRC_PROTOCOL
D/WifiNative-HAL(  758): callSECApiInt - ID [65]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6607): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6607): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6607): StateMachine : Current State = 1
,D/SecurityLogAgent( 6607): StateMachine : Changed Current State = 1
,D/WifiNative-HAL(  758): callSECApiBoolean - ID [13]
I/wpa_supplicant( 6647): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6647): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6647): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6647): P2P: Current p2p state = IDLE
I/wpa_supplicant( 6647): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 6647): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6647): First Scan Start
,I/wpa_supplicant( 6647): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL(  758): Setting external_sim to 1
,D/WifiStateMachine(  758): Setting OUI to DA-A1-19
I/WifiNative-HAL(  758): startHal
E/wifi    (  758): getStaticLongField sWifiHalHandle 0x999e186c
D/wifi    (  758): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x601f02
I/WifiNative-HAL(  758): Could not start hal
,E/native  (  758): do suspend true
,E/WifiStateMachine(  758): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,D/WifiScanningService(  758): SCAN_AVAILABLE : 3
D/RttService(  758): SCAN_AVAILABLE : 3
D/WifiScanningService(  758): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  758): startHal
E/wifi    (  758): getStaticLongField sWifiHalHandle 0x90ce999c
D/wifi    (  758): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xc01e12
I/WifiNative-HAL(  758): Could not start hal
E/WifiScanningService(  758): could not start HAL
D/RttService(  758): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  758): P2pDisabledState{ what=131203 }
,D/CommandListener(  289): Setting iface cfg
D/CommandListener(  289): Trying to bring up p2p0
D/WifiMonitor(  758): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService(  758): P2pEnablingState
,D/WifiP2pService(  758): P2pEnablingState{ what=147457 }
E/WifiStateMachine(  758): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL(  758): callSECStringApiVoid - ID [215]
E/WifiNative-HAL(  758): invaild command id : 215
,D/WifiP2pService(  758): P2p socket connection successful
D/WifiP2pService(  758): P2pEnabledState
,D/WifiDisplayController(  758): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
E/WifiStateMachine(  758): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController(  758): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  758): disconnect
D/WifiDisplayController(  758): updateConnection
D/WifiDisplayController(  758): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  758): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService(  758): sending p2p connection changed broadcast: IDLE
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 6647): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/Zygote  ( 6767): MountEmulatedStorage()
E/Zygote  ( 6767): v2
I/libpersona( 6767): KNOX_SDCARD checking this for 10192
I/libpersona( 6767): KNOX_SDCARD not a persona
,I/SELinux ( 6767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  758): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6767 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/AllShareCastTile( 1191): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter(  758): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1191): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
E/SELinux ( 6767): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiP2pService(  758): create mNetworkAgent
,D/WifiDisplayController(  758): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/wpa_supplicant( 6647): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/SecContentProvider2(  758): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  758): mCursor = null
,D/SecContentProvider2(  758): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  758): mCursor = null
,D/ConnectivityService(  758): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  758): Got NetworkAgent Messenger
D/ConnectivityService(  758): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService(  758): updateNetworkInfo()
D/ConnectivityService(  758): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  758): NetworkAgent connected
E/CSLegacyTypeTracker(  758): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,D/WifiNative-HAL(  758): p2pGetDeviceAddress
,D/WifiNative-HAL(  758): p2pGetDeviceAddress returning ea:50:8b:de:28:a3
D/WifiP2pService(  758): DeviceAddress: ea:28:a3
,D/WifiDisplayController(  758): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
D/WifiDisplayController(  758):  deviceAddress: ea:50:8b:de:28:a3
D/WifiDisplayController(  758):  primary type: 10-0050F204-5
D/WifiDisplayController(  758):  secondary type: null
D/WifiDisplayController(  758):  wps: 0
D/WifiDisplayController(  758):  grpcapab: 0
D/WifiDisplayController(  758):  devcapab: 0
D/WifiDisplayController(  758):  status: 3
D/WifiDisplayController(  758):  wfdInfo: null
D/WifiDisplayController(  758):  groupownerAddress: null
D/WifiDisplayController(  758):  GOdeviceName: null
D/WifiDisplayController(  758):  interfaceAddress: 
D/WifiDisplayController(  758):  SConnectInfo : null
,D/TimaKeyStoreProvider( 6767): TimaSignature is unavailable
,D/ActivityThread( 6767): Added TimaKeyStore provider
,D/WifiP2pService(  758): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  758): InactiveState
D/WifiP2pService(  758): InactiveState{ what=143376 }
D/WifiP2pService(  758): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 6647): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService(  758): updateNetworkInfo()
D/ConnectivityService(  758): ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
D/WifiP2pService(  758): InactiveState{ what=143376 }
,D/WifiP2pService(  758): P2pEnabledState{ what=143376 }
,D/ResourcesManager( 6767): creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,D/WifiDirectBR( 6767): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager(  758): Killing 5806:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,E/lowmemorykiller(  251): Error writing /proc/5806/oom_score_adj; errno=22
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1315): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 6364): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/WifiDirectBR( 6767): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 6767): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 6767): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/WifiDirectBR( 6767): stopServiceTest : false
,W/bt-l2cap( 6648): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  ( 6648): BTM_SecRegister:p_cb_info->p_le_callback == 0xafc25b05 
E/bt-btm  ( 6648): BTM_SecRegister: btm_cb.api.p_le_callback = 0xafc25b05 
,D/BluetoothAdapterProperties( 6648): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 0 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,E/bt-btif ( 6648): Calling BTA_HhEnable
,E/bt-btif ( 6648): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties( 6648): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6648): populateRssiValuesNative
I/bluedroid( 6648): getModelRssiValues
E/BluetoothServiceJni( 6648): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6648): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6648): Name is: Note3-1
,D/SettingsProvider(  758): name = bluetooth_name
D/BluetoothAdapterProperties( 6648): Scan Mode:20
,D/BluetoothAdapterProperties( 6648): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 6648): LE Address is:E0:B7:20:3E:93:BC
E/bt-btif ( 6648): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
D/bt_vendor( 6648): op for 2
D/bt_vendor( 6648): op for 6
,E/bt-btif ( 6648): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
D/bt_vendor( 6648): op for 7
E/bt-btif ( 6648): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 6648): btif_sock_init: !vhci_init
D/bt_upio ( 6648): proc btwrite assertion
D/IOP_DB_BT( 6648): db_open: file /etc/bluetooth/iop_bt.db
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bt_vendor( 6648): op for 7
D/IOP_DB_BT( 6648): db_open: db_open : handle 3026186256l, read 14063 bytes onto local cache
D/bt_upio ( 6648): BT_WAKE is asserted already
D/IOP_DB_BT( 6648): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 6648): db_query: result 1
I/        ( 6648): iop_db_open: iop_db_open status 0
D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bte_conf( 6648): Device ID record 1 : primary
D/bte_conf( 6648):   vendorId            = 0075
D/bte_conf( 6648):   vendorIdSource      = 0001
D/bte_conf( 6648):   product             = 0100
D/bte_conf( 6648):   version             = 0200
D/bte_conf( 6648):   clientExecutableURL = 
D/bte_conf( 6648):   serviceDescription  = 
D/bte_conf( 6648):   documentationURL    = 
D/bte_conf( 6648): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 6648): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6648): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6648): ScanMode =  20
D/BluetoothAdapterProperties( 6648): State =  11
,D/SecContentProvider(  758): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 6648): Scan Mode:21
D/BluetoothAdapterProperties( 6648): Setting state to 12
D/BluetoothAdapterProperties( 6648): Discoverable Timeout:120
I/BluetoothAdapterState( 6648): Bluetooth adapter state changed: 11-> 12
,D/SettingsProvider(  758): name = bluetooth_a2dp_sink_mode
,D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 1002
,D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  758): ret = -1
,W/BackupManagerService(  758): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,E/bt_h4   ( 6648): vendor lib postload completed
D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/BluetoothAdapterService( 6648): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6648): updateAdapterState state is 12
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/BluetoothAdapterService( 6648): Autoconnection is available 
D/BluetoothAdapterService( 6648): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 6648): starting service from this receiver
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
D/BluetoothA2dp( 2929): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 6648): onBluetoothStateChange: up=true
D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,I/BluetoothAdapterState( 6648): Entering On State from state = 11
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
D/BluetoothA2dp(  758): onBluetoothStateChange: up=true
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,W/InputMethodManagerService(  758): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  758): [BT Setting State] State =12
I/InputMethodManagerService(  758): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/BluetoothHeadset( 1400): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3c4d0273, true
,D/BluetoothHeadset( 1400): registerMessageListener
D/BluetoothTile( 1191):  onBluetoothStateChange:
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bt_vendor( 6648): op for 7
,D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
I/SamsungIME( 1726): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/HeadsetService( 6648): registerMessageListener
,I/BluetoothPbapService( 6648): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
D/HeadsetService( 6648): registerMessageListener
D/HeadsetStateMachine( 6648): Disconnected process message: 70
D/HeadsetStateMachine( 6648): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@39c8ccc7
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,I/Telecom ( 1400): BluetoothPhoneService: updateHeadsetWithCallState
I/Telecom ( 1400): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/bt_vendor( 6648): op for 7
D/HeadsetStateMachine( 6648): Disconnected process message: 9
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/HeadsetStateMachine( 6648): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
,D/BluetoothTile( 1191):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1191): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/audio_hw_primary(  303): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  303): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  303): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  303): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  303): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  303): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  303): adev_set_parameters: exit
E/HeadsetStateMachine( 6648): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothTile( 1191):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1191): onStateChanged: Bluetooth
,D/StatusBarManagerService(  758): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/StatusBarManagerService(  758): setIconVisibility slot=bluetooth visible=true
,D/PhoneStatusBar( 1191): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/BluetoothManagerService(  758): Broadcasting onBluetoothServiceUp() to 0 receivers.
,I/BluetoothPbapService( 6648): Handler(): got msg=1
D/SecContentProvider(  758): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/BluetoothPbapService( 6648): PBAP Service initSocket try: 0
,W/BluetoothAdapter( 6648): getBluetoothService() called with no BluetoothManagerCallback
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
D/BluetoothSocket( 6648): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket( 6648): bindListen(), new LocalSocket 
D/BluetoothSocket( 6648): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6648): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c30e7de
,D/BluetoothSocket( 6648): channel: 19
D/BluetoothPbapService( 6648): PBAP Socket is BluetoothServerSocket
D/BluetoothMapMasInstance( 6648): set MAP SDP message type : 1
,D/LocalBluetoothProfileManager( 1315): Adding local A2DP profile
,W/BluetoothAdapter( 6648): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6648): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 6648): bindListen(), new LocalSocket 
D/BluetoothSocket( 6648): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6648): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b2c8dbf
,D/bt_vendor( 6648): op for 7
D/bt_upio ( 6648): BT_WAKE is asserted already
D/BluetoothSocket( 6648): channel: 5
,D/LocalBluetoothProfileManager( 1315): Adding local HEADSET profile
,E/BluetoothHeadset( 1315): BTStateChangeCB is registed
,E/BluetoothHeadset( 1315): BluetoothHeadset service is binded
,W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 1315): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1315): PANU : true
D/LocalBluetoothProfileManager( 1315): Adding local MAP profile
,D/BluetoothMap( 1315): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 1315): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1315): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1315): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1315): onReceive
,D/BluetoothA2dp( 1315): Proxy object connected
D/A2dpProfile( 1315): Bluetooth service connected
,D/BluetoothAdapterService( 6648): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b36064
D/BtConfig.SecureMode( 6648): isSecureModeOn:false
,D/HeadsetProfile( 1315): Bluetooth service connected
,D/Bluetoothsap( 1315): BluetoothSAP Proxy object connected
,D/SapProfile( 1315): Bluetooth service connected
,D/Bluetoothsap( 1315): getConnectedDevices()
,D/BluetoothInputDevice( 1315): Proxy object connected
,D/HidProfile( 1315): Bluetooth service connected
,D/AuthorizationBluetoothService( 1480): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPan( 1315): BluetoothPAN Proxy object connected
,D/PanProfile( 1315): Bluetooth service connected
,D/BluetoothMap( 1315): Proxy object connected
,D/MapProfile( 1315): Bluetooth service connected
D/BluetoothPbap( 1315): Proxy object connected
D/PbapServerProfile( 1315): Bluetooth service connected
,D/SecContentProvider(  758): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/BluetoothAdapter( 6648): getBluetoothService() called with no BluetoothManagerCallback
,D/bt_vendor( 6648): op for 7
D/BluetoothSocket( 6648): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
D/BluetoothSocket( 6648): bindListen(), new LocalSocket 
D/BluetoothSocket( 6648): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6648): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11c4e451
D/BluetoothSocket( 6648): channel: 12
I/BtOppRfcommListener( 6648): Accept thread started.
,D/bt_upio ( 6648): BT_WAKE is asserted already
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 6647): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 6647): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6647): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 6647): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 6647): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,D/SecContentProvider2(  758): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  758): mCursor = null
,I/wpa_supplicant( 6647): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 6647): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 6647): Associated with C0.AA.4A
,D/SecContentProvider2(  758): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  758): mCursor = null
,I/wpa_supplicant( 6647): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 6647): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  758): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  758): mCursor = null
,I/wpa_supplicant( 6647): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 6647): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 6647): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 6647): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6647): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 6647): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
I/wpa_supplicant( 6647): Blacklist: Clear (temp) 
I/wpa_supplicant( 6647): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/WifiNative-HAL(  758): callSECApiVoid - ID [50]
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  758): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  758): Got NetworkAgent Messenger
D/ConnectivityService(  758): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  758): updateNetworkInfo()
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  758): NetworkAgent connected
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  289): Setting iface cfg
,E/Zygote  ( 6799): MountEmulatedStorage()
,E/Zygote  ( 6799): v2
I/libpersona( 6799): KNOX_SDCARD checking this for 10038
,I/libpersona( 6799): KNOX_SDCARD not a persona
,I/SELinux ( 6799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  758): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6799 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/WifiStateMachine(  758): Start Dhcp Watchdog 1
,D/SecContentProvider2(  758): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  758): mCursor = null
,I/SELinux ( 6799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
,E/SELinux ( 6799): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  758): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/TimaKeyStoreProvider( 6799): TimaSignature is unavailable
,D/ActivityThread( 6799): Added TimaKeyStore provider
,D/ResourcesManager( 6799): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 6799): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/native  (  758): do suspend false
,D/SecContentProvider2(  758): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  758): mCursor = null
,D/WifiP2pService(  758): InactiveState{ what=143375 }
D/WifiP2pService(  758): P2pEnabledState{ what=143375 }
,I/VlingoApplication( 6799): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/BluetoothHeadset( 6799): BTStateChangeCB is registed
,E/BluetoothHeadset( 6799): BluetoothHeadset service is binded
,E/lowmemorykiller(  251): Error writing /proc/5852/oom_score_adj; errno=22
I/ActivityManager(  758): Killing 5852:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,I/Hs20UtilService( 1315): Starting #2
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1315): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/dhcpcd  ( 6819): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6819): version 5.5.6 starting
,E/dhcpcd  ( 6819): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/SettingsProvider(  758): name = driving_mode_on
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 10038
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,D/BluetoothManager( 6799): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,E/SignOutReceiver( 6183): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  ( 6819): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6819): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6819): if(wlan0) info get Success. (MAC : C0.AA.4A)
,I/dhcpcd  ( 6819): bssid match
,I/dhcpcd  ( 6819): wlan0: rebinding lease of 192.168.1.128
,I/art     (  758): Explicit concurrent mark sweep GC freed 47538(2MB) AllocSpace objects, 1(16KB) LOS objects, 17% free, 37MB/45MB, paused 1.618ms total 97.544ms
,E/SMD     (  294): DCD ON
,D/bt_vendor( 6648): op for 7
,I/dhcpcd  ( 6819): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/dhcpcd  ( 6819): wlan0: leased 192.168.1.128 for 86400 seconds
,D/bt_upio ( 6648): ..proc_btwrite_timeout..
,D/ConnectivityService(  758): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,W/ProcessCpuTracker(  758): Skipping unknown process pid 6839
,E/native  (  758): do suspend true
,D/WifiP2pService(  758): InactiveState{ what=143375 }
,D/WifiP2pService(  758): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  758): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  758): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
,E/WifiStateMachine(  758): VerifyingLinkState enter
,D/WifiNative-HAL(  758): callSECApiInt - ID [210]
,E/ConnectivityService(  758): updateNetworkInfo()
,D/WifiWatchdogStateMachine(  758): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  758): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver(  758): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  758): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker(  758): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  758): Adding iface wlan0 to network 502
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  758): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine(  758): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/WifiTrafficPoller(  758): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  758): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  758): mBoosterFLAG : 0
I/WifiTrafficPoller(  758): current booster mode : FullMode
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/WifiNative-HAL(  758): callSECApiVoid - ID [212]
,E/WifiStateMachine(  758): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  758): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService(  758): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService(  758): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,E/ConnectivityService(  758): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  758): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  758): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  289): QcRouteController
,I/Hs20UtilService( 1315): Starting #3
I/Hs20UtilService( 1315): Message received 5007
D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,V/        (  289): QcRouteController
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/        (  289): QcRouteController
E/SignOutReceiver( 6183): NETWORK_STATE_CHANGED_ACTION
,V/        (  289): QcRouteController
,V/        (  289): QcRouteController
,I/Hs20UtilService( 1315): Starting #4
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1315): Message received 5007
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1315): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6183): NETWORK_STATE_CHANGED_ACTION
,V/        (  289): QcRouteController
,I/Hs20UtilService( 1315): Starting #5
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,V/        (  289): QcRouteController
,D/WifiStateMachine(  758): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  289): QcRouteController
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/        (  289): QcRouteController
,E/Watchdog(  758): !@Sync 5
E/SignOutReceiver( 6183): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger(  254): id=14 createSurf (1x1),1 flag=4, Uoast
,D/ConnectivityService(  758): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService(  758): LTETest block dns file not exists
,V/Nat464Xlat(  758): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  758): calling update connectivity
,E/ConnectivityService(  758): updateNetworkInfo()
D/ConnectivityService(  758): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  758): updateNetworkInfo()
D/ConnectivityService(  758): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/EntConnectivity(  758): Not allowed due to - mEnabled false
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  758): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Connected
D/ConnectivityService(  758): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  758):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  758):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  758):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/System.out(  758): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(  758): (HTTPLog)-Static: isShipBuild true
I/System.out(  758): (HTTPLog)-Thread-181-36260769: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(  758): (HTTPLog)-Static: isSBSettingEnabled false
,D/PowerManagerService(  758): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=758
,D/ConnectivityService(  758): currentScore = 0, newScore = 60
,D/ConnectivityService(  758):    accepting network in place of null
,D/ConnectivityService(  758): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  758): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/TelephonyNetworkFactory( 1421): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  758): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  758): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  758): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  758): MasterInitialState.processMessage what=3
D/ConnectivityService(  758): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  758): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  758): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  758): getSBEnabled() enabled =false
,D/SmartBondingService(  758): getSBEnabled() enabled =false
D/SmartBondingService(  758): getSBEnabled() enabled =false
,V/NetworkStats(  758): updateIfacesLocked()
V/NetworkStats(  758): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  758): UpdateStatsForKnox
D/ConnectivityService(  758): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/EntConnectivity(  758): Not allowed due to - mEnabled false
,D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  758): calling update connectivity
D/ConnectivityService(  758):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  758):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  758): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,V/NetworkStats(  758): performPollLocked() took 6ms
D/ConnectivityManager.CallbackHandler( 1191): CM callback handler got msg 524290
,D/SmartBondingService(  758): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  758): forceRefresh() from cache miss
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1191): updateDataNetType()
D/StatusBar.NetworkController( 1191): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1191): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1191): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,I/System.out(  758): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NtpTrustedTime(  758): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449832369333 mCachedNtpElapsedRealtime : 166152 mCachedNtpCertainty : 7
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
V/NetworkStats(  758): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 11 Dec 2015 11:12:49 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449832369066], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449832369050]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Validated
D/ConnectivityService(  758): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  758):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  758):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  758): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  758): calling update connectivity
D/ConnectivityService(  758):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  758):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  758): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1191): CM callback handler got msg 524290
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1191): updateDataNetType()
D/StatusBar.NetworkController( 1191): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1191): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 1191): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,I/jxcore-log( 6531): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6531): 
,D/PackageManager(  758): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  758): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 1865): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/SmartBondingService(  758): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  758): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  758): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  758): getSBEnabled() enabled =false
D/SmartBondingService(  758): getSBEnabled() enabled =false
,D/SmartBondingService(  758): getSBEnabled() enabled =false
D/SmartBondingService(  758): getNetworkEnabled : wifi : true mobile : true
W/ContextImpl( 1865): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,D/AlarmManagerService(  758): Setting time of day to sec=1449832369
D/AlarmManagerService(  758): Trying to open a file
,D/AlarmManagerService(  758): File Open Success
,D/AlarmManagerService(  758): File Close Success
,I/AlarmManagerService(  758): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager(  758): waitForAlarm result :65536
,W/AlarmManagerService(  758): Unable to set rtc to 1449832369: Invalid argument
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiStateMachine(  758): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_SET
,D/StatusBar-DoNotDistrub( 1191): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 1191): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/GpsLocationProvider(  758): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 1771): [Accuweather J]>>> SWW:64 [0:0] =============== BR act = androidintentactionTIME_SET
D/accuweather( 1771): [Accuweather J]>>> SWW:645 [0:0] renderUpdateAllCondition : [0] = 1
,D/accuweather( 1771): [Accuweather J]>>> WR:452 [0:0] =============== updateAllCondition = 1
D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3138): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3138): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 3138): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 3138): [llIlIIIIlllIlllllIll(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 3138): [IIllIIllIIIlllIlIIll(403/llllllIllIlIlllIIlIl)] Check completed.
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5081): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  758): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6924 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/Settings(  758): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Zygote  ( 6924): MountEmulatedStorage()
E/Zygote  ( 6924): v2
I/libpersona( 6924): KNOX_SDCARD checking this for 10014
I/libpersona( 6924): KNOX_SDCARD not a persona
,D/StatusBar-DoNotDistrub( 1191): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager(  303): getOutputsForDevice device 0002 -> 0002
I/AudioService(  758): getStreamVolume 5 index 0
,I/DBG_DM  ( 3138): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3138): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/StatusBar-DoNotDistrub( 1191): The STREAM NOTIFICATION volume is 0
,I/SELinux ( 6924): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 6924): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/StatusBarManagerService(  758): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
E/SELinux ( 6924): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/DrmEventService(  758):  no response from SecureClock 
,I/PCWCLIENTTRACE_PushUtil( 5891): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5891): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5891): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5891): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3138): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3138): [IIIlllIlIIlllIIIIllI(73/llllIIIllIlIIIIllllI)] 
D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6924): TimaSignature is unavailable
,D/ActivityThread( 6924): Added TimaKeyStore provider
,I/DBG_DM  ( 3138): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3138): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 3138): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 3138): [IIllIIllIIIlllIlIIll(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,E/Zygote  ( 6952): MountEmulatedStorage()
E/Zygote  ( 6952): v2
I/libpersona( 6952): KNOX_SDCARD checking this for 10004
I/libpersona( 6952): KNOX_SDCARD not a persona
,D/ConnectivityService(  758): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
,D/ConnectivityService(  758): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  758): identical MTU - not setting
D/ConnectivityService(  758): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  758): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,V/        (  289): QcRouteController
,I/ActivityManager(  758): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6952 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6952): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6952): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6952): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/        (  289): QcRouteController
,W/NetworkManagementService(  758): route cmd failed: 
W/NetworkManagementService(  758): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '54 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 54 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  758): '
W/NetworkManagementService(  758): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  758): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  758): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  758): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  758): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  758): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  758): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  758): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  758): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  758): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  758): calling update connectivity
D/SmartBondingService(  758): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  758): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  758): getSBEnabled() enabled =false
D/SmartBondingService(  758): getSBEnabled() enabled =false
D/SmartBondingService(  758): getSBEnabled() enabled =false
,D/ConnectivityService(  758):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  758):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,I/DBG_DM  ( 3138): [IIllIIllIIIlllIlIIll(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
D/ResourcesManager( 6924): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
D/ConnectivityService(  758): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1191): CM callback handler got msg 524295
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  758): calling update connectivity
D/ConnectivityService(  758):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  758):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  758): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1191): CM callback handler got msg 524295
,I/DBG_DM  ( 3138): [IIllIlIIlIlllIIllIII(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 3138): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,I/DBG_DM  ( 3138): [llIlIIIIlllIlllllIll(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3138): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/GoogleURLConnFactory( 1480): Using platform SSLCertificateSocketFactory
,I/DBG_DM  ( 3138): [llIlIIIIlllIlllllIll(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 3138): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3138): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,I/DBG_DM  ( 3138): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,D/TimaKeyStoreProvider( 6952): TimaSignature is unavailable
,D/ActivityThread( 6952): Added TimaKeyStore provider
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3138): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 3138): [IIllIlIIlIlllIIllIII(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 3138): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3138): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,E/DBG_DM  ( 3138): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 3138): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@1c30e7de
,D/ResourcesManager( 6952): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3138): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,E/Zygote  ( 6977): MountEmulatedStorage()
,E/Zygote  ( 6977): v2
I/libpersona( 6977): KNOX_SDCARD checking this for 10104
I/libpersona( 6977): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6977 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 3138): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/SELinux ( 6977): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6977): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/art     (  325): Explicit concurrent mark sweep GC freed 8762(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 430us total 17.619ms
,E/SELinux ( 6977): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 409us total 13.800ms
,I/FOTA_Client( 6924): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6924): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 402us total 14.138ms
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6977): TimaSignature is unavailable
,D/ActivityThread( 6977): Added TimaKeyStore provider
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 6997): MountEmulatedStorage()
E/Zygote  ( 6997): v2
I/libpersona( 6997): KNOX_SDCARD checking this for 10023
I/libpersona( 6997): KNOX_SDCARD not a persona
,I/SELinux ( 6997): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6997): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6997): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  758): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6997 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/SecContentProvider2(  758): uri = 14 selection = getSealedState
,D/SecContentProvider2(  758): mCursor = null
,V/GLSActivity( 1480): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 6977): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ApplicationPolicy(  758): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  758): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager(  758): showStatusBarByNotification() mOpenByNotification=false
,D/ResourcesManager( 1191): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,D/TimaKeyStoreProvider( 6997): TimaSignature is unavailable
,D/ActivityThread( 6997): Added TimaKeyStore provider
,D/ResourcesManager( 6997): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/DBG_DM  ( 3138): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/KnoxNotification( 1191): ----- inflateViews : modified publicViewLocal -----
,I/KLMS-2.4.511: ( 6997): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6997): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1449832370352
,I/KLMS-2.4.511: ( 6997): MainReciver(): TIME_CHANGED
,I/KLMS-2.4.511: ( 6997): StateImplV2(): dateTimeChanged().START : Fri Dec 11 12:12:50 GMT+01:00 2015
,D/KnoxNotification( 1191): ----- inflateViews : modified KnoxViewLocal -----
,I/DBG_DM  ( 3138): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/PersonaManager( 1191): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1191): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2e8dc0cd
,D/PersonaManager( 1191): isKioskContainerExistOnDevice
D/PersonaManager( 1191): isKioskContainerExistOnDevice
,I/KLMS-2.4.511: ( 6997): StateImplV2(): dateTimeChanged().END
,E/Zygote  ( 7013): MountEmulatedStorage()
E/Zygote  ( 7013): v2
I/libpersona( 7013): KNOX_SDCARD checking this for 1000
I/libpersona( 7013): KNOX_SDCARD not a persona
,I/SELinux ( 7013): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  758): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7013 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7013): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7013): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  758): Killing 5873:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,E/GpsLocationProvider(  758): No APN found to select.
,W/System.err( 5906): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
,D/PanelView( 1191): There is/are notification(s) 
D/PanelView( 1191): There is/are notification(s) 
W/System.err( 5906): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err( 5906): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err( 5906): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err( 5906): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err( 5906): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
W/System.err( 5906): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 5906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 5906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5906): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5906): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
W/System.err( 5906): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5906): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
W/System.err( 5906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
,I/PhenotypeConfigurator( 1480): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 7013): TimaSignature is unavailable
,I/DBG_DM  ( 3138): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3138): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 3138): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,D/ActivityThread( 7013): Added TimaKeyStore provider
,E/Zygote  ( 7029): MountEmulatedStorage()
I/libpersona( 7029): KNOX_SDCARD checking this for 10042
E/Zygote  ( 7029): v2
I/libpersona( 7029): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/com.sec.android.fota.osp.time.ServerTimeReceiver: pid=7029 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,E/SMD     (  294): DCD ON
,I/SELinux ( 7029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7029): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  758): Killing 5925:com.policydm/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7013): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7029): TimaSignature is unavailable
,D/ActivityThread( 7029): Added TimaKeyStore provider
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityThread( 1754): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1480): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 7029): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/DIAGMON_AGENT( 7013): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/SO_AGENT( 7029): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/SyncManager(  758): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 20139, reason: UserStart, SyncResult: databaseError: true stats []
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 5990): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/DIAGMON_AGENT( 7013): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/SyncManager(  758): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 199732, reason: UserStart
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,E/Auth.Api.Credentials( 1754): [CredentialSyncAdapter] Unknown sync event.
,D/SecContentProvider2(  758): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  758): mCursor = null
,E/Zygote  ( 7050): MountEmulatedStorage()
E/Zygote  ( 7050): v2
I/libpersona( 7050): KNOX_SDCARD checking this for 10076
I/libpersona( 7050): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7050 uid=10076 gids={50076, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  758): Killing 4629:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,I/SELinux ( 7050): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7050): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7050): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7050): TimaSignature is unavailable
,D/ActivityThread( 7050): Added TimaKeyStore provider
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6977): Delaying sync.
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7050): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,I/DIAGMON_AGENT( 7013): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7013): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7013): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7013): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7070): MountEmulatedStorage()
E/Zygote  ( 7070): v2
I/libpersona( 7070): KNOX_SDCARD checking this for 10106
I/libpersona( 7070): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7070 uid=10106 gids={50106, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 7070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  758): Killing 5949:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,I/SELinux ( 7070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7070): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ Time Manager ( 7050): Time Difference not stored. TIME_DIFFERENCE
,D/TimaKeyStoreProvider( 7070): TimaSignature is unavailable
,D/ActivityThread( 7070): Added TimaKeyStore provider
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 6924): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/ResourcesManager( 7070): creating new AssetManager and set to /system/app/ClockPackage_Osup/ClockPackage_Osup.apk
,W/ResourcesManager( 7070): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7070): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7070): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7070): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7070): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7070): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/FOTA_Client( 6924): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/ActivityManager(  758): Killing 6055:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
,I/System.out( 1480): (HTTPLog)-Static: isSBSettingEnabled false
,I/FOTA_Client( 6924): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/System.out( 1480): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1480): Tagging socket 66 with tag 1000120300000000{268440067,0} uid -1, pid: 1480, getuid(): 10015
,I/KLMS-2.4.511: ( 6997): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6997): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449832370917
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  758): Killing 4937:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
I/KLMS-2.4.511: ( 6997): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityChangeReceiver( 1754): Ignoring connectivity change
,D/SettingsProvider(  758): name = next_alarm_formatted
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SettingsProvider(  758): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  758): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  758): selectionArgs: false
D/SettingsProvider(  758): selectionArgs: 10106
D/SecContentProvider(  758): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  758): ret = -1
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6997): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 6997): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 6997): NetworkChangeOperations(): uploadRequestLog().START 
,D/ConnectivityService(  758): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  758): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  758): apparently satisfied.  currentScore=60
D/ConnectivityService(  758): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  758): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
D/ConnectivityManager.CallbackHandler( 1754): CM callback handler got msg 524290
,I/KLMS-2.4.511: ( 6997): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7090): MountEmulatedStorage()
E/Zygote  ( 7090): v2
I/libpersona( 7090): KNOX_SDCARD checking this for 10036
I/libpersona( 7090): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7090 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 7090): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7090): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7090): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7090): TimaSignature is unavailable
,D/ActivityThread( 7090): Added TimaKeyStore provider
,I/qtaguid ( 1480): Tagging socket 70 with tag 1000120300000000{268440067,0} uid -1, pid: 1480, getuid(): 10015
,I/ActivityManager(  758): Killing 6094:com.wsomacp/u0a29 (adj 15): bgCount ##41
,D/ResourcesManager( 7090): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 7090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7090): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 7105): MountEmulatedStorage()
E/Zygote  ( 7105): v2
I/libpersona( 7105): KNOX_SDCARD checking this for 10116
I/libpersona( 7105): KNOX_SDCARD not a persona
,E/Minikin ( 7090): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,I/ActivityManager(  758): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7105 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7105): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7105): TimaSignature is unavailable
,D/ActivityThread( 7105): Added TimaKeyStore provider
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  758): Killing 6078:com.google.android.apps.docs/u0a112 (adj 15): bgCount ##41
,D/ResourcesManager( 7105): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,I/SO_AGENT( 7029): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/elm:14491( 7105): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491( 7105): ELMEngine.ELMEngine( context ).
,D/elm:14491( 7105): MDMBridge.setEnterpriseBridge()
,D/elm:14491( 7105): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14491( 7105): ElmAgentService : onCreate()
,D/elm:14491( 7105): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/DelayedSyncController( 6977): Delaying sync.
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/elm:14491( 7105): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491( 7105): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491( 7105): ModuleBase.ModifySetAlarm()
D/elm:14491( 7105): MDMBridge.getInstance()
,D/elm:14491( 7105): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 7127): MountEmulatedStorage()
E/Zygote  ( 7127): v2
I/libpersona( 7127): KNOX_SDCARD checking this for 1000
I/libpersona( 7127): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7127 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7127): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7127): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7127): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491( 7105): ElmAgentService : onDestroy().
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 7127): TimaSignature is unavailable
,D/ActivityThread( 7127): Added TimaKeyStore provider
,E/Zygote  ( 7142): MountEmulatedStorage()
E/Zygote  ( 7142): v2
I/libpersona( 7142): KNOX_SDCARD checking this for 10172
I/libpersona( 7142): KNOX_SDCARD not a persona
,I/SELinux ( 7142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  758): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7142 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 7142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7142): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  758): Killing 6120:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/ResourcesManager( 7127): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/ActivityManager(  758): Killing 6148:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7142): TimaSignature is unavailable
,D/ActivityThread( 7142): Added TimaKeyStore provider
,D/ResourcesManager( 7142): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7142): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7142): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7142): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PicasaService( 5173): start picasa sync
,D/PicasaService( 5173): end picasa sync
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7171): MountEmulatedStorage()
E/Zygote  ( 7171): v2
I/libpersona( 7171): KNOX_SDCARD checking this for 10051
I/libpersona( 7171): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7171 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7171): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7171): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7171): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7186): MountEmulatedStorage()
,E/Zygote  ( 7186): v2
I/libpersona( 7186): KNOX_SDCARD checking this for 10043
I/libpersona( 7186): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7186 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7186): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/TimaKeyStoreProvider( 7171): TimaSignature is unavailable
,I/SELinux ( 7186): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/ActivityThread( 7171): Added TimaKeyStore provider
,E/SELinux ( 7186): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     (  325): Explicit concurrent mark sweep GC freed 8743(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 386us total 13.889ms
,D/SecurityLogAgent( 6607): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6607): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6607): StateMachine : Current State = 1
D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 283us total 10.017ms
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 7186): TimaSignature is unavailable
,D/ActivityThread( 7186): Added TimaKeyStore provider
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 281us total 10.665ms
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7205): MountEmulatedStorage()
E/Zygote  ( 7205): v2
I/libpersona( 7205): KNOX_SDCARD checking this for 1000
I/libpersona( 7205): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7205 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7205): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/PhenotypeConfigurator( 1480): Server returned 404
,D/TimaKeyStoreProvider( 7205): TimaSignature is unavailable
,D/ActivityThread( 7205): Added TimaKeyStore provider
,I/art     (  758): Explicit concurrent mark sweep GC freed 64159(3MB) AllocSpace objects, 9(144KB) LOS objects, 17% free, 37MB/45MB, paused 1.617ms total 98.474ms
,D/ResourcesManager( 7171): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7171): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7205): creating new AssetManager and set to /system/app/TimeService/TimeService.apk
,D/ResourcesManager( 7186): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/TimeService( 7205): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449832371716
D/        ( 7205): TimeServiceNative: User Time to be set is 1449832371716
D/QC-time-services( 7205): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7205): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7205): Lib:time_genoff_operation: pargs->ts_val = 1449832371716
,D/QC-time-services( 7205): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  364): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  364): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449832371716
D/QC-time-services(  364): Daemon:genoff_opr: Base = 2, val = 1449832371716, operation = 0
,D/QC-time-services(  364): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/19/70 18:1:17
D/QC-time-services(  364): Daemon:Value read from RTC seconds = 9396077000
D/QC-time-services(  364): Daemon:new time 1449832371716 
D/QC-time-services(  364): Daemon: delta 1440436294716 genoff 1440436294716 
D/QC-time-services(  364): Daemon:genoff_persistent_update: Writing genoff = 1440436294716 to memory
D/QC-time-services(  364): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  364): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  364): Updating the TOD offset
D/QC-time-services(  364): Daemon:genoff_persistent_update: Writing genoff = 1440436294716 to memory
D/QC-time-services(  364): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  364): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  364): Daemon:Update to modem bit set
D/QC-time-services(  364): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  364): Daemon: Base = 2, Value being sent to MODEM = 1124471494716
,E/QC-time-services( 7205): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  364): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  364): Daemon: Time-services: Waiting to acceptconnection
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7186): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7186): [PushClientApplication] Push log off : This is Ship build version
,D/comdaemonstockapp( 3427): [Daemon_Stock]>>> Stockclock_DaemonService.java:63 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 3427): [Daemon_Stock]>>> Stockclock_DaemonService.java:64 [0:0] appServiceStatus: 0
D/comdaemonstockapp( 3427): [Daemon_Stock]>>> Stockclock_DaemonService.java:65 [0:0] [AR]: 0
,D/comdaemonstockapp( 3427): [Daemon_Stock]>>> Stockclock_DaemonService.java:66 [0:0] [AR]: Next time = 0
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/daemonapp( 3427): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 3427): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3427): [MSC_Accu_Daemon]>>> daemonapp [Version : 14123102 ] [ 1 ] 
D/comsamsunglog( 3427): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3427): [MSC_Accu_Daemon]>>> ====================================================================================================================
,D/daemonapp( 3427): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3427): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 3427): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,I/CalendarProvider2( 7171): CalendarProvider2.onCreate() called
,D/daemonapp( 3427): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SPPClientService( 7186): PushLog.txt file is not deleted.
,D/SPPClientService( 7186): PushLog.txt file is not deleted.
D/SPPClientService( 7186): ============PushLog. stop!
,D/daemonapp( 3427): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,I/ActivityManager(  758): Killing 6163:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/daemonapp( 3427): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3427): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,D/daemonapp( 3427): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3427): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 3427): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3427): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,E/SPPClientService( 7186): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/dhcpcd  ( 6819): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 5990): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5990): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 5990): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5990): [SLFUCHKMGR] constructor called
,I/CheckinService( 1754): Checkin interval check for package: unspecified last checkin: 1449576540818 min interval config: 0 actual interval: 255830994
,I/SA      ( 5990): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5990): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 5990): [SCU] == networkStateCheck == true
I/SA      ( 5990): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5990): isChinaCountryCode : false
I/SA      ( 5990): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5990): [OR] == networkStateCheck true ==
,I/SA      ( 5990): [OR] GetMyCountryZoneTask
,I/SA      ( 5990): [OR] onReceive END
,I/SA      ( 5990): [SRS] prepareGetMyCountryZone
,I/SA      ( 5990): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5990): [SSP] query invoked
,I/SA      ( 5990): [TPMU] GetMccFromDB : null
,I/SA      ( 5990): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5990): [TPM] isNoProxy(default) : true
,E/File    ( 5990): fail readDirectory() errno=2
,I/ActivityManager(  758): Killing 6200:com.samsung.android.snote:provider/u0a168 (adj 15): bgCount ##41
D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7231): MountEmulatedStorage()
E/Zygote  ( 7231): v2
I/libpersona( 7231): KNOX_SDCARD checking this for 10074
I/libpersona( 7231): KNOX_SDCARD not a persona
,I/SELinux ( 7231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ActivityManager(  758): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7231 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 7231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7231): TimaSignature is unavailable
,D/ActivityThread( 7231): Added TimaKeyStore provider
,D/ResourcesManager( 7231): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,W/DriveInitializer( 1754): Awaiting to be initialized
,W/DriveInitializer( 1754): Background init thread started
,I/VacuumService( 1480): Vacuum at: now=1449832372005 tag=VacuumService
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1754): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,I/ActivityManager(  758): Killing 6219:com.sec.kidsplat.installer/u0a189 (adj 15): bgCount ##41
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/sCloudBackupApp( 7231): sCloudBackupApp Version Info : 3.13.7.KK_APP
I/SCloudBackupReceiver( 7231): Other Intent
,I/KnoxUsageLogPro( 6379): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 6379): premStatus:2
,I/KnoxUsageLogPro( 6379): isEulaShown : false
I/KnoxUsageLogPro( 6379): KnoxUsageReceiver onReceive : not Processible, just return
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/DriveInitializer( 1754): Background init thread ended
,E/Zygote  ( 7265): MountEmulatedStorage()
E/Zygote  ( 7265): v2
I/libpersona( 7265): KNOX_SDCARD checking this for 10146
I/libpersona( 7265): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7265 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  758): Killing 6244:com.sec.android.app.samsungapps/u0a45 (adj 15): bgCount ##41
,I/SELinux ( 7265): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7265): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7265): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  758): Killing 6308:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7265): TimaSignature is unavailable
,D/ActivityThread( 7265): Added TimaKeyStore provider
,D/ResourcesManager( 7265): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7265): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7265): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7265): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7265): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/WifiStateMachine(  758): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/PhenotypeConfigurator( 1480): Scheduling Phenotype for one-off execution 10513 seconds from now (1449832372343)
,D/GetConfigurationSnapshotOperation( 1480): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1480): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1480): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/btif_config_util( 6648): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/LocationManagerService(  758): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7265): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7265): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7265): Loading: webviewchromium
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/LibraryLoader( 7265): Time to load native libraries: 6 ms (timestamps 9362-9368)
,I/LibraryLoader( 7265): Expected native library version number "",actual native library version number ""
,I/System.out( 1480): (HTTPLog)-Static: isSBSettingEnabled false
,V/WebViewChromiumFactoryProvider( 7265): Binding Chromium to main looper Looper (main, tid 1) {45daefb}
,I/LibraryLoader( 7265): Expected native library version number "",actual native library version number ""
,I/chromium( 7265): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7265): Initializing chromium process, renderers=0
,W/art     ( 7265): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7265): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7265): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7265): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 7265): Requires BLUETOOTH permission
,I/Adreno-EGL( 7265): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7265): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7265): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7265): Local Branch: mybranch5813579
I/Adreno-EGL( 7265): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7265): Local Patches: NONE
I/Adreno-EGL( 7265): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/SA      ( 5990): [RC New] Execute method=[GET] start
,I/SA      ( 5990): [RC New] Security=[true]
,I/System.out( 5990): Thread-970(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5990): Thread-970(ApacheHTTPLog):isShipBuild true
,I/System.out( 5990): Thread-970(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
I/NSApplication( 7265): Starting up...
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1480): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1480): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 1480, getuid(): 10015
,I/SurfaceFlinger(  254): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=14 Removed Uoast (-2/9)
,D/PowerManagerService(  758): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 758) eventTime = 169510
,D/PowerManagerService(  758): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=758 (0x0)
D/PowerManagerService(  758): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=758, ws=WorkSource{10067}) (elapsedTime=3452)
,I/qtaguid ( 1480): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 1480, getuid(): 10015
,D/OpenGLRenderer( 3138): Render dirty regions requested: true
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/Atlas   ( 3138): Validating map...
,E/Zygote  ( 7330): MountEmulatedStorage()
E/Zygote  ( 7330): v2
I/libpersona( 7330): KNOX_SDCARD checking this for 10158
I/libpersona( 7330): KNOX_SDCARD not a persona
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=4, Uoast
,I/ActivityManager(  758): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7330 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  758): Killing 5293:sstream.app/u0a25 (adj 15): bgCount ##41
,I/SELinux ( 7330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7330): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PowerManagerService(  758): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=758
,I/Adreno-EGL( 3138): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 3138): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 3138): Build Date: 11/19/14 Wed
I/Adreno-EGL( 3138): Local Branch: mybranch5813579
I/Adreno-EGL( 3138): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 3138): Local Patches: NONE
I/Adreno-EGL( 3138): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/OpenGLRenderer( 3138): Initialized EGL, version 1.4
,D/TimaKeyStoreProvider( 7330): TimaSignature is unavailable
,D/ActivityThread( 7330): Added TimaKeyStore provider
,I/OpenGLRenderer( 3138): HWUI protection enabled for context ,  &this =0xa1c22088 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 3138): Enabling debug mode 0
,D/ResourcesManager( 7330): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7330): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7330): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7330): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/LocationManagerService(  758): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1480): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1480): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 1480, getuid(): 10015
,D/QuickConnect( 7330): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7330): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7330): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6607): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6607): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6607): StateMachine : Current State = 1
D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6607): StateMachine : Changed Current State = 1
,I/ActivityManager(  758): Killing 5333:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService(  758): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7347): MountEmulatedStorage()
E/Zygote  ( 7347): v2
I/libpersona( 7347): KNOX_SDCARD checking this for 10200
I/libpersona( 7347): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7347 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7347): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7347): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7347): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/System.out( 1480): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1480): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 1480, getuid(): 10015
,D/TimaKeyStoreProvider( 7347): TimaSignature is unavailable
,D/ActivityThread( 7347): Added TimaKeyStore provider
,D/ResourcesManager( 7347): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  758): Killing 6395:com.sec.knox.knoxsetupwizardclient/1000 (adj 13): bgCount ##41
,D/LocationManagerService(  758): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CalendarProvider2( 7171): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.SyncManager( 1754): SYNC; picasa accounts
,I/ActivityManager(  758): Killing 5469:com.android.vending/u0a33 (adj 13): bgCount ##41
,I/System.out( 1480): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1480): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 1480, getuid(): 10015
,D/NetworkLogImpl( 1754): Loaded NetworkSpeedPredictor
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 1754): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.UploadsManager( 1754): num queued entries: 0
,I/iu.UploadsManager( 1754): num updated entries: 0
D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.SyncManager( 1754): NEXT; no task
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7367): MountEmulatedStorage()
D/LocationManagerService(  758): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/Zygote  ( 7367): v2
I/libpersona( 7367): KNOX_SDCARD checking this for 10045
I/libpersona( 7367): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7367 uid=10045 gids={50045, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7367): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7367): TimaSignature is unavailable
,D/ActivityThread( 7367): Added TimaKeyStore provider
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1480): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1480): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 1480, getuid(): 10015
,D/ResourcesManager( 7367): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7367): notifyNetworkActivated
,W/ContextImpl( 7367): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  758): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1480): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GCM     ( 1480): GCM config loaded
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 5990): [RC New] [v2liruge] api execute + 627
,I/SA      ( 5990): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5990): AsyncTask #1 calls detatch()
,I/SA      ( 5990): [TPMU] getNetworkMcc : 
,I/SA      ( 5990): [SCU] saveMccToPreferece Start
,I/SA      ( 5990): [SCU] RegionMCC : 260
I/SA      ( 5990): [SSP] query invoked
,I/SA      ( 5990): [TPMU] GetMccFromDB : null
,I/SA      ( 5990): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5990): [SCU] saveMccToPreferece End
,I/SA      ( 5990): [RC New] executeRequest [v2liruge] end. 674
I/SA      ( 5990): [RC New] Execute end
I/SA      ( 5990): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5990): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7367): AutoUpdateManager:IDLE:execute
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7367): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7367): exit::IDLE
D/InitializeManagerStateMachine( 7367): entry::NETWORK_CHECK
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7367): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7367): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7367): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7367): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7367): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7367): entry::SUCCESS
D/hcjo    ( 7367): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7367): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 7367): RestApi Request Add : 2307
,E/File    ( 7367): fail readDirectory() errno=2
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/SSRM:n  (  758): SIOP:: AP = 370, PST = 324, CUR = 450
,E/Zygote  ( 7389): MountEmulatedStorage()
E/Zygote  ( 7389): v2
I/libpersona( 7389): KNOX_SDCARD checking this for 10171
I/libpersona( 7389): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7389 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,I/SELinux ( 7389): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7389): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7389): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,E/SMD     (  294): DCD ON
,D/TimaKeyStoreProvider( 7389): TimaSignature is unavailable
,D/ActivityThread( 7389): Added TimaKeyStore provider
,D/ResourcesManager( 7389): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7389): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7389): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/ActivityManager(  758): Killing 6263:com.sec.android.widgetapp.digitalclock/u0a109 (adj 13): bgCount ##41
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4296, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): stay LED for fully charged
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/InitializeManagerStateMachine( 7367): exit::SUCCESS
D/InitializeManagerStateMachine( 7367): entry::IDLE
,I/System.out( 7367): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7367): (HTTPLog)-Static: isShipBuild true
I/System.out( 7367): (HTTPLog)-Thread-1195-492714575: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7367): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7367): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 7367): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7367, getuid(): 10045
,I/qtaguid ( 7367): Untagging socket 26
,D/hcjo    ( 7367): AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
,D/hcjo    ( 7367): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
D/hcjo    ( 7367): AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
,D/hcjo    ( 7367): SelfUpdateManager:IDLE:execute
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7367): SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
,I/Volley  ( 7367): RestApi Request Add : 2346
,I/System.out( 7367): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7367): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 7367): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7367, getuid(): 10045
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/qtaguid ( 7367): Untagging socket -1
I/qtaguid ( 7367): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 7367): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 7367): untagSocket(-1) failed with errno -9
,D/hcjo    ( 7367): SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
D/hcjo    ( 7367): AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
D/hcjo    ( 7367): SellerAppAutoUpdate:clearFlag
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SellerAppAutoUpdateManagerStateMachine( 7367): execute::IDLE:EXECUTE
D/SellerAppAutoUpdateManagerStateMachine( 7367): exit::IDLE
D/SellerAppAutoUpdateManagerStateMachine( 7367): entry::TOKENCHECK
,D/SellerAppAutoUpdateManagerStateMachine( 7367): execute::TOKENCHECK:TOKEN_RECEIVED
D/SellerAppAutoUpdateManagerStateMachine( 7367): exit::TOKENCHECK
D/SellerAppAutoUpdateManagerStateMachine( 7367): entry::FAILED
D/hcjo    ( 7367): AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
D/SellerAppAutoUpdateManagerStateMachine( 7367): exit::FAILED
D/SellerAppAutoUpdateManagerStateMachine( 7367): entry::IDLE
,I/ActivityManager(  758): Killing 6278:com.sec.android.widgetapp.dualclockdigital/u0a115 (adj 13): bgCount ##41
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5891): mConnectivityHandler : connected
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 5891): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 5891): ================================================
,I/CSTORAGE( 5891):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 5891): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5891): [GetString-S]
,E/art     ( 5891): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 5891): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5891): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5891): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5891): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5891): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5891): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 6819): wlan0: sending IPv6 Router Solicitation
,I/SurfaceFlinger(  254): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=15 Removed Uoast (-2/9)
,D/PowerManagerService(  758): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 758) eventTime = 173049
,D/PowerManagerService(  758): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=758 (0x0)
D/PowerManagerService(  758): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=758, ws=WorkSource{1000}) (elapsedTime=3449)
,E/SMD     (  294): DCD ON
,I/GAV4    ( 7265): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  294): DCD ON
,I/art     (  758): Explicit concurrent mark sweep GC freed 35543(2MB) AllocSpace objects, 3(48KB) LOS objects, 17% free, 37MB/45MB, paused 1.468ms total 110.158ms
,I/dhcpcd  ( 6819): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6819): wlan0: no IPv6 Routers available
,V/AlarmManager(  758): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,D/PreloadUpdateManagerStateMachine( 7367): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7367): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7367): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7367): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7367): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7367): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7367): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7367): entry::IDLE
,D/SSRM:n  (  758): SIOP:: AP = 320, PST = 321, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryService(  758): stay LED for fully charged
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/PowerManagerService(  758): [PWL] Off : 75s ago
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  758): SIOP:: AP = 310, PST = 320, CUR = 450
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 6
,V/AlarmManager(  758): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 310, PST = 318, CUR = 450
,V/AlarmManager(  758): waitForAlarm result :4
,E/SMD     (  294): DCD ON,
,I/ClearcutLoggerApiImpl( 1480): disconnect managed GoogleApiClient
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 300, PST = 315, CUR = 450
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/Atfwd_Sendcmd(  359): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  359): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  758): [PWL] Off : 105s ago
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 300, PST = 314, CUR = 450
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/Watchdog(  758): !@Sync 7
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,V/AlarmManager(  758): waitForAlarm result :4
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): stay LED for fully charged
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityThread( 1754): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  758): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 199732, reason: UserStart, SyncResult: databaseError: true stats []
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  758): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 292430, reason: UserStart
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  758): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  758): mCursor = null
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 300, PST = 314, CUR = 450
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,V/AlarmManager(  758): waitForAlarm result :8
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryService(  758): stay LED for fully charged
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 300, PST = 314, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/PowerManagerService(  758): [PWL] Off : 140s ago
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 313, CUR = 450
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 8
,E/SMD     (  294): DCD ON
,V/AlarmManager(  758): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 309, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 301, CUR = 450
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 9
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,I/PowerManagerService(  758): [PWL] Off : 180s ago
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 296, CUR = 450
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,V/AlarmManager(  758): waitForAlarm result :8
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 293, CUR = 450
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/TimaService(  758): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  758): TimaServiceHandler.handleMessage what =1
,D/TimaService(  758): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  758): initializing...
,I/TLC_TIMA_PKM_initialize(  758): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  758): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  758): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  758): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  758): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  758): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  758): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  758): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  758): App is not loaded in QSEE
,D/QSEECOMAPI: (  758): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  758): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  758): Trustlet response is completed
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,I/jxcore-log( 6531): Connected to the server!
I/jxcore-log( 6531): 
,I/chromium( 6531): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  294): DCD ON
,I/Atfwd_Sendcmd(  359): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  359): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 291, CUR = 450
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  758): waitForAlarm result :4
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): stay LED for fully charged
,E/Zygote  ( 7509): MountEmulatedStorage()
,E/Zygote  ( 7509): v2
I/libpersona( 7509): KNOX_SDCARD checking this for 10096
I/libpersona( 7509): KNOX_SDCARD not a persona
,I/ActivityManager(  758): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7509 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,I/SELinux ( 7509): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7509): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7509): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7509): TimaSignature is unavailable
,D/ActivityThread( 7509): Added TimaKeyStore provider
,D/ResourcesManager( 7509): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  758): Killing 5645:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 13): bgCount ##41
,E/SMD     (  294): DCD ON
,I/ActivityManager(  758): Killing 6040:com.sec.android.provider.badge/u0a92 (adj 13): bgCount ##41
,I/PowerManagerService(  758): [PWL] Off : 225s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON,
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 11
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 12
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/PowerManagerService(  758): [PWL] Off : 275s ago
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 13
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 14
,E/SMD     (  294): DCD ON
,I/Atfwd_Sendcmd(  359): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  359): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  758): [PWL] Off : 330s ago
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 15
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/bootchecker(  355): bootchecker wake up!!
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 16
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 390s ago
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 289, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 17
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 288, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 286, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 18
,E/SMD     (  294): DCD ON
,I/Atfwd_Sendcmd(  359): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  359): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  758): [PWL] Off : 455s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 283, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Daemon(  359): Stop the daemon....
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 19
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  758): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  758): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  758): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON,
,D/SSRM:n  (  758): SIOP:: AP = 290, PST = 281, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  758): [PWL] Off : 525s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 21
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 22
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 23
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 600s ago
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/Watchdog(  758): !@Sync 24
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/Watchdog(  758): !@Sync 25
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 680s ago
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 26
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,V/AlarmManager(  758): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): stay LED for fully charged
,D/LightsService(  758): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  758): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  758): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  294): DCD ON
,I/MotionRecognitionService(  758): Plugged
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1754): Aggregate from 1449831189033 (log), 1449831189033 (data)
,D/LightsService(  758): [SvcLED]  onSensorChanged::light value = 83
,E/LightSensor(  758): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  758): unregisterListener ::   
,D/LightsService(  758): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 27
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 28
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  758): [PWL] Off : 765s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 29
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/TimaService(  758): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  758): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  758): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,V/AlarmManager(  758): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  758): !@Sync 31
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  758): [PWL] Off : 855s ago
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  758): !@Sync 32
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  758): !@Sync 33
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  758): !@Sync 34
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 950s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  758): !@Sync 35
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  758): !@Sync 36
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  758): !@Sync 37
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  758): !@Sync 38
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 1050s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  758): !@Sync 39
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/TimaService(  758): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  758): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  758): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  758): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  758): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  758): Updating Usage Statistics in DB @ 1449833417134
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
,W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
,W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
,W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
,W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
,W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
,W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
,W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
,W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
,W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  758): ::getAppControlDB: Exception to create DB
W/System.err(  758): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  758): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  758): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  758): Done Updating Usage Statistics in DB @ 1449833417334
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  758): !@Sync 40
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  758): !@Sync 41
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 1155s ago
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  758): !@Sync 42
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  758): !@Sync 43
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  758): !@Sync 44
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 45
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 1265s ago
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 46
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 47
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 48
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 49
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,I/PowerManagerService(  758): [PWL] Off : 1380s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/TimaService(  758): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  758): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  758): TimaServiceHandler.handleMessage what =1
,E/SMD     (  294): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response_id = 3
,E/Watchdog(  758): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,D/LightsService(  758): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,E/LightSensor(  758): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  758): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  294): DCD ON
,D/LightsService(  758): [SvcLED]  onSensorChanged::light value = 55
,E/LightSensor(  758): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  758): unregisterListener ::   
D/LightsService(  758): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): stay LED for fully charged
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 51
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): stay LED for fully charged
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 52
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryService(  758): stay LED for fully charged
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 53
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  758): [PWL] Off : 1500s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 54
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): stay LED for fully charged
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 55
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 56
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 57
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 1625s ago
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  294): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 58
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  758): !@Sync 59
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/NetworkStatsFactory(  758): UpdateStatsForKnox
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD ON
,D/TimaService(  758): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  758): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  758): TimaServiceHandler.handleMessage what =1
,E/SMD     (  294): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  758): !@Sync 60
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/NetworkStats(  758): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  758): UpdateStatsForKnox
,D/ConnectivityService(  758): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,V/NetworkStats(  758): performPollLocked() took 41ms
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,I/ProcessStatsService(  758): Prepared write state in 11ms
,V/AlarmManager(  758): waitForAlarm result :4
,I/ProcessStatsService(  758): Prepared write state in 10ms
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,V/AlarmManager(  758): OOI=Alarm{332b343a type 0 when 1449835838003 com.google.android.gms}
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/ProcessStatsService(  758): Pruning old procstats: /data/system/procstats/state-2015-12-10-14-38-20.bin
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1480): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1480): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  758): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  758):  next == MAX_VALUE
,I/System.out( 1480): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1480): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1480): Tagging socket 63 with tag 1000040100000000{268436481,0} uid 10015, pid: 1480, getuid(): 10015
,I/qtaguid ( 1480): Tagging socket 70 with tag 1000040100000000{268436481,0} uid 10015, pid: 1480, getuid(): 10015
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  758): !@Sync 61
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  758): Plugged
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,E/SMD     (  294): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  758): [PWL] Off : 1755s ago
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  758): !@Sync 62
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/Watchdog(  758): !@Sync 63
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON,
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  758): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  758): !@Sync 64
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  758): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  758): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  758): Plugged
,I/MotionRecognitionService(  758): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,V/HeadsetService( 6648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6648): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  758): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  758): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  758): !@Sync 65
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7708): 
D/AndroidRuntime( 7708): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7708): CheckJNI is OFF
D/AndroidRuntime( 7708): readGMSProperty: start
D/AndroidRuntime( 7708): readGMSProperty: already setted!!
D/AndroidRuntime( 7708): readGMSProperty: end
D/AndroidRuntime( 7708): addProductProperty: start
E/SMD     (  294): DCD ON
E/AffinityControl( 7708): AffinityControl: registerfunction enter
D/AndroidRuntime( 7708): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService(  758): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  758): START PACKAGE DELETE: observer{606606043}
D/PackageManager(  758): pkg{<packageName>}
D/PackageManager(  758): user{0}
D/PackageManager(  758): caller{2000}
D/PackageManager(  758): flags{3}
D/PersonaManagerService(  758): isFromApprovedUnInstaller: isApproved : true
D/PackageManager(  758): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService(  758): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  758): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  758): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  758): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  758): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  758): getApplicationUninstallationEnabled
D/ApplicationPolicy(  758): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  758): !@killApplicatoin: 10283, uninstall pkg
I/ActivityManager(  758): Force stopping com.test.thalitest appid=10283 user=-1: uninstall pkg
I/ActivityManager(  758): Killing 6531:com.test.thalitest/u0a283 (adj 0): stop com.test.thalitest
W/PackageSettings(  758): Skipping PackageSetting{12d70ef0 com.example.hello/10268} due to missing metadata
I/WindowState(  758): WIN DEATH: Window{1f0b4986 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  254): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  758): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  758): setMouseCustomIcon IconType is same.101
D/PointerIcon(  758): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  758): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  758): Killing 7127:com.policydm/1000 (adj 11): empty for 1800s
I/ActivityManager(  758): Killing 5419:com.sec.android.app.controlpanel/u0a134 (adj 11): empty for 1800s
I/ActivityManager(  758): Killing 7105:com.sec.esdk.elm/u0a116 (adj 13): empty for 1800s
I/ActivityManager(  758): Killing 7029:com.sec.android.soagent/u0a42 (adj 13): empty for 1800s
I/ActivityManager(  758): Killing 6799:com.vlingo.midas/u0a38 (adj 13): empty for 1800s
I/ActivityManager(  758): Killing 7090:com.samsung.android.app.pinboard:tagService/u0a36 (adj 13): empty for 1800s
I/ActivityManager(  758): Killing 6997:com.samsung.klmsagent/u0a23 (adj 13): empty for 1800s
I/ActivityManager(  758): Killing 6924:com.sec.android.fotaclient/u0a14 (adj 13): empty for 1800s
I/ActivityManager(  758): Killing 7070:com.sec.android.app.clockpackage/u0a106 (adj 13): empty for 1800s
I/ActivityManager(  758): Killing 7050:com.samsung.android.scloud.sync/u0a76 (adj 13): empty for 1800s
I/ActivityManager(  758): Killing 6012:com.android.mms/u0a55 (adj 13): empty for 1800s
D/CountryDetector(  758): No listener is left
I/ActivityManager(  758): Killing 7013:com.sec.android.diagmonagent/1000 (adj 13): empty for 1800s
I/ActivityManager(  758): Killing 4090:com.sec.android.app.shealth/u0a40 (adj 13): empty for 1800s
I/ActivityManager(  758): Killing 6952:com.sec.android.cloudagent/u0a4 (adj 15): empty for 1801s
I/ActivityManager(  758): Killing 5891:com.sec.pcw.device/1000 (adj 15): empty for 1801s
I/ActivityManager(  758): Killing 6183:com.samsung.android.snote/u0a168 (adj 15): empty for 1802s
D/SSRM:n  (  758): SIOP:: AP = 280, PST = 280, CUR = 450
I/ActivityManager(  758): Killing 6767:com.samsung.shareshot/u0a192 (adj 15): empty for 1805s
I/ActivityManager(  758): Killing 6364:com.samsung.android.app.FileShareServer/u0a88 (adj 15): empty for 1805s
I/ActivityManager(  758):   Force finishing activity ActivityRecord{1036eb80 u0 com.test.thalitest/.MainActivity t3}
D/FocusedStackFrame(  758): Set to : 0
I/ActivityManager(  758): Killing 7265:com.google.android.apps.magazines/u0a146 (adj 9): empty for 1800s
I/ActivityManager(  758): Killing 6977:com.android.chrome/u0a104 (adj 11): empty for 1800s
I/ActivityManager(  758): Killing 5400:com.sec.chaton/u0a102 (adj 11): empty for 1800s
I/ActivityManager(  758): Killing 6379:com.sec.knox.bridge/1000 (adj 11): empty for 1800s
I/ActivityManager(  758): Killing 7171:com.android.providers.calendar/u0a51 (adj 11): empty for 1800s
I/ActivityManager(  758): Killing 7231:com.samsung.android.scloud.backup/u0a74 (adj 11): empty for 1800s
I/ActivityManager(  758): Killing 5990:com.osp.app.signin/u0a50 (adj 11): empty for 1800s
I/ActivityManager(  758): Killing 7205:com.qualcomm.timeservice/1000 (adj 11): empty for 1800s
I/ActivityManager(  758): Killing 5173:com.sec.android.gallery3d/u0a53 (adj 11): empty for 1801s
W/ActivityManager(  758): Spurious death for ProcessRecord{b30f178 6531:com.test.thalitest/u0a283}, curProc for 6531: null
W/libprocessgroup(  758): failed to open /acct/uid_10168/pid_6183/cgroup.procs: No such file or directory
I/ActivityManager(  758): Killing 5449:com.google.android.apps.plus/u0a155 (adj 9): empty for 1800s
I/ActivityManager(  758): Killing 6654:tv.peel.samsung.app/u0a152 (adj 11): empty for 1800s
W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_7127/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10134/pid_5419/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10116/pid_7105/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10042/pid_7029/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10038/pid_6799/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10036/pid_7090/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10023/pid_6997/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10014/pid_6924/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10106/pid_7070/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10076/pid_7050/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10055/pid_6012/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_7013/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10040/pid_4090/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10004/pid_6952/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_5891/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10050/pid_5990/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10152/pid_6654/cgroup.procs: No such file or directory
D/ConnectivityService(  758): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/libprocessgroup(  758): failed to open /acct/uid_10192/pid_6767/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10104/pid_6977/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10102/pid_5400/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_6379/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10051/pid_7171/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10074/pid_7231/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_7205/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10053/pid_5173/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10155/pid_5449/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10088/pid_6364/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10146/pid_7265/cgroup.procs: No such file or directory
I/ActivityManager(  758): Force stopping com.test.thalitest appid=10283 user=0: pkg removed
I/art     ( 1502): Explicit concurrent mark sweep GC freed 681(43KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 18MB/31MB, paused 584us total 32.223ms
I/art     ( 5135): Explicit concurrent mark sweep GC freed 40590(2MB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 15MB/26MB, paused 599us total 39.832ms
D/ResourcesManager(  758): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 1480): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/SamsungIME( 1726): mOCRHelper is null
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
E/Zygote  ( 7753): MountEmulatedStorage()
E/Zygote  ( 7753): v2
I/libpersona( 7753): KNOX_SDCARD checking this for 10023
I/libpersona( 7753): KNOX_SDCARD not a persona
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/art     ( 1754): Explicit concurrent mark sweep GC freed 6788(391KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 22MB/30MB, paused 2.565ms total 118.951ms
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/ActivityManager(  758): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7753 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
W/SQLiteConnectionPool( 1754): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/SELinux ( 7753): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7753): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7753): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/TimaKeyStoreProvider( 7753): TimaSignature is unavailable
D/ActivityThread( 7753): Added TimaKeyStore provider
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/SurfaceWidgetView( 1444): destroyHardwareResources():705418629
V/WindowOrientationListener(  758): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  758): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  758): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  758): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  758): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/Launcher( 1444): onRestart, Launcher: 1064836816
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Books/Books.apk
D/Launcher( 1444): onStart, Launcher: 1064836816
D/Launcher.HomeView( 1444): onStart
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1771): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1771): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1771): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
V/ActivityThread( 1444): updateVisibility : ActivityRecord{2e3e0002 token=android.os.BinderProxy@2c670c2f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 7753): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/SurfaceFlinger(  254): id=16 createSurf (1080x1920),1 flag=4, Mauncher
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/StatusBarManagerService(  758): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  758): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/PointerIcon(  758): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  758): setMouseCustomIcon IconType is same.101
D/PointerIcon(  758): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  758): setHoveringSpenCustomIcon IconType is same.1
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/InputMethodManagerService(  758): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  758): Got RemoteException sending setActive(false) notification to pid 6531 uid 10283
D/SecContentProvider2(  758): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  758): mCursor = null
D/RegisteredServicesCache( 1415): empty dynamic service
W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/KLMS-2.4.511: ( 7753): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 7753): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449834173569
I/KLMS-2.4.511: ( 7753): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 7753): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
I/Timeline(  758): Timeline: Activity_windows_visible id: ActivityRecord{2d8126e7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1970426
D/RCPManagerService(  758): PackageReceiver onReceive()
I/HarmonyEASService(  758): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  758): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  758): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  758): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  758): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  758): uID is 10283
V/EnterpriseBillingPolicy(  758): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  758): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  758): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  758): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  758): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  758): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  758): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  758): removeObsoleteFile: deleting file=3_task.xml
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/talkback/talkback.apk
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
I/art     (  758): Explicit concurrent mark sweep GC freed 22914(1596KB) AllocSpace objects, 12(192KB) LOS objects, 17% free, 37MB/45MB, paused 2.306ms total 281.731ms
D/PackageManager(  758): delete codoeFile: 
D/EnterpriseDeviceManagerService(  758): Package has changed for user 0
D/EnterpriseDeviceManagerService(  758): Admin package name: com.google.android.gms
I/AASAUninstall(  758):  com.test.thalitest not target!
E/Zygote  ( 7776): MountEmulatedStorage()
E/Zygote  ( 7776): v2
I/libpersona( 7776): KNOX_SDCARD checking this for 10116
I/libpersona( 7776): KNOX_SDCARD not a persona
D/PackageManager(  758): result of delete: 1{606606043}
I/ActivityManager(  758): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7776 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 7776): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/AndroidRuntime( 7708): Shutting down VM
I/SELinux ( 7776): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7776): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  758): Killing 7330:com.samsung.android.sconnect/u0a158 (adj 15): empty for 1800s
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
D/TimaKeyStoreProvider( 7776): TimaSignature is unavailable
D/ActivityThread( 7776): Added TimaKeyStore provider
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
W/libprocessgroup(  758): failed to open /acct/uid_10158/pid_7330/cgroup.procs: No such file or directory
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 7776): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/elm:14491( 7776): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 7776): ELMEngine.ELMEngine( context ).
D/elm:14491( 7776): MDMBridge.setEnterpriseBridge()
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/elm:14491( 7776): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  758): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/elm:14491( 7776): ElmAgentService : onCreate()
D/elm:14491( 7776): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 7776): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7776): MDMBridge.getInstance()
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/elm:14491( 7776): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 7776): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/ResourcesManager(  758): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  758): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  758): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
E/Zygote  ( 7794): MountEmulatedStorage()
E/Zygote  ( 7794): v2
I/libpersona( 7794): KNOX_SDCARD checking this for 10021
I/libpersona( 7794): KNOX_SDCARD not a persona
I/ActivityManager(  758): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7794 uid=10021 gids={50021, 9997} abi=armeabi-v7a
D/ResourcesManager(  758): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/elm:14491( 7776): ElmAgentService : onDestroy().
I/SELinux ( 7794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  758): Killing 6720:com.android.email/u0a186 (adj 15): empty for 1801s
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/SELinux ( 7794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7794): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  325): Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 21.415ms total 34.821ms
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  758): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 340us total 21.487ms

```
