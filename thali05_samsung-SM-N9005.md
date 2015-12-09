#### Test 506502789252e15_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
D/AndroidRuntime( 6542): 
D/AndroidRuntime( 6542): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6542): CheckJNI is OFF
D/AndroidRuntime( 6542): readGMSProperty: start
D/AndroidRuntime( 6542): readGMSProperty: already setted!!
D/AndroidRuntime( 6542): readGMSProperty: end
D/AndroidRuntime( 6542): addProductProperty: start
E/AffinityControl( 6542): AffinityControl: registerfunction enter
D/AndroidRuntime( 6542): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  908): inState():  stateMachine is null !!
I/PersonaManagerService(  908): PersonaId don't exist
I/ActivityManager(  908): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  908): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  908): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  908): mDVFSHelper.acquire()
D/FocusedStackFrame(  908): Set to : 0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6557 uid=10276 gids={50276, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PointerIcon(  908): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  908): setMouseCustomIcon IconType is same.101
D/PointerIcon(  908): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  908): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6542): Shutting down VM
E/Zygote  ( 6557): MountEmulatedStorage()
E/Zygote  ( 6557): v2
I/libpersona( 6557): KNOX_SDCARD checking this for 10276
I/libpersona( 6557): KNOX_SDCARD not a persona
I/SELinux ( 6557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6557): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6557): TimaSignature is unavailable
D/ActivityThread( 6557): Added TimaKeyStore provider
V/WindowOrientationListener(  908): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  908): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  908): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  908): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  908): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  908): Display changed displayId=0
D/SurfaceWidgetView( 1448): destroyHardwareResources():467340676
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6557): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
,I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1765): [237392/8] Surface widget visibility changed visibility = false on instance = 1
,V/ActivityThread( 1448): updateVisibility : ActivityRecord{30332c35 token=android.os.BinderProxy@170def56 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1448): onTrimMemory. Level: 20
,I/WebViewFactory( 6557): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6557): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6557): Loading: webviewchromium
,I/LibraryLoader( 6557): Time to load native libraries: 6 ms (timestamps 9340-9346)
I/LibraryLoader( 6557): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6557): Binding Chromium to main looper Looper (main, tid 1) {18d6fe3e}
,I/LibraryLoader( 6557): Expected native library version number "",actual native library version number ""
,I/chromium( 6557): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6557): Initializing chromium process, renderers=0
,W/art     ( 6557): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6557): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6557): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6557): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
,I/chromium( 6557): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,I/Adreno-EGL( 6557): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6557): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6557): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6557): Local Branch: mybranch5813579
I/Adreno-EGL( 6557): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6557): Local Patches: NONE
I/Adreno-EGL( 6557): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,D/BluetoothAdapter( 6557): 922047647: getState() :  mService = null. Returning STATE_OFF
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/chromium( 6557): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6557): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/ActivityManager(  908): Activity pause timeout for ActivityRecord{15c43410 u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6557): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6557): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6557): CordovaWebView is running on device made by: samsung
,W/art     ( 6557): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6557): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 6557): performCreate Call secproduct feature valuefalse
D/Activity( 6557): performCreate Call debug elastic valuetrue
,I/PowerManagerService(  908): [PWL] Off : 50s ago
,D/OpenGLRenderer( 6557): Render dirty regions requested: true
,D/Atlas   ( 6557): Validating map...
,D/ActivityManager(  908): post active user change for 0
D/KnoxTimeoutHandler(  908): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  908): handleActiveUserChange for user 0
,V/ActivityThread( 6557): updateVisibility : ActivityRecord{26f661c token=android.os.BinderProxy@16dd72ee {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  908): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  908): setMouseCustomIcon IconType is same.101
D/PointerIcon(  908): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  908): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6557): Initialized EGL, version 1.4
,I/OpenGLRenderer( 6557): HWUI protection enabled for context ,  &this =0xb3b5eb28 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6557): Enabling debug mode 0
,D/InputMethodManagerService(  908): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  908): mDVFSHelper.release()
,I/Timeline(  908): Timeline: Activity_windows_visible id: ActivityRecord{15c43410 u0 com.test.thalitest/.MainActivity t3} time:159915
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6557): showStatusIcon on inactive InputConnection
,I/Timeline( 6557): Timeline: Activity_idle id: android.os.BinderProxy@16dd72ee time:159924
,I/SamsungIME( 1718): getCurrentCandidateView
,D/SSRM:n  (  908): SIOP:: AP = 310, PST = 336, CUR = 450
,D/SamsungIME( 1718): Dismiss ExpandCandiate
,I/chromium( 6557): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6557): 
,D/JsMessageQueue( 6557): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1718): getDebugLevel  : 0x4f4c
,D/jxcore_app_log( 6557): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357260032
D/JX-Cordova( 6557): jxcore cordova android initializing
,I/SamsungIME( 1718): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1718): KeybaordView init() : load resources
,I/SamsungIME( 1718): getCurrentKeyboard
,I/SamsungIME( 1718): getTextKeyboard
,D/SamsungIME( 1718): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/NtpTrustedTime(  908): forceRefresh() from cache miss
V/AlarmManager(  908): waitForAlarm result :4
D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
V/AlarmManager(  908): ___SyncScheduler (v3) ACTIVATED___
D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
V/AlarmManager(  908): <AppSync3 Whitelist>
D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
V/AlarmManager(  908): (AppSync) ### 0 added ###
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/NtpTrustedTime(  908): forceRefresh Fail.
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/SamsungIME( 1718): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/jxcore-log( 6557): Initializing JXcore engine
,W/jxcore-log( 6557): JXcore engine is ready
,W/jxcore-log( 6557): Starting JXcore engine
,E/auditd  ( 1785): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  908): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  908): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/Zygote  ( 6633): MountEmulatedStorage()
I/ActivityManager(  908): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6633 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6633): v2
I/libpersona( 6633): KNOX_SDCARD checking this for 1000
I/libpersona( 6633): KNOX_SDCARD not a persona
,I/SELinux ( 6633): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6633): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6633): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6633): TimaSignature is unavailable
,D/ActivityThread( 6633): Added TimaKeyStore provider
,D/ResourcesManager( 6633): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 6557): Platform android
W/jxcore-log( 6557): 
,W/jxcore-log( 6557): Process ARCH arm
W/jxcore-log( 6557): 
,D/SecurityLogAgent( 6633):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6633):  SeDenialReceiver : File path = null
,I/ActivityManager(  908): Killing 4918:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/jxcore-log( 6557): JXcore Cordova bridge is ready!
I/jxcore-log( 6557): 
,W/jxcore-log( 6557): JXcore engine is started
,I/jxcore-log( 6557): Toggling radios to true
I/jxcore-log( 6557): 
,D/BluetoothAdapter( 6557): enable()
,W/ActivityManager(  908): Permission Denial: getCurrentUser() from pid=6557, uid=10276 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  908): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  908): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6557, uid=10276 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  908): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/BluetoothManagerService(  908): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2141)
W/BluetoothManagerService(  908): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  908): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService(  908): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  908): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider(  908): name = bluetooth_on
,E/DevicePolicyManagerService(  908): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService(  908): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,I/WifiManager( 6557): packageName : com.test.thalitest
,D/SecContentProvider(  908): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  908): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  908): mCursor = null
,D/WifiService(  908): setWifiEnabled: true pid=6557, uid=10276
,W/ActivityManager(  908): Permission Denial: getCurrentUser() from pid=6557, uid=10276 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  908): Failed getting userId using ActivityManagerNative
W/WifiService(  908): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6557, uid=10276 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  908): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  908): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  908): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  908): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  908): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  908): name = wifi_on
,I/WifiService(  908): disconnect: pid=6557, uid=10276
,E/WifiHW  (  908): ##################### set firmware type 0 #####################
I/WifiHW  (  282): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
I/jxcore-log( 6557): Radios toggled
I/jxcore-log( 6557): 
I/WifiHW  (  282): module is semco
E/WifiHW  (  282): ==========[WIFI] SEMCO MODULE ===========
I/WifiHW  (  282): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  (  282): TEMP_FAILURE_RETRY complete
D/SoftapController(  282): Softap fwReload - Ok
,D/CommandListener(  282): Setting iface cfg
D/CommandListener(  282): Trying to bring down wlan0
,D/CommandListener(  282): Clearing all IP addresses on wlan0
I/libpersona( 6659): KNOX_SDCARD checking this for 1002
E/Zygote  ( 6659): MountEmulatedStorage()
I/libpersona( 6659): KNOX_SDCARD not a persona
E/Zygote  ( 6659): v2
,I/ActivityManager(  908): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6659 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,E/WifiHW  (  908): supplicant_name : p2p_supplicant
,D/WifiMonitor(  908): startMonitoring(wlan0) with mConnected = false
,D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,E/WifiHW  (  908): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 6659): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/libpersona( 6666): KNOX_SDCARD checking this for 10152
E/Zygote  ( 6666): MountEmulatedStorage()
I/libpersona( 6666): KNOX_SDCARD not a persona
E/Zygote  ( 6666): v2
I/SELinux ( 6659): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  908): Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6666 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 6666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6666): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/SELinux ( 6659): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiCredService( 1311): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/SmartBondingService(  908): getNetworkEnabled : wifi : false mobile : true
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=false enabledDesc:null
I/wpa_supplicant( 6665): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6665): Successfully initialized wpa_supplicant
D/STATUSBAR-WifiQuickSettingButton( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1185): Wifi onReceive(2)
D/HotspotTile( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1185): onStateChanged: Wi-Fi
,D/HotspotTile( 1185): onReceive : 2, 0
,I/SecureStorage( 6665): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6665): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  397): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6665
I/SecureStorage(  397): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 6665): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6665): ssSupport state is = 1
,I/wpa_supplicant( 6665): >>>>> GET KEY, IV <<<<<
,I/SecureStorage( 6665): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  397): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6665
I/SecureStorage(  397): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,D/TimaKeyStoreProvider( 6659): TimaSignature is unavailable
,D/ActivityThread( 6659): Added TimaKeyStore provider
,D/ResourcesManager( 6659): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
W/ResourcesManager( 6659): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6659): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 6666): TimaSignature is unavailable
D/ActivityThread( 6666): Added TimaKeyStore provider
D/ResourcesManager( 6666): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,I/BluetoothA2dpSinkServiceJni( 6659): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 6659): Adding GattService
,D/BtSettings.ProfileConfig( 6659): Adding HeadsetService
D/BtSettings.ProfileConfig( 6659): Adding A2dpService
D/BtSettings.ProfileConfig( 6659): Adding HidService
,D/BtSettings.ProfileConfig( 6659): Adding HealthService
D/BtSettings.ProfileConfig( 6659): Adding PanService
D/BtSettings.ProfileConfig( 6659): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 6659): Adding SapService
,D/BtSettings.ProfileConfig( 6659): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 6659): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 6659): Adding SapClientService
D/BtSettings.ProfileConfig( 6659): Adding HidDevService
I/BtSettings.ProfileConfig( 6659): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider(  908): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
,D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  908): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider(  908): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  908): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  908): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  908): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  908): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  908): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  908): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  908): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  908): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  908): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterState( 6659): make
,I/bluedroid( 6659): init
,I/BluetoothAdapterState( 6659): Entering OffState
,I/bte_conf( 6659): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/WebViewFactory( 6666): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/bte_conf( 6659): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6659): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6659): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,D/ResourcesManager( 6666): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,E/bt-btif ( 6659): btif_fetch_local_ble_random_bdaddr
I/bluedroid( 6659): get_profile_interface socket
I/bluedroid( 6659): get_profile_interface map_client
,D/BluetoothAdapterService( 6659): checkAddrForIOP: Loading from conf
,I/GKI_LINUX( 6659): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 6659): Address is:E0:DB:10:1F:C9:5E
,E/BluetoothServiceJni( 6659): populateRssiValuesNative
I/bluedroid( 6659): getModelRssiValues
E/BluetoothServiceJni( 6659): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/BluetoothAdapterProperties( 6659): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6659): Name is: Note3-1
D/SettingsProvider(  908): name = bluetooth_name
,I/bluedroid( 6659): config_hci_snoop_log
,D/BluetoothManagerService(  908): Broadcasting onBluetoothServiceUp() to 10 receivers.
,E/DevicePolicyManagerService(  908): getAllowBluetoothMode - value retunrs : 2
I/LibraryLoader( 6666): Loading: webviewchromium
,E/DevicePolicyManagerService(  908): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider(  908): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState( 6659): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties( 6659): Setting state to 11
,I/BluetoothAdapterState( 6659): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 6659): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6659): updateAdapterState state is 11
I/LibraryLoader( 6666): Time to load native libraries: 12 ms (timestamps 2965-2977)
,D/BluetoothAdapterService( 6659): Autoconnection is available 
D/BluetoothAdapterService( 6659): updateAdapterState prevState = 10newState = 11
I/LibraryLoader( 6666): Expected native library version number "",actual native library version number ""
,D/BluetoothSecureManager( 6659): getInstant: null
,D/BluetoothSecureManager( 6659): calling getMethod for getService
D/BluetoothSecureManager( 6659): calling getService
D/BluetoothSecureManager( 6659): getService return binder: android.os.BinderProxy@35b73897
,D/BluetoothSecureManagerService(  908): isSecureModeEnabled
D/BluetoothSecureManagerService(  908): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 6659): isSecureModeOn:false
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6659): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6659): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 6659): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6659): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 6659): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6659): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6659): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 6659): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6659): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 6659): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 6659): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 6659): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,W/InputMethodManagerService(  908): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  908): [BT Setting State] State =11
,D/BluetoothBondStateMachine( 6659): make
,D/BluetoothTile( 1185):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1185): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/StatusBarManagerService(  908): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/StatusBarManagerService(  908): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 1185): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/STATUSBAR-QSTileView( 1185): onStateChanged: Bluetooth
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.gatt.GattService
I/SamsungIME( 1718): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
D/PhoneStatusBar( 1185): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.hfp.HeadsetService
,I/BtGatt.JNI( 6659): classInitNative(L890): classInitNative: Success!
,I/BluetoothBondStateMachine( 6659): StableState(): Entering Off State
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BtGatt.DebugUtils( 6659): handleDebugAction() action=null
,D/BtGatt.GattService( 6659): Received start request. Starting profile...
D/BtGatt.GattService( 6659): start()
,I/bluedroid( 6659): get_profile_interface gatt
D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,D/BtGatt.AdvertiseManager( 6659): advertise manager created
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6659): Not skipping com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6659): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6659): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6659): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6659): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6659): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6659): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6659): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 6659): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetService( 6659): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 6659): classInitNative: succeeds
,D/HeadsetStateMachine( 6659): make
,V/WebViewChromiumFactoryProvider( 6666): Binding Chromium to main looper Looper (main, tid 1) {3837a9ec}
,I/LibraryLoader( 6666): Expected native library version number "",actual native library version number ""
,I/chromium( 6666): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,E/HeadsetStateMachine( 6659): # of Max HF connection is 2
,I/SecureStorage(  397): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,I/bluedroid( 6659): get_profile_interface handsfree
,I/DualScoManager( 6659): Instantiating Dual Sco Manager
,I/DualScoManager( 6659): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 6659): createCMTIContentObservers
,D/SettingsProvider(  908): name = bluetooth_hfp_allowed_bvra
,D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 6659): Enter Disconnected: -2
,D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,E/HeadsetStateMachine( 6659): set to mRemoteBrsf = 0
,I/BrowserStartupController( 6666): Initializing chromium process, renderers=0
,D/BluetoothA2dp(  908): Proxy object connected
,D/A2dpService( 6659): Received start request. Starting profile...
D/BluetoothA2dp( 2955): Proxy object connected
,W/art     ( 6666): Attempt to remove local handle scope entry from IRT, ignoring
,I/BluetoothAvrcpServiceJni( 6659): classInitNative: succeeds
V/Avrcp   ( 6659): make
V/Avrcp   ( 6659): Avrcp
I/bluedroid( 6659): get_profile_interface avrcp
,V/Avrcp   ( 6659): start
,D/HeadsetStateMachine( 6659): map size, before remove : 0
,D/HeadsetStateMachine( 6659): map size, after remove: 0
D/HeadsetStateMachine( 6659): mNextConnectingDevice : null
,E/RemoteController( 6659): Cannot set synchronization mode on an unregistered RemoteController
,W/chromium( 6666): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/Avrcp   ( 6659): ++registerMediaPlayers++
,I/Avrcp   ( 6659): No of Audio players :: 2
I/Avrcp   ( 6659): App Package name is com.google.android.music
,D/ResourcesManager( 6659): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/chromium( 6666): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6666): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46780 len=2953
I/Avrcp   ( 6659): App pkg name is Google Play Music
,I/chromium( 6666): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229536 len:643667
I/Avrcp   ( 6659): Name::Google Play Music
,V/Avrcp   ( 6659): MediaPlayerInfo: mPlayerId=1
I/Avrcp   ( 6659): App Package name is com.sec.android.app.music
,D/ResourcesManager( 6659): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   ( 6659): App pkg name is Music
,I/Avrcp   ( 6659): Name::Music
V/Avrcp   ( 6659): MediaPlayerInfo: mPlayerId=2
I/Avrcp   ( 6659):  set player publishabilty with player id::2 toBePublished ::true
,I/Avrcp   ( 6659): No of Video players :: 1
I/Avrcp   ( 6659): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager( 6659): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   ( 6659): Video App pkg name is Video Player
I/Avrcp   ( 6659): Name::Video Player
V/Avrcp   ( 6659): MediaPlayerInfo: mPlayerId=3
I/Avrcp   ( 6659): Add tempPlayer
V/Avrcp   ( 6659): MediaPlayerInfo: mPlayerId=4
I/Avrcp   ( 6659): Total no of players: 4
V/Avrcp   ( 6659): swapping the samsung player with 1st player
I/Avrcp   ( 6659):  Updating now playing list upon AVRCP Start
V/Avrcp   ( 6659): handleMessage, msg=207
,D/BluetoothMediaBrowser( 6659):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 6659): classInitNative: succeeds
D/A2dpStateMachine( 6659): make
,I/bluedroid( 6659): get_profile_interface a2dp
,I/GKI_LINUX( 6659): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 6659): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
D/A2dpStateMachine( 6659): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 6659): classInitNative: succeeds
,D/HidService( 6659): Received start request. Starting profile...
I/bluedroid( 6659): get_profile_interface hidhost
D/HidService( 6659): setHidService(): set to: null
D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,I/BluetoothHealthServiceJni( 6659): classInitNative: succeeds
,D/HealthService( 6659): Received start request. Starting profile...
,D/BluetoothMediaBrowser( 6659): no now playing list
,D/BluetoothMediaBrowser( 6659):  getNowPlayingId now playing id : -1
D/Avrcp   ( 6659):  checkNowPlayingList start
,I/bluedroid( 6659): get_profile_interface health
D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,I/BluetoothPanServiceJni( 6659): classInitNative(L105): succeeds
,D/BluetoothPan(  908): BluetoothPAN Proxy object connected
,D/PanService( 6659): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6659): initializeNative(L110): pan
I/bluedroid( 6659): get_profile_interface pan
,D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,D/BluetoothMapService( 6659): Received start request. Starting profile...
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,I/Adreno-EGL( 6666): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6666): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6666): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6666): Local Branch: mybranch5813579
I/Adreno-EGL( 6666): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6666): Local Patches: NONE
I/Adreno-EGL( 6666): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,E/Zygote  ( 6729): MountEmulatedStorage()
,E/Zygote  ( 6729): v2
I/libpersona( 6729): KNOX_SDCARD checking this for 10186
I/libpersona( 6729): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6729 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6729): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6729): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6729): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6729): TimaSignature is unavailable
,D/ActivityThread( 6729): Added TimaKeyStore provider
,D/ResourcesManager( 6729): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 6729): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6729): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6729): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6729): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6729): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/chromium( 6666): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6666): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6666): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6666): onDetachedFromWindow called when already detached. Ignoring
,I/SecureStorage( 6665): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 6665): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6665): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  397): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6665
I/SecureStorage(  397): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6665): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6665): ssSupport state is = 1
,I/wpa_supplicant( 6665): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6665): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6665): SIM READ ERROR
I/wpa_supplicant( 6665): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6665): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6665): SIM READ ERROR
I/wpa_supplicant( 6665): Blacklist: Clear (all) 
I/wpa_supplicant( 6665): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6665): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 6665): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6665): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 6665): rfkill: Cannot open RFKILL control device
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/BadgeProvider( 6083): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/BluetoothSAPServiceJni( 6659): classInitNative(L204): succeeds
,D/SapService( 6659): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 6659): initializeNative(L209): sap
I/bluedroid( 6659): get_profile_interface sap
D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,D/HeadsetStateMachine( 6659): Try to query the phonestate on bind
,I/Telecom ( 1395): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1395): BluetoothPhoneService: updateHeadsetWithCallState
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,I/Telecom ( 1395): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1395): Proxy not attached to service
,D/BadgeProvider( 6083): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/HeadsetStateMachine( 6659): Proxy object connected
D/BadgeProvider( 6083): sendNotify, [notify] : null
D/HeadsetPhoneState( 6659): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/BadgeProvider( 6083): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6083): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6083): update, [UpdateCount] : 1
D/HeadsetPhoneState( 6659): sendDeviceDataStateChanged
D/HeadsetPhoneState( 6659): Signal level : previous=0 curr=0
E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 6659): Proxy object connected
D/BluetoothAdapterService( 6659): Bluetooth A2dp source service connected
E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/HeadsetStateMachine( 6659): Disconnected process message: 11
D/Launcher.Model( 1448): reloadBadges entered.
D/HeadsetStateMachine( 6659): Disconnected process message: 18
,D/HeadsetStateMachine( 6659): Disconnected process message: 10
,E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,D/HeadsetPhoneState( 6659): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6659): Disconnected process message: 11
,I/ActivityManager(  908): Killing 5792:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/BluetoothAdapterState( 6659): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 6659): enable
,I/GKI_LINUX( 6659): gki_task_entry task_id=0 [BTU] starting
,I/bt_hci_bdroid( 6659): init
,I/bt_vendor( 6659): init
I/bt_vnd_conf( 6659): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6659): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6659): userial_init
D/bt_vendor( 6659): op for 5
,D/bt_vendor( 6659): op for 0
,D/bt_upio ( 6659): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6659): is_emulator_context : 0
D/bt_upio ( 6659): is_rfkill_disabled ? [0]
D/bt_upio ( 6659): is_rfkill_disabled ? [0]
,D/bt_vendor( 6659): op for 0
D/bt_upio ( 6659): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6659): is_emulator_context : 0
D/bt_upio ( 6659): is_rfkill_disabled ? [0]
,D/bt_vendor( 6659): op for 3
I/bt_userial_vendor( 6659): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 6659): userial_vendor_open():UART is setup
I/bt_userial_vendor( 6659): device fd = 65 open
D/bt_vendor( 6659): op for 1
D/bt_userial( 6659): Entering userial_read_thread()
E/bt_hwcfg( 6659): Start CFG HW, HCI reset
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,E/bt_hwcfg( 6659): Read Local Name after HCI reset
,E/SignOutReceiver( 6207): WIFI_STATE_CHANGED_ACTION
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/bt_hwcfg( 6659): Chipset BCM4335C0
D/bt_hwcfg( 6659): Target name = [BCM4335C0]
,I/bt_hwcfg( 6659): module_type[semco].
I/bt_hwcfg( 6659): not ZERO...
I/bt_hwcfg( 6659): module_type[semco] is invalid.
E/bt_hwcfg( 6659): patchram path ORG . BCM4335C0
E/bt_hwcfg( 6659): patchram path ORG .. BCM4335C0
E/bt_hwcfg( 6659): patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
E/bt_hwcfg( 6659): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6659): patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
E/bt_hwcfg( 6659): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6659): patchram path ORG bcm4335_V0093.0399.hcd BCM4335C0
E/bt_hwcfg( 6659): patchram path ORG bcm4335_V0093.0399_wisol.hcd BCM4335C0
E/bt_hwcfg( 6659): fw ver (org)0.0
E/bt_hwcfg( 6659): vendor lib preload failed to locate firmware patch file
E/bt_hwcfg( 6659): Remove module rev, try again BCM4335
D/bt_hwcfg( 6659): Target name = [BCM4335]
I/bt_hwcfg( 6659): module_type[semco].
I/bt_hwcfg( 6659): not ZERO...
I/bt_hwcfg( 6659): module_type[semco] is invalid.
E/bt_hwcfg( 6659): patchram path ORG . BCM4335
E/bt_hwcfg( 6659): patchram path ORG .. BCM4335
E/bt_hwcfg( 6659): patchram path ORG bcm2079xB4_firmware.ncd BCM4335
E/bt_hwcfg( 6659): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6659): patchram path ORG bcm2079xB5_firmware.ncd BCM4335
E/bt_hwcfg( 6659): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6659): patchram path ORG bcm4335_V0093.0399.hcd BCM4335
I/bt_hwcfg( 6659): patch(org) : bcm4335_V0093.0399.hcd
I/bt_hwcfg( 6659): Found patchfile: /vendor/firmware/bcm4335_V0093.0399.hcd
E/bt_hwcfg( 6659): ORG patchram base 0093
E/bt_hwcfg( 6659): ORG patchram minor 0399
E/bt_hwcfg( 6659): fw ver (org)93.399
E/bt_hwcfg( 6659): Final Patchram is /vendor/firmware/bcm4335_V0093.0399.hcd
,D/SecurityLogAgent( 6633): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6633): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6633): StateMachine : Current State = 1
,I/art     (  908): Explicit concurrent mark sweep GC freed 63070(3MB) AllocSpace objects, 31(496KB) LOS objects, 17% free, 37MB/45MB, paused 2.571ms total 97.619ms
,I/bt_hwcfg( 6659): Axi patch failure or not include AXI patching
,I/bt_hwcfg( 6659): bt vendor lib: set UART baud 3000000
,D/SecurityLogAgent( 6633): StateMachine : Changed Current State = 1
,I/ActivityManager(  908): Killing 5907:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,D/BluetoothNotiBroadcastReceiver( 1311): onReceive
,D/AuthorizationBluetoothService( 1471): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/bt_hwcfg( 6659): bt vendor lib: set UART baud 115200
,I/bt_hwcfg( 6659): FW Download delta = 510777
,D/bt_hwcfg( 6659): Settlement delay -- 100 ms
I/bt_hwcfg( 6659): Setting fw settlement delay to 100 
,E/Tethering(  908): No numeric data
,D/Tethering(  908): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  908): forceRefresh() from cache miss
,D/NtpTrustedTime(  908): forceRefresh Fail.
,D/HotspotTile( 1185): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1185): updateTetherState():false, false
,V/NetworkStats(  908): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  908): UpdateStatsForKnox
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  908): performPollLocked() took 4ms
,D/NtpTrustedTime(  908): forceRefresh() from cache miss
,D/NtpTrustedTime(  908): forceRefresh Fail.
,I/wpa_supplicant( 6665): wlan0: Setting scan request: 0 sec 100000 usec
,I/bt_hwcfg( 6659): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg( 6659): vendor lib fwcfg completed
,I/wpa_supplicant( 6665): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 6665): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 6665): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/        ( 6659): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6659): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6659): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6659): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6659): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6659): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6659): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6659): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6659): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6659): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6659): BTE_InitTraceLevels -- TRC_SAP
I/        ( 6659): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6659): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6659): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6659): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6659): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 6659): BTE_InitTraceLevels -- TRC_PROTOCOL
,I/SecureStorage(  397): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6665
I/SecureStorage(  397): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,I/SecureStorage( 6665): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6665): ssSupport state is = 1
,I/SecureStorage( 6665): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 6665): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  397): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6665
I/SecureStorage(  397): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,I/SecureStorage( 6665): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6665): ssSupport state is = 1
I/wpa_supplicant( 6665): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6665): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,E/wpa_supplicant( 6665): SIM READ ERROR
I/wpa_supplicant( 6665): rfkill: Cannot open RFKILL control device
,E/SMD     (  289): DCD ON
,I/wpa_supplicant( 6665): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 6665): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6665): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 6665): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6665): Skip scan - bUseNetwork false
,E/WifiStateMachine(  908): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-HAL(  908): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 6665): HOTSPOT20_ENABLE called
I/wpa_supplicant( 6665): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6665): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6665): SIM READ ERROR
I/wpa_supplicant( 6665): Blacklist: Clear (all) 
,I/wpa_supplicant( 6665): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 6665): Skip scan - bUseNetwork false
,D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/WifiNative-HAL(  908): callSECApiInt - ID [210]
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/WifiConfigStore(  908): Loading config and enabling all networks 
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1185): Wifi onReceive(3)
D/STATUSBAR-QSTileView( 1185): onStateChanged: Wi-Fi
,D/SmartBondingService(  908): getNetworkEnabled : wifi : true mobile : true
D/HotspotTile( 1185): onReceive : 3, 0
,D/WifiCredService( 1311): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/WifiConfigStore(  908): Not a HS20
,E/SignOutReceiver( 6207): WIFI_STATE_CHANGED_ACTION
,E/WifiConfigStore(  908): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6633): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6633): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6633): StateMachine : Current State = 1
,D/SecurityLogAgent( 6633): StateMachine : Changed Current State = 1
D/WifiNative-HAL(  908): callSECApiInt - ID [65]
,D/WifiNative-HAL(  908): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 6665): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6665): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6665): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6665): P2P: Current p2p state = IDLE
I/wpa_supplicant( 6665): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 6665): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6665): First Scan Start
,I/wpa_supplicant( 6665): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL(  908): Setting external_sim to 1
,D/WifiStateMachine(  908): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  908): startHal
E/wifi    (  908): getStaticLongField sWifiHalHandle 0x9b26686c
D/wifi    (  908): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x7022ce
I/WifiNative-HAL(  908): Could not start hal
,E/native  (  908): do suspend true
,E/WifiStateMachine(  908): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiP2pService(  908): P2pDisabledState{ what=131203 }
,D/WifiScanningService(  908): SCAN_AVAILABLE : 3
D/RttService(  908): SCAN_AVAILABLE : 3
D/WifiScanningService(  908): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  908): startHal
E/wifi    (  908): getStaticLongField sWifiHalHandle 0x94b9099c
D/wifi    (  908): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x502212
I/WifiNative-HAL(  908): Could not start hal
E/WifiScanningService(  908): could not start HAL
D/RttService(  908): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  282): Setting iface cfg
D/CommandListener(  282): Trying to bring up p2p0
D/WifiMonitor(  908): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService(  908): P2pEnablingState
D/WifiP2pService(  908): P2pEnablingState{ what=147457 }
,D/WifiP2pService(  908): P2p socket connection successful
D/WifiP2pService(  908): P2pEnabledState
,D/WifiDisplayController(  908): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  908): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  908): disconnect
D/WifiDisplayController(  908): updateConnection
E/WifiStateMachine(  908): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController(  908): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/WifiStateMachine(  908): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,D/WifiNative-HAL(  908): callSECStringApiVoid - ID [215]
E/WifiNative-HAL(  908): invaild command id : 215
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,D/WifiP2pService(  908): sending p2p connection changed broadcast: IDLE
,E/Zygote  ( 6777): MountEmulatedStorage()
,E/Zygote  ( 6777): v2
,I/ActivityManager(  908): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6777 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/wpa_supplicant( 6665): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
I/libpersona( 6777): KNOX_SDCARD checking this for 10192
I/libpersona( 6777): KNOX_SDCARD not a persona
,D/WifiDisplayController(  908): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiP2pService(  908): create mNetworkAgent
,D/ConnectivityService(  908): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  908): Got NetworkAgent Messenger
D/ConnectivityService(  908): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  908): NetworkAgent connected
,E/CSLegacyTypeTracker(  908): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,W/bt-l2cap( 6659): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  ( 6659): BTM_SecRegister:p_cb_info->p_le_callback == 0xafa18b05 
,E/bt-btm  ( 6659): BTM_SecRegister: btm_cb.api.p_le_callback = 0xafa18b05 
,I/wpa_supplicant( 6665): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  908): p2pGetDeviceAddress
,D/WifiNative-HAL(  908): p2pGetDeviceAddress returning ea:50:8b:de:28:a3
I/SELinux ( 6777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/WifiDisplayController(  908): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
D/WifiDisplayController(  908):  deviceAddress: ea:50:8b:de:28:a3
D/WifiDisplayController(  908):  primary type: 10-0050F204-5
D/WifiDisplayController(  908):  secondary type: null
D/WifiDisplayController(  908):  wps: 0
D/WifiDisplayController(  908):  grpcapab: 0
D/WifiDisplayController(  908):  devcapab: 0
D/WifiDisplayController(  908):  status: 3
D/WifiDisplayController(  908):  wfdInfo: null
D/WifiDisplayController(  908):  groupownerAddress: null
D/WifiDisplayController(  908):  GOdeviceName: null
D/WifiDisplayController(  908):  interfaceAddress: 
D/WifiDisplayController(  908):  SConnectInfo : null
D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
,D/WifiP2pService(  908): DeviceAddress: ea:28:a3
,I/SELinux ( 6777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6777): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
D/AllShareCastTile( 1185): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1185): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/WifiP2pService(  908): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  908): InactiveState
,D/WifiP2pService(  908): InactiveState{ what=143376 }
D/WifiP2pService(  908): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 6665): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
,D/WifiP2pService(  908): InactiveState{ what=143376 }
D/WifiP2pService(  908): P2pEnabledState{ what=143376 }
,D/TimaKeyStoreProvider( 6777): TimaSignature is unavailable
,D/ActivityThread( 6777): Added TimaKeyStore provider
,D/ResourcesManager( 6777): creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,D/WifiDirectBR( 6777): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager(  908): Killing 5869:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 6378): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/WifiDirectBR( 6777): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 6777): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 6777): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/WifiDirectBR( 6777): stopServiceTest : false
,D/BluetoothAdapterProperties( 6659): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 0 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,E/bt-btif ( 6659): Calling BTA_HhEnable
,E/bt-btif ( 6659): btif_storage_get_adapter_property service_mask:0x2120048
,D/BluetoothAdapterProperties( 6659): Address is:E0:DB:10:1F:C9:5E
,E/BluetoothServiceJni( 6659): populateRssiValuesNative
,I/bluedroid( 6659): getModelRssiValues
E/BluetoothServiceJni( 6659): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/BluetoothAdapterProperties( 6659): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6659): Name is: Note3-1
,D/BluetoothAdapterProperties( 6659): Scan Mode:20
,D/BluetoothAdapterProperties( 6659): Discoverable Timeout:120
D/BluetoothAdapterProperties( 6659): LE Address is:E0:B7:20:3E:93:BC
,E/bt-btif ( 6659): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
D/bt_vendor( 6659): op for 2
D/bt_vendor( 6659): op for 6
,E/bt-btif ( 6659): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 6659): btif_sock_init: !radio_req && !rfc_init
D/SettingsProvider(  908): name = bluetooth_name
,E/bt-btif ( 6659): btif_sock_init: !vhci_init
,D/IOP_DB_BT( 6659): db_open: file /etc/bluetooth/iop_bt.db
D/bt_vendor( 6659): op for 7
,D/bt_upio ( 6659): proc btwrite assertion
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/IOP_DB_BT( 6659): db_open: db_open : handle 3026128912l, read 14063 bytes onto local cache
D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/IOP_DB_BT( 6659): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT( 6659): db_query: result 1
I/        ( 6659): iop_db_open: iop_db_open status 0
,D/bte_conf( 6659): Device ID record 1 : primary
,D/bte_conf( 6659):   vendorId            = 0075
D/bte_conf( 6659):   vendorIdSource      = 0001
D/bte_conf( 6659):   product             = 0100
,D/bte_conf( 6659):   version             = 0200
D/bte_conf( 6659):   clientExecutableURL = 
D/bte_conf( 6659):   serviceDescription  = 
,D/bte_conf( 6659):   documentationURL    = 
D/bte_conf( 6659): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 6659): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6659): ScanMode =  20
D/BluetoothAdapterProperties( 6659): State =  11
D/SecContentProvider(  908): uri = 3 selection = isDiscoverableEnabled
D/BluetoothPanServiceJni( 6659): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterProperties( 6659): Setting state to 12
I/BluetoothAdapterState( 6659): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties( 6659): Scan Mode:21
,D/SettingsProvider(  908): name = bluetooth_a2dp_sink_mode
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 1002
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,D/BluetoothAdapterProperties( 6659): Discoverable Timeout:120
,W/BackupManagerService(  908): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 6659): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6659): updateAdapterState state is 12
,D/BluetoothA2dp( 2955): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 6659): onBluetoothStateChange: up=true
,D/BluetoothAdapterService( 6659): Autoconnection is available 
D/BluetoothAdapterService( 6659): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 6659): starting service from this receiver
,D/BluetoothA2dp(  908): onBluetoothStateChange: up=true
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,E/bt_h4   ( 6659): vendor lib postload completed
D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,I/BluetoothAdapterState( 6659): Entering On State from state = 11
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/BluetoothTile( 1185):  onBluetoothStateChange:
W/InputMethodManagerService(  908): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  908): [BT Setting State] State =12
I/InputMethodManagerService(  908): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
,D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
I/SamsungIME( 1718): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/bt_vendor( 6659): op for 7
,D/bt_upio ( 6659): BT_WAKE is asserted already
D/BluetoothHeadset( 1395): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@d1e2baa, true
D/BluetoothTile( 1185): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1185):  onBluetoothPairedDevicesChanged:
,I/BluetoothPbapService( 6659): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/BluetoothHeadset( 1395): registerMessageListener
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
D/HeadsetService( 6659): registerMessageListener
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/HeadsetService( 6659): registerMessageListener
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
D/HeadsetStateMachine( 6659): Disconnected process message: 70
D/HeadsetStateMachine( 6659): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1f50227c
I/Telecom ( 1395): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1395): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/StatusBarManagerService(  908): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
D/StatusBarManagerService(  908): setIconVisibility slot=bluetooth visible=true
,D/PhoneStatusBar( 1185): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,I/BluetoothPbapService( 6659): Handler(): got msg=1
D/BluetoothManagerService(  908): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/SecContentProvider(  908): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
D/HeadsetStateMachine( 6659): Disconnected process message: 9
D/HeadsetStateMachine( 6659): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,V/BluetoothPbapService( 6659): PBAP Service initSocket try: 0
D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/audio_hw_primary(  297): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  297): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  297): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  297): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  297): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  297): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  297): adev_set_parameters: exit
E/HeadsetStateMachine( 6659): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothTile( 1185):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1185): onStateChanged: Bluetooth
,D/BluetoothMapMasInstance( 6659): set MAP SDP message type : 1
,W/BluetoothAdapter( 6659): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6659): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
W/BluetoothAdapter( 6659): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 6659): bindListen(), new LocalSocket 
D/BluetoothSocket( 6659): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6659): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1171ae81
D/BluetoothSocket( 6659): channel: 19
D/BluetoothPbapService( 6659): PBAP Socket is BluetoothServerSocket
,D/BluetoothSocket( 6659): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 6659): bindListen(), new LocalSocket 
D/BluetoothSocket( 6659): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6659): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@958cb26
D/BluetoothSocket( 6659): channel: 5
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/LocalBluetoothProfileManager( 1311): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1311): Adding local HEADSET profile
,E/BluetoothHeadset( 1311): BTStateChangeCB is registed
,E/BluetoothHeadset( 1311): BluetoothHeadset service is binded
,W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 1311): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1311): PANU : true
D/LocalBluetoothProfileManager( 1311): Adding local MAP profile
,D/BluetoothMap( 1311): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 1311): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1311): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1311): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1311): onReceive
,D/BluetoothA2dp( 1311): Proxy object connected
D/A2dpProfile( 1311): Bluetooth service connected
,D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
D/BtConfig.SecureMode( 6659): isSecureModeOn:false
,D/HeadsetProfile( 1311): Bluetooth service connected
,D/AuthorizationBluetoothService( 1471): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/Bluetoothsap( 1311): BluetoothSAP Proxy object connected
,D/SapProfile( 1311): Bluetooth service connected
D/Bluetoothsap( 1311): getConnectedDevices()
,D/BluetoothInputDevice( 1311): Proxy object connected
,D/HidProfile( 1311): Bluetooth service connected
,D/BluetoothPan( 1311): BluetoothPAN Proxy object connected
,D/PanProfile( 1311): Bluetooth service connected
,D/BluetoothMap( 1311): Proxy object connected
,D/MapProfile( 1311): Bluetooth service connected
D/BluetoothPbap( 1311): Proxy object connected
D/PbapServerProfile( 1311): Bluetooth service connected
,D/SecContentProvider(  908): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/BluetoothAdapter( 6659): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6659): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
D/BluetoothSocket( 6659): bindListen(), new LocalSocket 
D/BluetoothSocket( 6659): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6659): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d2e9e80
D/BluetoothSocket( 6659): channel: 12
D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
I/BtOppRfcommListener( 6659): Accept thread started.
,I/wpa_supplicant( 6665): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 6665): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6665): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 6665): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 6665): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
,I/wpa_supplicant( 6665): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 6665): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
I/wpa_supplicant( 6665): Associated with C0.AA.4A
,D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
,I/wpa_supplicant( 6665): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 6665): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
,I/wpa_supplicant( 6665): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 6665): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 6665): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 6665): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6665): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 6665): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6665): Blacklist: Clear (temp) 
I/wpa_supplicant( 6665): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/WifiNative-HAL(  908): callSECApiVoid - ID [50]
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  908): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  908): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  908): Got NetworkAgent Messenger
E/WifiConfigStore(  908): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  908): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): NetworkAgent connected
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiConfigStore(  908): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  282): Setting iface cfg
,E/Zygote  ( 6809): MountEmulatedStorage()
,E/Zygote  ( 6809): v2
I/libpersona( 6809): KNOX_SDCARD checking this for 10038
I/libpersona( 6809): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6809 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/WifiStateMachine(  908): Start Dhcp Watchdog 1
,D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
,D/ConnectivityService(  908): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
I/SELinux ( 6809): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,I/SELinux ( 6809): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6809): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6809): TimaSignature is unavailable
,D/ActivityThread( 6809): Added TimaKeyStore provider
,D/ResourcesManager( 6809): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 6809): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/native  (  908): do suspend false
,D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  908): InactiveState{ what=143375 }
D/SecContentProvider2(  908): mCursor = null
,D/WifiP2pService(  908): P2pEnabledState{ what=143375 }
,I/VlingoApplication( 6809): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/BluetoothHeadset( 6809): BTStateChangeCB is registed
,E/BluetoothHeadset( 6809): BluetoothHeadset service is binded
,I/ActivityManager(  908): Killing 5931:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,I/Hs20UtilService( 1311): Starting #2
,I/Hs20UtilService( 1311): Message received 5007
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SettingsProvider(  908): name = driving_mode_on
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 10038
,D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
,E/dhcpcd  ( 6830): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6830): version 5.5.6 starting
,E/dhcpcd  ( 6830): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,D/BluetoothManager( 6809): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6207): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  ( 6830): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6830): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6830): if(wlan0) info get Success. (MAC : C0.AA.4A)
,I/dhcpcd  ( 6830): bssid match
,I/dhcpcd  ( 6830): wlan0: rebinding lease of 192.168.1.128
,E/Watchdog(  908): !@Sync 5
,D/bt_vendor( 6659): op for 7
,D/bt_upio ( 6659): ..proc_btwrite_timeout..
,I/dhcpcd  ( 6830): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/dhcpcd  ( 6830): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  908): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,E/native  (  908): do suspend true
,D/WifiP2pService(  908): InactiveState{ what=143375 }
,D/WifiP2pService(  908): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  908): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,E/WifiStateMachine(  908): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
E/WifiStateMachine(  908): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNative-HAL(  908): callSECApiInt - ID [210]
,E/ConnectivityService(  908): updateNetworkInfo()
,D/WifiWatchdogStateMachine(  908): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  908): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver(  908): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker(  908): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  908): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  908): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  908): Adding iface wlan0 to network 502
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 1311): Starting #3
,I/Hs20UtilService( 1311): Message received 5007
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,E/WifiStateMachine(  908): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiTrafficPoller(  908): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,E/SignOutReceiver( 6207): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine(  908): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  908): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
,I/WifiTrafficPoller(  908): mBoosterFLAG : 0
I/WifiTrafficPoller(  908): current booster mode : FullMode
D/WifiNative-HAL(  908): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1185): applyOpen
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/ConnectivityService(  908): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService(  908): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService(  908): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,E/ConnectivityService(  908): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  908): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  908): updateSourceRoutes : add src route for:192.168.1.128
V/        (  282): QcRouteController
,I/Hs20UtilService( 1311): Starting #4
,I/Hs20UtilService( 1311): Message received 5007
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/        (  282): QcRouteController
,E/SignOutReceiver( 6207): NETWORK_STATE_CHANGED_ACTION
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
I/Hs20UtilService( 1311): Starting #5
,I/Hs20UtilService( 1311): Message received 5007
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  908): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  282): QcRouteController
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6207): NETWORK_STATE_CHANGED_ACTION
,V/        (  282): QcRouteController
,I/SurfaceFlinger(  254): id=14 createSurf (1x1),1 flag=4, Uoast
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,D/PowerManagerService(  908): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=908
,V/        (  282): QcRouteController
,D/ConnectivityService(  908): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService(  908): LTETest block dns file not exists
,V/Nat464Xlat(  908): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  908): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  908): calling update connectivity
E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/ConnectivityService(  908): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  908): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity(  908): Not allowed due to - mEnabled false
D/ConnectivityService(  908): calling update connectivity
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  908): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  908):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  908):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/System.out(  908): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(  908): (HTTPLog)-Static: isShipBuild true
D/ConnectivityService(  908): currentScore = 0, newScore = 60
I/System.out(  908): (HTTPLog)-Thread-181-779673108: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/ConnectivityService(  908):    accepting network in place of null
I/System.out(  908): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  908): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,D/TelephonyNetworkFactory( 1424): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  908): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  908): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  908): MasterInitialState.processMessage what=3
D/NtpTrustedTime(  908): forceRefresh() from cache miss
,D/ConnectivityService(  908): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
V/NetworkStats(  908): updateIfacesLocked()
,V/NetworkStats(  908): performPollLocked(flags=0x1)
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  908): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/NetworkStatsFactory(  908): UpdateStatsForKnox
D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): 0
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 1185): updateDataNetType()
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 1185): NoService, mRoamingIconId = 0
D/SmartBondingService(  908): getSBEnabled() enabled =false
E/StatusBar.NetworkController( 1185): updateLTEICONDataNetType:0
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  908): forceRefresh Fail.
,D/SmartBondingService(  908): getNetworkEnabled : wifi : true mobile : true
D/EntConnectivity(  908): Not allowed due to - mEnabled false
,D/ConnectivityService(  908): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  908): calling update connectivity
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,V/NetworkStats(  908): performPollLocked() took 5ms
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1185): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/NtpTrustedTime(  908): forceRefresh() from cache miss
D/StatusBar.NetworkController( 1185): applyOpen
D/NtpTrustedTime(  908): forceRefresh Fail.
,V/NetworkStats(  908): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/System.out(  908): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:54:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449683685382], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449683685339]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Validated
D/ConnectivityService(  908): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  908): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  908):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  908):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  908): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  908): calling update connectivity
,D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  908): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524290
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1185): updateDataNetType()
D/StatusBar.NetworkController( 1185): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1185): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1185): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  908): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  908): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  908): SmartBondingReceiver: wifi ap is changed, init speed ratio
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1806): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
W/ContextImpl( 1806): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/SmartBondingService(  908): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  908): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  908): forceRefresh() from cache miss
,I/DBG_DM  ( 3169): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3169): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  908): forceRefresh Fail.
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5118): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 3169): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
I/DBG_DM  ( 3169): [llIlIIIIlllIlllllIll(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 3169): [IIllIIllIIIlllIlIIll(403/llllllIllIlIlllIIlIl)] Check completed.
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3169): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3169): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 3169): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3169): [IIIlllIlIIlllIIIIllI(73/llllIIIllIlIIIIllllI)] 
,I/PCWCLIENTTRACE_PushUtil( 5957): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5957): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5957): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5957): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3169): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3169): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 3
,I/DBG_DM  ( 3169): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 3169): [IIllIIllIIIlllIlIIll(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,E/Zygote  ( 6901): MountEmulatedStorage()
E/Zygote  ( 6901): v2
I/libpersona( 6901): KNOX_SDCARD checking this for 10004
I/libpersona( 6901): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3169): [IIllIIllIIIlllIlIIll(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [3]
,I/DBG_DM  ( 3169): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1280/handleMessage)] 
I/ActivityManager(  908): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6901 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DBG_DM  ( 3169): [com.wssyncmldm.XDMService(849/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 3169): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3169): [llIlIIIIlllIlllllIll(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3169): [llIlIIIIlllIlllllIll(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 3169): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3169): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/art     (  338): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 445us total 14.706ms
,I/DBG_DM  ( 3169): [com.wssyncmldm.ui.XUIFotaPostponeActivity(493/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3169): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 401us total 10.182ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 9.848ms
,I/SELinux ( 6901): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6901): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/GpsLocationProvider(  908): No APN found to select.
,E/SELinux ( 6901): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3169): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 6901): TimaSignature is unavailable
,D/ActivityThread( 6901): Added TimaKeyStore provider
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 6901): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/SecContentProvider2(  908): uri = 14 selection = getSealedState
,D/SecContentProvider2(  908): mCursor = null
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ApplicationPolicy(  908): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  908): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager(  908): showStatusBarByNotification() mOpenByNotification=false
,D/ResourcesManager( 1185): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,D/KnoxNotification( 1185): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1185): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1185): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1185): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@306fec
D/PersonaManager( 1185): isKioskContainerExistOnDevice
D/PersonaManager( 1185): isKioskContainerExistOnDevice
,D/PanelView( 1185): There is/are notification(s) 
,D/PanelView( 1185): There is/are notification(s) 
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1471): Vacuum at: now=1449683686026 tag=VacuumService
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6925): MountEmulatedStorage()
,E/Zygote  ( 6925): v2
I/libpersona( 6925): KNOX_SDCARD checking this for 1000
I/libpersona( 6925): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6925 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ConnectivityService(  908): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
,D/ConnectivityService(  908): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  908): identical MTU - not setting
D/ConnectivityService(  908): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  908): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,I/SELinux ( 6925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,W/NetworkManagementService(  908): route cmd failed: 
W/NetworkManagementService(  908): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '54 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 54 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  908): '
W/NetworkManagementService(  908): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  908): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  908): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  908): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  908): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  908): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  908): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  908): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  908): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  908): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/Nat464Xlat(  908): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  908): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
I/SELinux ( 6925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/ConnectivityService(  908): calling update connectivity
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  908): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  908): calling update connectivity
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524295
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
E/SELinux ( 6925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524295
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/Zygote  ( 6939): MountEmulatedStorage()
,E/Zygote  ( 6939): v2
I/libpersona( 6939): KNOX_SDCARD checking this for 10104
I/libpersona( 6939): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6939 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  908): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/SmartBondingService(  908): getSBEnabled() enabled =false
,I/SELinux ( 6939): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/TimaKeyStoreProvider( 6925): TimaSignature is unavailable
D/ActivityThread( 6925): Added TimaKeyStore provider
I/SELinux ( 6939): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6939): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 6939): TimaSignature is unavailable
,D/ActivityThread( 6939): Added TimaKeyStore provider
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6925): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/ResourcesManager( 6939): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityThread( 1747): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 6925): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 6925): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/Auth.Api.Credentials( 1747): [CredentialSyncAdapter] Unknown sync event.
,D/SyncManager(  908): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 19139, reason: UserStart, SyncResult: databaseError: true stats []
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  908): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 199867, reason: UserStart
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  908): Explicit concurrent mark sweep GC freed 73361(4MB) AllocSpace objects, 5(80KB) LOS objects, 17% free, 37MB/45MB, paused 1.562ms total 96.390ms
,D/SecContentProvider2(  908): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  908): mCursor = null
,I/DIAGMON_AGENT( 6925): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 6925): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6925): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6925): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6939): Delaying sync.
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  908): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  908): apparently satisfied.  currentScore=60
D/ConnectivityService(  908): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  908): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
D/ConnectivityManager.CallbackHandler( 1747): CM callback handler got msg 524290
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6974): MountEmulatedStorage()
E/Zygote  ( 6974): v2
I/libpersona( 6974): KNOX_SDCARD checking this for 10014
I/libpersona( 6974): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=6974 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 4142:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,I/SELinux ( 6974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6974): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6974): TimaSignature is unavailable
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ActivityThread( 6974): Added TimaKeyStore provider
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6974): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 6974): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 6974): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PicasaService( 5210): start picasa sync
,D/PicasaService( 5210): end picasa sync
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6939): Delaying sync.
,I/PhenotypeConfigurator( 1471): Scheduling Phenotype for one-off execution 7499 seconds from now (1449683686777)
,I/FOTA_Client( 6974): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6995): MountEmulatedStorage()
,E/Zygote  ( 6995): v2
I/libpersona( 6995): KNOX_SDCARD checking this for 10023
I/libpersona( 6995): KNOX_SDCARD not a persona
,D/PackageManager(  908): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/ActivityManager(  908): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6995 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/GetConfigurationSnapshotOperation( 1471): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/SELinux ( 6995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6995): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 6995): TimaSignature is unavailable
,D/ActivityThread( 6995): Added TimaKeyStore provider
,I/PhenotypeFlagCommitter( 1471): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1471): Using platform SSLCertificateSocketFactory
,D/ResourcesManager( 6995): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6995): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6995): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449683686959
,I/KLMS-2.4.511: ( 6995): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6995): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 6995): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 6995): NetworkChangeOperations(): uploadRequestLog().START 
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6995): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7017): MountEmulatedStorage()
,E/Zygote  ( 7017): v2
I/libpersona( 7017): KNOX_SDCARD checking this for 10036
I/libpersona( 7017): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7017 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 5990:com.policydm/1000 (adj 15): bgCount ##41
,I/SELinux ( 7017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7017): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/TimaKeyStoreProvider( 7017): TimaSignature is unavailable
,D/ActivityThread( 7017): Added TimaKeyStore provider
,D/ResourcesManager( 7017): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 7017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7017): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  908): Killing 4697:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,W/DriveInitializer( 1747): Awaiting to be initialized
,W/DriveInitializer( 1747): Background init thread started
,E/Minikin ( 7017): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,I/ActivityManager(  908): Killing 6011:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1747): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7037): MountEmulatedStorage()
I/libpersona( 7037): KNOX_SDCARD checking this for 10042
E/Zygote  ( 7037): v2
I/libpersona( 7037): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7037 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7037): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  908): Killing 6037:com.osp.app.signin/u0a50 (adj 15): bgCount ##41
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7037): TimaSignature is unavailable
,D/ActivityThread( 7037): Added TimaKeyStore provider
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/DriveInitializer( 1747): Background init thread ended
,D/ResourcesManager( 7037): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7037): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7066): MountEmulatedStorage()
I/libpersona( 7066): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7066): v2
I/libpersona( 7066): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7066 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7066): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7066): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7066): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  908): Killing 6096:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7066): TimaSignature is unavailable
,D/ActivityThread( 7066): Added TimaKeyStore provider
,I/System.out( 1471): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1471): (HTTPLog)-Static: isShipBuild true
I/System.out( 1471): (HTTPLog)-Thread-192-611761564: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1471): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  908): Killing 4975:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/ResourcesManager( 7066): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/System.out( 1471): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1471): Tagging socket 70 with tag 1000120100000000{268440065,0} uid -1, pid: 1471, getuid(): 10015
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 1471): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 1471, getuid(): 10015
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7089): MountEmulatedStorage()
I/libpersona( 7089): KNOX_SDCARD checking this for 10043
E/Zygote  ( 7089): v2
I/libpersona( 7089): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7089 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 6830): wlan0: sending IPv6 Router Solicitation
,I/SELinux ( 7089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7089): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7089): TimaSignature is unavailable
,D/ActivityThread( 7089): Added TimaKeyStore provider
,I/ActivityManager(  908): Killing 6134:com.wsomacp/u0a29 (adj 15): bgCount ##41
,D/SSRM:n  (  908): SIOP:: AP = 390, PST = 337, CUR = 450
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7089): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,I/jxcore-log( 6557): Test app app.js loaded
I/jxcore-log( 6557): 
,I/chromium( 6557): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1471): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1471): Tagging socket 70 with tag 1000120100000000{268440065,0} uid -1, pid: 1471, getuid(): 10015
,E/SPPClientService( 7089): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7089): [PushClientApplication] Push log off : This is Ship build version
,I/chromium( 6557): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SPPClientService( 7089): PushLog.txt file is not deleted.
D/SPPClientService( 7089): PushLog.txt file is not deleted.
D/SPPClientService( 7089): ============PushLog. stop!
,E/SPPClientService( 7089): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7107): MountEmulatedStorage()
,E/Zygote  ( 7107): v2
I/libpersona( 7107): KNOX_SDCARD checking this for 10050
I/libpersona( 7107): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7107 uid=10050 gids={50050, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 6118:com.google.android.apps.docs/u0a112 (adj 15): bgCount ##41
,E/SMD     (  289): DCD ON
,I/SELinux ( 7107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7107): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7107): TimaSignature is unavailable
,I/System.out( 1471): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1471): Tagging socket 70 with tag 1000120100000000{268440065,0} uid -1, pid: 1471, getuid(): 10015
D/ActivityThread( 7107): Added TimaKeyStore provider
,D/ResourcesManager( 7107): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SA      ( 7107): [SSP] onCreated
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1471): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1471): Tagging socket 70 with tag 1000120100000000{268440065,0} uid -1, pid: 1471, getuid(): 10015
,I/SA      ( 7107): [TPM] There is no property file
,I/SA      ( 7107): [SCU] isHaveSA() - false
,I/SA      ( 7107): [TPM] getModelProperty : null
I/SA      ( 7107): [TPM] getCSCProperty : null
,I/SA      ( 7107): [DM] init START
,I/SA      ( 7107): [DM] This device is not a Vodafone
I/SA      ( 7107): checkReactivationActive for LOLLIPOP
,I/SA      ( 7107): checkReactivationActive for reactiveActive
I/SA      ( 7107): setSupportRL : true
,I/SA      ( 7107): [SCU] isHaveSA() - false
I/SA      ( 7107): support phone number id : false
,I/SA      ( 7107): [DM] init END
,I/SA      ( 7107): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 7107): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 7107): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7107): [SLFUCHKMGR] constructor called
,I/SA      ( 7107): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7107): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7107): [SCU] == networkStateCheck == true
,I/SA      ( 7107): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7107): isChinaCountryCode : false
I/SA      ( 7107): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7107): [OR] == networkStateCheck true ==
,I/SA      ( 7107): [OR] GetMyCountryZoneTask
,I/SA      ( 7107): [OR] onReceive END
,I/ActivityManager(  908): Killing 6154:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/SA      ( 7107): [SRS] prepareGetMyCountryZone
,I/SA      ( 7107): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7107): [SSP] query invoked
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7107): [TPMU] GetMccFromDB : null
I/SA      ( 7107): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7107): [TPM] isNoProxy(default) : true
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/File    ( 7107): fail readDirectory() errno=2
,E/Zygote  ( 7129): MountEmulatedStorage()
,E/Zygote  ( 7129): v2
I/libpersona( 7129): KNOX_SDCARD checking this for 10074
I/libpersona( 7129): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7129 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7129): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7129): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7129): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7129): TimaSignature is unavailable
,D/ActivityThread( 7129): Added TimaKeyStore provider
,D/ResourcesManager( 7129): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp( 7129): sCloudBackupApp Version Info : 3.13.7.KK_APP
,I/SCloudBackupReceiver( 7129): Other Intent
,I/KnoxUsageLogPro( 6393): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 6393): premStatus:2
,I/KnoxUsageLogPro( 6393): isEulaShown : false
I/KnoxUsageLogPro( 6393): KnoxUsageReceiver onReceive : not Processible, just return
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6659): Disconnected process message: 10
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  908): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/Zygote  ( 7146): MountEmulatedStorage()
E/Zygote  ( 7146): v2
I/libpersona( 7146): KNOX_SDCARD checking this for 10146
I/libpersona( 7146): KNOX_SDCARD not a persona
,I/SELinux ( 7146): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  908): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7146 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7146): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7146): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager(  908): Killing 6174:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7146): TimaSignature is unavailable
,D/ActivityThread( 7146): Added TimaKeyStore provider
,I/art     (  338): Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 310us total 13.187ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 270us total 10.040ms
,D/ResourcesManager( 7146): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/btif_config_util( 6659): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 272us total 10.407ms
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7146): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7146): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7146): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7146): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  254): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=14 Removed Uoast (-2/9)
,D/PowerManagerService(  908): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 908) eventTime = 170777
,D/PowerManagerService(  908): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=908 (0x0)
D/PowerManagerService(  908): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=908, ws=WorkSource{10067}) (elapsedTime=3473)
,I/WebViewFactory( 7146): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7146): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7146): Loading: webviewchromium
,I/LibraryLoader( 7146): Time to load native libraries: 4 ms (timestamps 842-846)
,I/LibraryLoader( 7146): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7146): Binding Chromium to main looper Looper (main, tid 1) {25066452}
,I/LibraryLoader( 7146): Expected native library version number "",actual native library version number ""
,I/chromium( 7146): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7146): Initializing chromium process, renderers=0
,W/art     ( 7146): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7146): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7146): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7146): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 7146): Requires BLUETOOTH permission
,I/SA      ( 7107): [RC New] Execute method=[GET] start
,I/Adreno-EGL( 7146): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7146): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7146): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7146): Local Branch: mybranch5813579
I/Adreno-EGL( 7146): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7146): Local Patches: NONE
I/Adreno-EGL( 7146): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/SA      ( 7107): [RC New] Security=[true]
,I/System.out( 7107): Thread-1155(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7107): Thread-1155(ApacheHTTPLog):isShipBuild true
,I/System.out( 7107): Thread-1155(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/NSApplication( 7146): Starting up...
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7201): MountEmulatedStorage()
E/Zygote  ( 7201): v2
I/libpersona( 7201): KNOX_SDCARD checking this for 10158
I/libpersona( 7201): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7201 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7201): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  908): Killing 6189:com.samsung.helphub/1000 (adj 15): bgCount ##41
I/SELinux ( 7201): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7201): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 7201): TimaSignature is unavailable
,D/ActivityThread( 7201): Added TimaKeyStore provider
,D/ResourcesManager( 7201): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7201): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7201): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7201): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7201): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7201): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7201): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6633): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6633): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6633): StateMachine : Current State = 1
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6633): StateMachine : Changed Current State = 1
,I/ActivityManager(  908): Killing 6224:com.samsung.android.snote:provider/u0a168 (adj 15): bgCount ##41
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7216): MountEmulatedStorage()
E/Zygote  ( 7216): v2
I/libpersona( 7216): KNOX_SDCARD checking this for 10200
I/libpersona( 7216): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7216 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7216): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7216): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7216): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7216): TimaSignature is unavailable
,D/ActivityThread( 7216): Added TimaKeyStore provider
,D/ResourcesManager( 7216): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/iu.SyncManager( 1747): SYNC; picasa accounts
,D/NetworkLogImpl( 1747): Loaded NetworkSpeedPredictor
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 1747): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1747): num queued entries: 0
,I/iu.UploadsManager( 1747): num updated entries: 0
,I/iu.SyncManager( 1747): NEXT; no task
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  908): Killing 6242:com.sec.kidsplat.installer/u0a189 (adj 15): bgCount ##41
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 6268): notifyNetworkActivated
,W/ContextImpl( 6268): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  908): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1471): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GCM     ( 1471): GCM config loaded
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 6268): AutoUpdateManager:IDLE:execute
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 6268): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6268): exit::IDLE
D/InitializeManagerStateMachine( 6268): entry::NETWORK_CHECK
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 6268): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6268): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6268): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6268): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6268): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6268): entry::SUCCESS
,D/hcjo    ( 6268): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6268): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 6268): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6268): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 6268): exit::SUCCESS
D/InitializeManagerStateMachine( 6268): entry::IDLE
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7107): [RC New] [v2liruge] api execute + 644
,I/SA      ( 7107): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 7107): AsyncTask #1 calls detatch()
,I/SA      ( 7107): [TPMU] getNetworkMcc : 
,I/SA      ( 7107): [SCU] saveMccToPreferece Start
,I/SA      ( 7107): [SCU] RegionMCC : 260
I/SA      ( 7107): [SSP] query invoked
,I/art     (  908): Explicit concurrent mark sweep GC freed 47371(2MB) AllocSpace objects, 7(112KB) LOS objects, 17% free, 37MB/45MB, paused 1.247ms total 84.448ms
,I/SA      ( 7107): [TPMU] GetMccFromDB : null
I/SA      ( 7107): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7107): [SCU] saveMccToPreferece End
I/SA      ( 7107): [RC New] executeRequest [v2liruge] end. 781
,I/SA      ( 7107): [RC New] Execute end
I/SA      ( 7107): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7107): [OR] GetMyCountryZoneTask Success
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5957): mConnectivityHandler : connected,
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 5957): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 5957): ================================================
,I/CSTORAGE( 5957):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 5957): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5957): [GetString-S]
,E/art     ( 5957): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 5957): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5957): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5957): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5957): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5957): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5957): [ensureRegistration] - No Samsung account
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 6830): wlan0: sending IPv6 Router Solicitation
,I/GAV4    ( 7146): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  289): DCD ON
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7261): MountEmulatedStorage()
,E/Zygote  ( 7261): v2
,I/libpersona( 7261): KNOX_SDCARD checking this for 10051
I/libpersona( 7261): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7261 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7261): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7261): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7261): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7261): TimaSignature is unavailable
,D/ActivityThread( 7261): Added TimaKeyStore provider
,D/ResourcesManager( 7261): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7261): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 7261): CalendarProvider2.onCreate() called
,I/dhcpcd  ( 6830): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6830): wlan0: no IPv6 Routers available
,I/CalendarProvider2( 7261): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7303): MountEmulatedStorage()
,E/Zygote  ( 7303): v2
,I/libpersona( 7303): KNOX_SDCARD checking this for 10171
,I/ActivityManager(  908): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7303 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,I/libpersona( 7303): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Killing 6334:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): bgCount ##41
,I/SELinux ( 7303): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7303): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7303): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7303): TimaSignature is unavailable
,D/ActivityThread( 7303): Added TimaKeyStore provider
,D/ResourcesManager( 7303): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7303): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7303): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7333): MountEmulatedStorage()
,E/Zygote  ( 7333): v2
,I/libpersona( 7333): KNOX_SDCARD checking this for 10172
,I/libpersona( 7333): KNOX_SDCARD not a persona
,I/SELinux ( 7333): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  908): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7333 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 7333): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7333): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  908): Killing 5330:sstream.app/u0a25 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7333): TimaSignature is unavailable
,D/ActivityThread( 7333): Added TimaKeyStore provider
,D/ResourcesManager( 7333): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7333): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7333): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7333): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager(  908): Killing 5369:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 340, PST = 332, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6659): Disconnected process message: 10
D/BatteryService(  908): stay LED for fully charged
,D/PreloadUpdateManagerStateMachine( 6268): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6268): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6268): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6268): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6268): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6268): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6268): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6268): entry::IDLE
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{394bd96e u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/PowerManagerService(  908): [PWL] Off : 75s ago
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  908): SIOP:: AP = 320, PST = 328, CUR = 450
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 6
,E/SMD     (  289): DCD ON
,V/AlarmManager(  908): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:n  (  908): SIOP:: AP = 310, PST = 325, CUR = 450,
E/SMD     (  289): DCD ON
,V/AlarmManager(  908): waitForAlarm result :4
,E/SMD     (  289): DCD ON
,I/ClearcutLoggerApiImpl( 1471): disconnect managed GoogleApiClient
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 310, PST = 323, CUR = 450
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  356): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  356): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  908): [PWL] Off : 105s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 321, CUR = 450
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/Watchdog(  908): !@Sync 7
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager(  908): waitForAlarm result :4
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6659): Disconnected process message: 10
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityThread( 1747): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  908): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, SERVER, currentRunTime 199867, reason: ServiceChanged, SyncResult: databaseError: true stats []
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  908): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, SERVER, currentRunTime 291808, reason: ServiceChanged
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  908): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  908): mCursor = null
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 320, CUR = 450
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6659): Disconnected process message: 10
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 319, CUR = 450
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/PowerManagerService(  908): [PWL] Off : 140s ago
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 318, CUR = 450
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 8
,E/SMD     (  289): DCD ON
,V/AlarmManager(  908): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6659): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 317, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 308, CUR = 450
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 304, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 9
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6659): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  908): [PWL] Off : 180s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 302, CUR = 450
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6659): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 301, CUR = 450
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 299, CUR = 450
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  908): initializing...
,I/TLC_TIMA_PKM_initialize(  908): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  908): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  908): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  908): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  908): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  908): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  908): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  908): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  908): App is not loaded in QSEE
,D/QSEECOMAPI: (  908): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  908): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  908): Trustlet response is completed
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6659): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 299, CUR = 450
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  356): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  356): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 298, CUR = 450
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  908): waitForAlarm result :4
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,I/ActivityManager(  908): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7405 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7405): MountEmulatedStorage()
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,E/Zygote  ( 7405): v2
I/libpersona( 7405): KNOX_SDCARD checking this for 10096
I/libpersona( 7405): KNOX_SDCARD not a persona
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,I/SELinux ( 7405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7405): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7405): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6659): Disconnected process message: 10
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/TimaKeyStoreProvider( 7405): TimaSignature is unavailable
,D/ActivityThread( 7405): Added TimaKeyStore provider
,D/ResourcesManager( 7405): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  908): Killing 5452:com.sec.android.app.controlpanel/u0a134 (adj 13): bgCount ##41
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 225s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON,
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 297, CUR = 450
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6659): Disconnected process message: 10
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 11
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5502): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5502): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 296, CUR = 450
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6659): Disconnected process message: 10
,D/BatteryService(  908): stay LED for fully charged
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 295, CUR = 450
,V/AlarmManager(  908): waitForAlarm result :8
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6659): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 294, CUR = 450
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6659): Disconnected process message: 10
,I/jxcore-log( 6557): Toggling radios to false
I/jxcore-log( 6557): 
,D/BluetoothAdapter( 6557): disable()
,D/SettingsProvider(  908): name = bluetooth_on
,D/BluetoothAdapterState( 6659): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 6659): Setting state to 13
I/BluetoothAdapterState( 6659): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 6659): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 6659): updateAdapterState state is 13
,I/BluetoothPbapService( 6659): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 6659): Autoconnection is available 
,D/BluetoothAdapterService( 6659): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 6659): terminating service from this receiver
,D/BluetoothSocket( 6659): close() in, this: android.bluetooth.BluetoothSocket@824acb9, channel: 19, state: LISTENING
,D/BluetoothSocket( 6659): close() this: android.bluetooth.BluetoothSocket@824acb9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1171ae81, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@345418femSocket: android.net.LocalSocket@39e0385f impl:android.net.LocalSocketImpl@2e1f22ac fd:FileDescriptor[72]
D/BluetoothSocket( 6659): Closing mSocket: android.net.LocalSocket@39e0385f impl:android.net.LocalSocketImpl@2e1f22ac fd:FileDescriptor[72]
,D/BluetoothAdapterProperties( 6659): onBluetoothDisable()
,D/SecContentProvider(  908): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 6659): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 6659): Scan Mode:20
,D/BluetoothAdapterState( 6659): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 6659): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 6659): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 6659): cmd socket is not created
,E/BtOppRfcommListener( 6659): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 6659): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/bt_vendor( 6659): op for 7
,E/bt-btm  ( 6659): btm_ble_start_auto_conn start : 0, 0
,D/bt_upio ( 6659): proc btwrite assertion
,W/bt-btif ( 6659): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 6659): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 6659): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6659): L2CAP - PSM: 0x001b not found for deregistration
D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
,D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
,D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
,D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
,D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
,D/bt_upio ( 6659): BT_WAKE is asserted already
W/InputMethodManagerService(  908): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  908): [BT Setting State] State =13
,D/BluetoothTile( 1185):  onBluetoothStateChange:
,D/bt_vendor( 6659): op for 7
,D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/BluetoothTile( 1185):  onBluetoothPairedDevicesChanged:
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/BluetoothTile( 1185):  handleUpdatestate:false name:null
D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
,D/bt_vendor( 6659): op for 7
,D/bt_upio ( 6659): BT_WAKE is asserted already
,D/BluetoothTile( 1185): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothManager( 6809): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothSocket( 6659): close() in, this: android.bluetooth.BluetoothSocket@254c70a, channel: 5, state: LISTENING
D/BluetoothTile( 1185):  handleUpdatestate:false name:null
D/BluetoothSocket( 6659): close() this: android.bluetooth.BluetoothSocket@254c70a, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@958cb26, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e79fb7bmSocket: android.net.LocalSocket@10b1bd98 impl:android.net.LocalSocketImpl@3f0239f1 fd:FileDescriptor[74]
D/BluetoothSocket( 6659): Closing mSocket: android.net.LocalSocket@10b1bd98 impl:android.net.LocalSocketImpl@3f0239f1 fd:FileDescriptor[74]
I/BtOppRfcommListener( 6659): stopping Accept Thread
D/BluetoothSocket( 6659): close() in, this: android.bluetooth.BluetoothSocket@30049d6, channel: 12, state: LISTENING
D/StatusBarManagerService(  908): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
D/BluetoothSocket( 6659): close() this: android.bluetooth.BluetoothSocket@30049d6, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d2e9e80, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@f22d457mSocket: android.net.LocalSocket@20d11b44 impl:android.net.LocalSocketImpl@9ef842d fd:FileDescriptor[78]
D/BluetoothSocket( 6659): Closing mSocket: android.net.LocalSocket@20d11b44 impl:android.net.LocalSocketImpl@9ef842d fd:FileDescriptor[78]
I/BtOppRfcommListener( 6659): BluetoothSocket listen thread finished
,D/STATUSBAR-QSTileView( 1185): onStateChanged: Bluetooth
D/StatusBarManagerService(  908): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1185): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
I/WifiManager( 6557): packageName : com.test.thalitest
,D/SecContentProvider(  908): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  908): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  908): mCursor = null
,I/SamsungIME( 1718): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/WifiService(  908): setWifiEnabled: false pid=6557, uid=10276
D/SettingsProvider(  908): name = wifi_on
,D/BluetoothPbap( 1311): Proxy object disconnected
,D/PbapServerProfile( 1311): Bluetooth service disconnected
V/BluetoothEventManager( 1311): Received android.bluetooth.adapter.action.STATE_CHANGED
,I/jxcore-log( 6557): Radios toggled
I/jxcore-log( 6557): 
,E/WifiStateMachine(  908): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 6665): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6665): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 6665): P2P: Current p2p state = IDLE
,E/WifiConfigStore(  908): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/wpa_supplicant( 6665): Scan requested (ret=0) - scan timeout 30 seconds
,W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/native  (  908): do suspend true
,D/WifiP2pService(  908): InactiveState{ what=143375 }
,D/WifiP2pService(  908): P2pEnabledState{ what=143375 }
,D/DockEventReceiver( 1311): finishStartingService: stopping service
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,D/BluetoothNotiBroadcastReceiver( 1311): onReceive
,D/AuthorizationBluetoothService( 1471): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/NativeCrypto( 1471): Read error: ssl=0xaf21be00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1471): SSL shutdown failed: ssl=0xaf21be00: I/O error during system call, Broken pipe
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  908): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/qtaguid (  908): Tagging socket 419 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 908, getuid(): 1000
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
D/NetUtils(  908): android_net_utils_resetConnections in env=0xa939d320 clazz=0x9b05e98c iface=wlan0 mask=0x3
D/ConnectivityService(  908): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  908): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/System.out(  908): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
,I/WifiTrafficPoller(  908): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Validated
,D/WifiP2pService(  908): InactiveState{ what=131204 }
,D/WifiP2pService(  908): P2pEnabledState{ what=131204 }
D/WifiScanningService(  908): SCAN_AVAILABLE : 1
D/RttService(  908): SCAN_AVAILABLE : 1
D/WifiScanningService(  908): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  908): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  908): sending p2p connection changed broadcast: FAILED
,D/WifiDisplayController(  908): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  908): onP2pDisconnected
D/IpRemoteDisplayController(  908): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  908): WfdBridgeServer is already null
,D/WifiNetworkAgent(  908): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  908): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService(  908): sending p2p connection changed broadcast: DISCONNECTED
,D/WifiDisplayController(  908): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  908): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  908): disconnect
D/WifiDisplayController(  908): updateConnection
,D/WifiDisplayController(  908): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  908): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  908): onP2pDisconnected
D/WifiP2pService(  908): P2pDisablingState
D/IpRemoteDisplayController(  908): disconnectWfdBridgeServer
D/WifiP2pService(  908): P2pDisablingState{ what=147458 }
,D/IpRemoteDisplayController(  908): WfdBridgeServer is already null
D/WifiP2pService(  908): p2p socket connection lost
D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService(  908): P2pDisabledState
,D/AllShareCastTile( 1185): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1185): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,E/native  (  908): do suspend true
,I/Hs20UtilService( 1311): Starting #6
D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/Hs20UtilService( 1311): Message received 5007
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6207): NETWORK_STATE_CHANGED_ACTION
,W/bt-l2cap( 6659): HC lib lpm enable=0 return 0
D/bt_vendor( 6659): op for 6
W/bt-l2cap( 6659): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6659): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6659): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 6659): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 6659): RX termination
,W/bt-l2cap( 6659): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6659): L2CAP - PSM: 0x0019 not found for deregistration
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/bt-l2cap( 6659): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6659): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 6659): ag scb idx 1 not allocated
W/bt-btif ( 6659): ag scb idx 2 not allocated
E/bt-btif ( 6659): BTA AG is already disabled, ignoring ...
D/bt_vendor( 6659): op for 7
D/bt_upio ( 6659): BT_WAKE is asserted already
D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
W/bt_userial( 6659): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 6659): Leaving userial_read_thread()
D/bt_userial( 6659): userial_close_reader Joined userial reader thread: 0
D/bt_vendor( 6659): op for 9
D/bt_hwcfg( 6659): hw_epilog_process
D/bt_vendor( 6659): op for 4
I/bt_userial_vendor( 6659): device fd = 65 close
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
D/WifiP2pService(  908): P2pDisabledState{ what=143375 }
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
D/WifiP2pService(  908): DefaultState{ what=143375 }
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
D/bt_vendor( 6659): op for 0
D/bt_upio ( 6659): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6659): is_emulator_context : 0
D/bt_upio ( 6659): is_rfkill_disabled ? [0]
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
D/bt_vendor( 6659): cleanup
,I/GKI_LINUX( 6659): gki_task task_id=0 [BTU] terminating
,I/WifiTrafficPoller(  908): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
I/wpa_supplicant( 6665): p2p0: State: DISCONNECTED -> DISCONNECTED
,I/GKI_LINUX( 6659): GKI_exit_task 0 done
,I/GKI_LINUX( 6659): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 6659): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 6659): isSecureModeOn:false
D/BluetoothAdapterService( 6659): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 6659): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.gatt.GattService
,D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1185): Wifi onReceive(0)
D/STATUSBAR-QSTileView( 1185): onStateChanged: Wi-Fi
,D/HotspotTile( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1185): onReceive : 0, 0
,D/SmartBondingService(  908): getNetworkEnabled : wifi : false mobile : true
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 6659): handleDebugAction() action=null
,W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.hfp.HeadsetService
D/FileShare-Server( 6378): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/BtGatt.GattService( 6659): Received stop request...Stopping profile...
D/BtGatt.GattService( 6659): stop()
D/BtGatt.AdvertiseManager( 6659): advertise clients cleared
,D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  908): mCursor = null
,D/WifiCredService( 1311): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/WifiDirectBR( 6777): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDirectBR( 6777): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
W/BluetoothAdapterService( 6659): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.a2dp.A2dpService
W/ContextImpl( 6777): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/WifiDirectBR( 6777): stopServiceTest : false
,W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.hid.HidService
D/HeadsetService( 6659): Received stop request...Stopping profile...
,D/WifiDirectBR( 6777): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.hdp.HealthService
,D/AudioService(  908): onServiceDisconnected: Bluetooth profile: 1
,D/HeadsetProfile( 1311): Bluetooth service disconnected
W/BluetoothAdapterService( 6659): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.pan.PanService
W/BluetoothHeadset( 6809): Proxy not attached to service
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6659): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 6659): Not skipping com.broadcom.bt.service.sap.SapService
,I/wpa_supplicant( 6665): Blacklist: Clear (all) 
,E/SMD     (  289): DCD ON
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6659): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 6659): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6659): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6659): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6659): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6659): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 6659): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 6659): Stopping profile services that were post enabled
E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/A2dpService( 6659): Received stop request...Stopping profile...
,V/Avrcp   ( 6659): doQuit
,D/A2dpStateMachine( 6659): Exit Disconnected: -1
D/Avrcp   ( 6659): Unregistering previous receiver
,I/Hs20UtilService( 1311): Starting #7
D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,D/BluetoothA2dp( 2955): Proxy object disconnected
D/BluetoothA2dp(  908): Proxy object disconnected
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AudioService(  908): onServiceDisconnected: Bluetooth profile: 2
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/HidService( 6659): Received stop request...Stopping profile...
D/HidService( 6659): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 6659): Cleaning up Bluetooth HID Interface...
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
W/bt-btif ( 6659): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 6659): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,I/Hs20UtilService( 1311): Message received 5007
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 6659): Profile still running: com.android.bluetooth.hid.HidService
V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,D/BluetoothA2dp( 1311): Proxy object disconnected
D/A2dpProfile( 1311): Bluetooth service disconnected
D/BluetoothInputDevice( 1311): Proxy object disconnected
D/HidProfile( 1311): Bluetooth service disconnected
,W/BluetoothHeadsetServiceJni( 6659): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 6659): Cleaning up Bluetooth Handsfree callback object
I/wpa_supplicant( 6665): p2p0: CTRL-EVENT-TERMINATING 
,D/HealthService( 6659): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,D/PanService( 6659): Received stop request...Stopping profile...
I/wpa_supplicant( 6665): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
,D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
I/wpa_supplicant( 6665): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 6665): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 6665): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/BluetoothPan(  908): BluetoothPAN Proxy object disconnected
,D/BluetoothPan( 1311): BluetoothPAN Proxy object disconnected
D/PanProfile( 1311): Bluetooth service disconnected
,D/BluetoothMapService( 6659): Received stop request...Stopping profile...
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6207): NETWORK_STATE_CHANGED_ACTION
,D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,D/SapService( 6659): Received stop request...Stopping profile...
,D/SapService( 6659): Stopping Bluetooth SapService
D/BluetoothAdapterService( 6659): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36f5549f
,E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService( 6659): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 6659): Proxy object disconnected
D/BluetoothAdapterService( 6659): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 6659): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 6659): GKI_exit_task 2 done
I/GKI_LINUX( 6659): GKI_shutdown(): task [A2DP-MEDIA] terminated
,V/Avrcp   ( 6659): cleanup
E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 6659): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 6659): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 6659): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6659): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 6659): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothPanServiceJni( 6659): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6659): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothMap( 1311): Proxy object disconnected
D/MapProfile( 1311): Bluetooth service disconnected
,D/Bluetoothsap( 1311): BluetoothSAP Proxy object disconnected
D/BtSettings.ProfileConfig( 6659): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 6659): Profile still running: com.broadcom.bt.service.sap.SapService
D/SapProfile( 1311): Bluetooth service disconnected
E/BluetoothAdapterService(922047647)( 6659): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 6659): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6659): Setting state to 10
I/BluetoothAdapterState( 6659): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 6659): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6659): updateAdapterState state is 10
,D/BluetoothAdapterService( 6659): Autoconnection is available 
D/BluetoothAdapterService( 6659): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 6659): Entering OffState
W/BluetoothSAPServiceJni( 6659): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 6659): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothMap( 1311): onBluetoothStateChange: up=false
D/Bluetoothsap( 1311): onBluetoothStateChange: up=false
D/Bluetoothsap( 1311): Unbinding service...
,D/BluetoothA2dp( 2955): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 6659): onBluetoothStateChange: up=false
,E/SignOutReceiver( 6207): WIFI_STATE_CHANGED_ACTION
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6633): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6633): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6633): StateMachine : Current State = 1
D/SecurityLogAgent( 6633): StateMachine : Changed Current State = 1
,I/wpa_supplicant( 6665): Blacklist: Clear (all) 
,D/ConnectivityService(  908): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  908): calling update connectivity
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  908): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524292
D/ConnectivityService(  908): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/Nat464Xlat(  908): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  908): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  908): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Disconnected - quitting
D/TelephonyNetworkFactory( 1424): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  908): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  908): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  908): MasterInitialState.processMessage what=3
D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkStats(  908): updateIfacesLocked()
V/NetworkStats(  908): performPollLocked(flags=0x1)
,D/SmartBondingService(  908): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/NetworkStatsFactory(  908): UpdateStatsForKnox
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  908): getSBEnabled() enabled =false
D/NtpTrustedTime(  908): forceRefresh() from cache miss
D/SmartBondingService(  908): getSBEnabled() enabled =false
,D/BluetoothInputDevice( 1311): onBluetoothStateChange: up=false
D/ConnectivityManager.CallbackHandler( 1747): CM callback handler got msg 524292
,D/BluetoothA2dp( 1311): onBluetoothStateChange: up=false
,V/NetworkStats(  908): performPollLocked() took 3ms
,D/BluetoothPbap( 1311): onBluetoothStateChange: up=false
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BluetoothA2dp(  908): onBluetoothStateChange: up=false
,D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1185): updateDataNetType()
D/NtpTrustedTime(  908): forceRefresh Fail.
D/StatusBar.NetworkController( 1185): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1185): updateLTEICONDataNetType:0
,E/ConnectivityService(  908): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,D/SmartBondingService(  908): getNetworkEnabled : wifi : false mobile : true
,D/BluetoothManagerService(  908): Broadcasting onBluetoothServiceDown() to 12 receivers.
,D/StatusBar.NetworkController( 1185): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/NtpTrustedTime(  908): forceRefresh() from cache miss
,D/NtpTrustedTime(  908): forceRefresh Fail.
V/NetworkStats(  908): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/BluetoothManagerService(  908): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/EntConnectivity(  908): Not allowed due to - mEnabled false
,W/InputMethodManagerService(  908): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  908): [BT Setting State] State =10
I/InputMethodManagerService(  908): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapter( 1185): 444630444: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1185):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 1185): 444630444: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 6659): gki_task task_id=1 [BTIF] terminating
,D/BluetoothManager( 6809): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1185): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 1185): 444630444: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1185): 444630444: getState() :  mService = null. Returning STATE_OFF
I/SamsungIME( 1718): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothAdapter( 1185): 444630444: getState() :  mService = null. Returning STATE_OFF
,D/STATUSBAR-QSTileView( 1185): onStateChanged: Bluetooth
V/BluetoothEventManager( 1311): Received android.bluetooth.adapter.action.STATE_CHANGED
D/StatusBarManagerService(  908): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
D/StatusBarManagerService(  908): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1185): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
D/PhoneStatusBar( 1185): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
I/GKI_LINUX( 6659): GKI_exit_task 1 done
I/GKI_LINUX( 6659): GKI_shutdown(): task [BTIF] terminated
,W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/BluetoothServiceJni( 6659): cleanupNative: return from cleanup
,D/BluetoothAdapter( 1471): 856422651: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1471): 856422651: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 6659): System.exit called, status: 0
,I/AndroidRuntime( 6659): VM exiting with result code 0, cleanup skipped.
,D/DockEventReceiver( 1311): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1311): onReceive
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1424): FileWriteThread : threadType = 3
,I/ActivityManager(  908): Process com.android.bluetooth (pid 6659)(adj 0) has died(271,1468)
,D/AuthorizationBluetoothService( 1471): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 6665): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  908): InitialState.processMessage what=4
E/Tethering(  908): No numeric data
D/Tethering(  908): sendTetherStateChangedBroadcast 0, 0, 0
D/NtpTrustedTime(  908): forceRefresh() from cache miss
D/HotspotTile( 1185): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1185): updateTetherState():false, false
,D/NtpTrustedTime(  908): forceRefresh Fail.
,V/NetworkStats(  908): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  908): UpdateStatsForKnox
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  908): performPollLocked() took 4ms
,D/NtpTrustedTime(  908): forceRefresh() from cache miss
,D/NtpTrustedTime(  908): forceRefresh Fail.
,E/WifiStateMachine(  908): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-HAL(  908): callSECApiBoolean - ID [21]
,D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1185): Wifi onReceive(1)
D/SmartBondingService(  908): getNetworkEnabled : wifi : false mobile : true
W/Settings( 1471): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiCredService( 1311): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1185): onStateChanged: Wi-Fi
D/HotspotTile( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1185): onReceive : 1, 0
,E/SignOutReceiver( 6207): WIFI_STATE_CHANGED_ACTION
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6633): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6633): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6633): StateMachine : Current State = 1
D/SecurityLogAgent( 6633): StateMachine : Changed Current State = 1
,E/WifiStateMachine(  908): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  908): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ApplicationPolicy(  908): updateDataUsageMap
,D/SmartBondingService(  908): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  908): getSBEnabled() enabled =false
,D/SmartBondingService(  908): getSBEnabled() enabled =false
D/SmartBondingService(  908): getSBEnabled() enabled =false
,D/SmartBondingService(  908): getNetworkEnabled : wifi : false mobile : true
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 5957): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5957): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5957): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5957): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5957): noConnectivity : true
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3169): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/NetworkMonitor( 5118): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3169): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/DIAGMON_AGENT( 6925): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6925): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 6974): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6974): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6974): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 6995): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6995): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449683892967
,I/KLMS-2.4.511: ( 6995): MainReciver(): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6995): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.511: ( 6995): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7037): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7089): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7107): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 7107): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 7107): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7107): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7107): [OR] == isSIMCardReady false ==
,I/SA      ( 7107): [SCU] == networkStateCheck == false
I/SA      ( 7107): [OR] onReceive END
,E/SPPClientService( 7089): [[SystemStateMonitorService]] No Active Internet
,I/SCloudBackupReceiver( 7129): Other Intent
,I/KnoxUsageLogPro( 6393): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 6393): premStatus:2
,I/KnoxUsageLogPro( 6393): isEulaShown : false
I/KnoxUsageLogPro( 6393): KnoxUsageReceiver onReceive : not Processible, just return
,D/QuickConnect( 7201): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7201): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7201): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6633): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6633): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6633): StateMachine : Current State = 1
D/SecurityLogAgent( 6633): StateMachine : Changed Current State = 1
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.Environment( 1747): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1747): num queued entries: 0
,I/iu.UploadsManager( 1747): num updated entries: 0
,I/iu.SyncManager( 1747): NEXT; no task
,V/AlarmManager(  908): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog(  908): !@Sync 12
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 294, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/PowerManagerService(  908): [PWL] Off : 275s ago
,I/PowerManagerService(  908): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  908): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  908): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=908, ws=null) (elapsedTime=10448)
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 13
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 292, CUR = 450
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 291, CUR = 450
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  908): Failed to find a new network - expiring NetTransition Wakelock
,E/Watchdog(  908): !@Sync 14
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  356): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  356): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  908): [PWL] Off : 330s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 15
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/bootchecker(  341): bootchecker wake up!!
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 16
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 390s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 17
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 18
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  356): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  356): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  908): [PWL] Off : 455s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Daemon(  356): Stop the daemon....
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 19
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 287, CUR = 450
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 287, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 287, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  908): [PWL] Off : 525s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 286, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 21
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 284, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 283, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 22
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 282, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 282, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 23
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 600s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  908): !@Sync 24
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  908): !@Sync 25
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 680s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  908): !@Sync 26
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,V/AlarmManager(  908): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/LightsService(  908): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  908): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  908): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  908): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  908): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  908): unregisterListener ::   
,D/LightsService(  908): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  908): !@Sync 27
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  908): !@Sync 28
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  908): [PWL] Off : 765s ago
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,E/Watchdog(  908): !@Sync 29
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  908): !@Sync 30
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  908): !@Sync 31
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  908): [PWL] Off : 855s ago
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  908): !@Sync 32
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 33
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  908): !@Sync 34
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 950s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  908): !@Sync 35
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  908): !@Sync 36
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  908): !@Sync 37
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  908): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  908): !@Sync 38
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 1050s ago
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  908): !@Sync 39
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  908): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  908): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  908): Updating Usage Statistics in DB @ 1449684731640
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  908): Done Updating Usage Statistics in DB @ 1449684731825
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  908): !@Sync 40
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  908): !@Sync 41
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 1155s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  908): !@Sync 42
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 43
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 44
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 45
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 1265s ago
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 46
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 47
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 48
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 49
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 1380s ago
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  908): !@Sync 50
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 51
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 52
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 53
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 1500s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 54
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 55
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/Watchdog(  908): !@Sync 56
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  908): !@Sync 57
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  908): [PWL] Off : 1625s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  908): !@Sync 58
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  908): !@Sync 59
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/NetworkStatsFactory(  908): UpdateStatsForKnox
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  908): !@Sync 60
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  908): waitForAlarm result :4
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/LightsService(  908): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,E/LightSensor(  908): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  908): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,I/ProcessStatsService(  908): Prepared write state in 19ms
,I/ProcessStatsService(  908): Prepared write state in 9ms
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/NtpTrustedTime(  908): forceRefresh() from cache miss
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/NtpTrustedTime(  908): forceRefresh Fail.
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/NetworkStats(  908): performPollLocked(flags=0x3)
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/NetworkStatsFactory(  908): UpdateStatsForKnox
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  908): performPollLocked() took 11ms
,D/NtpTrustedTime(  908): forceRefresh() from cache miss
,D/NtpTrustedTime(  908): forceRefresh Fail.
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1747): Aggregate from 1449682882597 (log), 1449682882597 (data)
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1471): (HTTPLog)-Static: isSBSettingEnabled false
,E/Auth    ( 1471): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2: email
,D/LightsService(  908): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  908): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  908): unregisterListener ::   
,D/LightsService(  908): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/art     ( 1747): Explicit concurrent mark sweep GC freed 21739(1515KB) AllocSpace objects, 27(432KB) LOS objects, 25% free, 22MB/30MB, paused 872us total 79.263ms
,I/art     ( 1747): WaitForGcToComplete blocked for 79.935ms for cause Explicit
,I/art     ( 1747): Explicit concurrent mark sweep GC freed 535(24KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 22MB/30MB, paused 844us total 58.161ms
,V/AlarmManager(  908):  next == MAX_VALUE
,I/ProcessStatsService(  908): Pruning old procstats: /data/system/procstats/state-2015-12-09-06-35-27.bin
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  908): !@Sync 61
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 1755s ago
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  908): !@Sync 62
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  908): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  908): !@Sync 63
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/Watchdog(  908): !@Sync 64
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,E/Watchdog(  908): !@Sync 65
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7659): 
D/AndroidRuntime( 7659): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7659): CheckJNI is OFF
D/AndroidRuntime( 7659): readGMSProperty: start
D/AndroidRuntime( 7659): readGMSProperty: already setted!!
D/AndroidRuntime( 7659): readGMSProperty: end
D/AndroidRuntime( 7659): addProductProperty: start
E/AffinityControl( 7659): AffinityControl: registerfunction enter
D/AndroidRuntime( 7659): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService(  908): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  908): START PACKAGE DELETE: observer{424658071}
D/PackageManager(  908): pkg{<packageName>}
D/PackageManager(  908): user{0}
D/PackageManager(  908): caller{2000}
D/PackageManager(  908): flags{3}
D/PersonaManagerService(  908): isFromApprovedUnInstaller: isApproved : true
D/PackageManager(  908): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService(  908): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  908): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  908): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  908): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  908): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  908): getApplicationUninstallationEnabled
D/PackageManager(  908): !@killApplicatoin: 10276, uninstall pkg
D/ApplicationPolicy(  908): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10276 user=-1: uninstall pkg
I/ActivityManager(  908): Killing 6557:com.test.thalitest/u0a276 (adj 0): stop com.test.thalitest
W/PackageSettings(  908): Skipping PackageSetting{3663da6b com.example.hello/10268} due to missing metadata
D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
I/WindowState(  908): WIN DEATH: Window{2f6b6296 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  254): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  908): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  908): setMouseCustomIcon IconType is same.101
D/PointerIcon(  908): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  908): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  908): Killing 7333:com.android.calendar/u0a172 (adj 13): empty for 1806s
E/SMD     (  289): DCD ON
I/ActivityManager(  908): Killing 7303:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 13): empty for 1806s
I/ActivityManager(  908): Killing 7261:com.android.providers.calendar/u0a51 (adj 13): empty for 1808s
I/ActivityManager(  908): Killing 5210:com.sec.android.gallery3d/u0a53 (adj 13): empty for 1816s
I/ActivityManager(  908): Killing 6083:com.sec.android.provider.badge/u0a92 (adj 13): empty for 1822s
I/ActivityManager(  908): Killing 5682:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 13): empty for 1876s
I/ActivityManager(  908): Killing 6301:com.sec.android.widgetapp.dualclockdigital/u0a115 (adj 15): empty for 1880s
I/ActivityManager(  908): Killing 6286:com.sec.android.widgetapp.digitalclock/u0a109 (adj 15): empty for 1880s
I/ActivityManager(  908): Killing 6058:com.android.mms/u0a55 (adj 15): empty for 1880s
D/CountryDetector(  908): No listener is left
I/ActivityManager(  908): Killing 5502:com.android.vending/u0a33 (adj 15): empty for 1884s
I/ActivityManager(  908): Killing 6410:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty for 1885s
I/ActivityManager(  908):   Force finishing activity ActivityRecord{15c43410 u0 com.test.thalitest/.MainActivity t3}
D/FocusedStackFrame(  908): Set to : 0
W/ActivityManager(  908): Spurious death for ProcessRecord{38a6e684 6557:com.test.thalitest/u0a276}, curProc for 6557: null
W/libprocessgroup(  908): failed to open /acct/uid_10172/pid_7333/cgroup.procs: No such file or directory
W/libprocessgroup(  908): failed to open /acct/uid_10171/pid_7303/cgroup.procs: No such file or directory
W/libprocessgroup(  908): failed to open /acct/uid_10051/pid_7261/cgroup.procs: No such file or directory
W/libprocessgroup(  908): failed to open /acct/uid_10053/pid_5210/cgroup.procs: No such file or directory
W/libprocessgroup(  908): failed to open /acct/uid_10092/pid_6083/cgroup.procs: No such file or directory
W/libprocessgroup(  908): failed to open /acct/uid_10182/pid_5682/cgroup.procs: No such file or directory
W/libprocessgroup(  908): failed to open /acct/uid_10115/pid_6301/cgroup.procs: No such file or directory
W/libprocessgroup(  908): failed to open /acct/uid_10109/pid_6286/cgroup.procs: No such file or directory
W/libprocessgroup(  908): failed to open /acct/uid_10055/pid_6058/cgroup.procs: No such file or directory
W/libprocessgroup(  908): failed to open /acct/uid_10033/pid_5502/cgroup.procs: No such file or directory
W/libprocessgroup(  908): failed to open /acct/uid_1000/pid_6410/cgroup.procs: No such file or directory
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10276 user=0: pkg removed
I/art     ( 1595): Explicit concurrent mark sweep GC freed 691(40KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 18MB/31MB, paused 421us total 26.626ms
I/art     ( 5172): Explicit concurrent mark sweep GC freed 33542(1875KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 15MB/26MB, paused 434us total 31.935ms
I/art     ( 6207): Explicit concurrent mark sweep GC freed 8419(503KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 16MB/21MB, paused 343us total 47.555ms
I/art     ( 1747): Explicit concurrent mark sweep GC freed 150(5KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 22MB/30MB, paused 1.266ms total 76.006ms
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
W/GeofencerStateMachine( 1471): Ignoring removeGeofence because network location is disabled.
I/InputReader(  908): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1718): mOCRHelper is null
I/KLMS-2.4.511: ( 6995): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 6995): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449685504447
I/KLMS-2.4.511: ( 6995): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6995): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
I/art     (  908): Explicit concurrent mark sweep GC freed 19174(1827KB) AllocSpace objects, 19(304KB) LOS objects, 17% free, 37MB/45MB, paused 1.922ms total 150.608ms
D/ResourcesManager(  908): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  908): WaitForGcToComplete blocked for 80.660ms for cause Explicit
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/RegisteredServicesCache( 1412): empty dynamic service
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/SecContentProvider2(  908): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  908): mCursor = null
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/Zygote  ( 7697): MountEmulatedStorage()
E/Zygote  ( 7697): v2
I/libpersona( 7697): KNOX_SDCARD checking this for 10116
I/libpersona( 7697): KNOX_SDCARD not a persona
I/ActivityManager(  908): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7697 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 7697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/RCPManagerService(  908): PackageReceiver onReceive()
I/HarmonyEASService(  908): onReceive : android.intent.action.PACKAGE_REMOVED for 0
E/SELinux ( 7697): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/KnoxMUMContainerPolicy(  908): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  908): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  908): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  908): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  908): uID is 10276
V/EnterpriseBillingPolicy(  908): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  908): getProfileForApplication - enter
I/art     (  908): Explicit concurrent mark sweep GC freed 10678(495KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 37MB/45MB, paused 1.646ms total 250.253ms
V/EnterpriseBillingPolicyStorage(  908): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  908): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  908): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  908): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  908): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  908): removeObsoleteFile: deleting file=3_task.xml
D/TimaKeyStoreProvider( 7697): TimaSignature is unavailable
D/ActivityThread( 7697): Added TimaKeyStore provider
D/ResourcesManager( 7697): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/SurfaceWidgetView( 1448): destroyHardwareResources():467340676
V/WindowOrientationListener(  908): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  908): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  908): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  908): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  908): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/Launcher( 1448): onRestart, Launcher: 1063558075
D/Launcher( 1448): onStart, Launcher: 1063558075
D/Launcher.HomeView( 1448): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1765): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1765): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1765): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
V/ActivityThread( 1448): updateVisibility : ActivityRecord{30332c35 token=android.os.BinderProxy@170def56 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/elm:14491( 7697): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 7697): ELMEngine.ELMEngine( context ).
D/elm:14491( 7697): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/elm:14491( 7697): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/SurfaceFlinger(  254): id=15 createSurf (1080x1920),1 flag=4, Mauncher
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/elm:14491( 7697): ElmAgentService : onCreate()
D/elm:14491( 7697): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 7697): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7697): MDMBridge.getInstance()
D/elm:14491( 7697): MDMBridge.getAllLicenseInfoFromSDK()
D/PointerIcon(  908): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  908): setMouseCustomIcon IconType is same.101
D/PointerIcon(  908): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  908): setHoveringSpenCustomIcon IconType is same.1
D/elm:14491( 7697): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/InputMethodManagerService(  908): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 6557 uid 10276
E/Zygote  ( 7717): MountEmulatedStorage()
E/Zygote  ( 7717): v2
I/libpersona( 7717): KNOX_SDCARD checking this for 10021
I/libpersona( 7717): KNOX_SDCARD not a persona
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  908): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7717 uid=10021 gids={50021, 9997} abi=armeabi-v7a
D/PackageManager(  908): delete codoeFile: 
I/AASAUninstall(  908):  com.test.thalitest not target!
D/PackageManager(  908): result of delete: 1{424658071}
I/SELinux ( 7717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/elm:14491( 7697): ElmAgentService : onDestroy().
D/AndroidRuntime( 7659): Shutting down VM
I/SELinux ( 7717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7717): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/EnterpriseDeviceManagerService(  908): Package has changed for user 0
D/EnterpriseDeviceManagerService(  908): Admin package name: com.google.android.gms
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
I/Timeline(  908): Timeline: Activity_windows_visible id: ActivityRecord{2fde6fa7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1987081
D/TimaKeyStoreProvider( 7717): TimaSignature is unavailable
D/ActivityThread( 7717): Added TimaKeyStore provider
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 7717): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7717): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7717): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7717): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/Zygote  ( 7734): MountEmulatedStorage()
E/Zygote  ( 7734): v2
I/libpersona( 7734): KNOX_SDCARD checking this for 10025
I/libpersona( 7734): KNOX_SDCARD not a persona
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Maps/Maps.apk
I/ActivityManager(  908): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=7734 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/SELinux ( 7734): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/SELinux ( 7734): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
E/SELinux ( 7734): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager(  908): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  908): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  908): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
D/TimaKeyStoreProvider( 7734): TimaSignature is unavailable
D/ActivityThread( 7734): Added TimaKeyStore provider
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/ResourcesManager( 7734): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/ResourcesManager( 7734): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  908): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  908): onPackageRemoved : com.test.thalitest
W/linker  ( 7734): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/MVFD_interface( 7734): <<<  caMVFace_FaceInit
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7734): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7734): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
D/HockeyApp( 7734): Current handler class = sstream.app.util.Log$1
I/EventHub(  908): Removing device '/dev/input/event6' due to inotify event
E/SQLiteLog( 7734): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 7734): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 7734): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 7734): (14) os_unix.c:32503: (2) open(/data/data/sstream.app/databases/sstream.db) - 
E/SQLiteDatabase( 7734): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 7734): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 7734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7734): 	at sstream.app.provider.StoryProvider.delete(StoryProvider.java:90)
E/SQLiteDatabase( 7734): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:314)
E/SQLiteDatabase( 7734): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/SQLiteDatabase( 7734): 	at sstream.app.provider.DatabaseUtil.deleteConfigSettingForApp(DatabaseUtil.java:985)
E/SQLiteDatabase( 7734): 	at sstream.app.receiver.ApplicationCompatibleReceiver.onReceive(ApplicationCompatibleReceiver.java:216)
E/SQLiteDatabase( 7734): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 7734): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 7734): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 7734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7734): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7734): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 7734): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7734): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7734): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 7734): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
I/PCWCLIENTTRACE_PushUtil( 5957): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5957): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5957): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5957): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 7734): Shutting down VM
I/EventHub(  908): Removing device '/dev/input/event7' due to inotify event
I/ActivityManager(  908): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7774 uid=10039 gids={50039, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/Zygote  ( 7774): MountEmulatedStorage()
E/Zygote  ( 7774): v2
I/libpersona( 7774): KNOX_SDCARD checking this for 10039
I/libpersona( 7774): KNOX_SDCARD not a persona
D/HockeyApp( 7734): Writing unhandled exception to: /data/data/sstream.app/files/7b798b69-f1aa-421e-9428-91daf23a34ca.stacktrace
E/HockeyApp( 7734): Error saving exception stacktrace!
E/HockeyApp( 7734): 
E/HockeyApp( 7734): java.io.FileNotFoundException: /data/data/sstream.app/files/7b798b69-f1aa-421e-9428-91daf23a34ca.stacktrace: open failed: ENOENT (No such file or directory)
E/HockeyApp( 7734): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/HockeyApp( 7734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/HockeyApp( 7734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/HockeyApp( 7734): 	at java.io.FileWriter.<init>(FileWriter.java:80)
E/HockeyApp( 7734): 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
E/HockeyApp( 7734): 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
E/HockeyApp( 7734): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/HockeyApp( 7734): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/HockeyApp( 7734): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
E/HockeyApp( 7734): 	at libcore.io.Posix.open(Native Method)
E/HockeyApp( 7734): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/HockeyApp( 7734): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/HockeyApp( 7734): 	... 7 more
I/EventHub(  908): Removing device '/dev/input/event8' due to inotify event
I/SELinux ( 7774): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
D/ResourcesManager( 7734): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
E/SELinux ( 7774): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/EventHub(  908): Removing device '/dev/input/event9' due to inotify event
D/TimaKeyStoreProvider( 7774): TimaSignature is unavailable
D/ActivityThread( 7774): Added TimaKeyStore provider
W/ResourcesManager( 7734): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SQLiteLog( 7734): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 7734): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 7734): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 7734): (14) os_unix.c:32503: (2) open(/data/data/sstream.app/databases/sstream.db) - 

```
