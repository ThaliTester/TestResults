#### Test 56672827b6f75d5_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3521): !@Sync 4
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 273, CUR = 22
--------- beginning of main
D/AndroidRuntime(10453): 
D/AndroidRuntime(10453): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10453): CheckJNI is OFF
D/AndroidRuntime(10453): readGMSProperty: start
D/AndroidRuntime(10453): readGMSProperty: already setted!!
D/AndroidRuntime(10453): readGMSProperty: end
D/AndroidRuntime(10453): addProductProperty: start
D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/AffinityControl(10453): AffinityControl: registerfunction enter
D/AndroidRuntime(10453): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3521): inState():  stateMachine is null !!
I/PersonaManagerService( 3521): PersonaId don't exist
I/ActivityManager( 3521): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3521): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3521): mDVFSHelper.acquire()
D/FocusedStackFrame( 3521): Set to : 0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (10472): MountEmulatedStorage()
I/libpersona(10472): KNOX_SDCARD checking this for 10595
E/Zygote  (10472): v2
I/libpersona(10472): KNOX_SDCARD not a persona
I/SELinux (10472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=10472 uid=10595 gids={50595, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (10472): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10453): Shutting down VM
D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(10472): TimaSignature is unavailable
D/ActivityThread(10472): Added TimaKeyStore provider
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3521): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(10472): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2850): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2850): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 3997): updateVisibility : ActivityRecord{36b400f4 token=android.os.BinderProxy@363fda66 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3997): onTrimMemory. Level: 20
I/WebViewFactory(10472): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10472): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10472): Loading: webviewchromium
I/LibraryLoader(10472): Time to load native libraries: 3 ms (timestamps 4620-4623)
I/LibraryLoader(10472): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10472): Binding Chromium to main looper Looper (main, tid 1) {3cd72d3f}
,I/LibraryLoader(10472): Expected native library version number "",actual native library version number ""
,I/chromium(10472): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10472): Initializing chromium process, renderers=0
,W/art     (10472): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10472): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10472): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10472): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10472): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter(10472): 891397644: getState() :  mService = null. Returning STATE_OFF
,W/chromium(10472): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10472): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10472): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10472): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(10472): CordovaWebView is running on device made by: samsung
,W/art     (10472): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10472): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(10472): performCreate Call secproduct feature valuefalse
D/Activity(10472): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(10472): Render dirty regions requested: true
,D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2850): id=12 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(10472): Initialized EGL, version 1.4
,I/OpenGLRenderer(10472): HWUI protection enabled for context ,  &this =0xaf545060 ,&mEglDisplay = 1 , &mEglConfig = -1279758064 
,D/OpenGLRenderer(10472): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
,D/OpenGLRenderer(10472): Enabling debug mode 0
,D/mali_winsys(10472): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(10472): updateVisibility : ActivityRecord{2a60aa3c token=android.os.BinderProxy@421aa12 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3521): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3521): mDVFSHelper.release()
I/Timeline( 3521): Timeline: Activity_windows_visible id: ActivityRecord{2ea1c4c0 u0 com.test.thalitest/.MainActivity t25} time:134981
,W/IInputConnectionWrapper(10472): showStatusIcon on inactive InputConnection
,I/Timeline(10472): Timeline: Activity_idle id: android.os.BinderProxy@421aa12 time:134985
,D/JsMessageQueue(10472): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(10472): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10472): 
,D/jxcore_app_log(10472): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358473472
,I/chromium(10472): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/jxcore-log(10472): Initializing JXcore engine
W/jxcore-log(10472): JXcore engine is ready
,E/auditd  ( 4545): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3521): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3521): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10472): Starting JXcore engine
,W/jxcore-log(10472): Platform android
W/jxcore-log(10472): 
W/jxcore-log(10472): Process ARCH arm
W/jxcore-log(10472): 
,I/jxcore-log(10472): JXcore Cordova bridge is ready!
I/jxcore-log(10472): 
W/jxcore-log(10472): JXcore engine is started
,I/jxcore-log(10472): Toggling radios to true
I/jxcore-log(10472): 
,D/BluetoothAdapter(10472): enable()
,W/ActivityManager( 3521): Permission Denial: getCurrentUser() from pid=10472, uid=10595 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 3521): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 3521): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10472, uid=10595 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 3521): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/BluetoothManagerService( 3521): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2160)
W/BluetoothManagerService( 3521): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService( 3521): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 3521): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService( 3521): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3521): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 3521): name = bluetooth_on
,E/DevicePolicyManagerService( 3521): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3521): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/WifiManager(10472): packageName : com.test.thalitest
,D/WifiService( 3521): New client listening to asynchronous messages
D/SecContentProvider( 3521): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3521): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3521): mCursor = null
,D/WifiService( 3521): setWifiEnabled: true pid=10472, uid=10595
E/WifiService( 3521): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3521): Permission Denial: getCurrentUser() from pid=10472, uid=10595 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3521): Failed getting userId using ActivityManagerNative
W/WifiService( 3521): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10472, uid=10595 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3521): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3521): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3521): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3521): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3521): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3521): name = wifi_on
,E/WifiStateMachine( 3521): setting operational mode to 1
,E/WifiHW  ( 3521): ##################### set firmware type 0 #####################
I/WifiService( 3521): disconnect: pid=10472, uid=10595
,I/WifiHW  ( 2846): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
I/jxcore-log(10472): Radios toggled
I/jxcore-log(10472): 
E/Zygote  (10543): MountEmulatedStorage()
I/libpersona(10543): KNOX_SDCARD checking this for 1002
E/Zygote  (10543): v2
I/libpersona(10543): KNOX_SDCARD not a persona
I/jxcore-log(10472): My device name is: samsung-SM-N910C
I/jxcore-log(10472): 
,I/WifiHW  ( 2846): module is murata
E/WifiHW  ( 2846): ==========[WIFI] MURATA MODULE ===========
I/WifiHW  ( 2846): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_murata
E/WifiHW  ( 2846): TEMP_FAILURE_RETRY complete
D/SoftapController( 2846): Softap fwReload - Ok
I/SELinux (10543): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10543): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10543): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=10543 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/CommandListener( 2846): Setting iface cfg
D/CommandListener( 2846): Trying to bring down wlan0
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/TimaKeyStoreProvider(10543): TimaSignature is unavailable
,D/ActivityThread(10543): Added TimaKeyStore provider
,D/ResourcesManager(10543): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(10543): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(10543): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni(10543): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig(10543): Adding GattService
,D/BtSettings.ProfileConfig(10543): Adding HeadsetService
D/BtSettings.ProfileConfig(10543): Adding A2dpService
D/BtSettings.ProfileConfig(10543): Adding HidService
D/BtSettings.ProfileConfig(10543): Adding HealthService
,D/BtSettings.ProfileConfig(10543): Adding PanService
D/BtSettings.ProfileConfig(10543): Adding BluetoothMapService
D/BtSettings.ProfileConfig(10543): Adding SapService
D/BtSettings.ProfileConfig(10543): Adding HeadsetClientService
D/BtSettings.ProfileConfig(10543): Adding A2dpSinkService
D/BtSettings.ProfileConfig(10543): Adding SapClientService
D/BtSettings.ProfileConfig(10543): Adding HidDevService
I/BtSettings.ProfileConfig(10543): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,E/WifiHW  ( 3521): supplicant_name : p2p_supplicant
D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3521): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterState(10543): make
,I/bluedroid(10543): init
I/BluetoothAdapterState(10543): Entering OffState
,I/bte_conf(10543): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf(10543): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config(10543): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf(10543): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,I/wpa_supplicant(10558): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant(10558): Successfully initialized wpa_supplicant
,I/SecureStorage(10558): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,E/bt-btif (10543): btif_fetch_local_ble_random_bdaddr
I/bluedroid(10543): get_profile_interface socket
I/bluedroid(10543): get_profile_interface map_client
,D/BluetoothAdapterService(10543): checkAddrForIOP: Loading from conf
,D/BluetoothAdapterService(10543): Inband Ring is supported
,I/GKI_LINUX(10543): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties(10543): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10543): populateRssiValuesNative
I/bluedroid(10543): getModelRssiValues
E/BluetoothServiceJni(10543): model_rssi_values_callback: low = -75, mid = -65, high = 127
I/SecureStorage(10558): [INFO]: SPID(0x00000000)This device supports Secure Storage
D/BluetoothAdapterProperties(10543): modelRssiValuesCallback, low, mid, high = -75,-65,127
,I/SecureStorage( 2919): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10558
I/SecureStorage( 2919): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
I/SecureStorage(10558): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant(10558): ssSupport state is = 1
D/BluetoothAdapterProperties(10543): Name is: Note4-1
I/wpa_supplicant(10558): >>>>> GET KEY, IV <<<<<
D/SettingsProvider( 3521): name = bluetooth_name
I/SecureStorage(10558): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage( 2919): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10558
I/SecureStorage( 2919): [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,I/bluedroid(10543): config_hci_snoop_log
,D/BluetoothManagerService( 3521): Broadcasting onBluetoothServiceUp() to 11 receivers.
E/WifiStateMachine( 3521): setWifiState: enabling
,E/WifiStateMachine( 3521): Supplicant start successful
D/WifiMonitor( 3521): startMonitoring(wlan0) with mConnected = false
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3521): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : false mobile : false
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=false enabledDesc:null
,D/HotspotTile( 3692): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3692): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 3692): onReceive : 2, 0
D/STATUSBAR-WifiQuickSettingButton( 3692): Wifi onReceive(2)
,E/DevicePolicyManagerService( 3521): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3521): getAllowBluetoothMode - value retunrs : 2
,I/Hs20UtilService( 6287): Starting #2
,I/Hs20UtilService( 6287): Message received 5011
D/STATUSBAR-QSTileView( 3692): onStateChanged: Wi-Fi
,D/SecContentProvider( 3521): uri = 3 selection = isBluetoothEnabled
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/BluetoothAdapterState(10543): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties(10543): Setting state to 11
I/BluetoothAdapterState(10543): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService(10543): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10543): updateAdapterState state is 11
D/BluetoothAdapterService(10543): Autoconnection is available 
D/BluetoothAdapterService(10543): updateAdapterState prevState = 10newState = 11
D/BluetoothSecureManager(10543): getInstant: null
D/BluetoothSecureManager(10543): calling getMethod for getService
D/BluetoothSecureManager(10543): calling getService
,D/BluetoothSecureManager(10543): getService return binder: android.os.BinderProxy@15a78537
,D/BluetoothSecureManagerService( 3521): isSecureModeEnabled
,D/BluetoothSecureManagerService( 3521): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode(10543): isSecureModeOn:false
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
I/libpersona(10564): KNOX_SDCARD checking this for 10127
E/Zygote  (10564): MountEmulatedStorage()
I/libpersona(10564): KNOX_SDCARD not a persona
E/Zygote  (10564): v2
I/SELinux (10564): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/BluetoothAdapterService(10543): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10543): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10543): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/SELinux (10564): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/BluetoothAdapterService(10543): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
I/ActivityManager( 3521): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=10564 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
E/SELinux (10564): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BluetoothAdapterService(10543): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10543): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10543): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10543): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10543): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10543): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10543): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService(10543): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine(10543): make
I/BluetoothBondStateMachine(10543): StableState(): Entering Off State
W/BluetoothAdapterService(10543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.gatt.GattService
W/InputMethodManagerService( 3521): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3521): [BT Setting State] State =11
D/BluetoothTile( 3692): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 3692):  onBluetoothPairedDevicesChanged:
,D/STATUSBAR-QSTileView( 3692): onStateChanged: Bluetooth
,I/SamsungIME( 4466): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/BluetoothAdapterService(10543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
I/BtGatt.JNI(10543): classInitNative(L900): classInitNative: Success!
W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/StatusBarManagerService( 3521): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
D/BtGatt.DebugUtils(10543): handleDebugAction() action=null
D/BtGatt.GattService(10543): Received start request. Starting profile...
D/BtGatt.GattService(10543): start()
I/bluedroid(10543): get_profile_interface gatt
D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
D/BtGatt.AdvertiseManager(10543): advertise manager created
,D/StatusBarManagerService( 3521): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 3692): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,D/TimaKeyStoreProvider(10564): TimaSignature is unavailable
,D/ActivityThread(10564): Added TimaKeyStore provider
W/BluetoothAdapterService(10543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.a2dp.A2dpService
V/[CarModeFW]( 9950): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,W/BluetoothAdapterService(10543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,W/BluetoothAdapterService(10543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.hdp.HealthService
,D/HeadsetService(10543): Received start request. Starting profile...
,W/BluetoothAdapterService(10543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.pan.PanService
I/BluetoothHeadsetServiceJni(10543): classInitNative: succeeds
D/HeadsetStateMachine(10543): make
,D/ResourcesManager(10564): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,E/HeadsetStateMachine(10543): # of Max HF connection is 2
,W/BluetoothAdapterService(10543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService(10543): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10543): Not skipping com.broadcom.bt.service.sap.SapService
,I/bluedroid(10543): get_profile_interface handsfree
,W/BluetoothAdapterService(10543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10543): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10543): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10543): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10543): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
I/DualScoManager(10543): Instantiating Dual Sco Manager
I/DualScoManager(10543): Set HeadsetServiceHelper
W/BluetoothAdapterService(10543): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState(10543): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAtMessage(10543): createCMTIContentObservers
,D/SettingsProvider( 3521): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/KeyguardWallpaperUpdator(10564): cancelUpdateWallpaper
W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/KeyguardWallpaperUpdator(10564): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10564): stopCheckCategoryVersion
D/HeadsetStateMachine(10543): Enter Disconnected: -2
,D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,E/HeadsetStateMachine(10543): set to mRemoteBrsf = 0
,D/BluetoothA2dp( 3521): Proxy object connected
,D/BluetoothA2dp( 4806): Proxy object connected
D/HeadsetStateMachine(10543): map size, before remove : 0
D/HeadsetStateMachine(10543): map size, after remove: 0
D/A2dpService(10543): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni(10543): classInitNative: succeeds
V/Avrcp   (10543): make
V/Avrcp   (10543): Avrcp
I/bluedroid(10543): get_profile_interface avrcp
,V/Avrcp   (10543): start
,E/RemoteController(10543): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   (10543): ++registerMediaPlayers++
,I/Avrcp   (10543): No of Audio players :: 2
I/Avrcp   (10543): App Package name is com.google.android.music
,I/SignOutReceiver( 8245): WIFI_STATE_CHANGED_ACTION
,D/ResourcesManager(10543): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/Avrcp   (10543): App pkg name is Google Play Music
,I/Avrcp   (10543): Name::Google Play Music
V/Avrcp   (10543): MediaPlayerInfo: mPlayerId=1
I/Avrcp   (10543): App Package name is com.sec.android.app.music
,D/ResourcesManager(10543): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   (10543): App pkg name is Music
I/Avrcp   (10543): Name::Music
V/Avrcp   (10543): MediaPlayerInfo: mPlayerId=2
I/Avrcp   (10543): No of Video players :: 1
I/Avrcp   (10543): Video App Package name is com.sec.android.app.videoplayer
D/ResourcesManager(10543): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/Avrcp   (10543): Video App pkg name is Video Player
I/Avrcp   (10543): Name::Video Player
V/Avrcp   (10543): MediaPlayerInfo: mPlayerId=3
I/Avrcp   (10543): Add tempPlayer
V/Avrcp   (10543): MediaPlayerInfo: mPlayerId=4
I/Avrcp   (10543): Total no of players: 4
V/Avrcp   (10543): swapping the samsung player with 1st player
I/Avrcp   (10543):  Updating now playing list upon AVRCP Start
V/Avrcp   (10543): handleMessage, msg=207
D/BluetoothMediaBrowser(10543):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
V/Avrcp   (10543): CurrentAudioFocusPackageName is null
I/Avrcp   (10543): There is no currently selected player ,setting Samsung Music Player ID
I/Avrcp   (10543):  set player publishabilty with player id::1 toBePublished ::true
I/BluetoothA2dpServiceJni(10543): classInitNative: succeeds
D/A2dpStateMachine(10543): make
I/bluedroid(10543): get_profile_interface a2dp
E/Zygote  (10587): MountEmulatedStorage()
E/Zygote  (10587): v2
I/libpersona(10587): KNOX_SDCARD checking this for 1000
I/libpersona(10587): KNOX_SDCARD not a persona
,I/SELinux (10587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/GKI_LINUX(10543): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif (10543): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
D/A2dpStateMachine(10543): Enter Disconnected: -2
E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,I/SELinux (10587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/BluetoothHidServiceJni(10543): classInitNative: succeeds
I/ActivityManager( 3521): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=10587 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (10587): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/HidService(10543): Received start request. Starting profile...
I/bluedroid(10543): get_profile_interface hidhost
,D/HidService(10543): setHidService(): set to: null
D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
I/BluetoothHealthServiceJni(10543): classInitNative: succeeds
D/HealthService(10543): Received start request. Starting profile...
,I/bluedroid(10543): get_profile_interface health
D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,I/BluetoothPanServiceJni(10543): classInitNative(L105): succeeds
,D/BluetoothPan( 3521): BluetoothPAN Proxy object connected
,D/PanService(10543): Received start request. Starting profile...
D/BluetoothPanServiceJni(10543): initializeNative(L110): pan
I/bluedroid(10543): get_profile_interface pan
D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,D/HeadsetStateMachine(10543): Try to query the phonestate on bind
,I/Telecom ( 3951): BluetoothPhoneService: queryPhoneState
I/Telecom ( 3951): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 3951): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothMediaBrowser(10543): no now playing list
D/BluetoothMediaBrowser(10543):  getNowPlayingId now playing id : -1
W/BluetoothHeadset( 3951): Proxy not attached to service
D/Avrcp   (10543):  checkNowPlayingList start
,D/BluetoothMapService(10543): Received start request. Starting profile...
,D/TimaKeyStoreProvider(10587): TimaSignature is unavailable
,D/ActivityThread(10587): Added TimaKeyStore provider
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10607): MountEmulatedStorage()
E/Zygote  (10607): v2
I/libpersona(10607): KNOX_SDCARD checking this for 10178
I/libpersona(10607): KNOX_SDCARD not a persona
,I/SELinux (10607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=10607 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ResourcesManager(10587): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/TimaKeyStoreProvider(10607): TimaSignature is unavailable
,D/ActivityThread(10607): Added TimaKeyStore provider
,D/ResourcesManager(10607): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(10607): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(10607): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10607): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10607): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10607): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10607): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10623): MountEmulatedStorage()
I/libpersona(10623): KNOX_SDCARD checking this for 10186
E/Zygote  (10623): v2
I/libpersona(10623): KNOX_SDCARD not a persona
,I/SELinux (10623): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc tv.peel.smartremote for broadcast tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver: pid=10623 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/SELinux (10623): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10623): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Killing 9795:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10623): TimaSignature is unavailable
,D/ActivityThread(10623): Added TimaKeyStore provider
,D/ResourcesManager(10623): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,W/ResourcesManager(10623): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,D/HeadsetStateMachine(10543): Proxy object connected
,I/BluetoothSAPServiceJni(10543): classInitNative(L204): succeeds
,E/Zygote  (10646): MountEmulatedStorage()
E/Zygote  (10646): v2
I/libpersona(10646): KNOX_SDCARD checking this for 10082
I/libpersona(10646): KNOX_SDCARD not a persona
,I/SELinux (10646): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/SapService(10543): Received start request. Starting profile...
D/BluetoothSAPServiceJni(10543): initializeNative(L209): sap
I/bluedroid(10543): get_profile_interface sap
D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
D/HeadsetPhoneState(10543): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState(10543): sendDeviceDataStateChanged
D/HeadsetStateMachine(10543): Disconnected process message: 11
D/HeadsetStateMachine(10543): Disconnected process message: 18
D/HeadsetPhoneState(10543): Signal level : previous=0 curr=0
E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp(10543): Proxy object connected
D/HeadsetStateMachine(10543): Disconnected process message: 10
D/BluetoothAdapterService(10543): Bluetooth A2dp source service connected
E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/HeadsetPhoneState(10543): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/HeadsetStateMachine(10543): Disconnected process message: 11
E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
I/SELinux (10646): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10646): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=10646 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 9812:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 481us total 9.998ms
,E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState(10543): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid(10543): enable
,I/GKI_LINUX(10543): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid(10543): init
,I/bt_vendor(10543): init
I/bt_vnd_conf(10543): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf(10543): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial(10543): userial_init
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 351us total 8.702ms
,D/TimaKeyStoreProvider(10646): TimaSignature is unavailable
,D/ActivityThread(10646): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 691us total 8.923ms
,I/ActivityManager( 3521): Killing 9837:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/ResourcesManager(10646): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(10646): onCreate
D/BadgeProvider(10646): DatabaseHelper
,I/WebViewFactory(10623): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(10623): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/BadgeProvider(10646): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/LibraryLoader(10623): Loading: webviewchromium
,D/BadgeProvider(10646): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10646): sendNotify, [notify] : null
D/BadgeProvider(10646): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10646): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10646): update, [UpdateCount] : 1
D/Launcher.Model( 3997): reloadBadges entered.
I/LibraryLoader(10623): Time to load native libraries: 3 ms (timestamps 6991-6994)
I/LibraryLoader(10623): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10623): Binding Chromium to main looper Looper (main, tid 1) {16809e99}
,I/LibraryLoader(10623): Expected native library version number "",actual native library version number ""
,I/chromium(10623): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10623): Initializing chromium process, renderers=0
,W/art     (10623): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10623): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10623): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10623): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
I/chromium(10623): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
,W/ActivityManager( 3521): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/bt_userial_vendor(10543): userial vendor open: opening /dev/ttySAC3
,I/bt_userial_vendor(10543): userial_vendor_open():UART is setup
I/bt_userial_vendor(10543): device fd = 65 open
E/bt_hwcfg(10543): Start CFG HW, HCI reset
D/bt_userial(10543): Entering userial_read_thread()
,E/bt_hwcfg(10543): Read Local Name after HCI reset
,D/bt_hwcfg(10543): Chipset BCM43569A1
D/bt_hwcfg(10543): Target name = [BCM4358A1]
,I/bt_hwcfg(10543): module_type[murata].
I/bt_hwcfg(10543): module_type[murata] is invalid.
E/bt_hwcfg(10543): patchram path ORG . BCM4358A1
E/bt_hwcfg(10543): patchram path ORG .. BCM4358A1
E/bt_hwcfg(10543): patchram path ORG bcm4358A0_V0033.0000.hcd BCM4358A1
E/bt_hwcfg(10543): patchram path ORG bcm4358A1_V0044.0078.hcd BCM4358A1
I/bt_hwcfg(10543): patch(org) : bcm4358A1_V0044.0078.hcd
I/bt_hwcfg(10543): Found patchfile: /vendor/firmware/bcm4358A1_V0044.0078.hcd
E/bt_hwcfg(10543): ORG patchram base 0044
E/bt_hwcfg(10543): ORG patchram minor 0078
E/bt_hwcfg(10543): fw ver (org)44.78
E/bt_hwcfg(10543): Final Patchram is /vendor/firmware/bcm4358A1_V0044.0078.hcd
,W/chromium(10623): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10623): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/bt_hwcfg(10543): Axi patch failure or not include AXI patching
,I/bt_hwcfg(10543): bt vendor lib: set UART baud 3000000
,W/art     (10623): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10623): onDetachedFromWindow called when already detached. Ignoring
,I/SecureStorage(10558): [INFO]: SPID(0x00000005)Processing data has been completed
,I/SecureStorage(10558): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10558): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10558
I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10558): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10558): ssSupport state is = 1
,I/ActivityManager( 3521): Killing 9128:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,I/wpa_supplicant(10558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant(10558): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10558): SIM READ ERROR
I/wpa_supplicant(10558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10558): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10558): SIM READ ERROR
I/wpa_supplicant(10558): Blacklist: Clear (all) 
I/wpa_supplicant(10558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10558): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant(10558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10558): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant(10558): rfkill: Cannot open RFKILL control device
,D/BluetoothNotiBroadcastReceiver( 7801): onReceive
,D/AuthorizationBluetoothService( 4240): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_hwcfg(10543): bt vendor lib: set UART baud 115200
I/bt_hwcfg(10543): FW Download delta = 480690
D/bt_hwcfg(10543): Settlement delay -- 100 ms
I/bt_hwcfg(10543): Setting fw settlement delay to 100 
,I/bt_hwcfg(10543): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg(10543): vendor lib fwcfg completed
,I/        (10543): BTE_InitTraceLevels -- TRC_HCI
I/        (10543): BTE_InitTraceLevels -- TRC_L2CAP
I/        (10543): BTE_InitTraceLevels -- TRC_RFCOMM
I/        (10543): BTE_InitTraceLevels -- TRC_AVDT
I/        (10543): BTE_InitTraceLevels -- TRC_AVRC
I/        (10543): BTE_InitTraceLevels -- TRC_A2D
I/        (10543): BTE_InitTraceLevels -- TRC_BNEP
I/        (10543): BTE_InitTraceLevels -- TRC_BTM
I/        (10543): BTE_InitTraceLevels -- TRC_GAP
I/        (10543): BTE_InitTraceLevels -- TRC_PAN
I/        (10543): BTE_InitTraceLevels -- TRC_SAP
I/        (10543): BTE_InitTraceLevels -- TRC_SDP
I/        (10543): BTE_InitTraceLevels -- TRC_GATT
I/        (10543): BTE_InitTraceLevels -- TRC_SMP
I/        (10543): BTE_InitTraceLevels -- TRC_BTAPP
I/        (10543): BTE_InitTraceLevels -- TRC_BTIF
I/        (10543): BTE_InitTraceLevels -- TRC_PROTOCOL
,W/bt-l2cap(10543): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  (10543): BTM_SecRegister:p_cb_info->p_le_callback == 0xb390f9e1 
E/bt-btm  (10543): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb390f9e1 
,E/Tethering( 3521): No numeric data
,D/Tethering( 3521): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 3521): forceRefresh() from cache miss
,D/HotspotTile( 3692): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3692): updateTetherState():false, false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 3521): forceRefresh Fail.
,V/NetworkStats( 3521): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3521): UpdateStatsForKnox
,V/NetworkStats( 3521): performPollLocked() took 2ms
,D/NtpTrustedTime( 3521): forceRefresh() from cache miss
,D/NtpTrustedTime( 3521): forceRefresh Fail.
,I/wpa_supplicant(10558): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant(10558): wlan0: State: DISCONNECTED -> DISCONNECTED
I/SecureStorage(10558): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10558): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10558
I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10558): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10558): ssSupport state is = 1
,I/SecureStorage(10558): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,D/BluetoothAdapterProperties(10543): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif (10543): Calling BTA_HhEnable
,E/bt-btif (10543): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties(10543): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10543): populateRssiValuesNative
I/bluedroid(10543): getModelRssiValues
E/BluetoothServiceJni(10543): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10543): modelRssiValuesCallback, low, mid, high = -75,-65,127
I/SecureStorage(10558): [INFO]: SPID(0x00000005)This device supports Secure Storage
I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10558
I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10558): [INFO]: SPID(0x00000005)SS Daemon is running
D/BluetoothAdapterProperties(10543): Name is: Note4-1
I/wpa_supplicant(10558): ssSupport state is = 1
,I/wpa_supplicant(10558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10558): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10558): SIM READ ERROR
I/wpa_supplicant(10558): rfkill: Cannot open RFKILL control device
D/SettingsProvider( 3521): name = bluetooth_name
E/wpa_supplicant(10558): nl80211: Could not configure driver mode
E/wpa_supplicant(10558): p2p0: Failed to initialize driver interface
I/wpa_supplicant(10558): Blacklist: Clear (all) 
D/BluetoothAdapterProperties(10543): Scan Mode:20
,D/BluetoothAdapterProperties(10543): Discoverable Timeout:120
D/BluetoothAdapterProperties(10543): LE Address is:E0:B7:20:28:C5:81
E/bt-btif (10543): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif (10543): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif (10543): btif_sock_init: !radio_req && !rfc_init
E/bt-btif (10543): btif_sock_init: !vhci_init
I/SecureStorage(10558): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,D/IOP_DB_BT(10543): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT(10543): db_open: db_open : handle 3025457168l, read 14063 bytes onto local cache
D/IOP_DB_BT(10543): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT(10543): db_query: result 1
I/        (10543): iop_db_open: iop_db_open status 0
,D/bte_conf(10543): Device ID record 1 : primary
D/bte_conf(10543):   vendorId            = 0075
D/bte_conf(10543):   vendorIdSource      = 0001
D/bte_conf(10543):   product             = 0100
D/bte_conf(10543):   version             = 0200
D/bte_conf(10543):   clientExecutableURL = 
D/bte_conf(10543):   serviceDescription  = 
D/bte_conf(10543):   documentationURL    = 
D/bte_conf(10543): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni(10543): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState(10543): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties(10543): ScanMode =  20
D/BluetoothAdapterProperties(10543): State =  11
,D/SecContentProvider( 3521): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties(10543): Setting state to 12
I/BluetoothAdapterState(10543): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties(10543): Scan Mode:21
D/BluetoothAdapterProperties(10543): Discoverable Timeout:120
D/SettingsProvider( 3521): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
,D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecureStorage(10558): [INFO]: SPID(0x00000005)This device supports Secure Storage
,D/BluetoothAdapterService(10543): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10543): updateAdapterState state is 12
I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10558
I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10558): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10558): ssSupport state is = 1
,I/SecureStorage(10558): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,D/BluetoothA2dp( 3521): onBluetoothStateChange: up=true
D/BluetoothAdapterService(10543): Autoconnection is available 
D/BluetoothAdapterService(10543): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService(10543): starting service from this receiver
D/BluetoothA2dp(10543): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 4806): onBluetoothStateChange: up=true
,I/BluetoothAdapterState(10543): Entering On State from state = 11
,W/InputMethodManagerService( 3521): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3521): [BT Setting State] State =12
I/InputMethodManagerService( 3521): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/SecureStorage(10558): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10558
I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10558): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10558): ssSupport state is = 1
I/wpa_supplicant(10558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10558): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10558): SIM READ ERROR
I/wpa_supplicant(10558): rfkill: Cannot open RFKILL control device
D/BluetoothTile( 3692):  onBluetoothStateChange:
,D/BluetoothHeadset( 3951): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3f8842b1, true
,D/BluetoothHeadset( 3951): registerMessageListener
,I/BluetoothPbapService(10543): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,I/SamsungIME( 4466): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,E/bt_h4   (10543): vendor lib postload completed
D/BluetoothTile( 3692):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3692): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/StatusBarManagerService( 3521): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3521): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 3692): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/HeadsetService(10543): registerMessageListener
,D/BluetoothTile( 3692):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 3692): onStateChanged: Bluetooth
,D/HeadsetService(10543): registerMessageListener
D/HeadsetStateMachine(10543): Disconnected process message: 70
D/HeadsetStateMachine(10543): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@25086f6e
,I/Telecom ( 3951): BluetoothPhoneService: updateHeadsetWithCallState
I/Telecom ( 3951): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/ContextImpl( 7801): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
V/[CarModeFW]( 9950): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW]( 9950): ConnectivityManager-handleMessage INITIAL_STATE_ON
,D/HeadsetStateMachine(10543): Disconnected process message: 9
,D/HeadsetStateMachine(10543): mNumActive: 0 mNumHeld: 0 mCallState: 6
,I/AudioHardwareTinyALSA( 2855): setParameters(A2dpSuspended=false)
,E/HeadsetStateMachine(10543): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/LocalBluetoothProfileManager( 7801): Adding local A2DP profile
,I/wpa_supplicant(10558): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant(10558): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant(10558): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant(10558): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant(10558): Skip scan - bUseNetwork false
,E/WifiStateMachine( 3521): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,E/WifiStateMachine( 3521): setSuspendOptimizations: 2 true
E/WifiStateMachine( 3521): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine( 3521): Supplicant connection established
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [21]
I/wpa_supplicant(10558): HOTSPOT20_ENABLE called
I/wpa_supplicant(10558): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10558): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10558): SIM READ ERROR
I/wpa_supplicant(10558): Blacklist: Clear (all) 
,I/wpa_supplicant(10558): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant(10558): Skip scan - bUseNetwork false
E/WifiStateMachine( 3521): setWifiState: enabled
,D/WifiNative-HAL( 3521): callSECApiInt - ID [210]
,D/WifiConfigStore( 3521): Loading config and enabling all networks 
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3521): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3692): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3692): Wifi onReceive(3)
D/HotspotTile( 3692): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 3692): onStateChanged: Wi-Fi
,D/HotspotTile( 3692): onReceive : 3, 0
,E/WifiConfigStore( 3521): Not a HS20
,E/WifiConfigStore( 3521): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/WifiStateMachine( 3521): update LTECoexState:0
D/WifiNative-HAL( 3521): callSECApiInt - ID [65]
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 31838(1871KB) AllocSpace objects, 13(208KB) LOS objects, 24% free, 48MB/64MB, paused 1.805ms total 90.449ms
,D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant(10558): wlan0: Setting scan request: 8 sec 0 usec
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
I/wpa_supplicant(10558): reset timer : RESET_TIMER 0
I/wpa_supplicant(10558): P2P: Current p2p state = IDLE
I/wpa_supplicant(10558): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant(10558): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant(10558): First Scan Start
,I/wpa_supplicant(10558): Scan requested (ret=0) - scan timeout 30 seconds
D/BluetoothManagerService( 3521): Broadcasting onBluetoothServiceUp() to 0 receivers.
I/BluetoothPbapService(10543): Handler(): got msg=1
,D/SecContentProvider( 3521): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/WifiNative-HAL( 3521): Setting external_sim to 1
,D/WifiStateMachine( 3521): Setting OUI to DA-A1-19
I/WifiNative-HAL( 3521): startHal
E/wifi    ( 3521): getStaticLongField sWifiHalHandle 0x8f98c85c
D/wifi    ( 3521): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x5021c6
I/WifiNative-HAL( 3521): Could not start hal
,E/WifiStateMachine( 3521): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
D/LocalBluetoothProfileManager( 7801): Adding local HEADSET profile
,E/BluetoothHeadset( 7801): BTStateChangeCB is registed
,E/WifiStateMachine( 3521): Attempting to reconnect to wifi network ..
V/BluetoothPbapService(10543): PBAP Service initSocket try: 0
E/native  ( 3521): do suspend true
,E/BluetoothHeadset( 7801): BluetoothHeadset service is binded
,W/BluetoothAdapter(10543): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance(10543): set MAP SDP message type : 1
D/BluetoothSocket(10543): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket(10543): bindListen(), new LocalSocket 
D/BluetoothSocket(10543): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10543): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1fbe3a21
D/BluetoothSocket(10543): channel: 19
D/BluetoothPbapService(10543): PBAP Socket is BluetoothServerSocket
,E/WifiStateMachine( 3521): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - currTime: 1453394743092
D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
W/BluetoothAdapter(10543): getBluetoothService() called with no BluetoothManagerCallback
D/WifiP2pService( 3521): P2pDisabledState{ what=131203 }
,D/WifiScanningService( 3521): SCAN_AVAILABLE : 3
D/WifiScanningService( 3521): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 3521): startHal
E/wifi    ( 3521): getStaticLongField sWifiHalHandle 0x8e74498c
D/wifi    ( 3521): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x8020c6
I/WifiNative-HAL( 3521): Could not start hal
E/WifiScanningService( 3521): could not start HAL
D/RttService( 3521): SCAN_AVAILABLE : 3
D/RttService( 3521): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothSocket(10543): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/BluetoothSocket(10543): bindListen(), new LocalSocket 
E/WifiStateMachine( 3521): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/BluetoothSocket(10543): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10543): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@103afe46
W/ContextImpl( 7801): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/CommandListener( 2846): Setting iface cfg
,D/CommandListener( 2846): Trying to bring up p2p0
D/BluetoothSocket(10543): channel: 5
E/WifiStateMachine( 3521): set country code pl
D/WifiMonitor( 3521): startMonitoring(p2p0) with mConnected = true
,D/Bluetoothsap( 7801): bindService called to Bluetooth SAP Service
D/WifiP2pService( 3521): P2pEnablingState
D/WifiP2pService( 3521): P2pEnablingState{ what=147457 }
D/WifiP2pService( 3521): P2p socket connection successful
D/WifiP2pService( 3521): P2pEnabledState
,D/WifiP2pService( 3521): sending p2p connection changed broadcast: IDLE
,E/WifiStateMachine( 3521): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 3521): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiP2pService( 3521): create mNetworkAgent
,D/LocalBluetoothProfileManager( 7801): PANU : true
D/LocalBluetoothProfileManager( 7801): Adding local MAP profile
,D/BluetoothMap( 7801): Create BluetoothMap proxy object
,D/WifiDisplayController( 3521): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3521): disconnect
D/WifiDisplayController( 3521): updateConnection
D/WifiDisplayController( 3521): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3521): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 3692): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3692): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,W/LocalBluetoothProfileManager( 7801): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 7801): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 7801): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 7801): onReceive
,D/BluetoothA2dp( 7801): Proxy object connected
D/A2dpProfile( 7801): Bluetooth service connected
,D/ConnectivityService( 3521): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 3521): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 3521): updateNetworkInfo()
D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
D/BtConfig.SecureMode(10543): isSecureModeOn:false
,E/CSLegacyTypeTracker( 3521): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/wpa_supplicant(10558): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/WifiStateMachine( 3521): set frequency band 0
D/HeadsetProfile( 7801): Bluetooth service connected
,D/Bluetoothsap( 7801): BluetoothSAP Proxy object connected
,D/SapProfile( 7801): Bluetooth service connected
D/Bluetoothsap( 7801): getConnectedDevices()
,D/AuthorizationBluetoothService( 4240): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothInputDevice( 7801): Proxy object connected
D/HidProfile( 7801): Bluetooth service connected
,D/BluetoothPan( 7801): BluetoothPAN Proxy object connected
I/Hs20UtilService( 6287): Starting #3
D/PanProfile( 7801): Bluetooth service connected
,I/Hs20UtilService( 6287): Message received 5011
,I/WifiStateMachine( 3521): callSECApi what=207
,D/BluetoothMap( 7801): Proxy object connected
D/MapProfile( 7801): Bluetooth service connected
,D/BluetoothPbap( 7801): Proxy object connected
D/PbapServerProfile( 7801): Bluetooth service connected
,D/KeyguardWallpaperUpdator(10564): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(10564): cancelUpdateCategory
,D/KeyguardWallpaperUpdator(10564): stopCheckCategoryVersion
,D/SecContentProvider( 3521): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/SignOutReceiver( 8245): WIFI_STATE_CHANGED_ACTION
,I/wpa_supplicant(10558): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine( 3521): setDetailed state send new extra info
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,D/WifiNative-HAL( 3521): p2pGetDeviceAddress
,D/WifiNative-HAL( 3521): p2pGetDeviceAddress returning 92:b6:86:43:73:1c
,D/WifiP2pService( 3521): DeviceAddress: 92:73:1c
,D/WifiDisplayController( 3521): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note4-1
D/WifiDisplayController( 3521):  deviceAddress: 92:b6:86:43:73:1c
D/WifiDisplayController( 3521):  primary type: 10-0050F204-5
D/WifiDisplayController( 3521):  secondary type: null
D/WifiDisplayController( 3521):  wps: 0
D/WifiDisplayController( 3521):  grpcapab: 0
D/WifiDisplayController( 3521):  devcapab: 0
D/WifiDisplayController( 3521):  status: 3
D/WifiDisplayController( 3521):  wfdInfo: null
D/WifiDisplayController( 3521):  groupownerAddress: null
D/WifiDisplayController( 3521):  GOdeviceName: null
D/WifiDisplayController( 3521):  interfaceAddress: 
D/WifiDisplayController( 3521):  SConnectInfo : null
W/BluetoothAdapter(10543): getBluetoothService() called with no BluetoothManagerCallback
,E/WifiStateMachine( 3521): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL( 3521): callSECStringApiVoid - ID [215]
E/WifiNative-HAL( 3521): invaild command id : 215
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,D/BluetoothSocket(10543): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
D/BluetoothSocket(10543): bindListen(), new LocalSocket 
D/BluetoothSocket(10543): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10543): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e1238a0
D/BluetoothSocket(10543): channel: 12
I/BtOppRfcommListener(10543): Accept thread started.
,D/WifiP2pService( 3521): sending p2p persistent groups changed broadcast
D/NearbySettings( 7801): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 7801): MountReceiver.onReceive - Start HandlerThread
D/WifiP2pService( 3521): InactiveState
D/NearbySettings( 7801): MountReceiver.onReceive - Create mPrefHandler
,E/ConnectivityService( 3521): updateNetworkInfo()
D/WifiP2pService( 3521): InactiveState{ what=143376 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143376 }
,D/NearbySettings( 7801): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,I/wpa_supplicant(10558): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
V/NearbySettings( 7801): DMSUtil.isNetworkConnected - flag-null, state-null
,D/WifiP2pService( 3521): InactiveState{ what=143376 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143376 }
,I/NearbySettings( 7801): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/WifiService( 3521): New client listening to asynchronous messages
I/NearbySettings( 7801): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7801): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7801): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7801): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10735): MountEmulatedStorage()
E/Zygote  (10735): v2
I/libpersona(10735): KNOX_SDCARD checking this for 10079
I/libpersona(10735): KNOX_SDCARD not a persona
,I/SELinux (10735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10735): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=10735 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (10735): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10735): TimaSignature is unavailable
,D/ActivityThread(10735): Added TimaKeyStore provider
,D/ResourcesManager(10735): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(10735): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 3521): Killing 7731:com.android.mms/u0a52 (adj 13): bgCount ##31
,D/CountryDetector( 3521): No listener is left
,I/wpa_supplicant(10558): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant(10558): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant(10558): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant(10558): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant(10558): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3521): [1,453,394,743,647 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3521): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@c96ad7a sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/wpa_supplicant(10558): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant(10558): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant(10558): Associated with C0.AA.48
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3521): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/wpa_supplicant(10558): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant(10558): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/wpa_supplicant(10558): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant(10558): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant(10558): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant(10558): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(10558): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant(10558): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant(10558): Blacklist: Clear (temp) 
I/wpa_supplicant(10558): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3521): Network connection established
,D/WifiNative-HAL( 3521): callSECApiVoid - ID [50]
E/WifiStateMachine( 3521): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine( 3521): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3521): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 3521): hsengiv:checkWhatTypeOfNetwork and the value is false
E/WifiStateMachine( 3521): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine( 3521): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService( 3521): updateNetworkInfo()
,D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 6287): Starting #4
,I/Hs20UtilService( 6287): Message received 5007
,D/NearbySettings( 7801): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 7801): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 7801): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 7801): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7801): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7801): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7801): MountReceiver.mPrefHandler - 7002
E/WifiStateMachine( 3521): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine( 3521): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3521): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SignOutReceiver( 8245): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2846): Setting iface cfg
,E/WifiStateMachine( 3521): Start Dhcp Watchdog 1
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,E/WifiStateMachine( 3521): Force RSSI Broadcast 1/3
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3521): do suspend false
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/SecContentProvider2( 3521): mCursor = null
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,I/jxcore-log(10472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(10472): 
,E/dhcpcd  (10753): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (10753): version 5.5.6 starting
,E/dhcpcd  (10753): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (10753): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (10753): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (10753): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (10753): bssid match
,I/dhcpcd  (10753): wlan0: rebinding lease of 192.168.1.124
,I/dhcpcd  (10753): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (10753): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/jxcore-log(10472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(10472): 
,I/jxcore-log(10472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(10472): 
,I/jxcore-log(10472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(10472): 
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  ( 3521): do suspend true
,D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3521): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3521): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3521): Not connected state, yet.
E/WifiStateMachine( 3521): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3521): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine( 3521): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3521): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3521): callSECApiInt - ID [210]
E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
I/jxcore-log(10472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(10472): 
,E/ConnectivityService( 3521): updateNetworkInfo()
,D/ConnectivityService( 3521): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3521): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 3521): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 6287): Starting #5
,I/Hs20UtilService( 6287): Message received 5007
,D/NearbySettings( 7801): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 7801): MountReceiver.onReceive - Keep current state
,I/jxcore-log(10472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(10472): 
,E/WifiStateMachine( 3521): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3521): Now, connected state.
E/WifiStateMachine( 3521): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/ConnectivityService( 3521): Adding Route [fe80::/64 -> :: wlan0] to network 502
,E/WifiStateMachine( 3521): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService( 3521): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,I/SignOutReceiver( 8245): NETWORK_STATE_CHANGED_ACTION
I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
D/ConnectivityService( 3521): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,I/jxcore-log(10472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(10472): 
E/ConnectivityService( 3521): Unexpected mtu value: 0, wlan0
,V/        ( 2846): QcRouteController
,I/jxcore-log(10472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(10472): 
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3521): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3521): callSECApiVoid - ID [212]
E/WifiStateMachine( 3521): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3521): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/Hs20UtilService( 6287): Starting #6
,I/Hs20UtilService( 6287): Message received 5007
,D/NearbySettings( 7801): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 7801): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 7801): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 7801): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7801): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7801): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7801): MountReceiver.mPrefHandler - 7002
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,I/SignOutReceiver( 8245): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 6287): Starting #7
,I/Hs20UtilService( 6287): Message received 5007
,V/        ( 2846): QcRouteController
D/NearbySettings( 7801): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 7801): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3521): callSECApi what=220
D/WifiStateMachine( 3521): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,I/SignOutReceiver( 8245): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2846): QcRouteController
,D/ConnectivityService( 3521): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 3521): LTETest block dns file not exists
,E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3521): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Connected
D/ConnectivityService( 3521): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Checking http://clients3.google.com/generate_204 on "NG700"
,I/System.out( 3521): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3521): (HTTPLog)-Static: isShipBuild true
I/System.out( 3521): (HTTPLog)-Thread-187-695069159: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3521): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService( 3521):    accepting network in place of null
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/ConnectivityService( 3521): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 1000
,D/TelephonyNetworkFactory( 3981): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SurfaceFlinger( 2850): id=13 createSurf (1x1),1 flag=4, Uoast
,E/CSLegacyTypeTracker( 3521): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3521): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3521): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3521): MasterInitialState.processMessage what=3
D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/NetworkStatsFactory( 3521): UpdateStatsForKnox
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/NtpTrustedTime( 3521): forceRefresh() from cache miss
D/EntConnectivity( 3521): Not allowed due to - mEnabled false
V/NetworkStats( 3521): updateIfacesLocked()
V/NetworkStats( 3521): performPollLocked(flags=0x1)
D/ConnectivityService( 3521): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
V/NetworkStats( 3521): performPollLocked() took 2ms
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 1000
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 4449): CM callback handler got msg 524290
,D/PowerManagerService( 3521): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521
,D/mali_winsys( 3692): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/System.out( 3521): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NtpTrustedTime( 3521): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1453394745464 mCachedNtpElapsedRealtime : 139735 mCachedNtpCertainty : 16
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 16:45:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453394744772], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453394744753]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Validated
,D/ConnectivityService( 3521): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3521): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3521): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 3521): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 4449): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/jxcore-log(10472): Test app app.js loaded
I/jxcore-log(10472): 
,I/chromium(10472): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager( 3521): Killing 9876:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3521): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3521): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/AlarmManagerService( 3521): Setting time of day to sec=1453394745
D/AlarmManagerService( 3521): Trying to open a file
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/AlarmManagerService( 3521): File Open Success
D/AlarmManagerService( 3521): File Close Success
I/AlarmManagerService( 3521): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 3521): waitForAlarm result :65536
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 5973): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 5973): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 5973): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 5973): [IlIIlIIlIllllIlllIII(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 5973): [IlIlllIlllllIlIllllI(403/llllllIllIlIlllIIlIl)] Check completed.
,I/DBG_DM  ( 5973): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 5973): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ActivityManager( 3521): Failed to update preferences for: com.sec.android.app.myfiles
,D/WifiStateMachine( 3521): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_SET
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_SET
I/DBG_DM  ( 5973): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
D/StatusBar-DoNotDistrub( 3692): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 3692): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_DM  ( 5973): [IIlIIIlllllIIlIIIlII(72/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 5973): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/StatusBar-DoNotDistrub( 3692): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager( 2855): getOutputsForDevice device 0002 -> 0002
,I/AudioService( 3521): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 3692): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,W/Settings( 3521): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SettingsProvider( 3521): name = lockscreen_zoom_panning_effect
,D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10060
,D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,I/DBG_DM  ( 5973): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,W/SEC_DRM_PLUGIN_Playready( 2854): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1453394745 after conversion: 1453394745
W/SEC_DRM_PLUGIN_Playready( 2854): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1453394745 after conversion: 1453394745
,I/DBG_DM  ( 5973): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 5973): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,D/KeyguardEffectViewUtil( 3692): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3692): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3692): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3692): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3692): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{3d4a6512 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3692): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{164b4e3 V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3692): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{3d4a6512 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3692): clearEffect
D/WallpaperWidget( 3692): setLockScreenWallpaper()
D/KeyguardEffectViewUtil( 3692): getCurrentWallpaper() mWallpaperPath :null
,I/DBG_DM  ( 5973): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10813): MountEmulatedStorage()
I/libpersona(10813): KNOX_SDCARD checking this for 1000
E/Zygote  (10813): v2
I/libpersona(10813): KNOX_SDCARD not a persona
,I/SELinux (10813): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10813 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (10813): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10813): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5973): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
,I/DBG_DM  ( 5973): [IlIIlIIlIllllIlllIII(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 5973): [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 5973): [IlIIlIIlIllllIlllIII(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 5973): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 5973): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(502/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10813): TimaSignature is unavailable
,E/Zygote  (10830): MountEmulatedStorage()
I/libpersona(10830): KNOX_SDCARD checking this for 10090
E/Zygote  (10830): v2
I/libpersona(10830): KNOX_SDCARD not a persona
,I/SELinux (10830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=10830 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread(10813): Added TimaKeyStore provider
I/SELinux (10830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10830): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5973): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,I/DBG_DM  ( 5973): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,D/ResourcesManager(10813): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/DBG_DM  ( 5973): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,I/PCWCLIENTTRACE_LOG(10813): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(10813): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(10813): new DMDBOpenHelper instance
,I/DBG_DM  ( 5973): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 5973): [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,D/TimaKeyStoreProvider(10830): TimaSignature is unavailable
,D/ActivityThread(10830): Added TimaKeyStore provider
,I/DBG_DM  ( 5973): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 5973): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 5973): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@1ba3575d
,E/Zygote  (10847): MountEmulatedStorage()
I/libpersona(10847): KNOX_SDCARD checking this for 10050
E/Zygote  (10847): v2
I/libpersona(10847): KNOX_SDCARD not a persona
,I/SELinux (10847): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10847): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=10847 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (10847): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/GpsLocationProvider( 3521): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 5973): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,I/PCWCLIENTTRACE_PushUtil(10813): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(10813): sales region : global
I/PCWCLIENTTRACE_PushUtil(10813): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(10813): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10830): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/Zygote  (10864): MountEmulatedStorage()
E/Zygote  (10864): v2
I/libpersona(10864): KNOX_SDCARD checking this for 10135
I/libpersona(10864): KNOX_SDCARD not a persona
,I/SELinux (10864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10864): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=10864 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 4449): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3521): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 15583, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 3521): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 170662, reason: UserStart
,D/TimaKeyStoreProvider(10847): TimaSignature is unavailable
,D/ActivityThread(10847): Added TimaKeyStore provider
,I/DBG_DM  ( 5973): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/TimaKeyStoreProvider(10864): TimaSignature is unavailable
,D/ActivityThread(10864): Added TimaKeyStore provider
,I/DBG_DM  ( 5973): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,W/ResourceType( 4967): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4967): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/ActivityManager( 3521): Killing 9892:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/ResourcesManager(10847): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(10847): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/SecContentProvider2( 3521): uri = 14 selection = getSealedState
W/ResourcesManager(10847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10847): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/SecContentProvider2( 3521): mCursor = null
,W/ResourcesManager(10847): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(10847): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10847): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10847): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ApplicationPolicy( 3521): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 3521): showStatusBarByNotification() mOpenByNotification=false
,I/DBG_DM  ( 5973): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,D/ResourcesManager( 3692): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,I/KeyguardEffectViewUtil( 3692): set current wallpaper info
,D/SettingsProvider( 3521): name = keyguard_current_wallpaper_type
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10060
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,I/DBG_DM  ( 5973): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/ResourcesManager(10864): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3521): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10060
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3521): mCursor = null
,I/DBG_DM  ( 5973): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 5973): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 5973): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3521): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10060
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,I/MusicStore(10864): Database version: 104
,V/GLSActivity( 4240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,I/VacuumService( 4240): Vacuum at: now=1453394746402 tag=VacuumService
,D/DelayedSyncController(10830): Delaying sync.
,D/PackageManager( 3521): findPreferredActivity: No PreferredActivities set
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/NearbySource(10847): Nearby Source Create!
,D/NearbyContext(10847): Nearby Context Create!
,D/ResourcesManager(10864): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(10864): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(10864): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10847): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(10847): Samsung link source created
,E/Auth.Api.Credentials( 4449): [CredentialSyncAdapter] Unknown sync event.
,D/KnoxNotification( 3692): ----- inflateViews : modified publicViewLocal -----
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/KnoxNotification( 3692): ----- inflateViews : modified KnoxViewLocal -----
,V/JNIHelp (10864): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/PersonaManager( 3692): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 3692): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@16075a62
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
D/PersonaManager( 3692): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3692): Icon Only
,D/ContactProvider(10847): getAllContactInfoList Start
,I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
D/PanelView( 3692): There is/are notification(s) 
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
,D/KeyguardEffectViewUtil( 3692): isPowerSavingMode() :false
,W/ActivityThread(10864): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (10864): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f42dda3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10864): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(10864): GMSCore installation verified
D/KeyguardEffectViewUtil( 3692): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3692): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3692): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3692): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{3d4a6512 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3692): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{164b4e3 V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3692): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{3d4a6512 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3692): clearEffect
,V/GLSActivity( 4240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
I/ConfigStore(10864): Config Database version: 1
,D/ContactProvider(10847): getAllContactInfoList End
,I/syncContacts(10847): thread: 1458, sync time = 121
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10864): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,V/GLSActivity( 4240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PicasaService(10847): start picasa sync
,D/PicasaService(10847): end picasa sync
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10864): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10864): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3521): getStreamVolume 3 index 0
,I/MediaRouter(10864): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor(10864): type=WIFI subType= reason=null isConnected=true
,W/art     (10099): Attempt to remove local handle scope entry from IRT, ignoring
,E/Zygote  (10914): MountEmulatedStorage()
,E/Zygote  (10914): v2
I/libpersona(10914): KNOX_SDCARD checking this for 10002
I/libpersona(10914): KNOX_SDCARD not a persona
,I/SELinux (10914): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10914): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=10914 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (10914): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10914): TimaSignature is unavailable
,D/ActivityThread(10914): Added TimaKeyStore provider
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/DelayedSyncController(10830): Delaying sync.
,D/ResourcesManager(10914): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
I/NetworkMonitor(10864): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 3521): Killing 9910:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10147
,I/ActivityManager( 3521): Killing 9926:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10944): MountEmulatedStorage()
E/Zygote  (10944): v2
I/libpersona(10944): KNOX_SDCARD checking this for 1000
I/libpersona(10944): KNOX_SDCARD not a persona
,I/SELinux (10944): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10944): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10944): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=10944 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 9968:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10944): TimaSignature is unavailable
,D/ActivityThread(10944): Added TimaKeyStore provider
,D/ResourcesManager(10944): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 84704(4MB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 48MB/64MB, paused 4.720ms total 156.376ms
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
,I/DIAGMON_AGENT(10944): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/jxcore-log(10472): BLE advertisement is supported
I/jxcore-log(10472): 
,I/DIAGMON_AGENT(10944): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(10944): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(10944): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(10944): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10962): MountEmulatedStorage()
E/Zygote  (10962): v2
I/libpersona(10962): KNOX_SDCARD checking this for 10012
I/libpersona(10962): KNOX_SDCARD not a persona
,I/SELinux (10962): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10962): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=10962 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (10962): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10962): TimaSignature is unavailable
,D/ActivityThread(10962): Added TimaKeyStore provider
,D/ResourcesManager(10962): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3521): Killing 10015:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/FOTA_Client(10962): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(10962): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(10962): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10979): MountEmulatedStorage()
,E/Zygote  (10979): v2
I/libpersona(10979): KNOX_SDCARD checking this for 10021
I/libpersona(10979): KNOX_SDCARD not a persona
,I/SELinux (10979): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10979 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/SELinux (10979): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10979): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Killing 10000:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10979): TimaSignature is unavailable
,D/ActivityThread(10979): Added TimaKeyStore provider
,D/ResourcesManager(10979): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (10979): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 21 17:45:47 GMT+01:00 2016
,I/KLMS-2.4.521: (10979): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (10979): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (10979): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (10979): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (10979): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (10979): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  (10995): MountEmulatedStorage()
E/Zygote  (10995): v2
I/libpersona(10995): KNOX_SDCARD checking this for 10038
I/libpersona(10995): KNOX_SDCARD not a persona
,I/KLMS-2.4.521: (10979): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/SELinux (10995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (10979): StateImplV2(): networkChangeListener().START
,I/SELinux (10995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=10995 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
E/SELinux (10995): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (10979): NetworkChangeOperations(): uploadRequestLog().START 
,D/TimaKeyStoreProvider(10995): TimaSignature is unavailable
,D/ActivityThread(10995): Added TimaKeyStore provider
,I/KLMS-2.4.521: (10979): NetworkChangeOperations(): uploadRequestLog().END 
,D/ResourcesManager(10995): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/KLMS-2.4.521: (10979): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (10979): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3521): Killing 10033:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,I/SO_AGENT(10995): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3521): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,V/        ( 2846): QcRouteController
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,V/        ( 2846): QcRouteController
,W/NetworkManagementService( 3521): route cmd failed: 
W/NetworkManagementService( 3521): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '56 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 56 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3521): '
W/NetworkManagementService( 3521): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3521): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3521): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3521): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3521): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3521): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3521): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3521): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3521): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
,D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
,E/Zygote  (11017): MountEmulatedStorage()
I/libpersona(11017): KNOX_SDCARD checking this for 1000
E/Zygote  (11017): v2
I/libpersona(11017): KNOX_SDCARD not a persona
,D/ConnectivityManager.CallbackHandler( 4449): CM callback handler got msg 524295
,I/SELinux (11017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ConnectivityManager.CallbackHandler( 4449): CM callback handler got msg 524295
I/SELinux (11017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11017 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11017): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 10050:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 849us total 24.821ms
,D/TimaKeyStoreProvider(11017): TimaSignature is unavailable
,D/ActivityThread(11017): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.119ms total 19.327ms
,D/ResourcesManager(11017): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 436us total 17.131ms
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11038): MountEmulatedStorage()
E/Zygote  (11038): v2
I/libpersona(11038): KNOX_SDCARD checking this for 10039
I/libpersona(11038): KNOX_SDCARD not a persona
,I/SELinux (11038): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11038 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 10066:com.samsung.helphub/1000 (adj 13): bgCount ##31
,I/SELinux (11038): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11038): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 4240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider(11038): TimaSignature is unavailable
,D/ActivityThread(11038): Added TimaKeyStore provider
,D/ResourcesManager(11038): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/AclDataUtils(10099): Circle ID not found for type: 9
,D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - currTime: 1453394747931
D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/SPPClientService(11038): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11038): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService(11038): PushLog.txt file is not deleted.
D/SPPClientService(11038): PushLog.txt file is not deleted.
D/SPPClientService(11038): ============PushLog. stop!
,E/SPPClientService(11038): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11056): MountEmulatedStorage()
,E/Zygote  (11056): v2
I/libpersona(11056): KNOX_SDCARD checking this for 10045
I/libpersona(11056): KNOX_SDCARD not a persona
,I/SELinux (11056): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=11056 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11056): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Killing 10151:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,E/SELinux (11056): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 10168:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11056): TimaSignature is unavailable
,D/ActivityThread(11056): Added TimaKeyStore provider
,D/ResourcesManager(11056): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (11056): [SSP] onCreated
,I/SA      (11056): [TPM] There is no property file
,I/SA      (11056): [SCU] isHaveSA() - false
,I/SA      (11056): [TPM] getModelProperty : null
I/SA      (11056): [TPM] getCSCProperty : null
,I/SA      (11056): [DM] init START
,I/SA      (11056): [DM] This device is not a Vodafone
,I/SA      (11056): checkReactivationActive for LOLLIPOP
,I/SA      (11056): checkReactivationActive for reactiveActive
I/SA      (11056): setSupportRL : true
,I/SA      (11056): [SCU] isHaveSA() - false
I/SA      (11056): support phone number id : false
,I/SA      (11056): [DM] init END
I/SA      (11056): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11056): [SLFUCHKMGR] constructor called
,I/SA      (11056): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11056): [OR] == isSIMCardReady false ==
,I/SA      (11056): [SCU] == networkStateCheck == true
I/SA      (11056): [DM] getCountryCodeFromCSC : PL
I/SA      (11056): isChinaCountryCode : false
I/SA      (11056): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11056): [OR] == networkStateCheck true ==
,I/SA      (11056): [OR] GetMyCountryZoneTask
,I/SA      (11056): [OR] onReceive END
,I/ActivityManager( 3521): Killing 10187:com.facebook.system/u0a10 (adj 13): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/10187/oom_score_adj; errno=22
,I/SA      (11056): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11056): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11056): [SSP] query invoked
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/SA      (11056): [TPMU] GetMccFromDB : null
I/SA      (11056): [SCU] getMccFromPreferece mcc = 260
I/SA      (11056): [TPM] isNoProxy(default) : true
,E/Zygote  (11079): MountEmulatedStorage()
,E/Zygote  (11079): v2
I/libpersona(11079): KNOX_SDCARD checking this for 10067
I/libpersona(11079): KNOX_SDCARD not a persona
,I/SELinux (11079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11079 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux (11079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11079): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11079): TimaSignature is unavailable
,D/ActivityThread(11079): Added TimaKeyStore provider
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(11079): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11079): Other Intent
,I/ActivityManager( 3521): Killing 10239:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,D/accuweather( 5174): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 5174): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5174): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5174): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5174): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5174): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5174): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11096): MountEmulatedStorage()
E/Zygote  (11096): v2
I/libpersona(11096): KNOX_SDCARD checking this for 1000
I/libpersona(11096): KNOX_SDCARD not a persona
,I/SELinux (11096): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11096): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11096): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11096 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11096): TimaSignature is unavailable
,D/ActivityThread(11096): Added TimaKeyStore provider
,D/ResourcesManager(11096): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11096): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(11096): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(11096): premStatus:2
,I/KnoxUsageLogPro(11096): isEulaShown : false
I/KnoxUsageLogPro(11096): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(10564): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(10564): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10564): stopCheckCategoryVersion
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11111): MountEmulatedStorage()
E/Zygote  (11111): v2
I/libpersona(11111): KNOX_SDCARD checking this for 10136
I/libpersona(11111): KNOX_SDCARD not a persona
,I/SELinux (11111): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11111 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11111): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11111): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Killing 10286:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11111): TimaSignature is unavailable
,D/ActivityThread(11111): Added TimaKeyStore provider
,D/ResourcesManager(11111): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/WifiStateMachine( 3521): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3521): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11111): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11111): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11111): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11111): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/SA      (11056): [RC New] Execute method=[GET] start
,I/SA      (11056): [RC New] Security=[true]
,I/System.out(11056): Thread-1505(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11056): Thread-1505(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11056): Thread-1505(ApacheHTTPLog):isShipBuild true
I/System.out(11056): Thread-1505(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10045
,I/WebViewFactory(11111): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11111): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11111): Loading: webviewchromium
,I/LibraryLoader(11111): Time to load native libraries: 3 ms (timestamps 3025-3028)
I/LibraryLoader(11111): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11111): Binding Chromium to main looper Looper (main, tid 1) {48f1515}
,I/LibraryLoader(11111): Expected native library version number "",actual native library version number ""
,I/chromium(11111): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11111): Initializing chromium process, renderers=0
,W/art     (11111): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(11111): Requires BLUETOOTH permission
W/chromium(11111): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11111): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(11111): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/SurfaceFlinger( 2850): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger( 2850): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 3521): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3521) eventTime = 143128
,D/PowerManagerService( 3521): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521 (0x0)
D/PowerManagerService( 3521): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3521, ws=WorkSource{10060}) (elapsedTime=3490)
,I/NSApplication(11111): Starting up...
D/OpenGLRenderer( 5973): Render dirty regions requested: true
,I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3521): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/OpenGLRenderer( 5973): Initialized EGL, version 1.4
,E/Zygote  (11194): MountEmulatedStorage()
,E/Zygote  (11194): v2
I/libpersona(11194): KNOX_SDCARD checking this for 10150
I/libpersona(11194): KNOX_SDCARD not a persona
,I/SELinux (11194): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/OpenGLRenderer( 5973): HWUI protection enabled for context ,  &this =0xaf722088 ,&mEglDisplay = 1 , &mEglConfig = -1351229168 
,I/SELinux (11194): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11194): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=11194 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/OpenGLRenderer( 5973): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 5973): Enabling debug mode 0
,D/mali_winsys( 5973): new_window_surface returns 0x3000,  [616x201]-format:1
,I/ActivityManager( 3521): Killing 10302:com.android.calendar/u0a164 (adj 13): bgCount ##31
,I/dhcpcd  (10753): wlan0: sending IPv6 Router Solicitation
,D/TimaKeyStoreProvider(11194): TimaSignature is unavailable
,D/ActivityThread(11194): Added TimaKeyStore provider
,D/ResourcesManager(11194): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(11194): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11194): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11194): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(11194): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(11194): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(11194): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,I/ActivityManager( 3521): Killing 9666:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,I/iu.SyncManager( 4449): SYNC; picasa accounts
,D/NetworkLogImpl( 4449): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4449): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4449): num queued entries: 0
,I/iu.UploadsManager( 4449): num updated entries: 0
,I/iu.SyncManager( 4449): NEXT; no task
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10014
,E/Zygote  (11215): MountEmulatedStorage()
E/Zygote  (11215): v2
I/libpersona(11215): KNOX_SDCARD checking this for 10013
I/libpersona(11215): KNOX_SDCARD not a persona
,I/SELinux (11215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11215): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=11215 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (11215): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11215): TimaSignature is unavailable
,D/ActivityThread(11215): Added TimaKeyStore provider
,D/ResourcesManager(11215): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/ResourcesManager( 4240): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/WaitQueueForNetworkActivate(11215): notifyNetworkActivated
,I/GCM     ( 4240): GCM config loaded
,W/ContextImpl(11215): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3521): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/SA      (11056): [RC New] [v2liruge] api execute + 640
I/SA      (11056): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11056): AsyncTask #1 calls detatch()
,I/SA      (11056): [TPMU] getNetworkMcc : 
,I/SA      (11056): [SCU] saveMccToPreferece Start
I/SA      (11056): [SCU] RegionMCC : 260
I/SA      (11056): [SSP] query invoked
,I/SA      (11056): [TPMU] GetMccFromDB : null
I/SA      (11056): [SCU] getMccFromPreferece mcc = 260
I/SA      (11056): [SCU] saveMccToPreferece End
,I/SA      (11056): [RC New] executeRequest [v2liruge] end. 674
I/SA      (11056): [RC New] Execute end
,I/SA      (11056): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11056): [OR] GetMyCountryZoneTask Success
,D/hcjo    (11215): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(11215): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(11215): exit::IDLE
D/InitializeManagerStateMachine(11215): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(11215): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(11215): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(11215): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11215): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(11215): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11215): entry::SUCCESS
D/hcjo    (11215): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (11215): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,I/FOTA_Client(10962): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/splitIntent( 3521): Split this intent : android.intent.action.TIME_SET !!   mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=17 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 3521): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client(10962): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,E/Zygote  (11240): MountEmulatedStorage()
I/libpersona(11240): KNOX_SDCARD checking this for 10052
E/Zygote  (11240): v2
I/libpersona(11240): KNOX_SDCARD not a persona
,I/SELinux (11240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=11240 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux (11240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11240): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11255): MountEmulatedStorage()
E/Zygote  (11255): v2
I/libpersona(11255): KNOX_SDCARD checking this for 10164
I/libpersona(11255): KNOX_SDCARD not a persona
,I/SELinux (11255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11255): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=11255 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11240): TimaSignature is unavailable
,D/ActivityThread(11240): Added TimaKeyStore provider
,D/hcjo    (11215): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (11215): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(11215): exit::SUCCESS
D/InitializeManagerStateMachine(11215): entry::IDLE
,D/TimaKeyStoreProvider(11255): TimaSignature is unavailable
,I/KLMS-2.4.521: (10979): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Jan 21 17:45:49 GMT+01:00 2016
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 3777): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/ActivityThread(11255): Added TimaKeyStore provider
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.4.521: (10979): KLMSAbstractReciever(): onReceive().END.
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11240): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/ResourcesManager(11255): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11240): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(11240): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11240): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11240): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11240): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(11240): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (10979): KLMSIntentService(): onCreate()
,E/Zygote  (11272): MountEmulatedStorage()
E/Zygote  (11272): v2
I/libpersona(11272): KNOX_SDCARD checking this for 10036
I/libpersona(11272): KNOX_SDCARD not a persona
,I/SELinux (11272): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (10979): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SELinux (11272): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
I/ActivityManager( 3521): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/com.cigna.mobile.coach.CoachBroadcastReceiver: pid=11272 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
E/SELinux (11272): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/comsamsunglog( 3777): [MSC_Daemon]>>> ====================================================================================================================
I/KLMS-2.4.521: (10979): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/comsamsunglog( 3777): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
,W/ResourcesManager(11255): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/comsamsunglog( 3777): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3777): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.4.521: (10979): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
W/ResourcesManager(11255): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (10979): KLMSIntentService(): TIME_CHANGED
W/ResourcesManager(11255): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11255): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (10979): StateImplV2(): dateTimeChanged().START : Thu Jan 21 17:45:49 GMT+01:00 2016
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3777): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 3777): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/TimaKeyStoreProvider(11272): TimaSignature is unavailable
,D/comdaemonstockapp( 3777): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 3777): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/ActivityThread(11272): Added TimaKeyStore provider
,I/KLMS-2.4.521: (10979): StateImplV2(): dateTimeChanged().END
,D/ResourcesManager(11272): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/KLMS-2.4.521: (10979): KLMSIntentService(): onDestroy()
,D/Mms/MmsApp(11240): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(11240): init before art
D/Mms/ArtClassLoader(11240): init [DONE] art
D/Mms/TelephonyPermission(11240): start operation mode monitor
,I/CheckinService( 4449): Checkin interval check for package: unspecified last checkin: 1453082886478 min interval config: 0 actual interval: 311863149
,D/ResourcesManager(11240): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11240): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/btif_config_util(10543): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRM:n  ( 3521): SIOP:: AP = 280, PST = 270, CUR = 43
,I/ActivityManager( 3521): Killing 9264:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/Mms/TelephonyPermission(11240): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(11240): isDefault true
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/Mms/MmsApp(11240): onCreate() com.android.mms
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11293): MountEmulatedStorage()
,E/Zygote  (11293): v2
I/libpersona(11293): KNOX_SDCARD checking this for 10047
I/libpersona(11293): KNOX_SDCARD not a persona
,I/SELinux (11293): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/Mms/MmsApp(11240): [start]    initCountryIso consume time = 53.893792
,D/CountryDetector( 3521): The first listener is added
,I/SELinux (11293): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11293): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=11293 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Mms/MmsApp(11240): [end]    initCountryIso consume time = 10.914875
D/Mms/MmsConfig(11240): [start]    MmsConfig.init() consume time = 0.078666
,D/Mms/MmsConfig(11240): before partial update
,D/Mms/MmsConfig(11240): Load Resize quality : 80
,D/Mms/MmsConfig(11240):  enable multiwindow = true
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8749(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 851us total 24.560ms
,D/TimaKeyStoreProvider(11293): TimaSignature is unavailable
,D/ActivityThread(11293): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 861us total 18.530ms
,E/Mms/MessageUtils(11240): setCountryDetector : update country detector info 
E/Mms/MessageUtils(11240): updateCountryIso : update country iso info 
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 436us total 12.997ms
,D/Mms/PackageInfo(11240): com.sec.imsservice is not installed
D/Mms/MmsConfig(11240): [end]    init() consume time = 53.603875
,D/Mms/Contact(11240): [start]    init() consume time = 1.594
,D/SecurityLogAgent(10587): KnoxConfiguration : Current State = 0
,D/SecurityLogAgent(10587): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent(10587): StateMachine : Initialized
,D/SecurityLogAgent(10587): StateMachine : Changed Current State = 0
,D/SecurityLogAgent(10587): StateMachine : Current State = 0
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/Mms/Contact(11240): [end]    init consume time = 19.844959
,D/ResourcesManager(11293): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager(11293): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/Zygote  (11320): MountEmulatedStorage()
E/Zygote  (11320): v2
I/libpersona(11320): KNOX_SDCARD checking this for 10191
D/Mms/DraftCache(11240): [start]    rebuildCache consume time = 15.829708
I/libpersona(11320): KNOX_SDCARD not a persona
,I/SELinux (11320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11320): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=11320 uid=10191 gids={50191, 9997} abi=armeabi-v7a
,D/Mms/TelephonyUtils(11240): getSubId from simSlot 0, return Value = -1
D/TP/MmsSmsProvider( 3981): query,matched:12, calling pid = 11240
,D/Mms/DownloadManager(11240): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11240): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11240): auto download without roaming -> true
,D/Mms/DownloadManager(11240): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/TP/MmsSmsProvider( 3981): match 12:Elapsed time : 1.804 ms
,E/Mms/TelephonyUtils(11240): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(11240): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(11240): roaming -> false (slotId = 1)
D/Mms/DownloadManager(11240): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(11240): auto download without roaming -> true
D/Mms/DownloadManager(11240): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(11240): auto download during roaming secondary -> false
D/Mms/DownloadManager(11240): mAutoDownload ------> true
,I/CalendarProvider2(11293): CalendarProvider2.onCreate() called
,D/TP/MmsSmsProvider( 3981): query,matched:13, calling pid = 11240
,D/TimaKeyStoreProvider(11320): TimaSignature is unavailable
D/TP/MmsSmsProvider( 3981): match 13:Elapsed time : 1.326 ms
,D/ActivityThread(11320): Added TimaKeyStore provider
,D/Mms/Conversation(11240): [start]    init() consume time = 36.152542
,D/Mms/MmsApp(11240): [end]    onCreate() consume time = 0.498291
,D/Mms/DraftCache(11240): [end]    rebuildCache consume time = 4.182792
,D/TP/MmsSmsProvider( 3981): deleteConversation threadId: 9223372036854775807
,D/Mms/DownloadManager(11240): Service state changed: Bundle[mParcelledData.dataSize=692]
,D/Mms/DownloadManager(11240): roaming ------> false, mSimSlot = 0
,D/ResourcesManager(11320): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,D/TP/MmsSmsProvider( 3981): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): checkState()
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(11320): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): checkState() : APP TYPE = Full
,D/Mms/TelephonyUtils(11240): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(11240): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11240): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11240): auto download without roaming -> true
D/Mms/DownloadManager(11240): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(11240): mAutoDownload ------> true
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/Zygote  (11339): MountEmulatedStorage()
,E/Zygote  (11339): v2
I/libpersona(11339): KNOX_SDCARD checking this for 10069
I/libpersona(11339): KNOX_SDCARD not a persona
,E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
I/SELinux (11339): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
,I/SELinux (11339): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=11339 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11339): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 3981): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 3981): need read changed broadcast:false
,E/Zygote  (11351): MountEmulatedStorage()
,E/Zygote  (11351): v2
I/libpersona(11351): KNOX_SDCARD checking this for 10019
I/libpersona(11351): KNOX_SDCARD not a persona
,I/SELinux (11351): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11351): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11351): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=11351 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 35506(2MB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 48MB/64MB, paused 2.460ms total 143.082ms
,I/ActivityManager( 3521): Killing 10646:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/Mms/Conversation(11240): [end]    init consume time = 58.6595
D/Mms/MessagingNotification(11240): [start]    init() consume time = 0.09675
I/ActivityManager( 3521): Killing 9950:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11339): TimaSignature is unavailable
,D/ActivityThread(11339): Added TimaKeyStore provider
,I/PowerManagerService( 3521): [PWL] Off : 50s ago
,I/PowerManagerService( 3521): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3521): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 3521): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10014, pid=4240, ws=WorkSource{10014 com.google.android.gms}) (elapsedTime=486)
I/PowerManagerService( 3521): [PWL]       PARTIAL_WAKE_LOCK              'StartingAlertService' (uid=10164, pid=11255, ws=null) (elapsedTime=254)
,I/PowerManagerService( 3521): [PWL]       PARTIAL_WAKE_LOCK              'StartingAlertService' (uid=10164, pid=11255, ws=null) (elapsedTime=206)
I/PowerManagerService( 3521): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.reminders.notification.NotificationService' (uid=10014, pid=4449, ws=null) (elapsedTime=202)
I/PowerManagerService( 3521): [PWL]       PARTIAL_WAKE_LOCK              'WakefulIntentService[NotificationService]' (uid=10014, pid=4449, ws=WorkSource{10014 com.google.android.gms}) (elapsedTime=195)
,D/TimaKeyStoreProvider(11351): TimaSignature is unavailable
,D/Mms/MessagingNotification(11240): [end]    init consume time = 24.718542
,D/ActivityThread(11351): Added TimaKeyStore provider
,D/Mms/Synchronizer(11240): [start]    doSync consume time = 3.259416
,D/Mms/SpamFilter(11240): [start]    SpamFilter fill() begin consume time = 2.931834
,D/TP/MmsSmsProvider( 3981): query,matched:0, calling pid = 11240
,V/TP/MmsSmsProvider( 3981): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3981): match 0:Elapsed time : 2.463 ms
,D/ResourcesManager(11339): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,D/ResourcesManager(11351): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,I/PhenotypeConfigurator( 4240): Scheduling Phenotype for one-off execution 11066 seconds from now (1453394749942)
,D/TP/MmsSmsProvider( 3981): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 3981): syncDBData start
,V/TP/MmsSmsProvider( 3981): syncDBData sms end
,V/TP/MmsSmsProvider( 3981): syncDBData mms end
,E/JavaBinder(11240): !!! FAILED BINDER TRANSACTION !!!
,D/TP/MmsSmsProvider( 3981): query,matched:400, calling pid = 11240
V/TP/MmsSmsProvider( 3981): syncDBData end
,D/Mms/Synchronizer(11240): [end]    doSync consume time = 52.411083
,I/ActivityThread(11240): Removing dead content provider:android.content.ContentProviderProxy@274aaa4
,D/Mms/MessagingNotification(11240): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 3981): query,matched:26, calling pid = 11240
,D/TP/SmsProvider( 3981): match 26:Elapsed time : 1.490 ms
,D/Mms/SpamFilter(11240): [end]    SpamFilter fill() finished consume time = 14.183042
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:-163, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-250
D/BatteryService( 3521): stay LED for fully charged
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/TP/MmsSmsProvider( 3981): query,matched:6, calling pid = 11240
,D/GetConfigurationSnapshotOperation( 4240): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/TP/MmsSmsProvider( 3981): match 6:Elapsed time : 1.675 ms
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/accuweather( 5174): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 5174): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthServiceInstalled() : HealthService is Installed.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/ Time Manager (11339): Time Difference not stored. TIME_DIFFERENCE
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/com.sec.android.service.health.keyManager.KeyManager(11272): Current encrypted state : -1
,I/SecSQLiteOpenHelper(11272): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper(11272): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11272): Open platform.db in secure mode
D/SecSQLiteDatabase(11272): Android Version: 5.0.1
,D/SecSQLiteDatabase(11272): Load library secsqlite.so for Android 5.0.1
,I/PhenotypeFlagCommitter( 4240): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4240): Using platform SSLCertificateSocketFactory
E/Zygote  (11382): MountEmulatedStorage()
I/libpersona(11382): KNOX_SDCARD checking this for 10094
E/Zygote  (11382): v2
I/libpersona(11382): KNOX_SDCARD not a persona
,I/SELinux (11382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SecSQLiteDatabase(11272): openSecureDatabase...
I/SELinux (11382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=11382 uid=10094 gids={50094, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SecSQLiteDatabase(11272): private openSecureDatabase...
,I/SecSQLiteConnectionPool(11272): OpenSecure
E/SELinux (11382): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SecSQLiteConnectionPool(11272): OpenSecure with password
I/SecSQLiteConnectionPool(11272): openSecureConnectionLocked
,I/SecSQLiteDatabase(11272): ...private openSecureDatabase
I/SecSQLiteDatabase(11272): ...openSecureDatabase
,I/Mms/ReservationManager(11240): ReservationManager()
,I/ActivityManager( 3521): Killing 10269:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,I/Mms/ReservationManager(11240): resetAfterConnected()
,D/TimaKeyStoreProvider(11382): TimaSignature is unavailable
,D/ActivityThread(11382): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 3981): query,matched:7, calling pid = 11240
,D/TP/MmsSmsProvider( 3981): match 7:Elapsed time : 3.638 ms
,I/Mms/ReservationManager(11240): getReservedSendMessageCount(): retMessageCount=0
,D/ResourcesManager(11382): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,W/ResourcesManager(11382): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager(11382): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,E/SQLiteLog(11272): (26) statement aborts at 0: [PRAGMA user_version;] file is encrypted or is not a database
,E/SecDefaultDatabaseErrorHandler(11272): Corruption reported by sqlite on database: /data/data/com.sec.android.app.shealth/databases/platform.db
E/SecDefaultDatabaseErrorHandler(11272): backup the database file: /data/data/com.sec.android.app.shealth/databases/platform.db
,D/SecSQLiteOpenHelper(11272): ...getDatabaseLocked(b,b,pwd)
,W/ResourcesManager(11382): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11382): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11382): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(11382): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11398): MountEmulatedStorage()
I/libpersona(11398): KNOX_SDCARD checking this for 10028
E/Zygote  (11398): v2
I/libpersona(11398): KNOX_SDCARD not a persona
I/SELinux (11398): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11398): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11398): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=11398 uid=10028 gids={50028, 9997} abi=armeabi-v7a
,I/SecureStorage(11351): [INFO]: SPID(0x00000000)Processing data
D/PackageManager( 3521): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/ActivityManager( 3521): Killing 10735:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31,
I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Credentials: uid 10019, gid 10019, pid 11351
I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,D/TimaKeyStoreProvider(11398): TimaSignature is unavailable
,D/ActivityThread(11398): Added TimaKeyStore provider
,I/ActivityManager( 3521): Killing 7801:com.android.settings/1000 (adj 13): bgCount ##31
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ResourcesManager(11398): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,W/ResourcesManager(11398): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/SettingsProvider( 3521): name = next_alarm_formatted
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10094
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,V/GLSActivity( 4240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/OMACP   (11398): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,V/GLSActivity( 4240): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Mms/Omacp(11240): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/WifiService( 3521): Client connection lost with reason: 4
,I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,D/Mms/ArtClassLoader(11240): init before art
D/Mms/ArtClassLoader(11240): init [DONE] art
,I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,D/Mms/PerformanceUtils(11240): link cahcing start
I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   (11398): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,I/System.out( 4240): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10014
,D/Mms/PerformanceUtils(11240): link cahcing done
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11416): MountEmulatedStorage()
E/Zygote  (11416): v2
I/libpersona(11416): KNOX_SDCARD checking this for 10106
I/libpersona(11416): KNOX_SDCARD not a persona
,I/SELinux (11416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11416): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/System.out( 4240): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ActivityManager( 3521): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11416 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 8245:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
,I/qtaguid ( 4240): Tagging socket 78 with tag 1000040100000000{268436481,0} uid 10014, pid: 4240, getuid(): 10014
,D/TimaKeyStoreProvider(11416): TimaSignature is unavailable
,D/ActivityThread(11416): Added TimaKeyStore provider
,I/qtaguid ( 4240): Tagging socket 82 with tag 1000040100000000{268436481,0} uid 10014, pid: 4240, getuid(): 10014
,D/ResourcesManager(11416): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/elm:14491(11416): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491(11416): ELMEngine.ELMEngine( context ).
,D/elm:14491(11416): MDMBridge.setEnterpriseBridge()
,D/elm:14491(11416): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/elm:14491(11416): ElmAgentService : onCreate()
,D/elm:14491(11416): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14491(11416): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491(11416): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491(11416): ModuleBase.ModifySetAlarm()
D/elm:14491(11416): MDMBridge.getInstance()
D/elm:14491(11416): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (11433): MountEmulatedStorage()
,E/Zygote  (11433): v2
I/libpersona(11433): KNOX_SDCARD checking this for 10163
I/libpersona(11433): KNOX_SDCARD not a persona
,I/SELinux (11433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=11433 uid=10163 gids={50163, 9997} abi=armeabi-v7a
,I/SELinux (11433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11433): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/elm:14491(11416): ElmAgentService : onDestroy().
,I/ActivityManager( 3521): Killing 10211:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11433): TimaSignature is unavailable
,D/ActivityThread(11433): Added TimaKeyStore provider
,D/ResourcesManager(11433): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(11433): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11433): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/ActivityManager( 3521): Killing 10813:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,I/SecureStorage( 2919): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
,I/System.out( 4240): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10014
,I/CalendarProvider2(11293): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager( 3521): Killing 10847:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,I/System.out( 4240): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4240): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 4240, getuid(): 10014
,I/qtaguid ( 4240): Tagging socket 85 with tag 1000120100000000{268440065,0} uid -1, pid: 4240, getuid(): 10014
,V/AlarmManager( 3521): waitForAlarm result :4
,I/SecureStorage(11351): [INFO]: SPID(0x00000006)Processing data has been completed
,I/SecureStorage(11351): [INFO]: SPID(0x00000006)Skip using SecureStorageExceptionJNI
,I/SecSQLiteOpenHelper(11272): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11272): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11272): Open platform.db in secure mode
I/SecSQLiteDatabase(11272): openSecureDatabase...
I/SecSQLiteDatabase(11272): private openSecureDatabase...
I/SecSQLiteConnectionPool(11272): OpenSecure
I/SecSQLiteConnectionPool(11272): OpenSecure with password
I/SecSQLiteConnectionPool(11272): openSecureConnectionLocked
I/SecSQLiteDatabase(11272): ...private openSecureDatabase
I/SecSQLiteDatabase(11272): ...openSecureDatabase
,I/SecSQLiteOpenHelper(11272): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11272): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/-----SIC-----(11272): ------------------skip TGH
,I/SecSQLiteOpenHelper(11272): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11272): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11272): Open platform.db in secure mode
I/SecSQLiteDatabase(11272): openSecureDatabase...
I/SecSQLiteDatabase(11272): private openSecureDatabase...
I/SecSQLiteConnectionPool(11272): OpenSecure
I/SecSQLiteConnectionPool(11272): OpenSecure with password
I/SecSQLiteConnectionPool(11272): openSecureConnectionLocked
I/SecSQLiteDatabase(11272): ...private openSecureDatabase
I/SecSQLiteDatabase(11272): ...openSecureDatabase
,I/SecSQLiteOpenHelper(11272): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11272): ...getDatabaseLocked(b,b,pwd)
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11272): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11272): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer(11272): decode(33, 20909908, 4230)
,V/MediaPlayerService( 2855): decode(26, 20909908, 4230)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20909908, 4230)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
,V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
,I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/SO_AGENT(10995): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2855): wait for playback complete
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/SA      (11056): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11272): decode(36, 20763080, 15440)
V/MediaPlayerService( 2855): decode(26, 20763080, 15440)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20763080, 15440)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
V/AudioCache( 2855): notify(0xb020d1f0, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
V/MediaPlayerService( 2855): wait for playback complete
,I/ActivityManager( 3521): Killing 10864:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
D/AdaptiveEventManager( 3692): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
I/ActivityManager( 3521): Killing 10914:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
D/AdaptiveEventManager( 3692): M updateContainers()
D/AdaptiveEventContainerSmall( 3692): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3692): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3692): pedoEvent == null
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
D/AdaptiveEventManager( 3692): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3692): M updateContainers()
D/AdaptiveEventContainerSmall( 3692): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3692): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3692): pedoEvent == null
V/MediaPlayer(11272): decode(37, 20807608, 9226)
V/MediaPlayerService( 2855): decode(26, 20807608, 9226)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20807608, 9226)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
E/DatabaseUtils( 3521): Writing exception to parcel
E/DatabaseUtils( 3521): java.lang.NullPointerException: key == null
E/DatabaseUtils( 3521): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils( 3521): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils( 3521): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils( 3521): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:376)
E/DatabaseUtils( 3521): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils( 3521): 	at android.os.Binder.execTransact(Binder.java:446)
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 6, 0, 0)
V/AudioCache( 2855): ignored
I/AudioPlayer( 2855): First fillBuffer call!!
V/AwesomePlayer( 2855): addBatteryData
V/MediaPlayerService( 2855): wait for playback complete
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
W/System.err( 9858): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
W/System.err(11272): java.lang.NumberFormatException: Invalid int: "null"
W/System.err(11272): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err(11272): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err(11272): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err(11272): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:498)
W/System.err(11272): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1242)
W/System.err(11272): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11272): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11272): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 9858): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err( 9858): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err( 9858): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err( 9858): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err( 9858): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
W/System.err( 9858): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
I/splitIntent( 3521): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
W/System.err( 9858): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
W/System.err( 9858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9858): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9858): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9858): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9858): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 9858): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9858): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11272): decode(38, 20914220, 4890)
V/MediaPlayerService( 2855): decode(26, 20914220, 4890)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20914220, 4890)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/System.out( 4240): (HTTPLog)-Static: isSBSettingEnabled false
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/qtaguid ( 4240): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 4240, getuid(): 10014
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
V/MediaPlayerService( 2855): wait for playback complete
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11272): decode(39, 20840384, 17329)
V/MediaPlayerService( 2855): decode(26, 20840384, 17329)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20840384, 17329)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2855): wait for playback complete
E/Zygote  (11505): MountEmulatedStorage()
E/Zygote  (11505): v2
I/libpersona(11505): KNOX_SDCARD checking this for 10022
I/libpersona(11505): KNOX_SDCARD not a persona
I/SELinux (11505): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11505): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11505): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=11505 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11272): decode(40, 20740576, 6644)
V/MediaPlayerService( 2855): decode(26, 20740576, 6644)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
,V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20740576, 6644)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 8, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
,I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
,V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/TimaKeyStoreProvider(11505): TimaSignature is unavailable
,D/ActivityThread(11505): Added TimaKeyStore provider
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
V/MediaPlayerService( 2855): wait for playback complete
,I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
W/ResourcesManager(11505): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
W/ResourcesManager(11505): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
W/ResourcesManager(11505): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11272): decode(41, 20816916, 23389)
V/MediaPlayerService( 2855): decode(26, 20816916, 23389)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20816916, 23389)
V/AwesomePlayer( 2855): reset_l()
,V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
,I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
,V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/System.out( 4240): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 4240): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 4240, getuid(): 10014
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 6, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2855): wait for playback complete
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
,V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11272): decode(43, 20706272, 8154)
V/MediaPlayerService( 2855): decode(26, 20706272, 8154)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20706272, 8154)
V/AwesomePlayer( 2855): reset_l()
,V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
,I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
I/LocationWidgetApplication(11505): onCreate() : start
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2855): notify(0xb040f100, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 1, 0, 0)
V/AudioCache( 2855): prepared
,V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
D/LocationWidgetApplication(11505): countryCode = POLAND
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2855): wait for playback complete
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/LocationWidgetUtils(11505): getUpcommingInstances() start: 1453394751521, end: 1453935599999
,D/LocationWidgetUtils(11505): getUpcommingInstances() DB begin time >= start:1453394751521, DB begin time <= end:1453935599999
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out,
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
,V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11272): decode(42, 20679752, 4804)
,V/MediaPlayerService( 2855): decode(31, 20679752, 4804)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
,V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(31, 20679752, 4804)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
,V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
,V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
,I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 200, 973, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 1, 0, 0)
,V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/System.out( 4240): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4240): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 4240, getuid(): 10014
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1733175209, value : 485677307
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1733175209, value : 485677307
V/MediaPlayerService( 2855): wait for playback complete
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x84, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11272): decode(44, 20649204, 9400)
V/MediaPlayerService( 2855): decode(26, 20649204, 9400)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20649204, 9400)
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
,V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
,V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
,V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 200, 973, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
,V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,V/MediaPlayer(11272): decode(50, 20722624, 4112)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/MediaPlayerService( 2855): decode(39, 20722624, 4112)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(39, 20722624, 4112)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
,V/AwesomePlayer( 2855): onPrepareAsyncEvent
V/MediaPlayerService( 2855): wait for playback complete
,I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
E/SQLiteLog(11293): (284) automatic index on view_events(_id)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 200, 973, 0)
,V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 5, 0, 0)
,V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 1, 0, 0)
V/AudioCache( 2855): prepared
,V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/MediaPlayerService( 2855): wait for playback complete
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x85, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1,
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
,I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
,I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11272): decode(45, 20857804, 52024)
V/MediaPlayerService( 2855): decode(26, 20857804, 52024)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x86, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): setDefault
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20857804, 52024)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xb040f100, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0),
,V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
,V/MediaPlayerService( 2855): wait for prepare
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
,I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/SecMediaClock( 2855): SecMediaClock constructor
I/OggExtractor( 2855): ~OggExtractor --
,I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
,V/AudioPolicyManager( 2855): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
,I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,D/CalendarAlarmManager(11293): sys current time:1453394751588
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(48000, 2, 0x0, 1, 0)
D/CalendarAlarmManager(11293): reminder amount:0
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xb040f100, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthServiceInstalled() : HealthService is Installed.
,V/MediaPlayerService( 2855): wait for playback complete
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11272): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants(11272): RegionGroup for  is null
,D/LocationManagerService( 3521): getProviders()=[]
D/LocationManagerService( 3521): getProviders()=[passive]
D/LocationManagerService( 3521): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(11505): mPrivacy is null
,W/ContextImpl(11505): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,D/ContextFramework:PrivacyManager(11505): Service for PrivacyManager is connected
,D/BluetoothManager(11272): getConnectedDevices
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
,V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x87, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
D/BluetoothManager(11272): getConnectedDevices
,D/LWLocationManager(11505): Privacy service : STATUS_PLACE
D/LWLocationManager(11505): updateLocationStatus()
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer(11272): decode(46, 20722624, 4112)
V/MediaPlayerService( 2855): decode(26, 20722624, 4112)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20722624, 4112)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
I/LocationWidgetFuctionData(11505): readDB
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/BluetoothManager(11272): getConnectedDevices
,I/LocationWidgetFuctionData(11505): selectedAppSize: 3
I/LocationWidgetFuctionData(11505): configPlaceList aroundMeItems
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
,I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
,I/AudioPlayer( 2855): First fillBuffer call!!
V/MediaPlayerService( 2855): wait for playback complete
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE,
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xae821650, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae821650, 8, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x88, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
,I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
I/libpersona(11565): KNOX_SDCARD checking this for 10003
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/libpersona(11565): KNOX_SDCARD not a persona
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11272): decode(47, 20785700, 21825)
V/MediaPlayerService( 2855): decode(26, 20785700, 21825)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20785700, 21825)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xb020d1f0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
E/Zygote  (11565): MountEmulatedStorage()
E/Zygote  (11565): v2
I/SELinux (11565): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
,I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/ActivityManager( 3521): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=11565 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/SELinux (11565): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11565): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xb020d1f0, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2855): wait for playback complete
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/BluetoothManager(11272): getConnectedDevices
,D/TimaKeyStoreProvider(11565): TimaSignature is unavailable
,D/ActivityThread(11565): Added TimaKeyStore provider
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d1f0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x89, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/ActivityManager( 3521): Killing 10944:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer(11272): decode(48, 20684636, 21552)
V/MediaPlayerService( 2855): decode(26, 20684636, 21552)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20684636, 21552)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
,V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/ResourcesManager(11565): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/BluetoothManager(11272): getConnectedDevices
D/BluetoothManager(11272): getConnectedDevices
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
V/MediaPlayerService( 2855): wait for playback complete
,I/System.out( 4240): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4240): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 4240, getuid(): 10014
,I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,I/ActivityManager( 3521): Killing 11017:com.policydm/1000 (adj 13): bgCount ##31
,D/UserAnalysis.PlaceProvider(11565): PlaceProvider onCreate()
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x8a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
,I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out,
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
,V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l(),
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
,V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11272): decode(49, 20778600, 7017)
V/MediaPlayerService( 2855): decode(31, 20778600, 7017)
,I/Mms/MmsApp(11240):  start initViewCache mms
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault,
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
,V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(31, 20778600, 7017)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 8, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
D/Mms/ComposeMessageFragment(11240): [start]    fillCache consume time = 1846.068917
D/Mms/ComposeMessageFragment(11240): fillCache, easy = false
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
,V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
,V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 200, 973, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/UserAnalysis.SecureDbManager(11565): Key for secure DB is newly created
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
D/UserAnalysis.SecurePlaceDbHelper(11565): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(11565): Create SecureDbHelper
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xb040f100, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2855): wait for playback complete
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
D/IntelligenceServiceApplication(11565): onCreate()
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb040f100, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x8b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4240): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4240): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 4240, getuid(): 10014
,I/LocationWidgetFuctionData(11505): selectedAppSize: 3
,D/AbsListView(11240): Get MotionRecognitionManager
,D/MotionRecognitionService( 3521):  ssp status : true
I/LocationWidgetFuctionData(11505): selectedAppSize: 3
,I/LocationWidgetFuctionData(11505): selectedAppSize: 3
D/Mms/ComposeMessageFragment(11240): [end]    fillCache consume time = 75.773583
,I/LocationWidgetFuctionData(11505): selectedAppSize: 3
,E/LWLocationManager(11505): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(11505): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(11505): setShouldUpdateLocationId
D/LWLocationManager(11505): setShouldUpdateLocationId return false
D/LWLocationManager(11505): setShouldUpdateLocationId
D/LWLocationManager(11505): setShouldUpdateLocationId return false
D/LWLocationManager(11505): setShouldUpdateLocationId
D/LWLocationManager(11505): setShouldUpdateLocationId return false
D/LWLocationManager(11505): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/Mms/BubbleViewCache(11240): fillCache bubble = 8
,I/SurfaceFlinger( 2850): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2850): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3521): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3521) eventTime = 146643
,D/PowerManagerService( 3521): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521 (0x0)
,D/PowerManagerService( 3521): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3521, ws=WorkSource{1000}) (elapsedTime=3480)
,I/dhcpcd  (10753): wlan0: sending IPv6 Router Solicitation
,I/System.out( 3521): Thread-147(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3521): Thread-147(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3521): Thread-147(ApacheHTTPLog):isShipBuild true
I/System.out( 3521): Thread-147(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 1000
,I/GAV4    (11111): Thread[GAThread,5,main]: No campaign data found.
,I/System.out( 3521): AsyncTask #2 calls detatch()
,W/System.err( 3521): java.io.IOException: Not Found
,W/System.err( 3521): 	at a.d.b(Unknown Source)
,W/System.err( 3521): 	at a.d.doInBackground(Unknown Source)
W/System.err( 3521): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 3521): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 3521): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3521): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 3521): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 3521): 	at java.lang.Thread.run(Thread.java:818)
,I/GAV3    (11272): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  (10753): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (10753): wlan0: no IPv6 Routers available
,W/ProcessCpuTracker( 3521): Skipping unknown process pid 11697
,D/PreloadUpdateManagerStateMachine(11215): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(11215): exit::IDLE
D/PreloadUpdateManagerStateMachine(11215): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (11215): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (11215): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(11215): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(11215): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(11215): entry::IDLE
,D/SSRM:n  ( 3521): SIOP:: AP = 270, PST = 264, CUR = -163
,V/AlarmManager( 3521): waitForAlarm result :8
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:-29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:78
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 5
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 263, CUR = -29
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3521): [PWL] Off : 75s ago
,V/AlarmManager( 3521): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/ActivityThread( 4449): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3521): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 170662, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager( 3521): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 231187, reason: UserStart
,W/ResourceType( 4967): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4967): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3521): mCursor = null
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 259, CUR = 25
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4240): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 258, CUR = 41
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3521): !@Sync 6
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 257, CUR = 44
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3521): [PWL] Off : 105s ago
,V/AlarmManager( 3521): waitForAlarm result :4
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 252, CUR = 42
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3521): Skipping unknown process pid 11800
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 249, CUR = 39
,V/AlarmManager( 3521): waitForAlarm result :8
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3521): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3521): !@Sync 7
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 248, CUR = 38
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 248, CUR = 35
,I/PowerManagerService( 3521): [PWL] Off : 140s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 245, CUR = 35
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3521): !@Sync 8
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 243, CUR = 32
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 242, CUR = 30
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(10472): TAP version 13
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # multiplex can send data
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 1 String should be length:200
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # enqueue and run in order
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 2 firstPromise setTimeout expected 0 and got 0
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 3 firstPromise result expected 10 and got 10
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 4 firstPromise testValue expected 10 and got 10
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 5 secondPromise setTimeout expected 10 and got 10,
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 6 secondPromise result expected 100 and got 100
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 7 secondPromise testValue expected 100 and got 100
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 8 thirdPromise in promise expected 100 and got 100
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 9 thirdPromise result expected 1000 and got 1000
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 10 thirdPromise result expected 1000 and got 1000
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # basic
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 11 sane
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # another
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 12 sane
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # successfully create a new pkcs12 file and return hash value
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 13 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 14 null
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 15 (unnamed assert)
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 16 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 17 should not throw
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 18 (unnamed assert)
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 19 (unnamed assert)
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 20 should not throw
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 21 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 22 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 23 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # failed to get mobile documents path
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 24 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #init should register the peerAvailabilityChanged event
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 25 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 26 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 27 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #init should register the networkChanged event
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 28 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #startBroadcasting should throw on null device name
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 29 should throw
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #startBroadcasting should throw on empty string device name
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 30 should throw
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #startBroadcasting should throw on non-number port
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 31 should throw
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #startBroadcasting should throw on NaN port
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 32 should throw
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #startBroadcasting should throw on negative port
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 33 should throw
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #startBroadcasting should throw on too large port
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 34 should throw
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 35 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 36 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 37 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 38 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 39 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 40 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 41 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 42 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log(10472): 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 241, CUR = 30
,I/PowerManagerService( 3521): [PWL] Off : 180s ago
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 43 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 44 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log(10472): 
,V/AlarmManager( 3521): waitForAlarm result :8
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 45 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 46 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 47 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 48 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 49 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # should call Mobile("Disconnect") without an error
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 50 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 51 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # should call Mobile("Disconnect") and handle an error
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 52 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 53 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown,
I/jxcore-log(10472): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394880287.10472
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394880287.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38dccda7
D/BluetoothSocket(10472): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394880287.10472
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394880287.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=b0821d74-e043-4e16-bbb0-4787b3ce24cd
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=b0821d74-e043-4e16-bbb0-4787b3ce24cd, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
,D/BtGatt.AdvertiseManager(10543): number of adv instance running0
D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10543): starting multi advertising
D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
D/BtGatt.GattService(10543): registerClient() - UUID=25840139-9fe9-4647-b28b-22e18caf27c6
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=25840139-9fe9-4647-b28b-22e18caf27c6, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10543): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager(10543): handling starting scan
,D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394880287.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394880287.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394880287.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0,
,D/BtGatt.ScanManager(10543): allow scan with filters,
,D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
,D/WifiP2pService( 3521): InactiveState{ what=139292 }
,D/BtGatt.ScanManager(10543): set filter index= 3 for clientIf= 7
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/WifiP2pService( 3521): P2pEnabledState{ what=139292 }
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/WifiP2pService( 3521): P2pEnabledState add service
I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394880287.10472
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true
,I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper(10472): start: OK
,D/WifiP2pService( 3521): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
,I/jxcore-log(10472): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
,D/WifiP2pService( 3521): InactiveState{ what=139265 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
,D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3521): callSECApi what=74
,D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
,I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
,I/io.jxcore.node.ConnectionHelper(10472): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
,D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@17258fc0, channel: 6, state: LISTENING
,D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@17258fc0, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38dccda7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b4ae4f9mSocket: android.net.LocalSocket@223d8c3e impl:android.net.LocalSocketImpl@ae3ca9f fd:FileDescriptor[118]
,D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@223d8c3e impl:android.net.LocalSocketImpl@ae3ca9f fd:FileDescriptor[118]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
,D/WifiP2pService( 3521): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager(10543): message : 1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
,D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10543): Client app is not null!
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10543): stopScan() - queue size =1
,D/BtGatt.ScanManager(10543): filter size is 1
D/BtGatt.ScanManager(10543): delete FilterIndex - 3
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
D/WifiP2pService( 3521): InactiveState{ what=139298 }
D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10543): Plain text(LSB ~ MSB) = cb 1d 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
D/WifiP2pService( 3521): P2pEnabledState clear service
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = 94 42 f7 7a 07 c9 a8 b2 a9 5b ae 38 2a 2d 4b a2 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
D/WifiP2pService( 3521): remove client information from framework
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
I/wpa_supplicant(10558): P2P-FIND-STOPPED 
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): stop scan
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,I/jxcore-log(10472): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
D/WifiP2pService( 3521): InactiveState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
D/WifiP2pService( 3521): InactiveState{ what=147493 }
D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3521): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394880638.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394880638.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9cbd7b5
D/BluetoothSocket(10472): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394880638.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394880638.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=47406aff-fa58-4477-bc26-1a4be86f20fa
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=47406aff-fa58-4477-bc26-1a4be86f20fa, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
D/BtGatt.AdvertiseManager(10543): number of adv instance running0
D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): starting multi advertising
,D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=91930473-2f55-465b-94f1-9d2d9d7dcf04
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=91930473-2f55-465b-94f1-9d2d9d7dcf04, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10543): start scan with filters
,D/BtGatt.ScanManager(10543): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394880638.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394880638.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394880638.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3521): InactiveState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState add service
,D/WifiP2pService( 3521): add a new client
,D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): allow scan with filters
D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager(10543): set filter index= 4 for clientIf= 7
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
D/WifiP2pService( 3521): InactiveState{ what=139265 }
D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3521): callSECApi what=74
D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
I/wpa_supplicant(10558): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394880638.10472
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/io.jxcore.node.ConnectionHelper(10472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
I/jxcore-log(10472): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
D/WifiP2pService( 3521): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper(10472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@7bce516, channel: 6, state: LISTENING
D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@7bce516, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9cbd7b5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e3e6e97mSocket: android.net.LocalSocket@6114884 impl:android.net.LocalSocketImpl@338c486d fd:FileDescriptor[118]
D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@6114884 impl:android.net.LocalSocketImpl@338c486d fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
,D/BtGatt.AdvertiseManager(10543): message : 1
I/wpa_supplicant(10558): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
D/WifiP2pService( 3521): InactiveState{ what=147493 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3521): discovery change broadcast false
,D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10543): Client app is not null!
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
D/BtGatt.GattService(10543): stopScan() - queue size =1
,D/BtGatt.ScanManager(10543): filter size is 1
D/BtGatt.ScanManager(10543): delete FilterIndex - 4
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
D/WifiP2pService( 3521): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
D/WifiP2pService( 3521): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
,W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10543): Plain text(LSB ~ MSB) = ec 7c 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = 49 b5 3b 3b 1f 1e af 13 66 e8 23 8c 08 e4 f0 8f 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3521): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
D/WifiP2pService( 3521): InactiveState{ what=139268 }
,I/jxcore-log(10472): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): stop scan
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
D/WifiP2pService( 3521): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394880873.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394880873.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@af15d33
D/BluetoothSocket(10472): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394880873.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394880873.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=cd8bf3be-61de-4e02-a74b-55383e6eebbf
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=cd8bf3be-61de-4e02-a74b-55383e6eebbf, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
,D/BtGatt.AdvertiseManager(10543): number of adv instance running0
D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): starting multi advertising
,D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=d19aab7c-8a8b-4e58-b96c-d9ca805bba41
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=d19aab7c-8a8b-4e58-b96c-d9ca805bba41, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10543): start scan with filters
,D/BtGatt.ScanManager(10543): handling starting scan
,D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): allow scan with filters
D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager(10543): set filter index= 5 for clientIf= 7
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394880873.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394880873.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394880873.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3521): InactiveState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139292 },
,D/WifiP2pService( 3521): P2pEnabledState add service
,D/WifiP2pService( 3521): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
,D/WifiP2pService( 3521): InactiveState{ what=139265 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/WifiStateMachine( 3521): callSECApi what=74
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394880873.10472
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper(10472): start: OK
,I/wpa_supplicant(10558): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
,D/WifiP2pService( 3521): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log(10472): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
,I/wpa_supplicant(10558): P2P-FIND-STOPPED 
,I/io.jxcore.node.ConnectionHelper(10472): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
,D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@3977241c, channel: 6, state: LISTENING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@3977241c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@af15d33, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e631825mSocket: android.net.LocalSocket@232abdfa impl:android.net.LocalSocketImpl@28713fab fd:FileDescriptor[118]
,D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@232abdfa impl:android.net.LocalSocketImpl@28713fab fd:FileDescriptor[118]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
,D/ScanRecord(10543): parseFromBytes
,D/ScanRecord(10543): first manudata for manu ID
,D/BtGatt.GattService(10543): result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=275425970198}
,D/BtGatt.GattService(10543): filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,D/BtGatt.ContextMap(10543): sendClientScanResult for app id 7
,D/ScanRecord(10472): parseFromBytes
,D/ScanRecord(10472): first manudata for manu ID
,D/BluetoothLeScanner(10472): onScanResult() - ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=275425970198}
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=275425970198}
,D/WifiP2pService( 3521): InactiveState{ what=147493 }
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager(10543): message : 1
,D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
,D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
,D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3521): discovery change broadcast false
,D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10543): Client app is not null!
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10543): Plain text(LSB ~ MSB) = 33 a0 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = 74 b9 95 f1 03 b1 95 9f 0e 3b a6 8a c0 51 22 c8 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
,D/BtGatt.GattService(10543): stopScan() - queue size =1
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
D/BtGatt.ScanManager(10543): filter size is 1
D/BtGatt.ScanManager(10543): delete FilterIndex - 5
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): stop scan
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
,D/WifiP2pService( 3521): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
D/WifiP2pService( 3521): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...
D/WifiP2pService( 3521): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
D/WifiP2pService( 3521): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
I/jxcore-log(10472): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
D/WifiP2pService( 3521): InactiveState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
,D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394881197.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394881197.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ad211a1
D/BluetoothSocket(10472): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394881197.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394881197.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=f5c60648-967c-42db-aadd-3d0ea5c69c84
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10543): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10543): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=f5c60648-967c-42db-aadd-3d0ea5c69c84, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
D/BtGatt.AdvertiseManager(10543): number of adv instance running0
D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): starting multi advertising
,D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=798b7530-ec22-4197-9fe4-96c9d86f0096
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=798b7530-ec22-4197-9fe4-96c9d86f0096, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10543): start scan with filters
,D/BtGatt.ScanManager(10543): handling starting scan
,D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): allow scan with filters
,D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager(10543): set filter index= 6 for clientIf= 7
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394881197.10472","ra":"E0:DB:10:14:E2:C0"}
,I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394881197.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394881197.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3521): InactiveState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState add service
,D/WifiP2pService( 3521): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
,D/WifiP2pService( 3521): InactiveState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
,D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394881197.10472
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper(10472): start: OK
D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3521): callSECApi what=74
,D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
,I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant(10558): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log(10472): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
,D/ScanRecord(10543): parseFromBytes
,D/ScanRecord(10543): first manudata for manu ID
D/BtGatt.GattService(10543): result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=275675960114}
,D/BtGatt.GattService(10543): filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
D/BtGatt.ContextMap(10543): sendClientScanResult for app id 7
D/WifiP2pService( 3521): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper(10472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@37ef1252, channel: 6, state: LISTENING
D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@37ef1252, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ad211a1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@25cbf923mSocket: android.net.LocalSocket@11d3ee20 impl:android.net.LocalSocketImpl@368a53d9 fd:FileDescriptor[118]
D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@11d3ee20 impl:android.net.LocalSocketImpl@368a53d9 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
,D/ScanRecord(10472): parseFromBytes
D/ScanRecord(10472): first manudata for manu ID
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
D/BluetoothLeScanner(10472): onScanResult() - ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=275675960114}
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=275675960114}
,D/BtGatt.AdvertiseManager(10543): message : 1
D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/wpa_supplicant(10558): P2P-FIND-STOPPED 
,D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
D/WifiP2pService( 3521): InactiveState{ what=147493 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3521): discovery change broadcast false
,D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10543): Client app is not null!
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10543): stopScan() - queue size =1
D/BtGatt.ScanManager(10543): filter size is 1
D/BtGatt.ScanManager(10543): delete FilterIndex - 6
D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiP2pService( 3521): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...
D/WifiP2pService( 3521): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
,W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
D/WifiP2pService( 3521): remove client information from framework
W/bt-smp  (10543): Plain text(LSB ~ MSB) = 2f bb 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = 60 7b 4b 77 e8 e6 ef cd a3 d6 11 95 a3 69 03 bb 
D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/jxcore-log(10472): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): stop scan
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
D/WifiP2pService( 3521): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
D/WifiP2pService( 3521): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394881420.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394881420.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a5b047f
D/BluetoothSocket(10472): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394881420.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394881420.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=15e6fe15-e035-4eef-8076-8d0117529ae7
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=15e6fe15-e035-4eef-8076-8d0117529ae7, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
,D/BtGatt.AdvertiseManager(10543): number of adv instance running0
,D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
,D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): starting multi advertising
,D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=a23d26b1-c05f-44ce-a2a7-50ebc834d675
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=a23d26b1-c05f-44ce-a2a7-50ebc834d675, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService(10543): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager(10543): handling starting scan
,D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394881420.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394881420.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394881420.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.ScanManager(10543): allow scan with filters
D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10543): set filter index= 7 for clientIf= 7
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 51266(3MB) AllocSpace objects, 53(3MB) LOS objects, 24% free, 48MB/64MB, paused 3.455ms total 192.493ms
,D/WifiP2pService( 3521): InactiveState{ what=139292 }
D/WifiP2pService( 3521): P2pEnabledState{ what=139292 }
,D/ScanRecord(10543): parseFromBytes
D/ScanRecord(10543): first manudata for manu ID
D/WifiP2pService( 3521): P2pEnabledState add service
D/BtGatt.GattService(10543): result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-80, mTimestampNanos=276057601198}
D/BtGatt.GattService(10543): filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
D/BtGatt.ContextMap(10543): sendClientScanResult for app id 7
D/ScanRecord(10543): parseFromBytes
D/ScanRecord(10543): first manudata for manu ID
D/BtGatt.GattService(10543): result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-79, mTimestampNanos=276058141364}
D/BtGatt.GattService(10543): filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,D/BtGatt.ContextMap(10543): sendClientScanResult for app id 7
D/ScanRecord(10472): parseFromBytes
D/ScanRecord(10472): first manudata for manu ID
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
D/WifiP2pService( 3521): add a new client
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394881420.10472
I/io.jxcore.node.ConnectionHelper(10472): start: OK
D/BluetoothLeScanner(10472): onScanResult() - ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-80, mTimestampNanos=276057601198}
D/ScanRecord(10472): parseFromBytes
D/ScanRecord(10472): first manudata for manu ID
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
D/WifiP2pService( 3521): InactiveState{ what=139265 }
D/BluetoothLeScanner(10472): onScanResult() - ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-79, mTimestampNanos=276058141364}
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true
I/WifiStateMachine( 3521): callSECApi what=74
D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-80, mTimestampNanos=276057601198}
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-79, mTimestampNanos=276058141364}
I/wpa_supplicant(10558): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
D/WifiP2pService( 3521): discovery change broadcast true
I/jxcore-log(10472): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/wpa_supplicant(10558): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper(10472): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@277d6138, channel: 6, state: LISTENING
D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@277d6138, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a5b047f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d51a511mSocket: android.net.LocalSocket@2834a676 impl:android.net.LocalSocketImpl@1e670477 fd:FileDescriptor[118]
D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@2834a676 impl:android.net.LocalSocketImpl@1e670477 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
D/WifiP2pService( 3521): InactiveState{ what=147493 }
D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3521): discovery change broadcast false
D/BtGatt.AdvertiseManager(10543): message : 1
D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
,D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10543): Client app is not null!
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10543): stopScan() - queue size =1
,D/BtGatt.ScanManager(10543): filter size is 1
D/BtGatt.ScanManager(10543): delete FilterIndex - 7
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10543): Plain text(LSB ~ MSB) = 76 0b 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = 4f 44 5c 84 37 6c 56 4a 7e 3d f8 82 a0 75 75 69 
,D/WifiP2pService( 3521): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 3521): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): stop scan
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
D/WifiP2pService( 3521): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/jxcore-log(10472): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
D/WifiP2pService( 3521): InactiveState{ what=139307 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394881813.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394881813.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@61a814d
D/BluetoothSocket(10472): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394881813.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394881813.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=d4679720-2370-42ff-8365-55df9cd3161d
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=d4679720-2370-42ff-8365-55df9cd3161d, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
,D/BtGatt.AdvertiseManager(10543): number of adv instance running0
D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
,D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): starting multi advertising
,D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=d32b3e43-421c-4199-95db-4ddf19b6831b
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=d32b3e43-421c-4199-95db-4ddf19b6831b, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10543): start scan with filters
,D/BtGatt.ScanManager(10543): handling starting scan,
,D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394881813.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394881813.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394881813.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.ScanManager(10543): allow scan with filters
,D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10543): set filter index= 8 for clientIf= 7
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3521): InactiveState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState add service
,D/WifiP2pService( 3521): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
,D/WifiP2pService( 3521): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
,D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394881813.10472
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper(10472): start: OK
D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3521): callSECApi what=74
,D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
,I/jxcore-log(10472): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
,D/WifiP2pService( 3521): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper(10472): stop
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/wpa_supplicant(10558): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@36c60e4e, channel: 6, state: LISTENING
,D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@36c60e4e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@61a814d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9040b6fmSocket: android.net.LocalSocket@190ee07c impl:android.net.LocalSocketImpl@fa38d05 fd:FileDescriptor[118]
,D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@190ee07c impl:android.net.LocalSocketImpl@fa38d05 fd:FileDescriptor[118]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
,D/WifiP2pService( 3521): InactiveState{ what=147493 }
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager(10543): message : 1
,D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
,D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
,D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
,D/WifiP2pService( 3521): discovery change broadcast false
,D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService(10543): Client app is not null!
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
,W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
,W/bt-smp  (10543): Plain text(LSB ~ MSB) = d1 d2 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = 99 6a 29 00 d9 50 79 80 25 26 41 6e c8 77 21 70 
,D/BtGatt.GattService(10543): stopScan() - queue size =1
,D/BtGatt.ScanManager(10543): filter size is 1
,D/BtGatt.ScanManager(10543): delete FilterIndex - 8
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
D/BtGatt.ScanManager(10543): stop scan
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
D/WifiP2pService( 3521): InactiveState{ what=139298 }
D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
D/WifiP2pService( 3521): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
D/WifiP2pService( 3521): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
I/jxcore-log(10472): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
D/WifiP2pService( 3521): InactiveState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
D/WifiP2pService( 3521): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394882102.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394882102.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27efef8b
D/BluetoothSocket(10472): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394882102.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394882102.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=a4db1108-c1af-440b-a771-01633e97aaec
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=a4db1108-c1af-440b-a771-01633e97aaec, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
,D/BtGatt.AdvertiseManager(10543): number of adv instance running0
D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): starting multi advertising
,D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=29901333-2b4f-44f8-bb4d-f89bcb0d7154
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=29901333-2b4f-44f8-bb4d-f89bcb0d7154, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10543): start scan with filters
,D/BtGatt.ScanManager(10543): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): allow scan with filters
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394882102.10472","ra":"E0:DB:10:14:E2:C0"}
,D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394882102.10472","ra":"E0:DB:10:14:E2:C0"}
D/BtGatt.ScanManager(10543): set filter index= 9 for clientIf= 7
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394882102.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3521): InactiveState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState add service
,D/WifiP2pService( 3521): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
,D/WifiP2pService( 3521): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3521): callSECApi what=74
D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
I/io.jxcore.node.ConnectionHelper(10472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394882102.10472
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
I/jxcore-log(10472): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper(10472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@ca0c314, channel: 6, state: LISTENING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@ca0c314, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27efef8b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@115b57bdmSocket: android.net.LocalSocket@11ce21b2 impl:android.net.LocalSocketImpl@24b4c503 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@11ce21b2 impl:android.net.LocalSocketImpl@24b4c503 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant(10558): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
D/WifiP2pService( 3521): discovery change broadcast true
D/BtGatt.AdvertiseManager(10543): message : 1
D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
,D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/wpa_supplicant(10558): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10543): Client app is not null!
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,D/WifiP2pService( 3521): InactiveState{ what=147493 }
D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3521): discovery change broadcast false
D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10543): stopScan() - queue size =1
,D/BtGatt.ScanManager(10543): filter size is 1
D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
D/BtGatt.ScanManager(10543): delete FilterIndex - 9
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...
W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
D/WifiP2pService( 3521): InactiveState{ what=139298 }
,W/bt-smp  (10543): Plain text(LSB ~ MSB) = 58 63 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = b5 86 54 bb 5b f9 db 91 da 2c ae 7e 9a 76 c6 c0 
D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
D/WifiP2pService( 3521): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log(10472): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
,D/WifiP2pService( 3521): remove client information from framework
D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/WifiP2pService( 3521): InactiveState{ what=139268 }
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): stop scan,
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
D/WifiP2pService( 3521): InactiveState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3521): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394882343.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394882343.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@126ab2b9
D/BluetoothSocket(10472): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394882343.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394882343.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=69cafe70-d75d-42d9-b1cb-f11cac5e80e0
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=69cafe70-d75d-42d9-b1cb-f11cac5e80e0, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
,D/BtGatt.AdvertiseManager(10543): number of adv instance running0
,D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): starting multi advertising
,D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=87db8194-47c6-4605-bdb3-443485f0663c
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=87db8194-47c6-4605-bdb3-443485f0663c, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10543): start scan with filters
,D/BtGatt.ScanManager(10543): handling starting scan
,D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): allow scan with filters
,D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager(10543): set filter index= 10 for clientIf= 7
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394882343.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394882343.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394882343.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394882343.10472
,I/io.jxcore.node.ConnectionHelper(10472): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,I/jxcore-log(10472): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
D/WifiP2pService( 3521): InactiveState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139292 }
I/io.jxcore.node.ConnectionHelper(10472): stop
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
D/WifiP2pService( 3521): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService( 3521): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@2cb4350a, channel: 6, state: LISTENING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@2cb4350a, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@126ab2b9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9fd17bmSocket: android.net.LocalSocket@3601db98 impl:android.net.LocalSocketImpl@3f42fff1 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@3601db98 impl:android.net.LocalSocketImpl@3f42fff1 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
D/BtGatt.AdvertiseManager(10543): message : 1
D/WifiP2pService( 3521): InactiveState{ what=139265 }
D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
,D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3521): callSECApi what=74
D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
,I/wpa_supplicant(10558): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
D/WifiP2pService( 3521): discovery change broadcast true
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
,I/wpa_supplicant(10558): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
D/WifiP2pService( 3521): InactiveState{ what=147493 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3521): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
,D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10543): Client app is not null!
D/WifiP2pService( 3521): InactiveState{ what=139268 }
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10543): stopScan() - queue size =1
,D/BtGatt.ScanManager(10543): filter size is 1
D/BtGatt.ScanManager(10543): delete FilterIndex - 10
D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
D/WifiP2pService( 3521): InactiveState{ what=139298 }
,W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10543): Plain text(LSB ~ MSB) = 48 11 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = 9e 3f 98 7e 04 c4 41 0f f7 db 73 dc e1 09 d3 09 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
D/WifiP2pService( 3521): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
,D/WifiP2pService( 3521): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): stop scan
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
,I/jxcore-log(10472): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
D/WifiP2pService( 3521): InactiveState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3521): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394882573.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394882573.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cd00a57
D/BluetoothSocket(10472): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394882573.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394882573.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=49a06574-180b-4420-a439-9bcc0ce8c413
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=49a06574-180b-4420-a439-9bcc0ce8c413, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
,D/BtGatt.AdvertiseManager(10543): number of adv instance running0
,D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
,D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): starting multi advertising
,D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=e613efbd-3793-4413-a42d-14f2e353dae7
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=e613efbd-3793-4413-a42d-14f2e353dae7, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10543): start scan with filters
,D/BtGatt.ScanManager(10543): handling starting scan
,D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): allow scan with filters
,D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager(10543): set filter index= 11 for clientIf= 7
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394882573.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394882573.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394882573.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3521): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
D/WifiP2pService( 3521): P2pEnabledState{ what=139292 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394882573.10472
D/WifiP2pService( 3521): P2pEnabledState add service
I/io.jxcore.node.ConnectionHelper(10472): start: OK
,D/WifiP2pService( 3521): add a new client
,I/jxcore-log(10472): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
I/io.jxcore.node.ConnectionHelper(10472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService( 3521): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
,D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@1bdc85b0, channel: 6, state: LISTENING
D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@1bdc85b0, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cd00a57, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23c0bc29mSocket: android.net.LocalSocket@231acbae impl:android.net.LocalSocketImpl@130bed4f fd:FileDescriptor[118]
D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@231acbae impl:android.net.LocalSocketImpl@130bed4f fd:FileDescriptor[118]
,D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
I/WifiStateMachine( 3521): callSECApi what=74
D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
,I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager(10543): message : 1
,D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
I/wpa_supplicant(10558): p2p0: P2P: Reject scan trigger since one is already pending
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
D/WifiP2pService( 3521): discovery change broadcast true
,D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10543): Client app is not null!
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/wpa_supplicant(10558): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10543): stopScan() - queue size =1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,D/BtGatt.ScanManager(10543): filter size is 1
D/WifiP2pService( 3521): InactiveState{ what=147493 }
D/BtGatt.ScanManager(10543): delete FilterIndex - 11
D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3521): discovery change broadcast false
,W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10543): Plain text(LSB ~ MSB) = c8 39 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = 6d 20 60 72 41 00 e3 76 30 2c 71 1b db 82 2d 8f 
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
,D/BtGatt.ScanManager(10543): stop scan
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService( 3521): InactiveState{ what=139298 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 3521): P2pEnabledState clear service
,I/jxcore-log(10472): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
,D/WifiP2pService( 3521): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
D/WifiP2pService( 3521): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394882816.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,D/WifiP2pService( 3521): InactiveState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394882816.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a7ff1e5
D/BluetoothSocket(10472): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394882816.10472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394882816.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=c3936fcf-f400-4943-ae39-8d40f42df06e
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=c3936fcf-f400-4943-ae39-8d40f42df06e, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
,D/BtGatt.AdvertiseManager(10543): number of adv instance running0
D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): starting multi advertising
,D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=ef212a35-a816-457c-9c16-d9ed70e1378b
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=ef212a35-a816-457c-9c16-d9ed70e1378b, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService(10543): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
D/BtGatt.ScanManager(10543): handling starting scan
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394882816.10472","ra":"E0:DB:10:14:E2:C0"}
D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394882816.10472","ra":"E0:DB:10:14:E2:C0"}
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394882816.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
D/BtGatt.ScanManager(10543): allow scan with filters
D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10543): set filter index= 12 for clientIf= 7
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
D/WifiP2pService( 3521): InactiveState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState add service
D/WifiP2pService( 3521): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394882816.10472
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
D/WifiP2pService( 3521): InactiveState{ what=139265 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
I/jxcore-log(10472): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3521): callSECApi what=74
D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
I/io.jxcore.node.ConnectionHelper(10472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
,D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@3234a286, channel: 6, state: LISTENING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true
,D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@3234a286, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a7ff1e5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23923747mSocket: android.net.LocalSocket@3a035b74 impl:android.net.LocalSocketImpl@2903789d fd:FileDescriptor[118]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@3a035b74 impl:android.net.LocalSocketImpl@2903789d fd:FileDescriptor[118]
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
,I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant(10558): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
D/BtGatt.AdvertiseManager(10543): message : 1
,D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
D/WifiP2pService( 3521): discovery change broadcast true
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
,D/WifiP2pService( 3521): InactiveState{ what=139268 },
I/wpa_supplicant(10558): P2P-FIND-STOPPED 
D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10543): Client app is not null!
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
D/WifiP2pService( 3521): InactiveState{ what=147493 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
D/WifiP2pService( 3521): discovery change broadcast false
,D/BtGatt.GattService(10543): stopScan() - queue size =1
,W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
,W/bt-smp  (10543): Plain text(LSB ~ MSB) = b4 98 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = 31 e6 22 31 48 29 06 4b cf b2 a0 32 9f 1c 4e 66 
D/BtGatt.ScanManager(10543): filter size is 1
D/BtGatt.ScanManager(10543): delete FilterIndex - 12
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): stop scan
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
D/WifiP2pService( 3521): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 3521): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
D/WifiP2pService( 3521): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
D/WifiP2pService( 3521): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
,I/jxcore-log(10472): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,D/WifiP2pService( 3521): InactiveState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3521): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log(10472): 
,I/wpa_supplicant(10558): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3521): InactiveState{ what=147477 }
D/WifiP2pService( 3521): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3521): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3521): InactiveState{ what=139283 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3521): DefaultState{ what=139283 }
,D/WifiDisplayController( 3521): Received list of peers.
,D/WifiDisplayController( 3521):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394883888.10472
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394883888.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a3100e3
D/BluetoothSocket(10472): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
,I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394883888.10472
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394883888.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
,D/BtGatt.GattService(10543): registerClient() - UUID=e36ca59b-7c71-481b-8773-cc69dadae8ec
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=e36ca59b-7c71-481b-8773-cc69dadae8ec, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
,D/BtGatt.AdvertiseManager(10543): number of adv instance running0
D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): starting multi advertising
,D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=d6e01d0e-5b0f-40b3-abf8-23a5dbb6b0e2
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=d6e01d0e-5b0f-40b3-abf8-23a5dbb6b0e2, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService(10543): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager(10543): handling starting scan
,D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): allow scan with filters
D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10543): set filter index= 13 for clientIf= 7
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394883888.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394883888.10472","ra":"E0:DB:10:14:E2:C0"},
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394883888.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648,
,I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3521): InactiveState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3521): P2pEnabledState add service
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
,D/WifiP2pService( 3521): add a new client
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394883888.10472
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
,D/ScanRecord(10543): parseFromBytes
,D/ScanRecord(10543): first manudata for manu ID
,D/BtGatt.GattService(10543): result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=278382350823}
,D/BtGatt.GattService(10543): filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,D/BtGatt.ContextMap(10543): sendClientScanResult for app id 7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
,D/ScanRecord(10472): parseFromBytes
,D/ScanRecord(10472): first manudata for manu ID
,D/BluetoothLeScanner(10472): onScanResult() - ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=278382350823}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=278382350823}
,I/io.jxcore.node.ConnectionHelper(10472): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
,D/WifiP2pService( 3521): InactiveState{ what=139265 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
,I/jxcore-log(10472): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
,D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3521): callSECApi what=74
,D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
,I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
,D/WifiP2pService( 3521): discovery change broadcast true
,I/jxcore-log(10472): ok 75 Cannot call startBroadcasting twice
I/jxcore-log(10472): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
,I/wpa_supplicant(10558): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,D/WifiP2pService( 3521): InactiveState{ what=147493 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
,I/io.jxcore.node.ConnectionHelper(10472): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@335aa50c, channel: 6, state: LISTENING
,D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@335aa50c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a3100e3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f2a1e55mSocket: android.net.LocalSocket@34eb006a impl:android.net.LocalSocketImpl@1e2ba95b fd:FileDescriptor[118]
,D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@34eb006a impl:android.net.LocalSocketImpl@1e2ba95b fd:FileDescriptor[118]
D/WifiP2pService( 3521): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
,D/BtGatt.AdvertiseManager(10543): message : 1
,D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
,D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
,D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService(10543): Client app is not null!
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
,W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10543): Plain text(LSB ~ MSB) = ea d9 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = 0a 3e bd 84 fe 69 d4 ee eb 89 74 53 f5 34 f1 cd 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10543): stopScan() - queue size =1
,D/BtGatt.ScanManager(10543): filter size is 1
D/BtGatt.ScanManager(10543): delete FilterIndex - 13
D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): stop scan
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
,D/WifiP2pService( 3521): InactiveState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
D/WifiP2pService( 3521): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3521): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
I/jxcore-log(10472): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,D/WifiP2pService( 3521): InactiveState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3521): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # ThaliEmitter throws on connection to bad peer,
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394884728.10472
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394884728.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@193b4ad1
,D/BluetoothSocket(10472): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
,I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394884728.10472
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394884728.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
,D/BtGatt.GattService(10543): registerClient() - UUID=c7f12ef5-41c5-4b76-82c2-7a7be60ecceb
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=c7f12ef5-41c5-4b76-82c2-7a7be60ecceb, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
,D/BtGatt.AdvertiseManager(10543): number of adv instance running0
D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): starting multi advertising
,D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=e4613d3b-fbd7-4a04-b536-17f63b7865ec
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=e4613d3b-fbd7-4a04-b536-17f63b7865ec, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10543): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager(10543): handling starting scan
,D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): allow scan with filters
D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10543): set filter index= 14 for clientIf= 7
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394884728.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394884728.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394884728.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15,
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
D/WifiP2pService( 3521): InactiveState{ what=139292 }
D/WifiP2pService( 3521): P2pEnabledState{ what=139292 }
D/WifiP2pService( 3521): P2pEnabledState add service
D/WifiP2pService( 3521): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
,D/WifiP2pService( 3521): InactiveState{ what=139265 }
I/io.jxcore.node.ConnectionHelper(10472): start: OK
D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
,D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3521): callSECApi what=74
,I/jxcore-log(10472): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
,I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394884728.10472
,I/wpa_supplicant(10558): p2p0: P2P: Reject scan trigger since one is already pending
,I/io.jxcore.node.ConnectionHelper(10472): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper(10472): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper(10472): connect: Invalid Bluetooth address: foobar
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/WifiP2pService( 3521): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
,I/jxcore-log(10472): ok 78 Should not connect to a bad peer
I/jxcore-log(10472): 
,I/io.jxcore.node.ConnectionHelper(10472): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@264732c2, channel: 6, state: LISTENING
D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@264732c2, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@193b4ad1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d3e8d3mSocket: android.net.LocalSocket@3e5c9c10 impl:android.net.LocalSocketImpl@95b8309 fd:FileDescriptor[118]
D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@3e5c9c10 impl:android.net.LocalSocketImpl@95b8309 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
,I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager(10543): message : 1
D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
,D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/wpa_supplicant(10558): P2P-FIND-STOPPED 
,D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10543): Client app is not null!
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
D/WifiP2pService( 3521): InactiveState{ what=147493 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3521): discovery change broadcast false
D/BtGatt.GattService(10543): stopScan() - queue size =1
,W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10543): Plain text(LSB ~ MSB) = a0 45 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = d3 06 0c 99 03 9e b6 ad 21 ee f0 15 a6 ad d8 0d 
,D/BtGatt.ScanManager(10543): filter size is 1
D/BtGatt.ScanManager(10543): delete FilterIndex - 14
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
,D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
,D/BtGatt.ScanManager(10543): stop scan
D/WifiP2pService( 3521): InactiveState{ what=139298 }
D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...
,D/WifiP2pService( 3521): P2pEnabledState clear service
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3521): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
D/WifiP2pService( 3521): InactiveState{ what=139268 }
,I/jxcore-log(10472): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
D/WifiP2pService( 3521): InactiveState{ what=139307 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394885181.10472
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394885181.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10472): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10472): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,D/BluetoothSocket(10472): bindListen(), new LocalSocket 
D/BluetoothSocket(10472): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket(10472): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34ea3f2f
,D/BluetoothSocket(10472): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): start: OK
I/io.jxcore.node.ConnectionHelper(10472): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394885181.10472
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): createAdvertiseData: From: 1453394885181.10472 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10472): E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10472): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=30c1f59c-5f88-401a-87b4-35962f28e8ab
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=30c1f59c-5f88-401a-87b4-35962f28e8ab, clientIf=6
,D/BluetoothLeAdvertiser(10472): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10543): message : 0
,D/BtGatt.AdvertiseManager(10543): number of adv instance running0
D/BtGatt.AdvertiseManager(10543): size of list is =0
,D/BtGatt.AdvertiseManager(10543): starting advertising
D/BtGatt.AdvertiseManager(10543): isDualWavefalse
,D/BtGatt.GattService(10543): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10543): starting multi advertising
,D/BtGatt.GattService(10543): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10543): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10543): registerClient() - UUID=c4cdf13f-6d19-4de5-96f1-48e55c9ad74f
,I/wpa_supplicant(10558): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3521): InactiveState{ what=147477 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3521): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3521): InactiveState{ what=139283 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3521): DefaultState{ what=139283 }
,D/WifiDisplayController( 3521): Received list of peers.
D/WifiDisplayController( 3521):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BtGatt.GattService(10543): onClientRegistered() - UUID=c4cdf13f-6d19-4de5-96f1-48e55c9ad74f, clientIf=7
,D/BluetoothLeScanner(10472): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService(10543): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager(10543): handling starting scan
,D/BtGatt.GattService(10543): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10543): allow scan with filters,
,D/BtGatt.ScanManager(10543): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager(10543): set filter index= 15 for clientIf= 7
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10472): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394885181.10472","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453394885181.10472","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453394885181.10472","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager(10543): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3521): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): start: Starting P2P device discovery...
D/WifiP2pService( 3521): P2pEnabledState{ what=139292 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10472): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453394885181.10472
,I/jxcore-log(10472): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log(10472): 
,D/io.jxcore.node.ConnectionHelper(10472): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper(10472): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
,D/io.jxcore.node.ConnectionHelper(10472): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper(10472): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startBlePeerDiscovery: OK
D/WifiP2pService( 3521): P2pEnabledState add service
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10472): onStartSuccess
I/jxcore-log(10472): ok 81 Disconnect should fail to a non-existant peer 
I/jxcore-log(10472): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: RESTARTING
D/WifiP2pService( 3521): add a new client
,I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper(10472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): shutdown
D/BluetoothSocket(10472): close() in, this: android.bluetooth.BluetoothSocket@2ccfdd28, channel: 6, state: LISTENING
D/BluetoothSocket(10472): close() this: android.bluetooth.BluetoothSocket@2ccfdd28, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34ea3f2f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ed38a41mSocket: android.net.LocalSocket@377dbe6 impl:android.net.LocalSocketImpl@38ece527 fd:FileDescriptor[118]
D/BluetoothSocket(10472): Closing mSocket: android.net.LocalSocket@377dbe6 impl:android.net.LocalSocketImpl@38ece527 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10472): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10472): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local service added successfully
,D/WifiP2pService( 3521): InactiveState{ what=139265 }
D/BtGatt.AdvertiseManager(10543): message : 1
D/WifiP2pService( 3521): P2pEnabledState{ what=139265 }
,D/BtGatt.AdvertiseManager(10543): stop advertise for client 6
D/BtGatt.AdvertiseManager(10543):  dualWaveClientIf = 0client.clientIf6
D/WifiService( 3521): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3521): callSECApi what=74
D/WifiStateMachine( 3521): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
I/wpa_supplicant(10558): USE_NETWORK : USE_NETWORK OFF
,D/BtGatt.AdvertiseManager(10543): logClientsSet() - status: -1
,D/BtGatt.GattService(10543): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10543): Client app is not null!
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery started successfully
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: STARTED
,D/WifiP2pService( 3521): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsAdvertiserStartedChanged: false
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
I/wpa_supplicant(10558): P2P-FIND-STOPPED 
,D/BtGatt.GattService(10543): stopScan() - queue size =1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BtGatt.ScanManager(10543): filter size is 1
D/BtGatt.ScanManager(10543): delete FilterIndex - 15
,D/BtGatt.GattService(10543): unregisterClient() - clientIf=7
,D/WifiP2pService( 3521): InactiveState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,D/WifiP2pService( 3521): P2pEnabledState{ what=147493 }
W/bt-smp  (10543): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10543): Plain text(LSB ~ MSB) = e0 b7 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10543): Encrypted text(LSB ~ MSB) = 49 b5 50 5a 2d 67 1e 9f 70 6e 61 4e 40 49 e5 5e 
,D/WifiP2pService( 3521): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10472): setIsStarted: true
D/BtGatt.GattService(10543): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10543): callback done for clientIf - 7 status - 0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10472): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10472): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10472): release: No more listeners, de-initializing...
,D/WifiP2pService( 3521): InactiveState{ what=139298 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10472): setState: NOT_STARTED
D/WifiP2pService( 3521): P2pEnabledState{ what=139298 }
D/WifiP2pService( 3521): P2pEnabledState clear service
D/BtGatt.ScanManager(10543): stop scan
,I/io.jxcore.node.ConnectionHelper(10472): onDiscoveryManagerStateChanged: NOT_STARTED
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10543): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10543): configureRegularScanParams() - queue emtpy, scan stopped
,D/WifiP2pService( 3521): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10472): Local services cleared successfully
,D/WifiP2pService( 3521): InactiveState{ what=139268 }
,I/jxcore-log(10472): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log(10472): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10472): P2P device discovery stopped successfully
,D/WifiP2pService( 3521): InactiveState{ what=139307 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3521): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10472): Service requests cleared successfully
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log(10472): 
,W/BroadcastQueue( 3521): Skipping deliver [background] BroadcastRecord{3527abac u-1 android.net.wifi.p2p.DISCOVERY_STATE_CHANGE} to ReceiverList{31b9b1b9 10472 com.test.thalitest/10595/u0 remote:3d909780}: filter unregistered
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 83 should be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 84 should not be equal
I/jxcore-log(10472): 
,I/jxcore-log(10472): # setup
I/jxcore-log(10472): 
,I/jxcore-log(10472): # verify that Thali-specific messages are filtered correctly
I/jxcore-log(10472): 
,I/jxcore-log(10472): # teardown
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 85 irrelevant messages should be ignored
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 86 relevant messages should not be ignored
I/jxcore-log(10472): 
,I/jxcore-log(10472): ok 87 messages from this device should be ignored
I/jxcore-log(10472): 
,I/jxcore-log(10472): Tests Complete
I/jxcore-log(10472): 
,I/jxcore-log(10472): Total: 0	Passed: 0	Failed: 0
I/jxcore-log(10472): 
,I/chromium(10472): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log(10472): Toggling radios to false
I/jxcore-log(10472): 
,D/BluetoothAdapter(10472): disable()
,D/SettingsProvider( 3521): name = bluetooth_on
,I/chromium(10472): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,I/WifiManager(10472): packageName : com.test.thalitest
,D/BluetoothAdapterState(10543): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties(10543): Setting state to 13
I/BluetoothAdapterState(10543): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService(10543): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService(10543): updateAdapterState state is 13
,I/BluetoothPbapService(10543): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothSocket(10543): close() in, this: android.bluetooth.BluetoothSocket@36c30c59, channel: 19, state: LISTENING
,D/BluetoothSocket(10543): close() this: android.bluetooth.BluetoothSocket@36c30c59, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1fbe3a21, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@24a5901emSocket: android.net.LocalSocket@219bb0ff impl:android.net.LocalSocketImpl@23723ecc fd:FileDescriptor[72]
,D/BluetoothSocket(10543): Closing mSocket: android.net.LocalSocket@219bb0ff impl:android.net.LocalSocketImpl@23723ecc fd:FileDescriptor[72]
,D/BluetoothAdapterService(10543): Autoconnection is available 
,D/BluetoothAdapterService(10543): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService(10543): terminating service from this receiver
,D/BluetoothAdapterProperties(10543): onBluetoothDisable()
,D/SecContentProvider( 3521): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties(10543): Scan Mode:20
,I/BluetoothAdapterState(10543): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterState(10543): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif (10543): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif (10543): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/BtOppRfcommListener(10543): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif (10543): cmd socket is not created
,D/btif_config_util(10543): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  (10543): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif (10543): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap(10543): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap(10543): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap(10543): L2CAP - PSM: 0x001b not found for deregistration
,W/InputMethodManagerService( 3521): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3521): [BT Setting State] State =13
,D/BluetoothTile( 3692):  onBluetoothStateChange:
,D/SecContentProvider( 3521): uri = 18 selection = isWifiEnabled
D/BluetoothTile( 3692):  onBluetoothPairedDevicesChanged:
D/SecContentProvider2( 3521): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3521): mCursor = null
,D/BluetoothTile( 3692):  handleUpdatestate:false name:null
,D/BluetoothTile( 3692): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 3692):  handleUpdatestate:false name:null
,D/WifiService( 3521): setWifiEnabled: false pid=10472, uid=10595
,E/WifiService( 3521): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider( 3521): name = wifi_on
,I/SamsungIME( 4466): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/STATUSBAR-QSTileView( 3692): onStateChanged: Bluetooth
,D/StatusBarManagerService( 3521): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/StatusBarManagerService( 3521): setIconVisibility slot=bluetooth visible=false
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/jxcore-log(10472): Radios toggled
I/jxcore-log(10472): 
,I/jxcore-log(10472): ****TEST TOOK:  ms ****
I/jxcore-log(10472): 
I/jxcore-log(10472): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10472): 
,E/WifiStateMachine( 3521): WifiStateMachine: Leaving Connected state
I/wpa_supplicant(10558): reset timer : RESET_TIMER 0
I/wpa_supplicant(10558): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant(10558): Skip scan - bUseNetwork false
D/PhoneStatusBar( 3692): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
E/WifiStateMachine( 3521): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3521): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3521): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Zygote  (12082): MountEmulatedStorage()
E/Zygote  (12082): v2
I/libpersona(12082): KNOX_SDCARD checking this for 1000
I/libpersona(12082): KNOX_SDCARD not a persona
,I/SELinux (12082): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12082): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=12082 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12082): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3521): do suspend true
,D/BluetoothSocket(10543): close() in, this: android.bluetooth.BluetoothSocket@2c96902a, channel: 5, state: LISTENING
D/BluetoothSocket(10543): close() this: android.bluetooth.BluetoothSocket@2c96902a, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@103afe46, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6845e1bmSocket: android.net.LocalSocket@3eea7bb8 impl:android.net.LocalSocketImpl@23d8ed91 fd:FileDescriptor[74]
D/BluetoothSocket(10543): Closing mSocket: android.net.LocalSocket@3eea7bb8 impl:android.net.LocalSocketImpl@23d8ed91 fd:FileDescriptor[74]
,I/BtOppRfcommListener(10543): stopping Accept Thread
D/BluetoothSocket(10543): close() in, this: android.bluetooth.BluetoothSocket@2ae584f6, channel: 12, state: LISTENING
D/BluetoothSocket(10543): close() this: android.bluetooth.BluetoothSocket@2ae584f6, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e1238a0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3e80c0f7mSocket: android.net.LocalSocket@da79b64 impl:android.net.LocalSocketImpl@350dd1cd fd:FileDescriptor[77]
D/BluetoothSocket(10543): Closing mSocket: android.net.LocalSocket@da79b64 impl:android.net.LocalSocketImpl@350dd1cd fd:FileDescriptor[77]
I/BtOppRfcommListener(10543): BluetoothSocket listen thread finished
,D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,V/NativeCrypto( 4240): Read error: ssl=0xaec21600: I/O error during system call, Connection timed out
,V/NativeCrypto( 4240): SSL shutdown failed: ssl=0xaec21600: I/O error during system call, Broken pipe
,E/WifiStateMachine( 3521): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,D/ConnectivityService( 3521): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10014
,E/WifiStateMachine( 3521): scanCount==0 - aborting
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): ValidatedState{ when=-1ms what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): DefaultState{ when=-1ms what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/WifiScanningService( 3521): SCAN_AVAILABLE : 1
D/WifiScanningService( 3521): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService( 3521): SCAN_AVAILABLE : 1
E/WifiStateMachine( 3521): [1,453,394,886,517 ms] noteScanEnd no scan source
,D/WifiP2pService( 3521): InactiveState{ what=131204 }
D/RttService( 3521): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 3521): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/WifiP2pService( 3521): P2pEnabledState{ what=131204 }
,D/WifiDisplayController( 3521): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3521): sending p2p connection changed broadcast: FAILED
,D/WifiDisplayController( 3521): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3521): onP2pDisconnected
,D/IpRemoteDisplayController( 3521): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3521): WfdBridgeServer is already null
,E/WifiStateMachine( 3521): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3521): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3521): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3521): NetworkAgent: NetworkAgent channel lost
,D/WifiP2pService( 3521): sending p2p connection changed broadcast: DISCONNECTED
,I/System.out( 3521): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 3521): Tagging socket 422 with tag ffffffff00000000{4294967295,0} uid 10014, pid: 3521, getuid(): 1000
I/jxcore-log(10472): Toggling radios to false
I/jxcore-log(10472): 
D/BluetoothAdapter(10472): disable()
,I/System.out( 3521): (HTTPLog)-Static: isSBSettingEnabled false
,E/WifiStateMachine( 3521): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 3521): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 3521): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3521): disconnect
D/WifiDisplayController( 3521): updateConnection
D/WifiDisplayController( 3521): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider(12082): TimaSignature is unavailable
,D/ActivityThread(12082): Added TimaKeyStore provider
E/BluetoothManagerService( 3521): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager(10472): packageName : com.test.thalitest
,D/SecContentProvider( 3521): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3521): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3521): mCursor = null
,D/WifiService( 3521): setWifiEnabled: false pid=10472, uid=10595
E/WifiService( 3521): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider( 3521): name = wifi_on
,E/WifiController( 3521): illegal state found both WifiController and WifiStateMachine
,D/WifiP2pService( 3521): P2pDisablingState
,D/WifiP2pService( 3521): P2pDisablingState{ what=147458 }
D/WifiP2pService( 3521): p2p socket connection lost
,D/WifiP2pService( 3521): P2pDisabledState
,D/WifiP2pService( 3521): P2pDisabledState{ what=139283 }
,E/WifiStateMachine( 3521): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - enter - invokeEnterMethods
,I/jxcore-log(10472): Radios toggled
I/jxcore-log(10472): 
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3521): do suspend true
,D/WifiP2pService( 3521): DefaultState{ what=139283 }
,D/WifiDisplayController( 3521): Received list of peers.
,D/WifiDisplayController( 3521): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter( 3521): onP2pDisconnected
D/IpRemoteDisplayController( 3521): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3521): WfdBridgeServer is already null
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 0 for uid 1000
D/ConnectivityService( 3521): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 3521): Not allowed due to - mEnabled false
,D/ConnectivityService( 3521): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Validated
D/CSLegacyTypeTracker( 3521): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3521): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityManager.CallbackHandler( 4449): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 3981): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiP2pService( 3521): P2pDisabledState{ what=143375 }
D/WifiP2pService( 3521): DefaultState{ what=143375 }
,D/AllShareCastTile( 3692): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 3692): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/Tethering( 3521): MasterInitialState.processMessage what=3
D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,E/WifiStateMachine( 3521): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
V/NetworkStats( 3521): updateIfacesLocked()
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): performPollLocked(flags=0x1)
,D/bt_userial(10543): RX termination
W/bt_userial(10543): select_read return size <=0:-1, exiting userial_read_thread
D/NetworkStatsFactory( 3521): UpdateStatsForKnox
,W/bt-l2cap(10543): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap(10543): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap(10543): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap(10543): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap(10543): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap(10543): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap(10543): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap(10543): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap(10543): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif (10543): ag scb idx 1 not allocated
W/bt-btif (10543): ag scb idx 2 not allocated
E/bt-btif (10543): BTA AG is already disabled, ignoring ...
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,E/WifiStateMachine( 3521): stopping supplicant
I/wpa_supplicant(10558): p2p0: State: DISCONNECTED -> DISCONNECTED
D/bt_userial(10543): Leaving userial_read_thread()
,D/bt_userial(10543): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg(10543): hw_epilog_process
,D/ResourcesManager(12082): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
I/bt_userial_vendor(10543): device fd = 65 close
,E/WifiStateMachine( 3521): setWifiState: disabling
D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,V/NetworkStats( 3521): performPollLocked() took 9ms
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/EntConnectivity( 3521): Not allowed due to - mEnabled false
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/GKI_LINUX(10543): gki_task task_id=0 [BTU] terminating
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
I/GKI_LINUX(10543): GKI_exit_task 0 done
I/GKI_LINUX(10543): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState(10543): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode(10543): isSecureModeOn:false
D/BluetoothAdapterService(10543): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService(10543): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService(10543): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils(10543): handleDebugAction() action=null
,D/BtGatt.GattService(10543): Received stop request...Stopping profile...
D/BtGatt.GattService(10543): stop()
D/BtGatt.AdvertiseManager(10543): advertise clients cleared
W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,W/BluetoothAdapterService(10543): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,W/ResourcesManager(12082): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12082): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3692): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3692): Wifi onReceive(0)
D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SLocation( 3521): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/HotspotTile( 3692): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,W/ResourcesManager(12082): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
D/STATUSBAR-QSTileView( 3692): onStateChanged: Wi-Fi
,W/ResourcesManager(12082): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12082): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12082): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12082): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/HotspotTile( 3692): onReceive : 0, 0
,W/BluetoothAdapterService(10543): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/SmartBondingService( 3521): getNetworkEnabled : wifi : false mobile : false
E/WifiStateMachine( 3521): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService(10543): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService(10543): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService(10543): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService(10543): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService(10543): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService(10543): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService(10543): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService(10543): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10543): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService(10543): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10543): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService(10543): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10543): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService(10543): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState(10543): Stopping profile services that were post enabled
E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/HeadsetService(10543): Received stop request...Stopping profile...
,D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,D/A2dpService(10543): Received stop request...Stopping profile...
V/Avrcp   (10543): doQuit
D/A2dpStateMachine(10543): Exit Disconnected: -1
,D/AudioService( 3521): onServiceDisconnected: Bluetooth profile: 1
,D/Avrcp   (10543): Unregistering previous receiver
,D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,D/BluetoothA2dp( 3521): Proxy object disconnected
D/AudioService( 3521): onServiceDisconnected: Bluetooth profile: 2
,D/HidService(10543): Received stop request...Stopping profile...
D/HidService(10543): Stopping Bluetooth HidService
W/BluetoothHidServiceJni(10543): Cleaning up Bluetooth HID Interface...
W/bt-btif (10543): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni(10543): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
D/BluetoothA2dp( 4806): Proxy object disconnected
,D/HealthService(10543): Received stop request...Stopping profile...
D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,D/PanService(10543): Received stop request...Stopping profile...
D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,D/BluetoothPan( 3521): BluetoothPAN Proxy object disconnected
,D/BluetoothMapService(10543): Received stop request...Stopping profile...
,D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,D/SapService(10543): Received stop request...Stopping profile...
D/SapService(10543): Stopping Bluetooth SapService
D/BluetoothAdapterService(10543): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd72d3f
,E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(10543): Profile still running: com.android.bluetooth.hid.HidService
,W/BluetoothHeadsetServiceJni(10543): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni(10543): Cleaning up Bluetooth Handsfree callback object
,E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(10543): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp(10543): Proxy object disconnected
D/BluetoothAdapterService(10543): Bluetooth A2dp source service disconnected
,I/GKI_LINUX(10543): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX(10543): GKI_exit_task 2 done
I/GKI_LINUX(10543): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   (10543): cleanup
,E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
I/wpa_supplicant(10558): Blacklist: Clear (all) 
,D/BluetoothAdapterService(10543): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(10543): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni(10543): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni(10543): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService(10543): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothPanServiceJni(10543): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni(10543): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig(10543): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(10543): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(1020734783)(10543): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,W/BluetoothSAPServiceJni(10543): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
D/BluetoothAdapterState(10543): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties(10543): Setting state to 10
I/BluetoothAdapterState(10543): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(10543): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10543): updateAdapterState state is 10
,W/BluetoothSAPServiceJni(10543): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(10543): Autoconnection is available 
D/BluetoothAdapterService(10543): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState(10543): Entering OffState
,D/BluetoothA2dp( 3521): onBluetoothStateChange: up=false
,D/BluetoothA2dp(10543): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/BluetoothA2dp( 4806): onBluetoothStateChange: up=false
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/BluetoothManagerService( 3521): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/BluetoothManagerService( 3521): Broadcasting onBluetoothServiceUp() to 0 receivers.
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/MySettingsProvider(12082): DatabaseHelper(Context context):DATABASE_VERSION=1
,I/GKI_LINUX(10543): gki_task task_id=1 [BTIF] terminating
,W/InputMethodManagerService( 3521): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3521): [BT Setting State] State =10
I/InputMethodManagerService( 3521): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,E/SQLiteLog(12082): (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
,I/wpa_supplicant(10558): p2p0: CTRL-EVENT-TERMINATING 
,D/MySettingsProvider(12082): onCreate():(mDB == null)? false:true  =true
,I/wpa_supplicant(10558): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant(10558): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant(10558): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant(10558): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/BluetoothAdapter( 3692): 477092273: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 3692):  onBluetoothPairedDevicesChanged:
,D/BluetoothAdapter( 3692): 477092273: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 3692): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 3692): 477092273: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3692): 477092273: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3692): 477092273: getState() :  mService = null. Returning STATE_OFF
,D/STATUSBAR-QSTileView( 3692): onStateChanged: Bluetooth
,D/StatusBarManagerService( 3521): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,I/GKI_LINUX(10543): GKI_exit_task 1 done
I/GKI_LINUX(10543): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni(10543): cleanupNative: return from cleanup
I/SamsungIME( 4466): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/StatusBarManagerService( 3521): setIconVisibility slot=bluetooth visible=false
,D/BluetoothAdapter( 4240): 427654697: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4240): 427654697: getState() :  mService = null. Returning STATE_OFF
,D/PhoneStatusBar( 3692): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,I/art     (10543): System.exit called, status: 0
I/AndroidRuntime(10543): VM exiting with result code 0, cleanup skipped.
,D/AndroidRuntime(12097): 
D/AndroidRuntime(12097): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12097): CheckJNI is OFF
W/ContextImpl(12082): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/AndroidRuntime(12097): readGMSProperty: start
D/AndroidRuntime(12097): readGMSProperty: already setted!!
,D/AndroidRuntime(12097): readGMSProperty: end
D/AndroidRuntime(12097): addProductProperty: start
,D/BluetoothAdapter(12082): 41200292: getState() :  mService = null. Returning STATE_OFF
,D/LocalBluetoothProfileManager(12082): PANU : true
D/LocalBluetoothProfileManager(12082): Adding local MAP profile
D/BluetoothMap(12082): Create BluetoothMap proxy object
I/ActivityManager( 3521): Process com.android.bluetooth (pid 10543)(adj 0) has died(148,1200)
,W/ContextImpl(12082): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,I/wpa_supplicant(10558): Blacklist: Clear (all) 
,D/Bluetoothsap(12082): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager(12082): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver(12082): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver(12082): onReceive
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12136): MountEmulatedStorage()
E/Zygote  (12136): v2
I/libpersona(12136): KNOX_SDCARD checking this for 1002
I/libpersona(12136): KNOX_SDCARD not a persona
,I/SELinux (12136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=12136 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,E/SELinux (12136): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 11079:com.samsung.android.scloud.backup/u0a67 (adj 13): bgCount ##31
,E/AffinityControl(12097): AffinityControl: registerfunction enter
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 901us total 29.139ms
,D/TimaKeyStoreProvider(12136): TimaSignature is unavailable
,D/ActivityThread(12136): Added TimaKeyStore provider
,D/AndroidRuntime(12097): Calling main entry com.android.commands.pm.Pm
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 797us total 18.331ms
,D/PackageManager( 3521): START PACKAGE DELETE: observer{383680665}
D/PackageManager( 3521): pkg{<packageName>}
D/PackageManager( 3521): user{0}
D/PackageManager( 3521): caller{2000}
D/PackageManager( 3521): flags{3}
,D/PersonaManagerService( 3521): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService( 3521): isFromApprovedUnInstaller: isApproved : true
,D/PersonaManagerService( 3521): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 3521): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager( 3521): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager( 3521): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 3521): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3521): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3521): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3521): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3521): !@killApplicatoin: 10595, uninstall pkg
,I/ActivityManager( 3521): Force stopping com.test.thalitest appid=10595 user=-1: uninstall pkg
,I/ActivityManager( 3521): Killing 10472:com.test.thalitest/u0a595 (adj 0): stop com.test.thalitest
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 812us total 18.489ms
,D/ResourcesManager(12136): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(12136): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(12136): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ActivityManager( 3521):   Force finishing activity ActivityRecord{2ea1c4c0 u0 com.test.thalitest/.MainActivity t25}
,I/SurfaceFlinger( 2850): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2850): id=12 Removed NainActivit (-2/8)
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3521): Skipping PackageSetting{3cb0f25e com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3521): Force stopping com.test.thalitest appid=10595 user=0: pkg removed
,D/WifiService( 3521): Client connection lost with reason: 4
,I/BluetoothA2dpSinkServiceJni(12136): register_com_android_bluetooth_a2dp_sink
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 1542(78KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 735us total 29.050ms
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 7904): Explicit concurrent mark sweep GC freed 24396(1433KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.685ms total 46.395ms
,I/art     ( 4449): Explicit concurrent mark sweep GC freed 11916(801KB) AllocSpace objects, 23(368KB) LOS objects, 20% free, 31MB/39MB, paused 1.999ms total 61.624ms
,E/SamsungIME( 4466): mOCRHelper is null
,I/InputReader( 3521): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 4240): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LWLocationManager(11505): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11505): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/BtSettings.ProfileConfig(12136): Adding GattService
,D/BtSettings.ProfileConfig(12136): Adding HeadsetService
D/BtSettings.ProfileConfig(12136): Adding A2dpService
D/BtSettings.ProfileConfig(12136): Adding HidService
D/BtSettings.ProfileConfig(12136): Adding HealthService
D/BtSettings.ProfileConfig(12136): Adding PanService
D/BtSettings.ProfileConfig(12136): Adding BluetoothMapService
,D/BtSettings.ProfileConfig(12136): Adding SapService
D/BtSettings.ProfileConfig(12136): Adding HeadsetClientService
D/BtSettings.ProfileConfig(12136): Adding A2dpSinkService
D/BtSettings.ProfileConfig(12136): Adding SapClientService
D/BtSettings.ProfileConfig(12136): Adding HidDevService
I/BtSettings.ProfileConfig(12136): *********Initializing Bluetooth Profile Settings*******
,I/DBG_DM  ( 5973): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 5973): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/ResourceType( 4967): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4967): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/EnterpriseDeviceManagerService( 3521): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 3521): Admin package name: com.google.android.gms
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
,D/SettingsProvider( 3521): selectionArgs: 1002
,D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3521): ret = -1
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
,D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3521): ret = -1
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
,D/SettingsProvider( 3521): selectionArgs: 1002
,D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/SettingsProvider( 3521): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,I/ActivityManager( 3521): Killing 11096:com.sec.knox.bridge/1000 (adj 13): bgCount ##31
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/AuthorizationBluetoothService( 4240): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/Hs20UtilService( 6287): Starting #8
,I/Hs20UtilService( 6287): Message received 5007
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 55657(3MB) AllocSpace objects, 5(128KB) LOS objects, 24% free, 48MB/64MB, paused 3.012ms total 202.881ms
,I/art     ( 3521): WaitForGcToComplete blocked for 191.041ms for cause Explicit
D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/NearbySettings(12082): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings(12082): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings(12082): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings(12082): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(12082): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/NearbySettings(12082): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/WifiService( 3521): New client listening to asynchronous messages
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/NearbySettings(12082): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(12082): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings(12082): MountReceiver.onReceive - Set preference state off
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/wpa_supplicant(10558): wlan0: CTRL-EVENT-TERMINATING 
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/Tethering( 3521): InitialState.processMessage what=4
,V/NearbySettings(12082): MountReceiver.mPrefHandler - 7002
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/Tethering( 3521): No numeric data
,D/Tethering( 3521): sendTetherStateChangedBroadcast 0, 0, 0
,V/NetworkStats( 3521): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
E/WifiStateMachine( 3521): Supplicant connection lost
,D/HotspotTile( 3692): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3692): updateTetherState():false, false
,D/NetworkStatsFactory( 3521): UpdateStatsForKnox
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,V/NetworkStats( 3521): performPollLocked() took 11ms
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3521): mCursor = null
,E/Zygote  (12158): MountEmulatedStorage()
E/Zygote  (12158): v2
I/libpersona(12158): KNOX_SDCARD checking this for 10160
I/libpersona(12158): KNOX_SDCARD not a persona
,I/SELinux (12158): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12158): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.control.core.sync.scloud.ReceiverSignOut: pid=12158 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,E/SELinux (12158): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,E/WifiStateMachine( 3521): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-HAL( 3521): callSECApiBoolean - ID [21]
,E/WifiStateMachine( 3521): setWifiState: disabled
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/RegisteredServicesCache( 3966): empty dynamic service
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 3692): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3692): Wifi onReceive(1)
D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/STATUSBAR-QSTileView( 3692): onStateChanged: Wi-Fi
,D/HotspotTile( 3692): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/HotspotTile( 3692): onReceive : 1, 0
,W/Settings( 4240): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TimaKeyStoreProvider(12158): TimaSignature is unavailable
,D/ActivityThread(12158): Added TimaKeyStore provider
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(12158): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(12158): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12158): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12158): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourceType( 3521): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 10307(515KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.795ms total 172.706ms
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,V/Common  (12158): getScreenSize 1440 2560
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  (12177): MountEmulatedStorage()
I/JAM     (12158): Load The ApaService JNI
,E/Zygote  (12177): v2
I/libpersona(12177): KNOX_SDCARD checking this for 10160
I/JAM     (12158): version: ProfessionalAudio_v1.0.b5
I/libpersona(12177): KNOX_SDCARD not a persona
I/JAM     (12158): Try v1.0.b3 ...
D/Spen    (12158): SpenSdk version level = 55
D/Spen    (12158): SpenSdk jar version = 3.0.243
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
I/SELinux (12177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/Spen    (12158): SpenSdk apk version = 3.0.235
D/Spen    (12158): Server UPDATE Check
,W/linker  (12158): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
W/ResourcesManager(11505): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SELinux (12177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/SPenError(12158): JNI_OnLoad
,D/JNI_Bitmap(12158): Init .. Done
D/SPenSpiDecoder(12158): JNI_OnLoad .. Done
D/SPenError(12158): JNI_OnLoad Success
E/SELinux (12177): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PluginManager(12158): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
,D/PluginManager(12158): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(12158): JNI_OnLoad
I/ActivityManager( 3521): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=12177 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/Init_SPenSdk_Jni(12158): AndroidSDK: 21
D/Init_SPenSdk_Jni(12158): JNI_OnLoad .. Done
,D/Model_ObjectBase_Jni(12158): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni(12158): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(12158): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni(12158): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(12158): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni(12158): JNI_OnLoad .. Done
D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/Model_NoteDoc_Jni(12158): check build type eng[0]
D/Model_NoteDoc_Jni(12158): JNI_OnLoad .. Done
,D/Model_NoteFile_Jni(12158): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(12158): JNI_OnLoad .. Done
D/Model   (12158): OnLoad class Done
,D/spe_log (12158): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library(12158): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(12158): Canvas JNI_OnLoad enter!!
,D/SPen_Library(12158): Canvas JNI_OnLoad Success
D/SPen_Library(12158): TextView JNI_OnLoad enter!!
,D/SPen_Library(12158): TextView JNI_OnLoad Success
D/SPen_Library(12158): Text JNI_OnLoad enter!!
D/ResourcesManager(11505): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/SPen_Library(12158): Text JNI_OnLoad Success
D/SPen_Library(12158): FontManager JNI_OnLoad enter!!
D/SPen_Library(12158): FontManager JNI_OnLoad Success
D/SPen_Library(12158): CapturePage JNI_OnLoad enter!!
D/SPen_Library(12158): CapturePage JNI_OnLoad Success
D/SPen_Library(12158): Multi JNI_OnLoad enter!!
,D/SPen_Library(12158): Multi JNI_OnLoad Success
D/SPen_Library(12158): Draw Engine JNI_OnLoad Success
,D/SPen_Library(12158): Brush JNI_OnLoad enter!!
,D/SPen_Library(12158): Brush JNI_OnLoad Success
,D/SPen_Library(12158): ChineseBrush JNI_OnLoad enter!!
D/TimaKeyStoreProvider(12177): TimaSignature is unavailable
,D/SPen_Library(12158): ChineseBrush JNI_OnLoad Success
,D/ActivityThread(12177): Added TimaKeyStore provider
,D/SPen_Library(12158): InkPen JNI_OnLoad enter!!
D/SPen_Library(12158): InkPen JNI_OnLoad Success
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/SPen_Library(12158): Marker JNI_OnLoad enter!!
,D/SPen_Library(12158): Marker JNI_OnLoad Success
,D/SPen_Library(12158): Pencil JNI_OnLoad enter!!
,D/SPen_Library(12158): Pencil JNI_OnLoad Success
,D/SPen_Library(12158): NativePen JNI_OnLoad enter!!
,D/SPen_Library(12158): NativePen JNI_OnLoad Success
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/SPen_Library(12158): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library(12158): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library(12158): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library(12158): MontblancCalligraphyPen JNI_OnLoad Success
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/SPen_Library(12158): MagicPen JNI_OnLoad enter!!
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SPen_Library(12158): MagicPen JNI_OnLoad Success
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(11505): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11505): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11505): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/SPen_Library(12158): ObliquePen JNI_OnLoad enter!!
W/ResourcesManager(11505): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/SPen_Library(12158): ObliquePen JNI_OnLoad Success
,D/SPen_Library(12158): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(12158): FountainPen JNI_OnLoad Success
D/Spen    (12158): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(12158): SPenSdk_init2
D/Init_SPenSdk(12158): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(12158): Total S Pen SDK Directory Size = 0
D/Spen    (12158): initialize complete
D/ResourcesManager(12177): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/linker  (12158): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/ResourcesManager(12177): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12177): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SignOutReceiver(12158): NETWORK_STATE_CHANGED_ACTION
,W/ResourcesManager(12177): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,I/ActivityManager( 3521): Killing 10830:com.android.chrome/u0a90 (adj 13): bgCount ##31
,E/WifiStateMachine( 3521): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/WifiStateMachine( 3521): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/NearbySettings(12082): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings(12082): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(12082): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/NearbySettings(12082): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/NearbySettings(12082): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(12082): MountReceiver.onReceive - Set preference state off
V/NearbySettings(12082): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Books/Books.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/libpersona(12195): KNOX_SDCARD checking this for 10079
E/Zygote  (12195): MountEmulatedStorage()
I/libpersona(12195): KNOX_SDCARD not a persona
E/Zygote  (12195): v2
I/ActivityManager( 3521): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=12195 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12195): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/SELinux (12195): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
E/SELinux (12195): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/ActivityManager( 3521): Killing 10564:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 13): bgCount ##31
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/SNoteProvider(12177): onCreate enableSnoteSync = true
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/PackageManager( 3521): delete codoeFile: 
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/AASAUninstall( 3521):  com.test.thalitest not target!
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/PackageManager( 3521): result of delete: 1{383680665}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/AndroidRuntime(12097): Shutting down VM
,W/ResourcesManager( 3521): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/SNoteProvider(12177): ===query=== 
,D/TimaKeyStoreProvider(12195): TimaSignature is unavailable
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ActivityThread(12195): Added TimaKeyStore provider
,D/ResourcesManager(11505): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/Common  (12177): getScreenSize 1440 2560
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/FileShare-Server(12195): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/ActivityManager( 3521): Killing 11111:com.google.android.apps.magazines/u0a136 (adj 13): bgCount ##31
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/RCPManagerService( 3521): PackageReceiver onReceive()
I/HarmonyEASService( 3521): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3521): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3521): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3521): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3521): uID is 10595
D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
V/EnterpriseBillingPolicy( 3521): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3521): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3521): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3521): getBillingProfileForVpnEngine - start - com.test.thalitest
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/EnterpriseBillingPolicyStorage( 3521): getBillingProfileForVpnEngine - end - null
,D/TaskPersister( 3521): removeObsoleteFile: deleting file=25_task.xml
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SLocation( 3521): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/SmartBondingService( 3521): getSBEnabled() enabled =false
W/SLocation( 3521): No Active Data Connection
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : false mobile : false
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Hs20UtilService( 6287): Starting #9
I/Hs20UtilService( 6287): Message received 5007
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : false mobile : false
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/NearbySettings(12082): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(12082): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(12082): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/NearbySettings(12082): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(12082): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(12082): MountReceiver.onReceive - Set preference state off
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/NearbySettings(12082): MountReceiver.mPrefHandler - 7002
D/UsbSettingsManager( 3521): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3521): onPackageRemoved : com.test.thalitest
,D/GpsLocationProvider( 3521): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/SNoteProvider(12177): ===query=== 
,I/SignOutReceiver(12158): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 6287): Starting #10
,I/Hs20UtilService( 6287): Message received 5011
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Books/Books.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/ApplicationPolicy( 3521): updateDataUsageMap
I/ApplicationPolicy( 3521): updateDataUsageMap  idList is null 
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  (12215): MountEmulatedStorage()
,E/Zygote  (12215): v2
I/libpersona(12215): KNOX_SDCARD checking this for 10127
I/libpersona(12215): KNOX_SDCARD not a persona
,I/SELinux (12215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12215 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12215): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12215): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/TimaKeyStoreProvider(12215): TimaSignature is unavailable
,D/ActivityThread(12215): Added TimaKeyStore provider
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(12215): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/KeyguardWallpaperUpdator(12215): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12215): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12215): stopCheckCategoryVersion
,I/SignOutReceiver(12158): WIFI_STATE_CHANGED_ACTION
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,I/ActivityManager( 3521): Killing 10099:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,W/ContextImpl(12082): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/DockEventReceiver(12082): finishStartingService: stopping service
,D/ResourcesManager(11505): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/BluetoothNotiBroadcastReceiver(12082): onReceive
,D/ResourcesManager(11505): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/AuthorizationBluetoothService( 4240): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12235): MountEmulatedStorage()
E/Zygote  (12235): v2
I/libpersona(12235): KNOX_SDCARD checking this for 10063
I/libpersona(12235): KNOX_SDCARD not a persona
,I/SELinux (12235): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12235): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12235): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12235 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12235): TimaSignature is unavailable
,D/ActivityThread(12235): Added TimaKeyStore provider
,D/ResourcesManager(12235): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12235): onReceive()
,D/VRSetupWizardStub/PackageIntentReceiver(12235): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12235): packagename:com.test.thalitest
,I/KLMS-2.4.521: (10979): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 21 17:48:07 GMT+01:00 2016
,I/KLMS-2.4.521: (10979): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3521): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3521): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,I/KLMS-2.4.521: (10979): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (10979): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/elm:14491(11416): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/KLMS-2.4.521: (10979): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (10979): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (10979): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (10979): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (10979): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/elm:14491(11416): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3521): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3521): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3521): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3521): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/elm:14491(11416): ElmAgentService : onCreate()
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/UsbHostManager( 3521): displayNotification : [09h,00h,00h]
D/elm:14491(11416): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(11416): MainReceiver.listeningToPackageRemoved()
D/UsbHostManager( 3521): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3521): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3521): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/elm:14491(11416): MDMBridge.getInstance()
D/elm:14491(11416): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(11416): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (12258): MountEmulatedStorage()
E/Zygote  (12258): v2
I/libpersona(12258): KNOX_SDCARD checking this for 1000
I/libpersona(12258): KNOX_SDCARD not a persona
,I/ActivityManager( 3521): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=12258 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/elm:14491(11416): ElmAgentService : onDestroy().
,I/SELinux (12258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/SELinux (12258): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  (12269): MountEmulatedStorage()
E/Zygote  (12269): v2
I/libpersona(12269): KNOX_SDCARD checking this for 10050
I/libpersona(12269): KNOX_SDCARD not a persona
I/SELinux (12269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/UsbHostManager( 3521): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3521): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
I/SELinux (12269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12269 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (12269): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3521): Removing device '/dev/input/event10' due to inotify event
,I/KLMS-2.4.521: (10979): KLMSIntentService(): listeningToPackageRemoved().END
,I/EventHub( 3521): Removing device '/dev/input/event7' due to inotify event
,I/KLMS-2.4.521: (10979): KLMSIntentService(): onDestroy()
,D/com.sec.android.service.health.upgrade.UninstallReceiver(11351): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver(11351): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
,D/com.sec.android.service.health.upgrade.UninstallReceiver(11351): onReceive() : package name is not s health. Return !!!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12258): TimaSignature is unavailable
,D/ActivityThread(12258): Added TimaKeyStore provider
,D/TimaKeyStoreProvider(12269): TimaSignature is unavailable
,D/ActivityThread(12269): Added TimaKeyStore provider
,E/Zygote  (12289): MountEmulatedStorage()
E/Zygote  (12289): v2
I/libpersona(12289): KNOX_SDCARD checking this for 10183
I/EventHub( 3521): Removing device '/dev/input/event8' due to inotify event
I/libpersona(12289): KNOX_SDCARD not a persona
,I/SELinux (12289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12289 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,I/SELinux (12289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3521): Removing device '/dev/input/event9' due to inotify event
,D/TimaKeyStoreProvider(12289): TimaSignature is unavailable
,D/ActivityThread(12289): Added TimaKeyStore provider
,D/ResourcesManager(12269): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/EventHub( 3521): Removing device '/dev/input/event11' due to inotify event
,W/ResourcesManager(12269): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12269): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12269): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12269): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12269): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12269): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12269): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12269): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12258): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
D/LocationWidgetApplication(11505): getLastUiLocationId() : mLastUiLocationId = -100
,W/ResourcesManager(12258): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3521): Removing device '/dev/input/event12' due to inotify event
,D/ResourcesManager(12289): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/RCPManager(12258):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3521):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3521): queryAllProviders():  providerCallBack is not register for 0
,E/Zygote  (12304): MountEmulatedStorage()
,E/Zygote  (12304): v2
I/libpersona(12304): KNOX_SDCARD checking this for 1000
I/libpersona(12304): KNOX_SDCARD not a persona
,I/SELinux (12304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12304 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Killing 11194:com.samsung.android.sconnect/u0a150 (adj 13): bgCount ##31
,E/SELinux (12304): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3521): Removing device '/dev/input/event13' due to inotify event
,E/Zygote  (12319): MountEmulatedStorage()
E/Zygote  (12319): v2
I/libpersona(12319): KNOX_SDCARD checking this for 10101
I/libpersona(12319): KNOX_SDCARD not a persona
,I/ActivityManager( 3521): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12319 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/TimaKeyStoreProvider(12304): TimaSignature is unavailable
I/SELinux (12319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ActivityThread(12304): Added TimaKeyStore provider
E/SELinux (12319): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 10607:com.android.email/u0a178 (adj 13): bgCount ##31
,E/SQLiteLog(12289): (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3521): Removing device '/dev/input/event14' due to inotify event
,E/SQLiteDatabase(12289): Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
E/SQLiteDatabase(12289): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12289): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12289): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12289): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12289): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12289): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12289): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12289): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12289): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12289): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12289): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/SQLiteDatabase(12289): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/SQLiteDatabase(12289): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(12289): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(12289): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12289): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12289): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12289): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12289): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12289): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12289): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12289): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12289): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12289): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12289): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12289): Shutting down VM
,E/AndroidRuntime(12289): FATAL EXCEPTION: main
E/AndroidRuntime(12289): Process: com.samsung.android.provider.shootingmodeprovider, PID: 12289
E/AndroidRuntime(12289): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12289): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(12289): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(12289): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(12289): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(12289): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(12289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12289): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12289): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12289): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12289): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12289): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12289): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12289): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12289): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12289): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12289): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12289): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12289): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12289): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12289): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12289): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12289): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12289): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/AndroidRuntime(12289): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/AndroidRuntime(12289): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(12289): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(12289): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(12289): 	... 11 more
,V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
,D/ResourcesManager(12304): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(12319): TimaSignature is unavailable
,D/ActivityThread(12319): Added TimaKeyStore provider
E/DropBoxManagerService( 3521): Can't write: system_app_crash
E/DropBoxManagerService( 3521): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3521): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3521): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3521): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3521): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3521): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3521): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3521): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3521): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3521): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3521): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3521): 	... 5 more
,E/Watchdog( 3521): !@Sync 9
,E/SQLiteLog(12269): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,I/PCWCLIENTTRACE_LOG(12304): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12304): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper(12304): new DMDBOpenHelper instance
,E/SQLiteLog(12304): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(12269): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase(12269): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12269): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12269): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12269): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12269): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12269): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12269): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12269): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12269): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12269): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12269): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase(12269): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase(12269): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12269): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12269): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12269): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12269): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12269): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12269): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12269): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteDatabase(12304): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(12304): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12304): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12304): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12304): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12304): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12304): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12304): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12304): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12304): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12304): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12304): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12304): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12304): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12304): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12304): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(12304): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(12304): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(12304): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12304): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12304): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12304): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12304): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12304): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12304): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12304): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12304): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12304): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12304): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12304): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime(12304): Shutting down VM
,E/AndroidRuntime(12304): FATAL EXCEPTION: main
E/AndroidRuntime(12304): Process: com.sec.pcw.device, PID: 12304
E/AndroidRuntime(12304): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12304): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(12304): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(12304): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(12304): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(12304): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(12304): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12304): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12304): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12304): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12304): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12304): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12304): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12304): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12304): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12304): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12304): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12304): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12304): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12304): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12304): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12304): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12304): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12304): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12304): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12304): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12304): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12304): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(12304): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(12304): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(12304): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(12304): 	... 11 more

```
