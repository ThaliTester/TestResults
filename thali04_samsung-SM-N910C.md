#### Test 56449660bb41d23_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3506): !@Sync 4
,--------- beginning of main
D/AndroidRuntime(10612): 
D/AndroidRuntime(10612): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10612): CheckJNI is OFF
D/AndroidRuntime(10612): readGMSProperty: start
D/AndroidRuntime(10612): readGMSProperty: already setted!!
D/AndroidRuntime(10612): readGMSProperty: end
D/AndroidRuntime(10612): addProductProperty: start
D/SSRM:n  ( 3506): SIOP:: AP = 240, PST = 270, CUR = 28
E/AffinityControl(10612): AffinityControl: registerfunction enter
D/AndroidRuntime(10612): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3506): inState():  stateMachine is null !!
I/PersonaManagerService( 3506): PersonaId don't exist
I/ActivityManager( 3506): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3506): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3506): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3506): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3506): mDVFSHelper.acquire()
D/FocusedStackFrame( 3506): Set to : 0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/Zygote  (10630): MountEmulatedStorage()
E/Zygote  (10630): v2
I/libpersona(10630): KNOX_SDCARD checking this for 10594
I/libpersona(10630): KNOX_SDCARD not a persona
I/SELinux (10630): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3506): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=10630 uid=10594 gids={50594, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (10630): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10630): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10612): Shutting down VM
D/PointerIcon( 3506): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3506): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3506): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3506): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(10630): TimaSignature is unavailable
D/ActivityThread(10630): Added TimaKeyStore provider
V/WindowOrientationListener( 3506): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3506): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3506): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3506): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3506): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(10630): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2850): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2850): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 4000): updateVisibility : ActivityRecord{37a2c521 token=android.os.BinderProxy@138fc6e8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4000): onTrimMemory. Level: 20
D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3506): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
D/BatteryService( 3506): stay LED for fully charged
D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3506): Plugged
I/MotionRecognitionService( 3506): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/WebViewFactory(10630): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10630): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10630): Loading: webviewchromium
I/LibraryLoader(10630): Time to load native libraries: 4 ms (timestamps 4409-4413)
I/LibraryLoader(10630): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10630): Binding Chromium to main looper Looper (main, tid 1) {1265a4d9}
,I/LibraryLoader(10630): Expected native library version number "",actual native library version number ""
I/chromium(10630): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10630): Initializing chromium process, renderers=0
,W/art     (10630): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10630): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10630): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10630): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10630): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter(10630): 643268254: getState() :  mService = null. Returning STATE_OFF
,W/chromium(10630): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10630): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10630): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10630): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(10630): CordovaWebView is running on device made by: samsung
,W/art     (10630): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10630): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(10630): performCreate Call secproduct feature valuefalse
D/Activity(10630): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(10630): Render dirty regions requested: true
,D/ActivityManager( 3506): post active user change for 0
D/KnoxTimeoutHandler( 3506): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3506): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2850): id=12 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3506): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3506): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3506): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3506): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3506): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3506): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(10630): Initialized EGL, version 1.4
I/OpenGLRenderer(10630): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1279692528 
D/OpenGLRenderer(10630): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10630): Enabling debug mode 0
D/mali_winsys(10630): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(10630): updateVisibility : ActivityRecord{112ecb4e token=android.os.BinderProxy@10567fb4 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3506): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3506): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3506): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3506): mDVFSHelper.release()
,I/Timeline( 3506): Timeline: Activity_windows_visible id: ActivityRecord{3eefa0bc u0 com.test.thalitest/.MainActivity t25} time:134753
,W/IInputConnectionWrapper(10630): showStatusIcon on inactive InputConnection
,I/Timeline(10630): Timeline: Activity_idle id: android.os.BinderProxy@10567fb4 time:134758
,D/JsMessageQueue(10630): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(10630): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10630): 
,D/jxcore_app_log(10630): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361622400
,I/chromium(10630): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(10630): Initializing JXcore engine
W/jxcore-log(10630): JXcore engine is ready
,E/auditd  ( 4536): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3506): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3506): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3506): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10630): Starting JXcore engine
,W/jxcore-log(10630): Platform android
W/jxcore-log(10630): 
W/jxcore-log(10630): Process ARCH arm
W/jxcore-log(10630): 
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(10630): JXcore Cordova bridge is ready!
I/jxcore-log(10630): 
W/jxcore-log(10630): JXcore engine is started
,I/jxcore-log(10630): Toggling radios to true
I/jxcore-log(10630): 
,D/BluetoothAdapter(10630): enable()
,W/ActivityManager( 3506): Permission Denial: getCurrentUser() from pid=10630, uid=10594 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 3506): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 3506): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10630, uid=10594 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 3506): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/BluetoothManagerService( 3506): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2160)
W/BluetoothManagerService( 3506): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService( 3506): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 3506): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService( 3506): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3506): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 3506): name = bluetooth_on
,E/DevicePolicyManagerService( 3506): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3506): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,I/WifiManager(10630): packageName : com.test.thalitest
,D/WifiService( 3506): New client listening to asynchronous messages
D/SecContentProvider( 3506): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3506): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3506): mCursor = null
,D/WifiService( 3506): setWifiEnabled: true pid=10630, uid=10594
E/WifiService( 3506): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3506): Permission Denial: getCurrentUser() from pid=10630, uid=10594 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3506): Failed getting userId using ActivityManagerNative
W/WifiService( 3506): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10630, uid=10594 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3506): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3506): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3506): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3506): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3506): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3506): name = wifi_on
,I/WifiService( 3506): disconnect: pid=10630, uid=10594
,E/WifiStateMachine( 3506): setting operational mode to 1
,E/WifiHW  ( 3506): ##################### set firmware type 0 #####################
I/jxcore-log(10630): Radios toggled
I/jxcore-log(10630): 
,I/jxcore-log(10630): My device name is: samsung-SM-N910C
I/jxcore-log(10630): 
I/WifiHW  ( 2846): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,I/WifiHW  ( 2846): module is murata
E/WifiHW  ( 2846): ==========[WIFI] MURATA MODULE ===========
I/WifiHW  ( 2846): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_murata
E/WifiHW  ( 2846): TEMP_FAILURE_RETRY complete
D/SoftapController( 2846): Softap fwReload - Ok
,I/ActivityManager( 3506): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=10702 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
E/Zygote  (10702): MountEmulatedStorage()
I/libpersona(10702): KNOX_SDCARD checking this for 1002
E/Zygote  (10702): v2
I/libpersona(10702): KNOX_SDCARD not a persona
I/SELinux (10702): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10702): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/CommandListener( 2846): Setting iface cfg
D/CommandListener( 2846): Trying to bring down wlan0
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
E/SELinux (10702): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 281us total 10.126ms
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 643us total 8.466ms
,D/TimaKeyStoreProvider(10702): TimaSignature is unavailable
D/ActivityThread(10702): Added TimaKeyStore provider
I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 246us total 7.794ms
D/ResourcesManager(10702): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
W/ResourcesManager(10702): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(10702): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni(10702): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig(10702): Adding GattService
,D/BtSettings.ProfileConfig(10702): Adding HeadsetService
D/BtSettings.ProfileConfig(10702): Adding A2dpService
D/BtSettings.ProfileConfig(10702): Adding HidService
D/BtSettings.ProfileConfig(10702): Adding HealthService
D/BtSettings.ProfileConfig(10702): Adding PanService
D/BtSettings.ProfileConfig(10702): Adding BluetoothMapService
D/BtSettings.ProfileConfig(10702): Adding SapService
D/BtSettings.ProfileConfig(10702): Adding HeadsetClientService
D/BtSettings.ProfileConfig(10702): Adding A2dpSinkService
D/BtSettings.ProfileConfig(10702): Adding SapClientService
D/BtSettings.ProfileConfig(10702): Adding HidDevService
I/BtSettings.ProfileConfig(10702): *********Initializing Bluetooth Profile Settings*******
D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
E/WifiHW  ( 3506): supplicant_name : p2p_supplicant
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3506): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,I/wpa_supplicant(10717): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant(10717): Successfully initialized wpa_supplicant
,I/SecureStorage(10717): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecureStorage(10717): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage( 2916): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10717
I/SecureStorage( 2916): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
I/SecureStorage(10717): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant(10717): ssSupport state is = 1
,I/wpa_supplicant(10717): >>>>> GET KEY, IV <<<<<
,I/SecureStorage(10717): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage( 2916): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10717
I/SecureStorage( 2916): [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,D/BluetoothAdapterState(10702): make
,I/bluedroid(10702): init
I/BluetoothAdapterState(10702): Entering OffState
,I/bte_conf(10702): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf(10702): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config(10702): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf(10702): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif (10702): btif_fetch_local_ble_random_bdaddr
I/bluedroid(10702): get_profile_interface socket
I/bluedroid(10702): get_profile_interface map_client
,D/BluetoothAdapterService(10702): checkAddrForIOP: Loading from conf
,I/GKI_LINUX(10702): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterService(10702): Inband Ring is supported
,D/BluetoothAdapterProperties(10702): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10702): populateRssiValuesNative
I/bluedroid(10702): getModelRssiValues
E/BluetoothServiceJni(10702): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10702): modelRssiValuesCallback, low, mid, high = -75,-65,127
,D/BluetoothAdapterProperties(10702): Name is: Note4-1
,D/SettingsProvider( 3506): name = bluetooth_name
,I/bluedroid(10702): config_hci_snoop_log
,D/BluetoothManagerService( 3506): Broadcasting onBluetoothServiceUp() to 11 receivers.
,E/DevicePolicyManagerService( 3506): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3506): getAllowBluetoothMode - value retunrs : 2
,E/WifiStateMachine( 3506): setWifiState: enabling
,E/WifiStateMachine( 3506): Supplicant start successful
D/WifiMonitor( 3506): startMonitoring(wlan0) with mConnected = false
,D/SecContentProvider( 3506): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState(10702): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties(10702): Setting state to 11
I/BluetoothAdapterState(10702): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(10702): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10702): updateAdapterState state is 11
,D/SmartBondingService( 3506): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothAdapterService(10702): Autoconnection is available 
D/BluetoothAdapterService(10702): updateAdapterState prevState = 10newState = 11
D/BluetoothSecureManager(10702): getInstant: null
D/BluetoothSecureManager(10702): calling getMethod for getService
D/BluetoothSecureManager(10702): calling getService
,D/BluetoothSecureManager(10702): getService return binder: android.os.BinderProxy@3d261611
D/SLocation( 3506): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/BluetoothSecureManagerService( 3506): isSecureModeEnabled
D/BluetoothSecureManagerService( 3506): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode(10702): isSecureModeOn:false
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3693): Wifi onReceive(2)
,D/STATUSBAR-QSTileView( 3693): onStateChanged: Wi-Fi
W/BluetoothAdapterService(10702): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/HotspotTile( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/HotspotTile( 3693): onReceive : 2, 0
,W/BluetoothAdapterService(10702): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService(10702): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(10702): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/SmartBondingService( 3506): getNetworkEnabled : wifi : false mobile : false
W/BluetoothAdapterService(10702): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService(10702): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10702): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10702): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10702): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService(10702): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10702): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService(10702): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine(10702): make
,W/BluetoothAdapterService(10702): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine(10702): StableState(): Entering Off State
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.gatt.GattService
,W/InputMethodManagerService( 3506): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3506): [BT Setting State] State =11
,D/BluetoothTile( 3693):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3693): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,I/SamsungIME( 4454): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/StatusBarManagerService( 3506): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/STATUSBAR-QSTileView( 3693): onStateChanged: Bluetooth
W/BluetoothAdapterService(10702): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/StatusBarManagerService( 3506): setIconVisibility slot=bluetooth visible=false
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.hfp.HeadsetService
,I/BtGatt.JNI(10702): classInitNative(L900): classInitNative: Success!
,I/Hs20UtilService( 6284): Starting #2
I/Hs20UtilService( 6284): Message received 5011
D/BtGatt.DebugUtils(10702): handleDebugAction() action=null
,D/PhoneStatusBar( 3693): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
D/BtGatt.GattService(10702): Received start request. Starting profile...
D/BtGatt.GattService(10702): start()
I/bluedroid(10702): get_profile_interface gatt
D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
D/BtGatt.AdvertiseManager(10702): advertise manager created
,W/BluetoothAdapterService(10702): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.a2dp.A2dpService
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,V/[CarModeFW](10089): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/Zygote  (10726): MountEmulatedStorage()
I/libpersona(10726): KNOX_SDCARD checking this for 10127
E/Zygote  (10726): v2
I/libpersona(10726): KNOX_SDCARD not a persona
,I/SELinux (10726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10726): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=10726 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
,W/BluetoothAdapterService(10702): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.hid.HidService
,D/HeadsetService(10702): Received start request. Starting profile...
,W/BluetoothAdapterService(10702): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.hdp.HealthService
,I/BluetoothHeadsetServiceJni(10702): classInitNative: succeeds
,D/HeadsetStateMachine(10702): make
,E/HeadsetStateMachine(10702): # of Max HF connection is 2
,W/BluetoothAdapterService(10702): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService(10702): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService(10702): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10702): Not skipping com.broadcom.bt.service.sap.SapService
,I/bluedroid(10702): get_profile_interface handsfree
,D/TimaKeyStoreProvider(10726): TimaSignature is unavailable
,D/ActivityThread(10726): Added TimaKeyStore provider
W/BluetoothAdapterService(10702): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10702): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10702): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10702): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10702): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10702): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10702): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService(10702): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/DualScoManager(10702): Instantiating Dual Sco Manager
I/DualScoManager(10702): Set HeadsetServiceHelper
I/BluetoothAdapterState(10702): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAtMessage(10702): createCMTIContentObservers
,D/SettingsProvider( 3506): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine(10702): Enter Disconnected: -2
,E/HeadsetStateMachine(10702): set to mRemoteBrsf = 0
,D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
D/HeadsetStateMachine(10702): map size, before remove : 0
D/HeadsetStateMachine(10702): map size, after remove: 0
,E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/BluetoothA2dp( 3506): Proxy object connected
D/BluetoothA2dp( 4805): Proxy object connected
,D/A2dpService(10702): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni(10702): classInitNative: succeeds
V/Avrcp   (10702): make
V/Avrcp   (10702): Avrcp
I/bluedroid(10702): get_profile_interface avrcp
,V/Avrcp   (10702): start
,D/ResourcesManager(10726): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,E/RemoteController(10702): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   (10702): ++registerMediaPlayers++
,I/Avrcp   (10702): No of Audio players :: 2
I/Avrcp   (10702): App Package name is com.google.android.music
,D/ResourcesManager(10702): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   (10702): App pkg name is Google Play Music
,I/Avrcp   (10702): Name::Google Play Music
V/Avrcp   (10702): MediaPlayerInfo: mPlayerId=1
I/Avrcp   (10702): App Package name is com.sec.android.app.music
,D/ResourcesManager(10702): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   (10702): App pkg name is Music
,I/Avrcp   (10702): Name::Music
V/Avrcp   (10702): MediaPlayerInfo: mPlayerId=2
,I/Avrcp   (10702): No of Video players :: 1
I/Avrcp   (10702): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager(10702): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   (10702): Video App pkg name is Video Player
,I/Avrcp   (10702): Name::Video Player
V/Avrcp   (10702): MediaPlayerInfo: mPlayerId=3
I/Avrcp   (10702): Add tempPlayer
V/Avrcp   (10702): MediaPlayerInfo: mPlayerId=4
I/Avrcp   (10702): Total no of players: 4
V/Avrcp   (10702): swapping the samsung player with 1st player
I/Avrcp   (10702):  Updating now playing list upon AVRCP Start
V/Avrcp   (10702): handleMessage, msg=207
D/BluetoothMediaBrowser(10702):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,V/Avrcp   (10702): CurrentAudioFocusPackageName is null
I/Avrcp   (10702): There is no currently selected player ,setting Samsung Music Player ID
I/Avrcp   (10702):  set player publishabilty with player id::1 toBePublished ::true
I/BluetoothA2dpServiceJni(10702): classInitNative: succeeds
D/A2dpStateMachine(10702): make
,I/bluedroid(10702): get_profile_interface a2dp
I/GKI_LINUX(10702): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif (10702): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
D/A2dpStateMachine(10702): Enter Disconnected: -2
,I/BluetoothHidServiceJni(10702): classInitNative: succeeds
D/HidService(10702): Received start request. Starting profile...
I/bluedroid(10702): get_profile_interface hidhost
D/HidService(10702): setHidService(): set to: null
D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
,I/BluetoothHealthServiceJni(10702): classInitNative: succeeds
,D/HealthService(10702): Received start request. Starting profile...
,I/bluedroid(10702): get_profile_interface health
D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
,I/BluetoothPanServiceJni(10702): classInitNative(L105): succeeds
,D/BluetoothPan( 3506): BluetoothPAN Proxy object connected
,D/KeyguardWallpaperUpdator(10726): cancelUpdateWallpaper
D/PanService(10702): Received start request. Starting profile...
D/BluetoothPanServiceJni(10702): initializeNative(L110): pan
I/bluedroid(10702): get_profile_interface pan
D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
,D/KeyguardWallpaperUpdator(10726): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10726): stopCheckCategoryVersion
,D/BluetoothMapService(10702): Received start request. Starting profile...
,I/SignOutReceiver( 8324): WIFI_STATE_CHANGED_ACTION
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10751): MountEmulatedStorage()
I/libpersona(10751): KNOX_SDCARD checking this for 10178
E/Zygote  (10751): v2
I/libpersona(10751): KNOX_SDCARD not a persona
,I/SELinux (10751): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10751): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3506): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=10751 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux (10751): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothMediaBrowser(10702): no now playing list
D/BluetoothMediaBrowser(10702):  getNowPlayingId now playing id : -1
D/Avrcp   (10702):  checkNowPlayingList start
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10751): TimaSignature is unavailable
,D/ActivityThread(10751): Added TimaKeyStore provider
,E/Zygote  (10766): MountEmulatedStorage()
E/Zygote  (10766): v2
I/libpersona(10766): KNOX_SDCARD checking this for 1000
I/libpersona(10766): KNOX_SDCARD not a persona
,I/SELinux (10766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3506): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=10766 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (10766): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10751): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(10751): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(10751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10751): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10751): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10751): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10751): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(10766): TimaSignature is unavailable
,D/ActivityThread(10766): Added TimaKeyStore provider
,D/ResourcesManager(10766): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10782): MountEmulatedStorage()
I/libpersona(10782): KNOX_SDCARD checking this for 10186
E/Zygote  (10782): v2
I/libpersona(10782): KNOX_SDCARD not a persona
,I/SELinux (10782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10782): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3506): Start proc tv.peel.smartremote for broadcast tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver: pid=10782 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 3506): Killing 9938:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,D/RCPManagerService( 3506): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(10782): TimaSignature is unavailable
,D/ActivityThread(10782): Added TimaKeyStore provider
,D/RCPManagerService( 3506): exchangeData() failure , invalid userId
,D/RCPManagerService( 3506): exchangeData() failure , invalid userId
,D/ResourcesManager(10782): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,W/ResourcesManager(10782): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/RCPManagerService( 3506): exchangeData() failure , invalid userId
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
,D/HeadsetStateMachine(10702): Try to query the phonestate on bind
,I/Telecom ( 3951): BluetoothPhoneService: queryPhoneState
,E/Zygote  (10805): MountEmulatedStorage()
I/Telecom ( 3951): BluetoothPhoneService: updateHeadsetWithCallState
E/Zygote  (10805): v2
I/libpersona(10805): KNOX_SDCARD checking this for 10082
I/libpersona(10805): KNOX_SDCARD not a persona
,I/SELinux (10805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3506): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=10805 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/SELinux (10805): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/Telecom ( 3951): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 3951): Proxy not attached to service
,D/HeadsetStateMachine(10702): Proxy object connected
D/HeadsetPhoneState(10702): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine(10702): Disconnected process message: 11
,I/BluetoothSAPServiceJni(10702): classInitNative(L204): succeeds
,D/SapService(10702): Received start request. Starting profile...
D/BluetoothSAPServiceJni(10702): initializeNative(L209): sap
I/bluedroid(10702): get_profile_interface sap
D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
D/HeadsetPhoneState(10702): sendDeviceDataStateChanged
D/HeadsetPhoneState(10702): Signal level : previous=0 curr=0
E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp(10702): Proxy object connected
D/BluetoothAdapterService(10702): Bluetooth A2dp source service connected
E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/HeadsetStateMachine(10702): Disconnected process message: 18
E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/HeadsetStateMachine(10702): Disconnected process message: 10
D/HeadsetPhoneState(10702): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine(10702): Disconnected process message: 11
,I/ActivityManager( 3506): Killing 9955:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/BluetoothAdapterState(10702): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid(10702): enable
,D/TimaKeyStoreProvider(10805): TimaSignature is unavailable
D/ActivityThread(10805): Added TimaKeyStore provider
,I/bt_hci_bdroid(10702): init
I/GKI_LINUX(10702): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor(10702): init
I/bt_vnd_conf(10702): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/ActivityManager( 3506): Killing 9980:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
I/bt_vnd_conf(10702): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial(10702): userial_init
,D/ResourcesManager(10805): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(10805): onCreate
D/BadgeProvider(10805): DatabaseHelper
,D/BadgeProvider(10805): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(10805): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10805): sendNotify, [notify] : null
D/BadgeProvider(10805): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10805): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10805): update, [UpdateCount] : 1
,D/Launcher.Model( 4000): reloadBadges entered.
,I/WebViewFactory(10782): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(10782): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(10782): Loading: webviewchromium
,I/LibraryLoader(10782): Time to load native libraries: 3 ms (timestamps 6835-6838)
I/LibraryLoader(10782): Expected native library version number "",actual native library version number ""
,I/bt_userial_vendor(10702): userial vendor open: opening /dev/ttySAC3
,I/bt_userial_vendor(10702): userial_vendor_open():UART is setup
I/bt_userial_vendor(10702): device fd = 65 open
E/bt_hwcfg(10702): Start CFG HW, HCI reset
D/bt_userial(10702): Entering userial_read_thread()
,V/WebViewChromiumFactoryProvider(10782): Binding Chromium to main looper Looper (main, tid 1) {14d8a223}
,I/LibraryLoader(10782): Expected native library version number "",actual native library version number ""
,I/chromium(10782): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
E/bt_hwcfg(10702): Read Local Name after HCI reset
,W/ActivityManager( 3506): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/BrowserStartupController(10782): Initializing chromium process, renderers=0
,W/art     (10782): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10782): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10782): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10782): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
I/chromium(10782): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
,D/bt_hwcfg(10702): Chipset BCM43569A1
D/bt_hwcfg(10702): Target name = [BCM4358A1]
,I/bt_hwcfg(10702): module_type[murata].
I/bt_hwcfg(10702): module_type[murata] is invalid.
E/bt_hwcfg(10702): patchram path ORG . BCM4358A1
E/bt_hwcfg(10702): patchram path ORG .. BCM4358A1
E/bt_hwcfg(10702): patchram path ORG bcm4358A0_V0033.0000.hcd BCM4358A1
E/bt_hwcfg(10702): patchram path ORG bcm4358A1_V0044.0078.hcd BCM4358A1
I/bt_hwcfg(10702): patch(org) : bcm4358A1_V0044.0078.hcd
I/bt_hwcfg(10702): Found patchfile: /vendor/firmware/bcm4358A1_V0044.0078.hcd
E/bt_hwcfg(10702): ORG patchram base 0044
E/bt_hwcfg(10702): ORG patchram minor 0078
E/bt_hwcfg(10702): fw ver (org)44.78
E/bt_hwcfg(10702): Final Patchram is /vendor/firmware/bcm4358A1_V0044.0078.hcd
,I/bt_hwcfg(10702): Axi patch failure or not include AXI patching
,I/bt_hwcfg(10702): bt vendor lib: set UART baud 3000000
,I/SecureStorage(10717): [INFO]: SPID(0x00000005)Processing data has been completed
,I/SecureStorage(10717): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,W/chromium(10782): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10782): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/SecureStorage(10717): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10717
I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10717): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10717): ssSupport state is = 1
,I/wpa_supplicant(10717): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10717): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10717): SIM READ ERROR
I/wpa_supplicant(10717): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10717): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10717): SIM READ ERROR
I/wpa_supplicant(10717): Blacklist: Clear (all) 
,I/wpa_supplicant(10717): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10717): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant(10717): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10717): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant(10717): rfkill: Cannot open RFKILL control device
,W/art     (10782): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10782): onDetachedFromWindow called when already detached. Ignoring
,I/ActivityManager( 3506): Killing 9235:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/BluetoothNotiBroadcastReceiver( 7650): onReceive
,D/AuthorizationBluetoothService( 4239): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_hwcfg(10702): bt vendor lib: set UART baud 115200
I/bt_hwcfg(10702): FW Download delta = 457622
D/bt_hwcfg(10702): Settlement delay -- 100 ms
I/bt_hwcfg(10702): Setting fw settlement delay to 100 
,I/bt_hwcfg(10702): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg(10702): vendor lib fwcfg completed
,I/        (10702): BTE_InitTraceLevels -- TRC_HCI
I/        (10702): BTE_InitTraceLevels -- TRC_L2CAP
I/        (10702): BTE_InitTraceLevels -- TRC_RFCOMM
I/        (10702): BTE_InitTraceLevels -- TRC_AVDT
I/        (10702): BTE_InitTraceLevels -- TRC_AVRC
I/        (10702): BTE_InitTraceLevels -- TRC_A2D
I/        (10702): BTE_InitTraceLevels -- TRC_BNEP
I/        (10702): BTE_InitTraceLevels -- TRC_BTM
I/        (10702): BTE_InitTraceLevels -- TRC_GAP
I/        (10702): BTE_InitTraceLevels -- TRC_PAN
I/        (10702): BTE_InitTraceLevels -- TRC_SAP
I/        (10702): BTE_InitTraceLevels -- TRC_SDP
I/        (10702): BTE_InitTraceLevels -- TRC_GATT
I/        (10702): BTE_InitTraceLevels -- TRC_SMP
I/        (10702): BTE_InitTraceLevels -- TRC_BTAPP
I/        (10702): BTE_InitTraceLevels -- TRC_BTIF
I/        (10702): BTE_InitTraceLevels -- TRC_PROTOCOL
,E/Tethering( 3506): No numeric data
,D/Tethering( 3506): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 3506): forceRefresh() from cache miss
,D/HotspotTile( 3693): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3693): updateTetherState():false, false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 3506): forceRefresh Fail.
V/NetworkStats( 3506): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3506): UpdateStatsForKnox
V/NetworkStats( 3506): performPollLocked() took 2ms
,D/NtpTrustedTime( 3506): forceRefresh() from cache miss
,D/NtpTrustedTime( 3506): forceRefresh Fail.
,W/bt-l2cap(10702): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  (10702): BTM_SecRegister:p_cb_info->p_le_callback == 0xb39eb9e1 
E/bt-btm  (10702): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb39eb9e1 
,I/wpa_supplicant(10717): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant(10717): wlan0: State: DISCONNECTED -> DISCONNECTED
I/SecureStorage(10717): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10717): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10717
I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10717): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10717): ssSupport state is = 1
,I/SecureStorage(10717): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10717): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10717
I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10717): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10717): ssSupport state is = 1
I/wpa_supplicant(10717): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10717): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10717): SIM READ ERROR
I/wpa_supplicant(10717): rfkill: Cannot open RFKILL control device
E/wpa_supplicant(10717): nl80211: Could not configure driver mode
E/wpa_supplicant(10717): p2p0: Failed to initialize driver interface
I/wpa_supplicant(10717): Blacklist: Clear (all) 
,I/SecureStorage(10717): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10717): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10717
I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
D/BluetoothAdapterProperties(10702): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
I/SecureStorage(10717): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10717): ssSupport state is = 1
I/SecureStorage(10717): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,E/bt-btif (10702): Calling BTA_HhEnable
E/bt-btif (10702): btif_storage_get_adapter_property service_mas, proto_id 6, chan_id
D/BluetoothAdapterProperties(10702): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10702): populateRssiValuesNative
I/bluedroid(10702): getModelRssiValues
E/BluetoothServiceJni(10702): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10702): modelRssiValuesCallback, low, mid, high = -75,-65,127
,D/BluetoothAdapterProperties(10702): Name is: Note4-1
D/SettingsProvider( 3506): name = bluetooth_name
D/BluetoothAdapterProperties(10702): Scan Mode:20
D/BluetoothAdapterProperties(10702): Discoverable Timeout:120
D/BluetoothAdapterProperties(10702): LE Address is:E0:B7:20:28:C5:81
E/bt-btif (10702): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif (10702): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif (10702): btif_sock_init: !radio_req && !rfc_init
E/bt-btif (10702): btif_sock_init: !vhci_init
D/IOP_DB_BT(10702): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT(10702): db_open: db_open : handle 3012829200l, read 14063 bytes onto local cache
D/IOP_DB_BT(10702): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT(10702): db_query: result 1
I/        (10702): iop_db_open: iop_db_open status 0
,D/bte_conf(10702): Device ID record 1 : primary
D/bte_conf(10702):   vendorId            = 0075
D/bte_conf(10702):   vendorIdSource      = 0001
D/bte_conf(10702):   product             = 0100
D/bte_conf(10702):   version             = 0200
D/bte_conf(10702):   clientExecutableURL = 
D/bte_conf(10702):   serviceDescription  = 
D/bte_conf(10702):   documentationURL    = 
D/bte_conf(10702): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni(10702): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState(10702): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties(10702): ScanMode =  20
D/BluetoothAdapterProperties(10702): State =  11
,D/SecContentProvider( 3506): uri = 3 selection = isDiscoverableEnabled
D/BluetoothAdapterProperties(10702): Setting state to 12
I/BluetoothAdapterState(10702): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties(10702): Scan Mode:21
D/BluetoothAdapterProperties(10702): Discoverable Timeout:120
,D/SettingsProvider( 3506): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
I/SecureStorage(10717): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10717
I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10717): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10717): ssSupport state is = 1
I/wpa_supplicant(10717): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10717): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10717): SIM READ ERROR
I/wpa_supplicant(10717): rfkill: Cannot open RFKILL control device
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService(10702): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10702): updateAdapterState state is 12
,D/BluetoothA2dp( 4805): onBluetoothStateChange: up=true
D/BluetoothA2dp( 3506): onBluetoothStateChange: up=true
,D/BluetoothA2dp(10702): onBluetoothStateChange: up=true
D/BluetoothAdapterService(10702): Autoconnection is available 
,D/BluetoothAdapterService(10702): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService(10702): starting service from this receiver
,I/BluetoothAdapterState(10702): Entering On State from state = 11
,W/InputMethodManagerService( 3506): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3506): [BT Setting State] State =12
I/InputMethodManagerService( 3506): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/BluetoothPbapService(10702): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothTile( 3693):  onBluetoothStateChange:
D/BluetoothHeadset( 3951): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@37911a7b, true
,D/BluetoothTile( 3693):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3693): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothHeadset( 3951): registerMessageListener
,I/SamsungIME( 4454): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,E/bt_h4   (10702): vendor lib postload completed
,D/StatusBarManagerService( 3506): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3506): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 3693): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/HeadsetService(10702): registerMessageListener
,D/HeadsetService(10702): registerMessageListener
D/HeadsetStateMachine(10702): Disconnected process message: 70
D/HeadsetStateMachine(10702): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1faecd29
,I/Telecom ( 3951): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 3951): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/BluetoothTile( 3693):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 3693): onStateChanged: Bluetooth
,D/HeadsetStateMachine(10702): Disconnected process message: 9
D/HeadsetStateMachine(10702): mNumActive: 0 mNumHeld: 0 mCallState: 6
,W/ContextImpl( 7650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,V/[CarModeFW](10089): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
D/[CarModeFW](10089): ConnectivityManager-handleMessage INITIAL_STATE_ON
,I/AudioHardwareTinyALSA( 2855): setParameters(A2dpSuspended=false)
,E/HeadsetStateMachine(10702): terminateScoUsingVirtualVoiceCall:No present call to terminate
,I/BluetoothPbapService(10702): Handler(): got msg=1
,D/BluetoothManagerService( 3506): Broadcasting onBluetoothServiceUp() to 0 receivers.
,I/wpa_supplicant(10717): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant(10717): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,D/SecContentProvider( 3506): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/LocalBluetoothProfileManager( 7650): Adding local A2DP profile
,V/BluetoothPbapService(10702): PBAP Service initSocket try: 0
,D/LocalBluetoothProfileManager( 7650): Adding local HEADSET profile
,E/BluetoothHeadset( 7650): BTStateChangeCB is registed
,W/BluetoothAdapter(10702): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10702): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket(10702): bindListen(), new LocalSocket 
D/BluetoothSocket(10702): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10702): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ac1f861
D/BluetoothSocket(10702): channel: 19
D/BluetoothPbapService(10702): PBAP Socket is BluetoothServerSocket
D/BluetoothMapMasInstance(10702): set MAP SDP message type : 1
E/BluetoothHeadset( 7650): BluetoothHeadset service is binded
,W/BluetoothAdapter(10702): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10702): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket(10702): bindListen(), new LocalSocket 
D/BluetoothSocket(10702): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10702): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a4a7f86
D/BluetoothSocket(10702): channel: 5
,W/ContextImpl( 7650): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 7650): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 7650): PANU : true
D/LocalBluetoothProfileManager( 7650): Adding local MAP profile
,D/BluetoothMap( 7650): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 7650): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 7650): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 7650): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 7650): onReceive
,D/BluetoothA2dp( 7650): Proxy object connected
D/A2dpProfile( 7650): Bluetooth service connected
,D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
D/BtConfig.SecureMode(10702): isSecureModeOn:false
,D/HeadsetProfile( 7650): Bluetooth service connected
,D/Bluetoothsap( 7650): BluetoothSAP Proxy object connected
,D/SapProfile( 7650): Bluetooth service connected
D/Bluetoothsap( 7650): getConnectedDevices()
,D/BluetoothInputDevice( 7650): Proxy object connected
D/HidProfile( 7650): Bluetooth service connected
,D/AuthorizationBluetoothService( 4239): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPan( 7650): BluetoothPAN Proxy object connected
D/PanProfile( 7650): Bluetooth service connected
,D/BluetoothMap( 7650): Proxy object connected
D/MapProfile( 7650): Bluetooth service connected
D/BluetoothPbap( 7650): Proxy object connected
D/PbapServerProfile( 7650): Bluetooth service connected
,D/SecContentProvider( 3506): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/wpa_supplicant(10717): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant(10717): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant(10717): Skip scan - bUseNetwork false
,E/WifiStateMachine( 3506): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,E/WifiStateMachine( 3506): setSuspendOptimizations: 2 true
E/WifiStateMachine( 3506): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine( 3506): Supplicant connection established
,D/WifiNative-HAL( 3506): callSECApiBoolean - ID [21]
,I/wpa_supplicant(10717): HOTSPOT20_ENABLE called
I/wpa_supplicant(10717): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10717): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10717): SIM READ ERROR
I/wpa_supplicant(10717): Blacklist: Clear (all) 
,W/BluetoothAdapter(10702): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10702): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
D/BluetoothSocket(10702): bindListen(), new LocalSocket 
,D/BluetoothSocket(10702): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10702): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f13afe0
D/BluetoothSocket(10702): channel: 12
I/BtOppRfcommListener(10702): Accept thread started.
,I/wpa_supplicant(10717): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant(10717): Skip scan - bUseNetwork false
,E/WifiStateMachine( 3506): setWifiState: enabled
D/WifiNative-HAL( 3506): callSECApiInt - ID [210]
,D/SmartBondingService( 3506): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/WifiConfigStore( 3506): Loading config and enabling all networks 
D/SLocation( 3506): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/SmartBondingService( 3506): getNetworkEnabled : wifi : true mobile : false
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/HotspotTile( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3693): Wifi onReceive(3)
D/STATUSBAR-QSTileView( 3693): onStateChanged: Wi-Fi
,I/Hs20UtilService( 6284): Starting #3
D/HotspotTile( 3693): onReceive : 3, 0
,I/Hs20UtilService( 6284): Message received 5011
I/WifiStateMachine( 3506): callSECApi what=207
,D/KeyguardWallpaperUpdator(10726): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(10726): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10726): stopCheckCategoryVersion
,E/WifiConfigStore( 3506): Not a HS20
,E/WifiConfigStore( 3506): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/SignOutReceiver( 8324): WIFI_STATE_CHANGED_ACTION
,I/WifiStateMachine( 3506): update LTECoexState:0
D/WifiNative-HAL( 3506): callSECApiInt - ID [65]
,D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant(10717): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant(10717): reset timer : RESET_TIMER 0
I/wpa_supplicant(10717): P2P: Current p2p state = IDLE
I/wpa_supplicant(10717): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant(10717): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant(10717): First Scan Start
,I/wpa_supplicant(10717): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL( 3506): Setting external_sim to 1
D/WifiStateMachine( 3506): Setting OUI to DA-A1-19
I/WifiNative-HAL( 3506): startHal
E/wifi    ( 3506): getStaticLongField sWifiHalHandle 0x8fc0485c
D/wifi    ( 3506): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x602342
I/WifiNative-HAL( 3506): Could not start hal
,E/WifiStateMachine( 3506): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,E/WifiStateMachine( 3506): Attempting to reconnect to wifi network ..
,E/native  ( 3506): do suspend true
,E/WifiStateMachine( 3506): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiStateMachine( 3506): updateConfiguredNetworkExpiration - currTime: 1453390936790
D/WifiP2pService( 3506): P2pDisabledState{ what=131203 }
D/WifiStateMachine( 3506): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/WifiScanningService( 3506): SCAN_AVAILABLE : 3
D/WifiScanningService( 3506): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 3506): startHal
D/RttService( 3506): SCAN_AVAILABLE : 3
,E/WifiStateMachine( 3506): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL( 3506): callSECStringApiVoid - ID [215]
E/wifi    ( 3506): getStaticLongField sWifiHalHandle 0x8e9bc98c
E/WifiNative-HAL( 3506): invaild command id : 215
D/wifi    ( 3506): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x102346
D/RttService( 3506): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 3506): Could not start hal
E/WifiScanningService( 3506): could not start HAL
E/WifiStateMachine( 3506): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3506): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,D/CommandListener( 2846): Setting iface cfg
D/CommandListener( 2846): Trying to bring up p2p0
,D/WifiMonitor( 3506): startMonitoring(p2p0) with mConnected = true
E/WifiStateMachine( 3506): set country code pl
,D/WifiP2pService( 3506): P2pEnablingState
,D/WifiP2pService( 3506): P2pEnablingState{ what=147457 }
,D/WifiP2pService( 3506): P2p socket connection successful
,D/WifiP2pService( 3506): P2pEnabledState
D/WifiP2pService( 3506): sending p2p connection changed broadcast: IDLE
,E/WifiStateMachine( 3506): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 3506): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiP2pService( 3506): create mNetworkAgent
,D/WifiDisplayController( 3506): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3506): disconnect
D/WifiDisplayController( 3506): updateConnection
D/WifiDisplayController( 3506): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3506): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3506): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/NearbySettings( 7650): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 7650): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 7650): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 7650): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/AllShareCastTile( 3693): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3506): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
V/NearbySettings( 7650): DMSUtil.isNetworkConnected - flag-null, state-null
D/AllShareCastTile( 3693): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,I/NearbySettings( 7650): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 7650): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 7650): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7650): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 7650): MountReceiver.mPrefHandler - 7002
,I/wpa_supplicant(10717): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/WifiStateMachine( 3506): set frequency band 0
,D/ConnectivityService( 3506): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 3506): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3506): updateNetworkInfo()
,D/ConnectivityService( 3506): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/CSLegacyTypeTracker( 3506): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,I/wpa_supplicant(10717): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/WifiStateMachine( 3506): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3506): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine( 3506): setDetailed state send new extra info
,D/SecContentProvider2( 3506): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3506): mCursor = null
,D/SecContentProvider2( 3506): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3506): mCursor = null
D/WifiNative-HAL( 3506): p2pGetDeviceAddress
,D/WifiNative-HAL( 3506): p2pGetDeviceAddress returning 92:b6:86:43:73:1c
,D/WifiP2pService( 3506): DeviceAddress: 92:73:1c
,D/WifiDisplayController( 3506): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note4-1
D/WifiDisplayController( 3506):  deviceAddress: 92:b6:86:43:73:1c
D/WifiDisplayController( 3506):  primary type: 10-0050F204-5
D/WifiDisplayController( 3506):  secondary type: null
D/WifiDisplayController( 3506):  wps: 0
D/WifiDisplayController( 3506):  grpcapab: 0
D/WifiDisplayController( 3506):  devcapab: 0
D/WifiDisplayController( 3506):  status: 3
D/WifiDisplayController( 3506):  wfdInfo: null
D/WifiDisplayController( 3506):  groupownerAddress: null
D/WifiDisplayController( 3506):  GOdeviceName: null
D/WifiDisplayController( 3506):  interfaceAddress: 
D/WifiDisplayController( 3506):  SConnectInfo : null
,D/WifiP2pService( 3506): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 3506): InactiveState
D/WifiP2pService( 3506): InactiveState{ what=143376 }
D/WifiP2pService( 3506): P2pEnabledState{ what=143376 }
,I/wpa_supplicant(10717): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService( 3506): updateNetworkInfo()
D/WifiP2pService( 3506): InactiveState{ what=143376 }
D/WifiP2pService( 3506): P2pEnabledState{ what=143376 }
,I/art     ( 3506): Explicit concurrent mark sweep GC freed 42390(2MB) AllocSpace objects, 13(208KB) LOS objects, 24% free, 48MB/64MB, paused 1.255ms total 86.532ms
,D/WifiService( 3506): New client listening to asynchronous messages
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10899): MountEmulatedStorage()
I/libpersona(10899): KNOX_SDCARD checking this for 10079
E/Zygote  (10899): v2
I/libpersona(10899): KNOX_SDCARD not a persona
,I/SELinux (10899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10899): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3506): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=10899 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10899): TimaSignature is unavailable
,D/ActivityThread(10899): Added TimaKeyStore provider
,D/ResourcesManager(10899): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(10899): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 3506): Killing 8417:com.android.mms/u0a52 (adj 13): bgCount ##31
,D/CountryDetector( 3506): No listener is left
,I/wpa_supplicant(10717): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant(10717): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant(10717): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant(10717): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant(10717): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3506): [1,453,390,937,346 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3506): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@f8dd174 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3506): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3506): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,D/SecContentProvider2( 3506): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3506): mCursor = null
,I/wpa_supplicant(10717): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant(10717): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3506): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3506): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3506): setDetailed state send new extra info"NG700"
I/wpa_supplicant(10717): Associated with C0.AA.48
,D/SecContentProvider2( 3506): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3506): mCursor = null
,I/wpa_supplicant(10717): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant(10717): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3506): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3506): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3506): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3506): mCursor = null
,I/wpa_supplicant(10717): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant(10717): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant(10717): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3506): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3506): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant(10717): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(10717): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant(10717): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant(10717): Blacklist: Clear (temp) 
I/wpa_supplicant(10717): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3506): Network connection established
D/WifiNative-HAL( 3506): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3506): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine( 3506): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3506): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3506): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine( 3506): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3506): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3506): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3506): updateNetworkInfo()
,D/ConnectivityService( 3506): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 6284): Starting #4
,I/Hs20UtilService( 6284): Message received 5007
E/WifiStateMachine( 3506): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine( 3506): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3506): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3506): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/NearbySettings( 7650): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 7650): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 7650): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 7650): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7650): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7650): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7650): MountReceiver.mPrefHandler - 7002
,D/CommandListener( 2846): Setting iface cfg
,I/SignOutReceiver( 8324): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3506): Start Dhcp Watchdog 1
,D/SecContentProvider2( 3506): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 3506): mCursor = null
,E/WifiStateMachine( 3506): Force RSSI Broadcast 1/3
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3506): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3506): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3506): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3506): do suspend false
,D/SecContentProvider2( 3506): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3506): InactiveState{ what=143375 }
D/SecContentProvider2( 3506): mCursor = null
D/WifiP2pService( 3506): P2pEnabledState{ what=143375 }
,I/jxcore-log(10630): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(10630): 
,E/dhcpcd  (10918): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (10918): version 5.5.6 starting
,E/dhcpcd  (10918): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (10918): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (10918): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (10918): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (10918): bssid match
,I/dhcpcd  (10918): wlan0: rebinding lease of 192.168.1.124
,I/jxcore-log(10630): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(10630): 
,I/jxcore-log(10630): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(10630): 
,I/jxcore-log(10630): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(10630): 
,I/jxcore-log(10630): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(10630): 
,I/jxcore-log(10630): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(10630): 
,I/jxcore-log(10630): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(10630): 
,I/dhcpcd  (10918): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (10918): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3506): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3506): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3506): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3506): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3506): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3506): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3506): do suspend true
,D/WifiP2pService( 3506): InactiveState{ what=143375 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3506): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3506): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3506): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3506): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3506): Not connected state, yet.
E/WifiStateMachine( 3506): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3506): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3506): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3506): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3506): callSECApiInt - ID [210]
E/WifiStateMachine( 3506): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3506): updateNetworkInfo()
,D/ConnectivityService( 3506): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3506): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 3506): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3506): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3506): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiWatchdogStateMachine.SingDnsChecker( 3506): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3506): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,I/Hs20UtilService( 6284): Starting #5
,I/Hs20UtilService( 6284): Message received 5007
,D/NearbySettings( 7650): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 7650): MountReceiver.onReceive - Keep current state
,E/WifiStateMachine( 3506): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3506): Now, connected state.
E/WifiStateMachine( 3506): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3506): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3506): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService( 3506): Adding Route [fe80::/64 -> :: wlan0] to network 502
,I/SignOutReceiver( 8324): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 3506): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
D/ConnectivityService( 3506): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,E/WifiStateMachine( 3506): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService( 3506): Unexpected mtu value: 0, wlan0
,E/WifiStateMachine( 3506): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/WifiTrafficPoller( 3506): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3506): callSECApiVoid - ID [212]
,V/        ( 2846): QcRouteController
,I/WifiStateMachine( 3506): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/Hs20UtilService( 6284): Starting #6
,I/Hs20UtilService( 6284): Message received 5007
,D/NearbySettings( 7650): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 7650): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 7650): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,V/        ( 2846): QcRouteController
I/NearbySettings( 7650): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7650): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7650): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7650): MountReceiver.mPrefHandler - 7002
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,I/SignOutReceiver( 8324): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2846): QcRouteController
,I/ActivityManager( 3506): Killing 10019:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,I/Hs20UtilService( 6284): Starting #7
I/Hs20UtilService( 6284): Message received 5007
,V/        ( 2846): QcRouteController
,D/NearbySettings( 7650): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 7650): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3506): callSECApi what=220
D/WifiStateMachine( 3506): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,I/SignOutReceiver( 8324): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,W/NetworkManagementService( 3506): route cmd failed: 
W/NetworkManagementService( 3506): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '52 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 52 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3506): '
W/NetworkManagementService( 3506): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3506): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3506): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3506): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3506): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3506): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3506): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3506): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6313)
W/NetworkManagementService( 3506): 	at com.android.server.ConnectivityService.access$2700(ConnectivityService.java:231)
W/NetworkManagementService( 3506): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2449)
W/NetworkManagementService( 3506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3506): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3506): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3506): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 3506): LTETest block dns file not exists
,D/ConnectivityService( 3506): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
E/ConnectivityService( 3506): updateNetworkInfo()
E/ConnectivityService( 3506): updateNetworkInfo()
D/ConnectivityService( 3506): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3506): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3506): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3506): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3506): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3506): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3506): Checking http://clients3.google.com/generate_204 on "NG700"
I/System.out( 3506): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3506): (HTTPLog)-Static: isShipBuild true
I/System.out( 3506): (HTTPLog)-Thread-189-813945296: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3506): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService( 3506):    accepting network in place of null
D/ConnectivityService( 3506): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/TelephonyNetworkFactory( 3979): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SurfaceFlinger( 2850): id=13 createSurf (1x1),1 flag=4, Uoast
E/CSLegacyTypeTracker( 3506): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3506): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService( 3506): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 1000
D/ConnectivityService( 3506): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 3506): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/Tethering( 3506): MasterInitialState.processMessage what=3
D/SmartBondingService( 3506): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NtpTrustedTime( 3506): forceRefresh() from cache miss
V/NetworkStats( 3506): updateIfacesLocked()
V/NetworkStats( 3506): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3506): UpdateStatsForKnox
D/SmartBondingService( 3506): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/SmartBondingService( 3506): getSBEnabled() enabled =false
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 1000
D/SmartBondingService( 3506): getSBEnabled() enabled =false
D/SmartBondingService( 3506): getSBEnabled() enabled =false
D/SmartBondingService( 3506): getNetworkEnabled : wifi : true mobile : false
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
V/NetworkStats( 3506): performPollLocked() took 8ms
D/ConnectivityManager.CallbackHandler( 4479): CM callback handler got msg 524290
D/PowerManagerService( 3506): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3506
D/mali_winsys( 3693): new_window_surface returns 0x3000,  [1120x201]-format:1
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/System.out( 3506): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3506): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 15:42:19 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453390938850], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453390938837]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3506): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3506): Validated
,D/ConnectivityService( 3506): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3506): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3506): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 3506): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3506): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 4479): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/NtpTrustedTime( 3506): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1453390939604 mCachedNtpElapsedRealtime : 139944 mCachedNtpCertainty : 9
,D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
V/NetworkStats( 3506): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
,D/ConnectivityService( 3506): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3506): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3506): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3506): SmartBondingReceiver: wifi ap is changed, init speed ratio
D/SmartBondingService( 3506): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3506): getSBEnabled() enabled =false
D/SmartBondingService( 3506): getSBEnabled() enabled =false
D/SmartBondingService( 3506): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
D/SmartBondingService( 3506): getNetworkEnabled : wifi : true mobile : false
,D/AlarmManagerService( 3506): Setting time of day to sec=1453390939
D/AlarmManagerService( 3506): Trying to open a file
D/AlarmManagerService( 3506): File Open Success
D/AlarmManagerService( 3506): File Close Success
I/AlarmManagerService( 3506): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 3506): waitForAlarm result :65536
,I/DBG_DM  ( 5900): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 5900): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 5900): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,V/AlarmManager( 3506): waitForAlarm result :8
,I/DBG_DM  ( 5900): [IlIIlIIlIllllIlllIII(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 5900): [IlIlllIlllllIlIllllI(403/llllllIllIlIlllIIlIl)] Check completed.
,D/WifiStateMachine( 3506): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,I/DBG_DM  ( 5900): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 5900): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_SET
D/SettingsProvider( 3506): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 10060
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,I/DBG_DM  ( 5900): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5900): [IIlIIIlllllIIlIIIlII(72/llllIIIllIlIIIIllllI)] 
,W/Settings( 3506): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,I/DBG_DM  ( 5900): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/KeyguardEffectViewUtil( 3693): isPowerSavingMode() :false
D/KeyguardEffectViewUtil( 3693): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3693): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{128902b4 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{2e612edd V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3693): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{128902b4 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3693): clearEffect
D/WallpaperWidget( 3693): setLockScreenWallpaper()
,D/KeyguardEffectViewUtil( 3693): getCurrentWallpaper() mWallpaperPath :null
,E/Zygote  (10979): MountEmulatedStorage()
E/Zygote  (10979): v2
I/libpersona(10979): KNOX_SDCARD checking this for 1000
I/libpersona(10979): KNOX_SDCARD not a persona
,W/SEC_DRM_PLUGIN_Playready( 2854): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1453390939 after conversion: 1453390939
W/SEC_DRM_PLUGIN_Playready( 2854): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1453390939 after conversion: 1453390939
I/SELinux (10979): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3506): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10979 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (10979): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10979): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5900): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 5900): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 5900): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 5900): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 5900): [IlIIlIIlIllllIlllIII(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,E/Zygote  (10996): MountEmulatedStorage()
E/Zygote  (10996): v2
I/libpersona(10996): KNOX_SDCARD checking this for 10090
I/libpersona(10996): KNOX_SDCARD not a persona
,I/SELinux (10996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/DBG_DM  ( 5900): [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
D/TimaKeyStoreProvider(10979): TimaSignature is unavailable
I/SELinux (10996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ActivityThread(10979): Added TimaKeyStore provider
E/SELinux (10996): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3506): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=10996 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 5900): [IlIIlIIlIllllIlllIII(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 5900): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 5900): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 5900): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(502/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,I/GoogleURLConnFactory( 4239): Using platform SSLCertificateSocketFactory
,E/Zygote  (11012): MountEmulatedStorage()
I/libpersona(11012): KNOX_SDCARD checking this for 10050
E/Zygote  (11012): v2
I/libpersona(11012): KNOX_SDCARD not a persona
,I/SELinux (11012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11012): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10996): TimaSignature is unavailable
I/ActivityManager( 3506): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=11012 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ActivityThread(10996): Added TimaKeyStore provider
,D/GpsLocationProvider( 3506): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 5900): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5900): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,I/DBG_DM  ( 5900): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 5900): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 5900): [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,E/DBG_DM  ( 5900): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,D/TimaKeyStoreProvider(11012): TimaSignature is unavailable
,D/ActivityThread(11012): Added TimaKeyStore provider
,E/DBG_DM  ( 5900): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@1519986b
,D/ResourcesManager(10996): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(10979): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/DBG_DM  ( 5900): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,D/ResourcesManager(11012): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(11012): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11012): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11012): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11012): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11012): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(11012): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(11012): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11012): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityThread( 4479): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3506): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 15760, reason: UserStart, SyncResult: databaseError: true stats []
,I/PCWCLIENTTRACE_LOG(10979): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(10979): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(10979): new DMDBOpenHelper instance
,D/SyncManager( 3506): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 172889, reason: UserStart
,I/PCWCLIENTTRACE_PushUtil(10979): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(10979): sales region : global
I/PCWCLIENTTRACE_PushUtil(10979): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(10979): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/KeyguardEffectViewUtil( 3693): set current wallpaper info
,D/SettingsProvider( 3506): name = keyguard_current_wallpaper_type
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 10060
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 4945): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4945): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,E/Zygote  (11037): MountEmulatedStorage()
I/libpersona(11037): KNOX_SDCARD checking this for 10135
E/Zygote  (11037): v2
I/libpersona(11037): KNOX_SDCARD not a persona
,I/ActivityManager( 3506): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11037 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PhenotypeConfigurator( 4239): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/DBG_DM  ( 5900): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/SELinux (11037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11037): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3506): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 10060
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,I/DBG_DM  ( 5900): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2( 3506): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3506): mCursor = null
,I/ActivityManager( 3506): Killing 10035:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11037): TimaSignature is unavailable
,D/ActivityThread(11037): Added TimaKeyStore provider
,V/GLSActivity( 4239): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager(11037): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3506): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 10060
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
D/SecContentProvider2( 3506): uri = 14 selection = getSealedState
D/SecContentProvider2( 3506): mCursor = null
,W/BackupManagerService( 3506): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/ApplicationPolicy( 3506): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3506): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 3506): showStatusBarByNotification() mOpenByNotification=false
D/StatusBar-DoNotDistrub( 3693): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 3693): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
I/DBG_DM  ( 5900): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,D/ResourcesManager( 3693): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,D/StatusBar-DoNotDistrub( 3693): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager( 2855): getOutputsForDevice device 0002 -> 0002
,I/AudioService( 3506): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 3693): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService( 3506): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,I/DBG_DM  ( 5900): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/PackageManager( 3506): findPreferredActivity: No PreferredActivities set
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DBG_DM  ( 5900): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 5900): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 5900): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,D/DelayedSyncController(10996): Delaying sync.
,E/Auth.Api.Credentials( 4479): [CredentialSyncAdapter] Unknown sync event.
,I/MusicStore(11037): Database version: 104
,D/NearbySource(11012): Nearby Source Create!
D/NearbyContext(11012): Nearby Context Create!
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11012): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(11012): Samsung link source created
,D/KnoxNotification( 3693): ----- inflateViews : modified publicViewLocal -----
,D/WifiDisplayAdapter( 3506): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ResourcesManager(11037): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11037): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11037): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/KnoxNotification( 3693): ----- inflateViews : modified KnoxViewLocal -----
,D/WifiDisplayAdapter( 3506): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ContactProvider(11012): getAllContactInfoList Start
,D/PersonaManager( 3693): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 3693): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@330e3384
D/PersonaManager( 3693): isKioskContainerExistOnDevice
D/PersonaManager( 3693): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3693): Icon Only
,I/System.out( 4239): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10014
,I/StatusBar( 3693): Icon Only
,D/PanelView( 3693): There is/are notification(s) 
D/PanelView( 3693): There is/are notification(s) 
,D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
,D/KeyguardEffectViewUtil( 3693): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3693): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3693): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{128902b4 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{2e612edd V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3693): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{128902b4 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3693): clearEffect
,V/JNIHelp (11037): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ContactProvider(11012): getAllContactInfoList End
I/syncContacts(11012): thread: 1483, sync time = 47
,V/GLSActivity( 4239): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 3506): Killing 10053:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,I/System.out( 4239): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4239): Tagging socket 56 with tag 1000120300000000{268440067,0} uid -1, pid: 4239, getuid(): 10014
,W/ActivityThread(11037): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11037): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@27c4b99d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11037): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11037): GMSCore installation verified
,I/ConfigStore(11037): Config Database version: 1
,D/PanelView( 3693): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11037): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11037): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11037): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3506): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3506): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3506): getStreamVolume 3 index 0
,I/MediaRouter(11037): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/DelayedSyncController(10996): Delaying sync.
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor(11037): type=WIFI subType= reason=null isConnected=true
,E/Zygote  (11078): MountEmulatedStorage()
E/Zygote  (11078): v2
I/libpersona(11078): KNOX_SDCARD checking this for 10002
I/libpersona(11078): KNOX_SDCARD not a persona
,I/SELinux (11078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11078): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11078 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3506): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 508us total 11.737ms
,I/ActivityManager( 3506): Killing 10069:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,I/qtaguid ( 4239): Tagging socket 72 with tag 1000120300000000{268440067,0} uid -1, pid: 4239, getuid(): 10014
,I/NetworkMonitor(11037): type=WIFI subType= reason=null isConnected=true
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 251us total 9.197ms
,D/TimaKeyStoreProvider(11078): TimaSignature is unavailable
D/ActivityThread(11078): Added TimaKeyStore provider
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 264us total 8.403ms
,D/ResourcesManager(11078): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/PicasaService(11012): start picasa sync
,D/PicasaService(11012): end picasa sync
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11102): MountEmulatedStorage()
I/libpersona(11102): KNOX_SDCARD checking this for 1000
E/Zygote  (11102): v2
I/libpersona(11102): KNOX_SDCARD not a persona
,I/SELinux (11102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 3506): Explicit concurrent mark sweep GC freed 76064(3MB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 48MB/64MB, paused 1.547ms total 87.820ms
,I/ActivityManager( 3506): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11102 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11102): TimaSignature is unavailable
,D/ActivityThread(11102): Added TimaKeyStore provider
,D/ResourcesManager(11102): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/ActivityManager( 3506): Killing 10111:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,V/GLSActivity( 4239): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4239): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DIAGMON_AGENT(11102): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11102): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,W/art     (10241): Attempt to remove local handle scope entry from IRT, ignoring
,I/DIAGMON_AGENT(11102): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11102): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11102): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10147
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11132): MountEmulatedStorage()
E/Zygote  (11132): v2
I/libpersona(11132): KNOX_SDCARD checking this for 10012
I/libpersona(11132): KNOX_SDCARD not a persona
,I/SELinux (11132): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11132): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11132): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11132 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11132): TimaSignature is unavailable
,D/ActivityThread(11132): Added TimaKeyStore provider
,D/ResourcesManager(11132): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3506): Killing 10158:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/FOTA_Client(11132): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11132): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11132): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11149): MountEmulatedStorage()
E/Zygote  (11149): v2
I/libpersona(11149): KNOX_SDCARD checking this for 10021
I/libpersona(11149): KNOX_SDCARD not a persona
,I/SELinux (11149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11149): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11149 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3506): Killing 10143:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11149): TimaSignature is unavailable
,D/ActivityThread(11149): Added TimaKeyStore provider
,D/ResourcesManager(11149): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11149): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 21 16:42:20 GMT+01:00 2016
,I/KLMS-2.4.521: (11149): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11149): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11149): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11149): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (11149): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11149): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11149): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11149): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11149): NetworkChangeOperations(): uploadRequestLog().START 
,E/Zygote  (11165): MountEmulatedStorage()
I/libpersona(11165): KNOX_SDCARD checking this for 10038
E/Zygote  (11165): v2
I/libpersona(11165): KNOX_SDCARD not a persona
I/SELinux (11165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11165): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11165 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11149): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11149): StateImplV2(): networkChangeListener().END
,W/PhenotypeConfigurator( 4239): Server returned 404
,I/KLMS-2.4.521: (11149): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3506): Killing 10178:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11165): TimaSignature is unavailable
,D/ActivityThread(11165): Added TimaKeyStore provider
,D/ResourcesManager(11165): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11165): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11185): MountEmulatedStorage()
E/Zygote  (11185): v2
I/libpersona(11185): KNOX_SDCARD checking this for 1000
I/libpersona(11185): KNOX_SDCARD not a persona
,I/SELinux (11185): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11185): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11185): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11185 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3506): Killing 10194:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11185): TimaSignature is unavailable
,D/ActivityThread(11185): Added TimaKeyStore provider
,D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11205): MountEmulatedStorage()
I/libpersona(11205): KNOX_SDCARD checking this for 10039
E/Zygote  (11205): v2
I/libpersona(11205): KNOX_SDCARD not a persona
,I/SELinux (11205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11205): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3506): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11205 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3506): Killing 10209:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11205): TimaSignature is unavailable
,D/ActivityThread(11205): Added TimaKeyStore provider
,D/ResourcesManager(11205): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(11205): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11205): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(11205): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/SPPClientService(11205): PushLog.txt file is not deleted.
D/SPPClientService(11205): PushLog.txt file is not deleted.
D/SPPClientService(11205): ============PushLog. stop!
,E/Zygote  (11223): MountEmulatedStorage()
E/Zygote  (11223): v2
I/libpersona(11223): KNOX_SDCARD checking this for 10045
I/libpersona(11223): KNOX_SDCARD not a persona
,I/SELinux (11223): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11223): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11223): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=11223 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3506): Killing 10294:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11223): TimaSignature is unavailable
,D/ActivityThread(11223): Added TimaKeyStore provider
,D/ResourcesManager(11223): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (11223): [SSP] onCreated
,I/SA      (11223): [TPM] There is no property file
,I/SA      (11223): [SCU] isHaveSA() - false
,I/SA      (11223): [TPM] getModelProperty : null
I/SA      (11223): [TPM] getCSCProperty : null
,I/SA      (11223): [DM] init START
,I/SA      (11223): [DM] This device is not a Vodafone
,I/SA      (11223): checkReactivationActive for LOLLIPOP
,I/SA      (11223): checkReactivationActive for reactiveActive
I/SA      (11223): setSupportRL : true
,I/SA      (11223): [SCU] isHaveSA() - false
I/SA      (11223): support phone number id : false
,I/SA      (11223): [DM] init END
I/SA      (11223): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11223): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11223): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11223): [SLFUCHKMGR] constructor called
,I/SA      (11223): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11223): [OR] == isSIMCardReady false ==
,I/SA      (11223): [SCU] == networkStateCheck == true
I/SA      (11223): [DM] getCountryCodeFromCSC : PL
I/SA      (11223): isChinaCountryCode : false
I/SA      (11223): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11223): [OR] == networkStateCheck true ==
,I/SA      (11223): [OR] GetMyCountryZoneTask
,I/SA      (11223): [OR] onReceive END
,I/SA      (11223): [SRS] prepareGetMyCountryZone
I/ActivityManager( 3506): Killing 10311:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11223): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11223): [SSP] query invoked
,I/SA      (11223): [TPMU] GetMccFromDB : null
I/SA      (11223): [SCU] getMccFromPreferece mcc = 260
I/SA      (11223): [TPM] isNoProxy(default) : true
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11245): MountEmulatedStorage()
E/Zygote  (11245): v2
I/libpersona(11245): KNOX_SDCARD checking this for 10067
I/libpersona(11245): KNOX_SDCARD not a persona
,I/SELinux (11245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11245): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3506): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11245 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11245): TimaSignature is unavailable
,D/ActivityThread(11245): Added TimaKeyStore provider
,D/ResourcesManager(11245): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(11245): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11245): Other Intent
,I/ActivityManager( 3506): Killing 10327:com.facebook.system/u0a10 (adj 13): bgCount ##31
,D/accuweather( 5231): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 5231): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5231): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5231): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5231): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5231): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5231): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11262): MountEmulatedStorage()
I/libpersona(11262): KNOX_SDCARD checking this for 1000
E/Zygote  (11262): v2
I/libpersona(11262): KNOX_SDCARD not a persona
,I/SELinux (11262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11262): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11262 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11262): TimaSignature is unavailable
,D/ActivityThread(11262): Added TimaKeyStore provider
,D/ResourcesManager(11262): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11262): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(11262): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(11262): premStatus:2
,I/KnoxUsageLogPro(11262): isEulaShown : false
I/KnoxUsageLogPro(11262): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(10726): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(10726): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10726): stopCheckCategoryVersion
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11277): MountEmulatedStorage()
E/Zygote  (11277): v2
I/libpersona(11277): KNOX_SDCARD checking this for 10136
I/libpersona(11277): KNOX_SDCARD not a persona
,I/SELinux (11277): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11277): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11277): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3506): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11277 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3506): Killing 10383:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11277): TimaSignature is unavailable
,D/ActivityThread(11277): Added TimaKeyStore provider
,D/ResourcesManager(11277): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11277): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11277): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11277): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11277): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/SA      (11223): [RC New] Execute method=[GET] start
,I/WebViewFactory(11277): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11277): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11277): Loading: webviewchromium
,I/LibraryLoader(11277): Time to load native libraries: 3 ms (timestamps 2029-2032)
I/LibraryLoader(11277): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11277): Binding Chromium to main looper Looper (main, tid 1) {3578013f}
,I/LibraryLoader(11277): Expected native library version number "",actual native library version number ""
I/SA      (11223): [RC New] Security=[true]
I/chromium(11277): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/System.out(11223): Thread-1530(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11223): Thread-1530(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out(11223): Thread-1530(ApacheHTTPLog):isShipBuild true
I/System.out(11223): Thread-1530(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10045
,I/BrowserStartupController(11277): Initializing chromium process, renderers=0
,W/art     (11277): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(11277): Requires BLUETOOTH permission
,W/chromium(11277): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11277): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(11277): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(11277): Starting up...
,I/ActivityManager( 3506): Killing 10427:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 15): bgCount ##31
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11345): MountEmulatedStorage()
I/libpersona(11345): KNOX_SDCARD checking this for 10150
E/Zygote  (11345): v2
I/libpersona(11345): KNOX_SDCARD not a persona
,I/SELinux (11345): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11345): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11345): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3506): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=11345 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11345): TimaSignature is unavailable
,D/ActivityThread(11345): Added TimaKeyStore provider
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8749(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 554us total 14.700ms
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 533us total 8.474ms
,D/ResourcesManager(11345): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(11345): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11345): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11345): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 261us total 8.037ms
,D/QuickConnect(11345): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(11345): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(11345): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3506): exchangeData() failure , invalid userId
,D/RCPManagerService( 3506): exchangeData() failure , invalid userId
,I/ActivityManager( 3506): Killing 10442:com.android.calendar/u0a164 (adj 13): bgCount ##31
,I/iu.SyncManager( 4479): SYNC; picasa accounts
,D/NetworkLogImpl( 4479): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4479): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4479): num queued entries: 0
,I/iu.UploadsManager( 4479): num updated entries: 0
I/iu.SyncManager( 4479): NEXT; no task
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10014
,E/Zygote  (11366): MountEmulatedStorage()
E/Zygote  (11366): v2
I/libpersona(11366): KNOX_SDCARD checking this for 10013
I/libpersona(11366): KNOX_SDCARD not a persona
,I/SELinux (11366): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11366): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11366): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3506): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=11366 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/WifiStateMachine( 3506): updateConfiguredNetworkExpiration - currTime: 1453390941942
D/WifiStateMachine( 3506): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/TimaKeyStoreProvider(11366): TimaSignature is unavailable
,D/ActivityThread(11366): Added TimaKeyStore provider
,V/GLSActivity( 4239): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4239): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager(11366): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,E/AclDataUtils(10241): Circle ID not found for type: 9
,D/WaitQueueForNetworkActivate(11366): notifyNetworkActivated
,W/ContextImpl(11366): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3506): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ResourcesManager( 4239): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GCM     ( 4239): GCM config loaded
,I/ActivityManager( 3506): Killing 9807:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/hcjo    (11366): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(11366): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(11366): exit::IDLE
D/InitializeManagerStateMachine(11366): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(11366): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(11366): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(11366): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11366): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(11366): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11366): entry::SUCCESS
D/hcjo    (11366): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/FOTA_Client(11132): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/hcjo    (11366): AutoUpdateTriggerManager:IDLE:setInterval:345600000
I/splitIntent( 3506): Split this intent : android.intent.action.TIME_SET !!   mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=17 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 3506): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client(11132): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,E/Zygote  (11390): MountEmulatedStorage()
E/Zygote  (11390): v2
I/libpersona(11390): KNOX_SDCARD checking this for 10052
I/libpersona(11390): KNOX_SDCARD not a persona
,I/SELinux (11390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3506): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=11390 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux (11390): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/hcjo    (11366): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (11366): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(11366): exit::SUCCESS
D/InitializeManagerStateMachine(11366): entry::IDLE
,D/TimaKeyStoreProvider(11390): TimaSignature is unavailable
,D/ActivityThread(11390): Added TimaKeyStore provider
,E/Zygote  (11406): MountEmulatedStorage()
E/Zygote  (11406): v2
I/libpersona(11406): KNOX_SDCARD checking this for 10164
I/libpersona(11406): KNOX_SDCARD not a persona
,I/SELinux (11406): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3506): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=11406 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux (11406): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11406): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.4.521: (11149): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Jan 21 16:42:22 GMT+01:00 2016
,D/TimaKeyStoreProvider(11406): TimaSignature is unavailable
,D/ActivityThread(11406): Added TimaKeyStore provider
,D/ResourcesManager(11390): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(11390): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(11390): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/KLMS-2.4.521: (11149): KLMSAbstractReciever(): onReceive().END.
W/ResourcesManager(11390): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11390): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11390): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(11390): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/KLMS-2.4.521: (11149): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11149): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/KLMS-2.4.521: (11149): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
D/comsamsunglog( 3778): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3778): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/comsamsunglog( 3778): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3778): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/ResourcesManager(11406): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11406): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11406): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11406): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11406): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (11149): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,E/Zygote  (11422): MountEmulatedStorage()
E/Zygote  (11422): v2
I/libpersona(11422): KNOX_SDCARD checking this for 10036
I/libpersona(11422): KNOX_SDCARD not a persona
,I/SELinux (11422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (11149): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.4.521: (11149): StateImplV2(): dateTimeChanged().START : Thu Jan 21 16:42:22 GMT+01:00 2016
,I/SELinux (11422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3506): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/com.cigna.mobile.coach.CoachBroadcastReceiver: pid=11422 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/SELinux (11422): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 3778): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3778): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 3778): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/KLMS-2.4.521: (11149): StateImplV2(): dateTimeChanged().END
,I/KLMS-2.4.521: (11149): KLMSIntentService(): onDestroy()
,D/Mms/MmsApp(11390): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(11390): init before art
,D/TimaKeyStoreProvider(11422): TimaSignature is unavailable
,D/ActivityThread(11422): Added TimaKeyStore provider
,D/Mms/ArtClassLoader(11390): init [DONE] art
,D/comdaemonstockapp( 3778): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 3778): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/Mms/TelephonyPermission(11390): start operation mode monitor
,D/ResourcesManager(11390): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11390): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/VacuumService( 4239): Vacuum at: now=1453390942220 tag=VacuumService
,D/ResourcesManager(11422): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/Mms/TelephonyPermission(11390): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(11390): isDefault true
D/Mms/MmsApp(11390): onCreate() com.android.mms
,D/Mms/MmsApp(11390): [start]    initCountryIso consume time = 37.630625
,D/CountryDetector( 3506): The first listener is added
,I/CheckinService( 4479): Checkin interval check for package: unspecified last checkin: 1453082886478 min interval config: 0 actual interval: 308055759
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/MmsApp(11390): [end]    initCountryIso consume time = 7.981083
D/Mms/MmsConfig(11390): [start]    MmsConfig.init() consume time = 0.065625
,D/Mms/MmsConfig(11390): before partial update
,D/Mms/MmsConfig(11390): Load Resize quality : 80
,D/Mms/MmsConfig(11390):  enable multiwindow = true
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Mms/MessageUtils(11390): setCountryDetector : update country detector info 
E/Mms/MessageUtils(11390): updateCountryIso : update country iso info 
,E/Zygote  (11448): MountEmulatedStorage()
I/libpersona(11448): KNOX_SDCARD checking this for 10047
E/Zygote  (11448): v2
I/libpersona(11448): KNOX_SDCARD not a persona
,I/SELinux (11448): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3506): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=11448 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11448): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/Mms/PackageInfo(11390): com.sec.imsservice is not installed
D/Mms/MmsConfig(11390): [end]    init() consume time = 36.269667
,D/Mms/Contact(11390): [start]    init() consume time = 0.375916
E/SELinux (11448): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Killing 9371:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/Mms/Contact(11390): [end]    init consume time = 5.706959
,D/Mms/DraftCache(11390): [start]    rebuildCache consume time = 2.552125
,D/TP/MmsSmsProvider( 3979): query,matched:13, calling pid = 11390
,D/TP/MmsSmsProvider( 3979): query,matched:12, calling pid = 11390
,D/TP/MmsSmsProvider( 3979): match 13:Elapsed time : 2.047 ms
,D/TP/MmsSmsProvider( 3979): match 12:Elapsed time : 2.828 ms
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthServiceInstalled() : HealthService is Installed.
D/Mms/TelephonyUtils(11390): getSubId from simSlot 0, return Value = -1
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/Mms/DownloadManager(11390): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11390): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11390): auto download without roaming -> true
D/Mms/DownloadManager(11390): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/SecurityLogAgent(10766): KnoxConfiguration : Current State = 0
D/SecurityLogAgent(10766): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent(10766): StateMachine : Initialized
D/SecurityLogAgent(10766): StateMachine : Changed Current State = 0
,D/Mms/DraftCache(11390): [end]    rebuildCache consume time = 17.498375
D/SecurityLogAgent(10766): StateMachine : Current State = 0
,D/TimaKeyStoreProvider(11448): TimaSignature is unavailable
D/ActivityThread(11448): Added TimaKeyStore provider
,E/Mms/TelephonyUtils(11390): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(11390): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(11390): roaming -> false (slotId = 1)
D/Mms/DownloadManager(11390): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(11390): auto download without roaming -> true
D/Mms/DownloadManager(11390): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(11390): auto download during roaming secondary -> false
D/Mms/DownloadManager(11390): mAutoDownload ------> true
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsApp(11390): [end]    onCreate() consume time = 12.6135
,D/Mms/Conversation(11390): [start]    init() consume time = 1.656083
,D/ResourcesManager(11448): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,D/Mms/DownloadManager(11390): Service state changed: Bundle[mParcelledData.dataSize=692]
,D/Mms/DownloadManager(11390): roaming ------> false, mSimSlot = 0
,W/ResourcesManager(11448): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/Mms/TelephonyUtils(11390): getSubId from simSlot 0, return Value = -1
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
I/libpersona(11479): KNOX_SDCARD checking this for 10191
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/libpersona(11479): KNOX_SDCARD not a persona
E/Zygote  (11479): MountEmulatedStorage()
E/Zygote  (11479): v2
,D/Mms/DownloadManager(11390): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11390): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11390): auto download without roaming -> true
D/Mms/DownloadManager(11390): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(11390): mAutoDownload ------> true
,I/SELinux (11479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3506): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=11479 uid=10191 gids={50191, 9997} abi=armeabi-v7a
,I/SELinux (11479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/SELinux (11479): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,I/CalendarProvider2(11448): CalendarProvider2.onCreate() called
,E/Zygote  (11489): MountEmulatedStorage()
I/libpersona(11489): KNOX_SDCARD checking this for 10069
E/Zygote  (11489): v2
I/libpersona(11489): KNOX_SDCARD not a persona
I/SELinux (11489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3506): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=11489 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3506): Killing 10805:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
I/SELinux (11489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11489): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,I/SA      (11223): [RC New] [v2liruge] api execute + 662
I/SA      (11223): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11223): AsyncTask #1 calls detatch()
,E/Zygote  (11504): MountEmulatedStorage()
E/Zygote  (11504): v2
I/libpersona(11504): KNOX_SDCARD checking this for 10019
I/libpersona(11504): KNOX_SDCARD not a persona
,I/SELinux (11504): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/TimaKeyStoreProvider(11479): TimaSignature is unavailable
,I/ActivityManager( 3506): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=11504 uid=10019 gids={50019, 9997} abi=armeabi-v7a
I/SELinux (11504): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11504): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityThread(11479): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 3979): deleteConversation threadId: 9223372036854775807
,I/SA      (11223): [TPMU] getNetworkMcc : 
,D/TP/MmsSmsProvider( 3979): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,I/SA      (11223): [SCU] saveMccToPreferece Start
I/SA      (11223): [SCU] RegionMCC : 260
I/SA      (11223): [SSP] query invoked
,D/TimaKeyStoreProvider(11489): TimaSignature is unavailable
,D/ActivityThread(11489): Added TimaKeyStore provider
,E/SQLiteLog( 3979): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3979): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3979): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3979): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3979): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3979): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 3979): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 3979): need read changed broadcast:false
,D/ResourcesManager(11479): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,D/TimaKeyStoreProvider(11504): TimaSignature is unavailable
D/ActivityThread(11504): Added TimaKeyStore provider
,W/ResourcesManager(11479): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Mms/Conversation(11390): [end]    init consume time = 64.740458
D/Mms/MessagingNotification(11390): [start]    init() consume time = 0.423375
,I/art     ( 3506): Explicit concurrent mark sweep GC freed 36728(2MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 48MB/64MB, paused 1.352ms total 83.583ms
,I/SA      (11223): [TPMU] GetMccFromDB : null
I/SA      (11223): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11223): [SCU] saveMccToPreferece End
,I/SA      (11223): [RC New] executeRequest [v2liruge] end. 787
I/SA      (11223): [RC New] Execute end
,I/SA      (11223): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11223): [OR] GetMyCountryZoneTask Success
,I/ActivityManager( 3506): Killing 10089:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/ResourcesManager(11489): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,D/ResourcesManager(11504): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/Mms/MessagingNotification(11390): [end]    init consume time = 88.027209
,D/Mms/SpamFilter(11390): [start]    SpamFilter fill() begin consume time = 1.097083
,D/Mms/Synchronizer(11390): [start]    doSync consume time = 1.295042
,D/TP/MmsSmsProvider( 3979): query,matched:0, calling pid = 11390
V/TP/MmsSmsProvider( 3979): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3979): match 0:Elapsed time : 0.990 ms
,D/TP/MmsSmsProvider( 3979): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 3979): syncDBData start
,D/TP/MmsSmsProvider( 3979): query,matched:400, calling pid = 11390
V/TP/MmsSmsProvider( 3979): syncDBData sms end
,V/TP/MmsSmsProvider( 3979): syncDBData mms end
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
V/TP/MmsSmsProvider( 3979): syncDBData end
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11529): MountEmulatedStorage()
E/Zygote  (11529): v2
I/libpersona(11529): KNOX_SDCARD checking this for 10082
I/libpersona(11529): KNOX_SDCARD not a persona
,I/SELinux (11529): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3506): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=11529 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,I/SELinux (11529): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11529): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/Mms/Synchronizer(11390): [end]    doSync consume time = 22.806333
,D/Mms/SpamFilter(11390): [end]    SpamFilter fill() finished consume time = 1.553417
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/ActivityManager( 3506): Killing 10410:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/com.sec.android.service.health.keyManager.KeyManager(11422): Current encrypted state : -1
,I/SecSQLiteOpenHelper(11422): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11422): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11422): Open platform.db in secure mode
D/SecSQLiteDatabase(11422): Android Version: 5.0.1
D/SecSQLiteDatabase(11422): Load library secsqlite.so for Android 5.0.1
,D/accuweather( 5231): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 5231): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/TimaKeyStoreProvider(11529): TimaSignature is unavailable
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
D/ActivityThread(11529): Added TimaKeyStore provider
,I/ Time Manager (11489): Time Difference not stored. TIME_DIFFERENCE
,I/SecSQLiteDatabase(11422): openSecureDatabase...
,I/SecSQLiteDatabase(11422): private openSecureDatabase...
I/SecSQLiteConnectionPool(11422): OpenSecure
I/SecSQLiteConnectionPool(11422): OpenSecure with password
I/SecSQLiteConnectionPool(11422): openSecureConnectionLocked
,I/SecSQLiteDatabase(11422): ...private openSecureDatabase
I/SecSQLiteDatabase(11422): ...openSecureDatabase
,E/Zygote  (11548): MountEmulatedStorage()
I/libpersona(11548): KNOX_SDCARD checking this for 10094
E/Zygote  (11548): v2
I/libpersona(11548): KNOX_SDCARD not a persona
,I/SELinux (11548): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11548): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11548): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=11548 uid=10094 gids={50094, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3506): Killing 10899:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31
,D/ResourcesManager(11529): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/TimaKeyStoreProvider(11548): TimaSignature is unavailable
,D/ActivityThread(11548): Added TimaKeyStore provider
,E/SQLiteLog(11422): (26) statement aborts at 0: [PRAGMA user_version;] file is encrypted or is not a database
,E/SecDefaultDatabaseErrorHandler(11422): Corruption reported by sqlite on database: /data/data/com.sec.android.app.shealth/databases/platform.db
E/SecDefaultDatabaseErrorHandler(11422): backup the database file: /data/data/com.sec.android.app.shealth/databases/platform.db
D/SecSQLiteOpenHelper(11422): ...getDatabaseLocked(b,b,pwd)
,D/BadgeProvider(11529): onCreate
D/BadgeProvider(11529): DatabaseHelper
,D/ResourcesManager(11548): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,W/ResourcesManager(11548): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(11548): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11548): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11548): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11548): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11548): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/Mms/MessagingNotification(11390): checkBadgeCount unreadCount=0 badgeCount=0
,I/SecureStorage(11504): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Credentials: uid 10019, gid 10019, pid 11504
I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,D/TP/SmsProvider( 3979): query,matched:26, calling pid = 11390
,D/TP/SmsProvider( 3979): match 26:Elapsed time : 1.886 ms
,I/ActivityManager( 3506): Killing 7650:com.android.settings/1000 (adj 13): bgCount ##31
,D/TP/MmsSmsProvider( 3979): query,matched:6, calling pid = 11390
,D/TP/MmsSmsProvider( 3979): match 6:Elapsed time : 0.799 ms
,I/Mms/ReservationManager(11390): ReservationManager()
,I/Mms/ReservationManager(11390): resetAfterConnected()
,D/TP/MmsSmsProvider( 3979): query,matched:7, calling pid = 11390
,D/TP/MmsSmsProvider( 3979): match 7:Elapsed time : 2.325 ms
,I/Mms/ReservationManager(11390): getReservedSendMessageCount(): retMessageCount=0
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11566): MountEmulatedStorage()
I/libpersona(11566): KNOX_SDCARD checking this for 10028
E/Zygote  (11566): v2
I/libpersona(11566): KNOX_SDCARD not a persona
,I/SELinux (11566): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11566): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11566): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=11566 uid=10028 gids={50028, 9997} abi=armeabi-v7a
,I/WifiStateMachine( 3506): REQUEST_POWER_SAVE_ON
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 680us total 12ms
,I/dhcpcd  (10918): wlan0: sending IPv6 Router Solicitation
,D/WifiService( 3506): Client connection lost with reason: 4
,D/TimaKeyStoreProvider(11566): TimaSignature is unavailable
,D/ActivityThread(11566): Added TimaKeyStore provider
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 571us total 9.595ms
,I/ActivityManager( 3506): Killing 8324:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
,D/ResourcesManager(11566): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 565us total 9.523ms
,W/ResourcesManager(11566): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/SettingsProvider( 3506): name = next_alarm_formatted
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 10094
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,E/WifiStateMachine( 3506): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/OMACP   (11566): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp(11390): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/Mms/ArtClassLoader(11390): init before art
D/Mms/ArtClassLoader(11390): init [DONE] art
,D/Mms/PerformanceUtils(11390): link cahcing start
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
D/Mms/PerformanceUtils(11390): link cahcing done
,I/OMACP   (11566): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11586): MountEmulatedStorage()
I/libpersona(11586): KNOX_SDCARD checking this for 10106
E/Zygote  (11586): v2
I/libpersona(11586): KNOX_SDCARD not a persona
,I/SELinux (11586): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11586): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11586): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3506): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11586 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3506): Killing 10350:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11586): TimaSignature is unavailable
,D/ActivityThread(11586): Added TimaKeyStore provider
,D/ResourcesManager(11586): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/elm:14491(11586): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491(11586): ELMEngine.ELMEngine( context ).
D/elm:14491(11586): MDMBridge.setEnterpriseBridge()
,D/elm:14491(11586): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14491(11586): ElmAgentService : onCreate()
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/elm:14491(11586): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14491(11586): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14491(11586): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491(11586): ModuleBase.ModifySetAlarm()
D/elm:14491(11586): MDMBridge.getInstance()
D/elm:14491(11586): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (11604): MountEmulatedStorage()
I/libpersona(11604): KNOX_SDCARD checking this for 10163
E/Zygote  (11604): v2
I/libpersona(11604): KNOX_SDCARD not a persona
,I/SELinux (11604): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11604): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11604): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=11604 uid=10163 gids={50163, 9997} abi=armeabi-v7a
,D/elm:14491(11586): ElmAgentService : onDestroy().
,I/ActivityManager( 3506): Killing 10979:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11604): TimaSignature is unavailable
,D/ActivityThread(11604): Added TimaKeyStore provider
,D/ResourcesManager(11604): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(11604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11604): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/ActivityManager( 3506): Killing 11037:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,I/SurfaceFlinger( 2850): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger( 2850): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 3506): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3506) eventTime = 143232
,D/PowerManagerService( 3506): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3506 (0x0)
D/PowerManagerService( 3506): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3506, ws=WorkSource{10060}) (elapsedTime=3474)
,D/OpenGLRenderer( 5900): Render dirty regions requested: true
,I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=4, Uoast
,I/jxcore-log(10630): Test app app.js loaded
I/jxcore-log(10630): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(10630): BLE advertisement is supported
I/jxcore-log(10630): 
,D/PowerManagerService( 3506): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3506
,I/chromium(10630): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/OpenGLRenderer( 5900): Initialized EGL, version 1.4
,I/OpenGLRenderer( 5900): HWUI protection enabled for context ,  &this =0xaf322088 ,&mEglDisplay = 1 , &mEglConfig = -1355423472 
,D/OpenGLRenderer( 5900): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 5900): Enabling debug mode 0
,D/mali_winsys( 5900): new_window_surface returns 0x3000,  [616x201]-format:1
,I/SecureStorage( 2916): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
,D/btif_config_util(10702): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/SecureStorage(11504): [INFO]: SPID(0x00000006)Processing data has been completed
,I/SecureStorage(11504): [INFO]: SPID(0x00000006)Skip using SecureStorageExceptionJNI
,I/SecSQLiteOpenHelper(11422): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper(11422): getDatabaseLocked(b,b,pwd)...
,I/SecSQLiteOpenHelper(11422): Open platform.db in secure mode
,I/SecSQLiteDatabase(11422): openSecureDatabase...
,I/SecSQLiteDatabase(11422): private openSecureDatabase...
,I/SecSQLiteConnectionPool(11422): OpenSecure
I/SecSQLiteConnectionPool(11422): OpenSecure with password
,I/SecSQLiteConnectionPool(11422): openSecureConnectionLocked
,I/SecSQLiteDatabase(11422): ...private openSecureDatabase
,I/SecSQLiteDatabase(11422): ...openSecureDatabase
,I/CalendarProvider2(11448): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager( 3506): Killing 11078:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,I/SecSQLiteOpenHelper(11422): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11422): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/-----SIC-----(11422): ------------------skip TGH
,I/SecSQLiteOpenHelper(11422): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11422): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11422): Open platform.db in secure mode
I/SecSQLiteDatabase(11422): openSecureDatabase...
I/SecSQLiteDatabase(11422): private openSecureDatabase...
I/SecSQLiteConnectionPool(11422): OpenSecure
I/SecSQLiteConnectionPool(11422): OpenSecure with password
I/SecSQLiteConnectionPool(11422): openSecureConnectionLocked
,I/SecSQLiteDatabase(11422): ...private openSecureDatabase
I/SecSQLiteDatabase(11422): ...openSecureDatabase
,I/SecSQLiteOpenHelper(11422): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11422): ...getDatabaseLocked(b,b,pwd)
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11422): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11422): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer(11422): decode(33, 20909908, 4230)
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
V/AudioCache( 2855): notify(0xaeb4b380, 8, 0, 0)
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
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/SO_AGENT(11165): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/SA      (11223): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/SSRM:n  ( 3506): SIOP:: AP = 300, PST = 269, CUR = 48
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
,V/MediaPlayerService( 2855): wait for playback complete
,I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out,
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
,I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
,V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
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
,V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11422): decode(35, 20763080, 15440)
V/MediaPlayerService( 2855): decode(26, 20763080, 15440)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
,V/AwesomePlayer( 2855): setDefault,
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
V/StagefrightPlayer( 2855): setDataSource(26, 20763080, 15440)
V/AwesomePlayer( 2855): reset_l(),
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
,V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
,I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
,V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
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
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xae9204c0, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
,V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 6, 0, 0)
,V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1733175209, value : 485677307
,V/MediaPlayerService( 2855): wait for playback complete
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1733175209, value : 485677307
,I/ActivityManager( 3506): Killing 11012:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31,
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/AdaptiveEventManager( 3693): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3693): M updateContainers()
D/AdaptiveEventContainerSmall( 3693): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3693): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3693): pedoEvent == null
,D/AdaptiveEventManager( 3693): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3693): M updateContainers()
D/AdaptiveEventContainerSmall( 3693): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3693): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3693): pedoEvent == null
I/ActivityManager( 3506): Killing 11102:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
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
,I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
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
V/AwesomePlayer( 2855): destructor
E/DatabaseUtils( 3506): Writing exception to parcel
E/DatabaseUtils( 3506): java.lang.NullPointerException: key == null
E/DatabaseUtils( 3506): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils( 3506): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils( 3506): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils( 3506): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:376)
E/DatabaseUtils( 3506): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils( 3506): 	at android.os.Binder.execTransact(Binder.java:446)
,V/AwesomePlayer( 2855): reset_l()
,V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer(11422): decode(34, 20807608, 9226)
V/MediaPlayerService( 2855): decode(31, 20807608, 9226)
V/MediaPlayerService( 2855): player type = 3
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
V/StagefrightPlayer( 2855): setDataSource(31, 20807608, 9226)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,W/System.err(10001): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
W/System.err(10001): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err(10001): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err(10001): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err(10001): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err(10001): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
W/System.err(10001): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
I/splitIntent( 3506): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
W/System.err(10001): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
W/System.err(10001): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10001): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10001): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10001): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10001): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10001): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,W/System.err(10001): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
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
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,W/System.err(11422): java.lang.NumberFormatException: Invalid int: "null"
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
W/System.err(11422): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err(11422): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err(11422): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err(11422): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:498)
W/System.err(11422): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1242)
W/System.err(11422): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11422): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11422): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
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
V/AudioCache( 2855): notify(0xaea34060, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
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
,V/AwesomePlayer( 2855): mSecMediaClock clear
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
,V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11422): decode(37, 20914220, 4890)
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
V/AudioCache( 2855): notify(0xb050f510, 8, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
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
,V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
,V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
,I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l,
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xb050f510, 1, 0, 0),
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,V/MediaPlayerService( 2855): wait for playback complete
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 8, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
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
V/MediaPlayer(11422): decode(39, 20840384, 17329)
V/MediaPlayerService( 2855): decode(26, 20840384, 17329)
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
V/StagefrightPlayer( 2855): setDataSource(26, 20840384, 17329)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 8, 0, 0)
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
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 1, 0, 0)
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
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
,V/MediaPlayerService( 2855): wait for playback complete
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,D/PackageManager( 3506): [MSG] WRITE_PACKAGE_RESTRICTIONS
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
,E/Zygote  (11688): MountEmulatedStorage()
E/Zygote  (11688): v2
I/libpersona(11688): KNOX_SDCARD checking this for 10022
I/libpersona(11688): KNOX_SDCARD not a persona
I/ActivityManager( 3506): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=11688 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
I/SELinux (11688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): addBatteryData
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 8, 0, 0)
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
,I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
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
,V/AwesomePlayer( 2855): reset_l()
I/SELinux (11688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer(11422): decode(38, 20740576, 6644)
E/SELinux (11688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/MediaPlayerService( 2855): decode(31, 20740576, 6644)
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
V/StagefrightPlayer( 2855): setDataSource(31, 20740576, 6644)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 8, 0, 0)
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
,V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
,V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 1, 0, 0)
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
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
,V/MediaPlayerService( 2855): wait for playback complete
I/AudioPlayer( 2855): First fillBuffer call!!
,I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
,I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
,V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
,V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset,
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2855): mAudioTrackVector clear
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
V/MediaPlayer(11422): decode(41, 20816916, 23389)
V/MediaPlayerService( 2855): decode(26, 20816916, 23389)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
,V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
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
V/StagefrightPlayer( 2855): setDataSource(26, 20816916, 23389)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xae9204c0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
,V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
,V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
,V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
,V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/TimaKeyStoreProvider(11688): TimaSignature is unavailable
D/ActivityThread(11688): Added TimaKeyStore provider
,I/PowerManagerService( 3506): [PWL] Off : 50s ago
,I/PowerManagerService( 3506): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3506): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 3506): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10094, pid=11548, ws=null) (elapsedTime=1326)
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
,I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 200, 973, 0)
,V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
,V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0,
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 6, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,V/MediaPlayerService( 2855): wait for playback complete
,D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(11688): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11688): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
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
V/AwesomePlayer( 2855): mSecCapture clear
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
V/MediaPlayer(11422): decode(42, 20706272, 8154)
V/MediaPlayerService( 2855): decode(26, 20706272, 8154)
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
,V/StagefrightPlayer( 2855): setDataSource(26, 20706272, 8154)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 8, 0, 0)
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
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
,I/SecVideoCapture( 2855): reset
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
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event ,
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 5, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
,V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
V/MediaPlayerService( 2855): wait for playback complete
,I/AudioPlayer( 2855): First fillBuffer call!!
,I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,I/LocationWidgetApplication(11688): onCreate() : start
,D/LocationWidgetApplication(11688): countryCode = POLAND
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xaea34060, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 8, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
,I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
I/AudioPlayer( 2855): reset out
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
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
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11422): decode(43, 20679752, 4804)
V/MediaPlayerService( 2855): decode(26, 20679752, 4804)
V/MediaPlayerService( 2855): player type = 3
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
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
V/StagefrightPlayer( 2855): setDataSource(26, 20679752, 4804)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec,
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
,I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
D/LocationWidgetUtils(11688): getUpcommingInstances() start: 1453390944029, end: 1453935599999
D/LocationWidgetUtils(11688): getUpcommingInstances() DB begin time >= start:1453390944029, DB begin time <= end:1453935599999
,I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3506): online:4, current avg:-403, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:96
,D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3506): stay LED for fully charged
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
V/MediaPlayerService( 2855): wait for playback complete
,I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
I/MotionRecognitionService( 3506): Plugged
I/MotionRecognitionService( 3506): setPowerConnected  = true
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 8, 0, 0)
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
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10702): Disconnected process message: 10
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer(11422): decode(44, 20649204, 9400)
V/MediaPlayerService( 2855): decode(26, 20649204, 9400)
,V/MediaPlayerService( 2855): player type = 3
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
,V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
,V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20649204, 9400)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted,
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService( 2855): prepare,
,V/AwesomePlayer( 2855): prepareAsync
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
,I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/MediaPlayer(11422): decode(50, 20722624, 4112)
V/MediaPlayerService( 2855): decode(36, 20722624, 4112)
V/MediaPlayerService( 2855): player type = 3
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
,V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(36, 20722624, 4112)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xaeb4b380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
,V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2855): notify(0xaeb4b380, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 1, 0, 0)
V/AudioCache( 2855): prepared
,V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
V/MediaPlayerService( 2855): wait for playback complete
I/AudioPlayer( 2855): First fillBuffer call!!
,I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
V/MediaPlayerService( 2855): wait for playback complete
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
,E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xaeb4b380, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
,V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x86, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
,V/AwesomePlayer( 2855): mSecCapture clear
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
,V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
,V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
,V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x85, OMX_CommandStateSet, OMX_StateIdle)
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants(11422): RegionGroup for  is null
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
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
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
,V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer(11422): decode(45, 20857804, 52024)
V/MediaPlayerService( 2855): decode(26, 20857804, 52024)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthServiceInstalled() : HealthService is Installed.
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
,V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
,V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20857804, 52024)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2855): mAudioTrackVector clear
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
D/SHealthUpgrade(SHealthUpgradeUtil)(11422): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
,I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
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
V/AudioPolicyManager( 2855): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 5, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
,V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
D/LocationManagerService( 3506): getProviders()=[]
D/LocationManagerService( 3506): getProviders()=[passive]
D/LocationManagerService( 3506): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(48000, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 6, 0, 0)
,V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2855): wait for playback complete
,D/LWLocationManager(11688): mPrivacy is null
,W/ContextImpl(11688): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,D/ContextFramework:PrivacyManager(11688): Service for PrivacyManager is connected,
,D/BluetoothManager(11422): getConnectedDevices
,D/BluetoothManager(11422): getConnectedDevices
,D/LWLocationManager(11688): Privacy service : STATUS_PLACE
D/LWLocationManager(11688): updateLocationStatus()
,D/BluetoothManager(11422): getConnectedDevices
,I/LocationWidgetFuctionData(11688): readDB
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae9204c0, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x87, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
,I/OggExtractor( 2855): ~OggExtractor --
I/LocationWidgetFuctionData(11688): selectedAppSize: 3
I/LocationWidgetFuctionData(11688): configPlaceList aroundMeItems
,D/BluetoothManager(11422): getConnectedDevices
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,I/AudioPlayer( 2855): reset out
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
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
,V/AwesomePlayer( 2855): reset_l()
,V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,E/Zygote  (11746): MountEmulatedStorage()
E/Zygote  (11746): v2
I/libpersona(11746): KNOX_SDCARD checking this for 10003
I/libpersona(11746): KNOX_SDCARD not a persona
,I/SELinux (11746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,V/MediaPlayer(11422): decode(46, 20722624, 4112)
V/MediaPlayerService( 2855): decode(31, 20722624, 4112)
,V/MediaPlayerService( 2855): player type = 3
,V/AwesomePlayer( 2855): setDefault
I/ActivityManager( 3506): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=11746 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
I/SELinux (11746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
V/AwesomePlayer( 2855): constructor
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
E/SELinux (11746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
,V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(31, 20722624, 4112)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 8, 0, 0)
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
,V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
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
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 1, 0, 0)
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
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
,I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2855): wait for playback complete
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaea34060, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x88, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,D/TimaKeyStoreProvider(11746): TimaSignature is unavailable
,D/ActivityThread(11746): Added TimaKeyStore provider
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
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer(11422): decode(47, 20785700, 21825)
D/BluetoothManager(11422): getConnectedDevices
,V/MediaPlayerService( 2855): decode(26, 20785700, 21825)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
,V/AwesomePlayer( 2855): setDefault
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
V/StagefrightPlayer( 2855): setDataSource(26, 20785700, 21825)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,I/ActivityManager( 3506): Killing 11185:com.policydm/1000 (adj 13): bgCount ##31
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
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1,
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,D/BluetoothManager(11422): getConnectedDevices
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
,I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2855): wait for playback complete
,D/ResourcesManager(11746): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,I/ActivityManager( 3506): Killing 11245:com.samsung.android.scloud.backup/u0a67 (adj 13): bgCount ##31
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
I/Mms/MmsApp(11390):  start initViewCache mms
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
,V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb050f510, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
D/UserAnalysis.PlaceProvider(11746): PlaceProvider onCreate()
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x89, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,D/Mms/ComposeMessageFragment(11390): [start]    fillCache consume time = 1822.078
D/Mms/ComposeMessageFragment(11390): fillCache, easy = false
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
,V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11422): decode(48, 20684636, 21552)
,V/MediaPlayerService( 2855): decode(26, 20684636, 21552)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
,V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
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
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
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
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 1, 0, 0)
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
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
V/MediaPlayerService( 2855): wait for playback complete
,D/UserAnalysis.SecureDbManager(11746): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(11746): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(11746): Create SecureDbHelper
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
D/IntelligenceServiceApplication(11746): onCreate()
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaeb4b380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x8a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
,I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
,I/SecMediaClock( 2855): SecMediaClock destructor
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
,V/AwesomePlayer( 2855): reset_l()
,V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer(11422): decode(49, 20778600, 7017)
,V/MediaPlayerService( 2855): decode(26, 20778600, 7017)
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
V/StagefrightPlayer( 2855): setDataSource(26, 20778600, 7017)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 8, 0, 0)
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
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 5, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
,I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
V/MediaPlayerService( 2855): wait for playback complete
,D/AbsListView(11390): Get MotionRecognitionManager
,D/MotionRecognitionService( 3506):  ssp status : true
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,D/Mms/ComposeMessageFragment(11390): [end]    fillCache consume time = 77.966833
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 2, 0, 0)
,V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb236c380, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x8b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
,I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
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
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
,V/AwesomePlayer( 2855): mSecMediaClock clear
,I/LocationWidgetFuctionData(11688): selectedAppSize: 3
,I/LocationWidgetFuctionData(11688): selectedAppSize: 3
,I/LocationWidgetFuctionData(11688): selectedAppSize: 3
,I/LocationWidgetFuctionData(11688): selectedAppSize: 3
,E/LWLocationManager(11688): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(11688): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(11688): setShouldUpdateLocationId
D/LWLocationManager(11688): setShouldUpdateLocationId return false
D/LWLocationManager(11688): setShouldUpdateLocationId
D/LWLocationManager(11688): setShouldUpdateLocationId return false
D/LWLocationManager(11688): setShouldUpdateLocationId
D/LWLocationManager(11688): setShouldUpdateLocationId return false
D/LWLocationManager(11688): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,D/Mms/BubbleViewCache(11390): fillCache bubble = 8
,V/AlarmManager( 3506): waitForAlarm result :4
,E/SQLiteLog(11448): (284) automatic index on view_events(_id)
,D/CalendarAlarmManager(11448): sys current time:1453390944997
,D/CalendarAlarmManager(11448): reminder amount:0
,W/ContextImpl( 3506): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SurfaceFlinger( 2850): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2850): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3506): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3506) eventTime = 146745
,D/PowerManagerService( 3506): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3506 (0x0)
D/PowerManagerService( 3506): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3506, ws=WorkSource{1000}) (elapsedTime=3472)
,I/GAV4    (11277): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  (10918): wlan0: sending IPv6 Router Solicitation
,I/System.out( 3506): Thread-155(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 3506): Thread-155(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3506): Thread-155(ApacheHTTPLog):isShipBuild true
I/System.out( 3506): Thread-155(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 1000
,I/System.out( 3506): AsyncTask #6 calls detatch()
W/System.err( 3506): java.io.IOException: Not Found
W/System.err( 3506): 	at a.d.b(Unknown Source)
W/System.err( 3506): 	at a.d.doInBackground(Unknown Source)
W/System.err( 3506): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 3506): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 3506): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3506): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 3506): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 3506): 	at java.lang.Thread.run(Thread.java:818)
,I/GAV3    (11422): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  (10918): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (10918): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(11366): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(11366): exit::IDLE
D/PreloadUpdateManagerStateMachine(11366): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (11366): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (11366): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(11366): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(11366): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(11366): entry::IDLE
,D/SSRM:n  ( 3506): SIOP:: AP = 270, PST = 263, CUR = -403
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3506): online:4, current avg:-104, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:96
D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3506): Plugged
,I/MotionRecognitionService( 3506): setPowerConnected  = true
D/BatteryService( 3506): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine(10702): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3506): !@Sync 5
,D/SSRM:n  ( 3506): SIOP:: AP = 260, PST = 265, CUR = -104
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3506): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
,D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3506): Plugged
,I/MotionRecognitionService( 3506): setPowerConnected  = true
,D/BatteryService( 3506): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10702): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3506): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3506): [PWL] Off : 75s ago
,V/AlarmManager( 3506): waitForAlarm result :4
,D/SSRM:n  ( 3506): SIOP:: AP = 250, PST = 265, CUR = 6
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3506): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
,D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3506): Plugged
,I/MotionRecognitionService( 3506): setPowerConnected  = true
,D/BatteryService( 3506): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10702): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3506): waitForAlarm result :8
,I/ClearcutLoggerApiImpl( 4239): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3506): SIOP:: AP = 240, PST = 265, CUR = 42
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3506): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:65
,D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3506): Plugged
,D/BatteryService( 3506): stay LED for fully charged
I/MotionRecognitionService( 3506): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10702): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3506): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3506): !@Sync 6
,D/SSRM:n  ( 3506): SIOP:: AP = 240, PST = 263, CUR = 53
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3506): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
,D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3506): Plugged
,I/MotionRecognitionService( 3506): setPowerConnected  = true
,D/BatteryService( 3506): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10702): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3506): [PWL] Off : 105s ago
,V/AlarmManager( 3506): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/ActivityThread( 4479): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3506): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 172889, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager( 3506): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 265834, reason: UserStart
,W/ResourceType( 4945): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4945): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3506): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3506): mCursor = null
,D/SSRM:n  ( 3506): SIOP:: AP = 240, PST = 258, CUR = 52
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3506): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3506): stay LED for fully charged
,I/MotionRecognitionService( 3506): Plugged
,I/MotionRecognitionService( 3506): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10702): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3506): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3506): SIOP:: AP = 240, PST = 257, CUR = 48
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3506): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3506): Plugged
,I/MotionRecognitionService( 3506): setPowerConnected  = true
,D/BatteryService( 3506): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10702): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3506): waitForAlarm result :4
,E/Watchdog( 3506): !@Sync 7
,D/SSRM:n  ( 3506): SIOP:: AP = 240, PST = 256, CUR = 46
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3506): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3506): stay LED for fully charged
,I/MotionRecognitionService( 3506): Plugged
,I/MotionRecognitionService( 3506): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10702): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3506): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3506): waitForAlarm result :4
,D/SSRM:n  ( 3506): SIOP:: AP = 240, PST = 256, CUR = 43,
,I/PowerManagerService( 3506): [PWL] Off : 140s ago
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3506): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3506): stay LED for fully charged
,I/MotionRecognitionService( 3506): Plugged
,I/MotionRecognitionService( 3506): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10702): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3506): waitForAlarm result :8
,D/SSRM:n  ( 3506): SIOP:: AP = 230, PST = 251, CUR = 39
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3506): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3506): stay LED for fully charged
,I/MotionRecognitionService( 3506): Plugged
,I/MotionRecognitionService( 3506): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10702): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3506): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3506): !@Sync 8
,D/SSRM:n  ( 3506): SIOP:: AP = 230, PST = 249, CUR = 38
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3506): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3506): Plugged
,I/MotionRecognitionService( 3506): setPowerConnected  = true
,D/BatteryService( 3506): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10702): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(10630): TAP version 13
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # multiplex can send data
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 1 String should be length:200
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # basic
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 2 sane
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # another
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 3 sane
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # successfully create a new pkcs12 file and return hash value
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 4 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 5 null
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 6 (unnamed assert)
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 7 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 8 should not throw
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 9 (unnamed assert)
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 10 (unnamed assert)
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 11 should not throw
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 12 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 13 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,D/SSRM:n  ( 3506): SIOP:: AP = 230, PST = 247, CUR = 37
,I/jxcore-log(10630): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 14 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # failed to get mobile documents path
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 15 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #init should register the peerAvailabilityChanged event
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 16 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 17 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 18 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #init should register the networkChanged event
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 19 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #startBroadcasting should throw on null device name,
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 20 should throw
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #startBroadcasting should throw on empty string device name
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 21 should throw
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #startBroadcasting should throw on non-number port
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 22 should throw
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup,
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #startBroadcasting should throw on NaN port
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 23 should throw
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #startBroadcasting should throw on negative port
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 24 should throw
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #startBroadcasting should throw on too large port
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 25 should throw
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 26 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 27 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 28 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 29 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 30 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 31 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 32 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 33 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup,
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 34 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 35 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 36 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 37 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 38 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,D/BatteryService( 3506): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3506): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3506): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3506): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3506): stay LED for fully charged
,I/MotionRecognitionService( 3506): Plugged
,I/MotionRecognitionService( 3506): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,I/jxcore-log(10630): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log(10630): 
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10702): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 39 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 40 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # should call Mobile("Disconnect") without an error
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 41 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 42 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # should call Mobile("Disconnect") and handle an error
I/jxcore-log(10630): 
,W/ContextImpl( 3506): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 43 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 44 should be equal
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391065611.10630
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391065611.10630","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a5ab7da
D/BluetoothSocket(10630): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391065611.10630
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391065611.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=9bc20b3b-9a2f-4e94-9c0b-74060ffa35f8
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=9bc20b3b-9a2f-4e94-9c0b-74060ffa35f8, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
,D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
,D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): starting multi advertising
,D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=fe62699d-3c0d-4775-ac92-290db7a12d18
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=fe62699d-3c0d-4775-ac92-290db7a12d18, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10702): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391065611.10630","ra":"E0:DB:10:14:E2:C0"}
,D/BtGatt.ScanManager(10702): handling starting scan
,D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391065611.10630","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391065611.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): allow scan with filters
,D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager(10702): set filter index= 3 for clientIf= 7
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3506): InactiveState{ what=139292 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3506): P2pEnabledState add service
,D/WifiP2pService( 3506): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391065611.10630
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
,I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): start: OK
,I/jxcore-log(10630): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
,D/WifiP2pService( 3506): InactiveState{ what=139265 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
,D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3506): callSECApi what=74
,D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
,I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
I/io.jxcore.node.ConnectionHelper(10630): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
,D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@3717b5e7, channel: 6, state: LISTENING
,D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@3717b5e7, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a5ab7da, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@62f0594mSocket: android.net.LocalSocket@1a30a83d impl:android.net.LocalSocketImpl@16286832 fd:FileDescriptor[118]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
,D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@1a30a83d impl:android.net.LocalSocketImpl@16286832 fd:FileDescriptor[118]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
,D/WifiP2pService( 3506): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager(10702): message : 1
,D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
,D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1
,D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService(10702): Client app is not null!
,W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10702): Plain text(LSB ~ MSB) = 70 f5 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = 4c 0b 81 ca 2e 28 e5 38 e3 d1 b5 bf ff 86 79 87 
D/ScanRecord(10702): parseFromBytes
D/ScanRecord(10702): first manudata for manu ID
D/BtGatt.GattService(10702): result: ScanResult{mDevice=F0:8B:B2:7E:EA:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -80, -59, 89, 63, 117, 105]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-80, mTimestampNanos=266297260322}
D/BtGatt.GattService(10702): filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10702): stopScan() - queue size =1
D/BtGatt.ContextMap(10702): sendClientScanResult for app id 7
,D/BtGatt.ScanManager(10702): filter size is 1
D/BtGatt.ScanManager(10702): delete FilterIndex - 3
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
,D/ScanRecord(10630): parseFromBytes
D/ScanRecord(10630): first manudata for manu ID
D/BluetoothLeScanner(10630): onScanResult() - ScanResult{mDevice=F0:8B:B2:7E:EA:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -80, -59, 89, 63, 117, 105]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-80, mTimestampNanos=266297260322}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
,D/WifiP2pService( 3506): InactiveState{ what=139298 }
D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 3506): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
E/BtGatt.ContextMap(10702): Context not found for ID 7
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 3506): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
D/WifiP2pService( 3506): InactiveState{ what=139268 }
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
I/wpa_supplicant(10717): P2P-FIND-STOPPED 
D/BtGatt.ScanManager(10702): stop scan
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
,I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
,D/WifiP2pService( 3506): InactiveState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState clear service request
,I/jxcore-log(10630): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
,D/WifiP2pService( 3506): InactiveState{ what=147493 }
D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3506): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391065973.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391065973.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cc0e700
D/BluetoothSocket(10630): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391065973.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391065973.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=e7a19aaa-b0e1-4b32-801e-9c57e53e5659
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=e7a19aaa-b0e1-4b32-801e-9c57e53e5659, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): starting multi advertising
,D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=5c21a1d3-b5ac-4c22-ba32-145477007cc7
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=5c21a1d3-b5ac-4c22-ba32-145477007cc7, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService(10702): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
D/BtGatt.ScanManager(10702): handling starting scan
,D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): allow scan with filters
D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10702): set filter index= 4 for clientIf= 7
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391065973.10630","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391065973.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391065973.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15,
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000,
,D/WifiP2pService( 3506): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3506): P2pEnabledState add service,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiP2pService( 3506): add a new client
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391065973.10630
I/io.jxcore.node.ConnectionHelper(10630): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING,
,I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/WifiP2pService( 3506): InactiveState{ what=139265 },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
,D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
,I/jxcore-log(10630): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3506): callSECApi what=74
,D/WifiP2pService( 3506): discovery change broadcast true
D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant(10717): p2p0: P2P: Reject scan trigger since one is already pending
,I/io.jxcore.node.ConnectionHelper(10630): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
,D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@1f99a1f5, channel: 6, state: LISTENING
D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@1f99a1f5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cc0e700, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3c40cb8amSocket: android.net.LocalSocket@1c56e5fb impl:android.net.LocalSocketImpl@26349618 fd:FileDescriptor[118]
D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@1c56e5fb impl:android.net.LocalSocketImpl@26349618 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiP2pService( 3506): InactiveState{ what=139268 }
D/BtGatt.AdvertiseManager(10702): message : 1
,D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
I/wpa_supplicant(10717): P2P-FIND-STOPPED 
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1
,D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0,
D/WifiP2pService( 3506): InactiveState{ what=147493 }
D/BtGatt.GattService(10702): Client app is not null!
D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/WifiP2pService( 3506): discovery change broadcast false
D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10702): stopScan() - queue size =1
W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10702): Plain text(LSB ~ MSB) = 50 58 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = 63 69 5a b6 65 68 28 2f dd 95 80 4a cd a1 64 49 
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
,D/WifiP2pService( 3506): InactiveState{ what=139268 }
,D/BtGatt.ScanManager(10702): filter size is 1
D/BtGatt.ScanManager(10702): delete FilterIndex - 4
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): stop scan
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
D/WifiP2pService( 3506): InactiveState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3506): P2pEnabledState clear service
,I/jxcore-log(10630): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
,D/WifiP2pService( 3506): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
D/WifiP2pService( 3506): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/WifiP2pService( 3506): InactiveState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391066190.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391066190.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ce81656
D/BluetoothSocket(10630): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391066190.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391066190.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=376a6c11-0099-4323-bfbc-317807e26afa
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=376a6c11-0099-4323-bfbc-317807e26afa, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): starting multi advertising
,D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=280aa43a-0130-4cdf-bfd6-fddddc4519c6
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=280aa43a-0130-4cdf-bfd6-fddddc4519c6, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10702): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager(10702): handling starting scan
,D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10702): allow scan with filters
D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10702): set filter index= 5 for clientIf= 7
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391066190.10630","ra":"E0:DB:10:14:E2:C0"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391066190.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391066190.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000,
,D/WifiP2pService( 3506): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391066190.10630
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
,D/WifiP2pService( 3506): P2pEnabledState add service
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/jxcore-log(10630): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
,D/WifiP2pService( 3506): add a new client
,I/io.jxcore.node.ConnectionHelper(10630): stop
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
,D/WifiP2pService( 3506): InactiveState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@25561973, channel: 6, state: LISTENING
,I/WifiStateMachine( 3506): callSECApi what=74
,D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
,D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@25561973, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ce81656, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35c1030mSocket: android.net.LocalSocket@3041b4a9 impl:android.net.LocalSocketImpl@34bb9a2e fd:FileDescriptor[118]
,I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@3041b4a9 impl:android.net.LocalSocketImpl@34bb9a2e fd:FileDescriptor[118]
,I/wpa_supplicant(10717): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
,D/BtGatt.AdvertiseManager(10702): message : 1
,D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
,D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1,
,D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10702): Client app is not null!
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
,W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
,W/bt-smp  (10702): Plain text(LSB ~ MSB) = 11 22 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = dc e4 05 92 77 c2 45 61 5d eb 60 a7 d5 ec dd 76 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
,D/WifiP2pService( 3506): discovery change broadcast true
,D/BtGatt.GattService(10702): stopScan() - queue size =1
,D/BtGatt.ScanManager(10702): filter size is 1
,D/BtGatt.ScanManager(10702): delete FilterIndex - 5
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10702): stop scan
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/WifiP2pService( 3506): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
,I/wpa_supplicant(10717): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3506): InactiveState{ what=147493 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3506): discovery change broadcast false
,I/jxcore-log(10630): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/WifiP2pService( 3506): InactiveState{ what=139298 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
D/WifiP2pService( 3506): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391066481.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
D/WifiP2pService( 3506): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
D/WifiP2pService( 3506): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
,D/WifiP2pService( 3506): InactiveState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3506): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391066481.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ca9ff5c
D/BluetoothSocket(10630): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391066481.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391066481.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=2f48bac8-7737-4a21-b16e-6c0c6725ae7a
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=2f48bac8-7737-4a21-b16e-6c0c6725ae7a, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): starting multi advertising
,D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=7dd9209e-b772-473d-8111-1203d03c0ecd
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=7dd9209e-b772-473d-8111-1203d03c0ecd, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10702): start scan with filters
,D/BtGatt.ScanManager(10702): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10702): allow scan with filters
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391066481.10630","ra":"E0:DB:10:14:E2:C0"}
D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10702): set filter index= 6 for clientIf= 7
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391066481.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391066481.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3506): InactiveState{ what=139292 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3506): P2pEnabledState add service
,D/WifiP2pService( 3506): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
,D/WifiP2pService( 3506): InactiveState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391066481.10630
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper(10630): start: OK
,D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
,D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3506): callSECApi what=74
D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
,I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant(10717): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log(10630): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
D/WifiP2pService( 3506): discovery change broadcast true
,D/WifiP2pService( 3506): InactiveState{ what=139268 }
,I/wpa_supplicant(10717): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper(10630): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@1eda4fe1, channel: 6, state: LISTENING
D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@1eda4fe1, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ca9ff5c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1050c106mSocket: android.net.LocalSocket@1dd633c7 impl:android.net.LocalSocketImpl@ae4ddf4 fd:FileDescriptor[118]
D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@1dd633c7 impl:android.net.LocalSocketImpl@ae4ddf4 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
D/WifiP2pService( 3506): InactiveState{ what=147493 }
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3506): discovery change broadcast false
,D/BtGatt.AdvertiseManager(10702): message : 1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
,D/ScanRecord(10702): parseFromBytes
D/ScanRecord(10702): first manudata for manu ID
D/BtGatt.GattService(10702): result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=267048855614}
D/BtGatt.GattService(10702): filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
D/BtGatt.ContextMap(10702): sendClientScanResult for app id 7
,D/ScanRecord(10630): parseFromBytes
D/ScanRecord(10630): first manudata for manu ID
D/BluetoothLeScanner(10630): onScanResult() - ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=267048855614}
D/WifiP2pService( 3506): InactiveState{ what=139268 }
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=267048855614}
D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1
,D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10702): Client app is not null!
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10702): stopScan() - queue size =1
D/BtGatt.ScanManager(10702): filter size is 1
D/BtGatt.ScanManager(10702): delete FilterIndex - 6
D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
D/WifiP2pService( 3506): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
D/WifiP2pService( 3506): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10702): Plain text(LSB ~ MSB) = 61 1d 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = 2a bc 82 96 6a 11 21 b5 99 cb af 91 13 51 49 d1 
,D/WifiP2pService( 3506): remove client information from framework
I/jxcore-log(10630): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10702): stop scan
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
D/WifiP2pService( 3506): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391066717.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
D/WifiP2pService( 3506): InactiveState{ what=139307 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3506): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391066717.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15a7e792
D/BluetoothSocket(10630): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391066717.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391066717.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=47dc9aa1-1827-4efc-a215-a69ad9641830
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=47dc9aa1-1827-4efc-a215-a69ad9641830, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
,D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): starting multi advertising
,D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0,
D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=5bb9a8ef-6185-455e-bca8-cc89b5d9ab19
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=5bb9a8ef-6185-455e-bca8-cc89b5d9ab19, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10702): start scan with filters
,D/BtGatt.ScanManager(10702): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391066717.10630","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391066717.10630","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391066717.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): allow scan with filters
,D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10702): set filter index= 7 for clientIf= 7
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3506): InactiveState{ what=139292 }
D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
D/WifiP2pService( 3506): P2pEnabledState add service
D/WifiP2pService( 3506): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391066717.10630
,D/WifiP2pService( 3506): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3506): callSECApi what=74
D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
I/jxcore-log(10630): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant(10717): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper(10630): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@189fd4bf, channel: 6, state: LISTENING
D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@189fd4bf, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15a7e792, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3999f78cmSocket: android.net.LocalSocket@32433ed5 impl:android.net.LocalSocketImpl@1184d6ea fd:FileDescriptor[118]
D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@32433ed5 impl:android.net.LocalSocketImpl@1184d6ea fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
D/WifiP2pService( 3506): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
D/BtGatt.AdvertiseManager(10702): message : 1
D/WifiP2pService( 3506): InactiveState{ what=139268 }
I/wpa_supplicant(10717): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1
D/WifiP2pService( 3506): InactiveState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3506): discovery change broadcast false
,D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10702): Client app is not null!
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
,D/WifiP2pService( 3506): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10702): stopScan() - queue size =1
D/BtGatt.ScanManager(10702): filter size is 1
D/BtGatt.ScanManager(10702): delete FilterIndex - 7
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10702): Plain text(LSB ~ MSB) = f7 0d 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = b9 26 1b 44 b6 ac 4d 4e d5 9c 15 42 d6 1a 2a 45 
D/WifiP2pService( 3506): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
D/WifiP2pService( 3506): P2pEnabledState clear service
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10702): stop scan
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
,D/WifiP2pService( 3506): remove client information from framework
,I/jxcore-log(10630): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
D/WifiP2pService( 3506): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/WifiP2pService( 3506): InactiveState{ what=139307 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391066972.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391066972.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b50078
D/BluetoothSocket(10630): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391066972.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391066972.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=baa504a5-1818-44ee-a2dd-5167c9b9cc5c
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=baa504a5-1818-44ee-a2dd-5167c9b9cc5c, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
,D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
,D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10702): starting multi advertising
D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=f31c6842-9a28-4c1e-9803-927402c1c3ba
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=f31c6842-9a28-4c1e-9803-927402c1c3ba, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10702): start scan with filters
,D/BtGatt.ScanManager(10702): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391066972.10630","ra":"E0:DB:10:14:E2:C0"}
,D/BtGatt.ScanManager(10702): allow scan with filters
D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391066972.10630","ra":"E0:DB:10:14:E2:C0"}
D/BtGatt.ScanManager(10702): set filter index= 8 for clientIf= 7
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391066972.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3506): InactiveState{ what=139292 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3506): P2pEnabledState add service
,D/WifiP2pService( 3506): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
,D/WifiP2pService( 3506): InactiveState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
,D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391066972.10630
,D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3506): callSECApi what=74
D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
,I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,D/WifiP2pService( 3506): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper(10630): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
,D/WifiP2pService( 3506): InactiveState{ what=139268 }
,I/wpa_supplicant(10717): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/WifiP2pService( 3506): InactiveState{ what=147493 }
,I/jxcore-log(10630): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3506): discovery change broadcast false
,I/io.jxcore.node.ConnectionHelper(10630): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@1465738d, channel: 6, state: LISTENING
D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@1465738d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b50078, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4755942mSocket: android.net.LocalSocket@32354d53 impl:android.net.LocalSocketImpl@3f736690 fd:FileDescriptor[118]
D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@32354d53 impl:android.net.LocalSocketImpl@3f736690 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
D/WifiP2pService( 3506): InactiveState{ what=139268 }
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
,D/BtGatt.AdvertiseManager(10702): message : 1
,D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1
,D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10702): Client app is not null!
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10702): stopScan() - queue size =1
,D/BtGatt.ScanManager(10702): filter size is 1
D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
D/BtGatt.ScanManager(10702): delete FilterIndex - 8
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
,D/WifiP2pService( 3506): InactiveState{ what=139298 }
D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 3506): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10702): Plain text(LSB ~ MSB) = 62 df 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = a3 3b 43 53 fb 2c 5e 29 a2 88 59 38 64 c2 aa d5 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService( 3506): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/WifiP2pService( 3506): InactiveState{ what=139268 }
,D/BtGatt.ScanManager(10702): stop scan
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log(10630): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/WifiP2pService( 3506): InactiveState{ what=139307 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391067186.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391067186.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d03c78e
D/BluetoothSocket(10630): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391067186.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391067186.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=4dc82430-a6a9-4934-8fb1-693bd82b8628
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=4dc82430-a6a9-4934-8fb1-693bd82b8628, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
,D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): starting multi advertising
,D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=29ebd17f-9793-4931-a88a-e2d2644d1ecf
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=29ebd17f-9793-4931-a88a-e2d2644d1ecf, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10702): start scan with filters
,D/BtGatt.ScanManager(10702): handling starting scan
,D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): allow scan with filters
,D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10702): set filter index= 9 for clientIf= 7
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391067186.10630","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391067186.10630","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391067186.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000
,I/art     ( 3506): Explicit concurrent mark sweep GC freed 51259(3MB) AllocSpace objects, 53(3MB) LOS objects, 24% free, 49MB/65MB, paused 2.061ms total 169.521ms
,D/WifiP2pService( 3506): InactiveState{ what=139292 }
D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
D/WifiP2pService( 3506): P2pEnabledState add service
,D/WifiP2pService( 3506): add a new client
,D/ScanRecord(10702): parseFromBytes
,D/ScanRecord(10702): first manudata for manu ID
,D/BtGatt.GattService(10702): result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-73, mTimestampNanos=267916303114}
D/BtGatt.GattService(10702): filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
D/BtGatt.ContextMap(10702): sendClientScanResult for app id 7
D/ScanRecord(10630): parseFromBytes
D/ScanRecord(10630): first manudata for manu ID
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
,D/ScanRecord(10702): parseFromBytes
D/ScanRecord(10702): first manudata for manu ID
D/BluetoothLeScanner(10630): onScanResult() - ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-73, mTimestampNanos=267916303114}
,D/BtGatt.GattService(10702): result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-73, mTimestampNanos=267919675780}
D/BtGatt.GattService(10702): filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
D/BtGatt.ContextMap(10702): sendClientScanResult for app id 7
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391067186.10630
I/io.jxcore.node.ConnectionHelper(10630): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-73, mTimestampNanos=267916303114}
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
I/jxcore-log(10630): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
D/ScanRecord(10630): parseFromBytes
D/ScanRecord(10630): first manudata for manu ID
D/BluetoothLeScanner(10630): onScanResult() - ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-73, mTimestampNanos=267919675780}
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-73, mTimestampNanos=267919675780}
D/WifiP2pService( 3506): InactiveState{ what=139265 }
I/io.jxcore.node.ConnectionHelper(10630): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@11ff13cb, channel: 6, state: LISTENING
I/WifiStateMachine( 3506): callSECApi what=74
D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@11ff13cb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d03c78e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3ba577a8mSocket: android.net.LocalSocket@3d952c1 impl:android.net.LocalSocketImpl@1d053a66 fd:FileDescriptor[118]
D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
,D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@3d952c1 impl:android.net.LocalSocketImpl@1d053a66 fd:FileDescriptor[118]
I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
I/wpa_supplicant(10717): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager(10702): message : 1
,D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
,D/WifiP2pService( 3506): discovery change broadcast true
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1
,D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10702): Client app is not null!
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
D/WifiP2pService( 3506): InactiveState{ what=139268 }
,I/wpa_supplicant(10717): P2P-FIND-STOPPED 
,W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10702): Plain text(LSB ~ MSB) = 62 fd 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = f7 c9 b9 04 91 50 99 8c b7 7d 4c da 83 86 ef 8e 
,D/BtGatt.GattService(10702): stopScan() - queue size =1
,D/BtGatt.ScanManager(10702): filter size is 1
D/BtGatt.ScanManager(10702): delete FilterIndex - 9
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
D/BtGatt.ScanManager(10702): stop scan
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
D/WifiP2pService( 3506): InactiveState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
D/WifiP2pService( 3506): discovery change broadcast false
,I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3506): InactiveState{ what=139298 }
D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
D/WifiP2pService( 3506): P2pEnabledState clear service
I/jxcore-log(10630): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
D/WifiP2pService( 3506): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
,D/WifiP2pService( 3506): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/WifiP2pService( 3506): InactiveState{ what=139307 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391067620.10630
D/WifiP2pService( 3506): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391067620.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20ae6654
D/BluetoothSocket(10630): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391067620.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391067620.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=3319db36-501f-4ad4-92b1-b56b38199805
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=3319db36-501f-4ad4-92b1-b56b38199805, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): starting multi advertising
,D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=41f9ab7d-290c-4dc4-bcac-8a775fe7c93f
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=41f9ab7d-290c-4dc4-bcac-8a775fe7c93f, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10702): start scan with filters
,D/BtGatt.ScanManager(10702): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): allow scan with filters
,D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10702): set filter index= 10 for clientIf= 7
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391067620.10630","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391067620.10630","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391067620.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3506): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
,D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
,D/WifiP2pService( 3506): P2pEnabledState add service
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391067620.10630
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper(10630): start: OK
,I/jxcore-log(10630): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
,D/WifiP2pService( 3506): add a new client
,I/io.jxcore.node.ConnectionHelper(10630): stop
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService( 3506): InactiveState{ what=139265 }
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@1ad498f9, channel: 6, state: LISTENING
,D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@1ad498f9, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20ae6654, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3cb7303emSocket: android.net.LocalSocket@38a69e9f impl:android.net.LocalSocketImpl@31402bec fd:FileDescriptor[118]
,D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
,D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@38a69e9f impl:android.net.LocalSocketImpl@31402bec fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
,D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
,I/WifiStateMachine( 3506): callSECApi what=74
D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
,D/ScanRecord(10702): parseFromBytes
,D/ScanRecord(10702): first manudata for manu ID
,D/BtGatt.GattService(10702): result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=268159751114}
,D/BtGatt.GattService(10702): filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
,D/BtGatt.ContextMap(10702): sendClientScanResult for app id 7
I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
,D/BtGatt.AdvertiseManager(10702): message : 1
,D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
,D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1
,D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService(10702): Client app is not null!
,D/ScanRecord(10630): parseFromBytes
,D/ScanRecord(10630): first manudata for manu ID
,D/BluetoothLeScanner(10630): onScanResult() - ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=268159751114}
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-72, mTimestampNanos=268159751114}
,W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
,W/bt-smp  (10702): Plain text(LSB ~ MSB) = e7 9c 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = f4 86 f8 59 a7 f2 d8 cd 21 b9 51 93 3c d5 fe 28 
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10702): stopScan() - queue size =1
I/wpa_supplicant(10717): p2p0: P2P: Reject scan trigger since one is already pending
,D/BtGatt.ScanManager(10702): filter size is 1
,D/BtGatt.ScanManager(10702): delete FilterIndex - 10
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/WifiP2pService( 3506): discovery change broadcast true
D/BtGatt.ScanManager(10702): stop scan
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/WifiP2pService( 3506): InactiveState{ what=139268 }
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
I/wpa_supplicant(10717): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 3506): InactiveState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
D/WifiP2pService( 3506): discovery change broadcast false
,W/BroadcastQueue( 3506): Skipping deliver [background] BroadcastRecord{317c3a2 u-1 android.net.wifi.p2p.DISCOVERY_STATE_CHANGE} to ReceiverList{b713997 10630 com.test.thalitest/10594/u0 remote:301ffc16}: filter unregistered
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
D/WifiP2pService( 3506): InactiveState{ what=139298 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService( 3506): P2pEnabledState clear service
,I/jxcore-log(10630): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
D/WifiP2pService( 3506): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
D/WifiP2pService( 3506): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/WifiP2pService( 3506): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391067856.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391067856.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4f2124a
D/BluetoothSocket(10630): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391067856.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391067856.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=795edfec-1451-407a-9d21-af46887fe434
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=795edfec-1451-407a-9d21-af46887fe434, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
,D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): starting multi advertising
,D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=33222d7b-4605-465d-b8f7-7ae7a1a22fea
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=33222d7b-4605-465d-b8f7-7ae7a1a22fea, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10702): start scan with filters
,D/BtGatt.ScanManager(10702): handling starting scan
,D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): allow scan with filters
,D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10702): set filter index= 11 for clientIf= 7
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391067856.10630","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391067856.10630","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391067856.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3506): InactiveState{ what=139292 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3506): P2pEnabledState add service
,D/WifiP2pService( 3506): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
,D/WifiP2pService( 3506): InactiveState{ what=139265 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
I/WifiStateMachine( 3506): callSECApi what=74
D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391067856.10630
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,I/wpa_supplicant(10717): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiP2pService( 3506): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper(10630): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/WifiP2pService( 3506): InactiveState{ what=139268 }
I/wpa_supplicant(10717): P2P-FIND-STOPPED 
,I/jxcore-log(10630): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
,D/WifiP2pService( 3506): InactiveState{ what=147493 }
I/io.jxcore.node.ConnectionHelper(10630): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@3f07c297, channel: 6, state: LISTENING
D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@3f07c297, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4f2124a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@b620c84mSocket: android.net.LocalSocket@2aa7bc6d impl:android.net.LocalSocketImpl@2e22a0a2 fd:FileDescriptor[118]
D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@2aa7bc6d impl:android.net.LocalSocketImpl@2e22a0a2 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
,D/BtGatt.AdvertiseManager(10702): message : 1
D/WifiP2pService( 3506): discovery change broadcast false
D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10702): Client app is not null!
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
D/WifiP2pService( 3506): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10702): stopScan() - queue size =1
,D/BtGatt.ScanManager(10702): filter size is 1
D/BtGatt.ScanManager(10702): delete FilterIndex - 11
D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
D/WifiP2pService( 3506): InactiveState{ what=139298 }
D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
D/WifiP2pService( 3506): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10702): Plain text(LSB ~ MSB) = 6e 10 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = 55 6f 6b aa 8f 0b 24 18 0e 6e 97 57 fc 96 78 b8 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3506): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
D/WifiP2pService( 3506): InactiveState{ what=139268 }
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): stop scan
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log(10630): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/WifiP2pService( 3506): InactiveState{ what=139307 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391068099.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391068099.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f356cf0
D/BluetoothSocket(10630): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391068099.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391068099.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=3b001b59-f71b-47ad-9634-d6859af67579
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=3b001b59-f71b-47ad-9634-d6859af67579, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
,D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): starting multi advertising
,D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=1d4289db-dc0d-48be-9fff-7db5406d2821
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=1d4289db-dc0d-48be-9fff-7db5406d2821, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService(10702): start scan with filters
,D/BtGatt.ScanManager(10702): handling starting scan
,D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): allow scan with filters
,D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager(10702): set filter index= 12 for clientIf= 7
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391068099.10630","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391068099.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391068099.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3506): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): start: OK,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391068099.10630
,I/jxcore-log(10630): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
I/io.jxcore.node.ConnectionHelper(10630): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@36f90c25, channel: 6, state: LISTENING
D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@36f90c25, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f356cf0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@135ba1famSocket: android.net.LocalSocket@2aba53ab impl:android.net.LocalSocketImpl@1815ea08 fd:FileDescriptor[118]
,D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@2aba53ab impl:android.net.LocalSocketImpl@1815ea08 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running,
D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
D/WifiP2pService( 3506): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService( 3506): add a new client
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/WifiP2pService( 3506): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
D/BtGatt.AdvertiseManager(10702): message : 1
D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1
D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3506): callSECApi what=74
D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant(10717): p2p0: P2P: Reject scan trigger since one is already pending
D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10702): Client app is not null!
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
D/WifiP2pService( 3506): discovery change broadcast true
D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
,D/WifiP2pService( 3506): InactiveState{ what=139268 }
I/wpa_supplicant(10717): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10702): stopScan() - queue size =1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/WifiP2pService( 3506): InactiveState{ what=147493 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
D/BtGatt.ScanManager(10702): filter size is 1
D/BtGatt.ScanManager(10702): delete FilterIndex - 12
D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
D/WifiP2pService( 3506): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
,W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10702): Plain text(LSB ~ MSB) = 56 50 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = 6a 29 26 dd 86 e8 e5 0e 11 05 f7 92 3c ce c9 66 
,D/WifiP2pService( 3506): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
,D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10702): stop scan
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
D/WifiP2pService( 3506): P2pEnabledState clear service
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log(10630): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
,D/WifiP2pService( 3506): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
D/WifiP2pService( 3506): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/WifiP2pService( 3506): InactiveState{ what=139307 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391068494.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391068494.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cb1e3c6
D/BluetoothSocket(10630): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391068494.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391068494.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=41abb45b-f444-4c0b-9d0e-c76931c9ecdd
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=41abb45b-f444-4c0b-9d0e-c76931c9ecdd, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
,D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
,D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): starting multi advertising
,D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=f70ac5d8-92a4-46cf-bd5e-ae27e3cc4ed3
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=f70ac5d8-92a4-46cf-bd5e-ae27e3cc4ed3, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService(10702): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
D/BtGatt.ScanManager(10702): handling starting scan
,D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10702): allow scan with filters
D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10702): set filter index= 13 for clientIf= 7
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391068494.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391068494.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391068494.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3506): InactiveState{ what=139292 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
D/WifiP2pService( 3506): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
D/WifiP2pService( 3506): add a new client
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391068494.10630
,I/io.jxcore.node.ConnectionHelper(10630): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
D/WifiP2pService( 3506): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/WifiStateMachine( 3506): callSECApi what=74
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
,D/WifiP2pService( 3506): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
D/WifiP2pService( 3506): InactiveState{ what=139268 }
,I/wpa_supplicant(10717): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log(10630): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/WifiP2pService( 3506): InactiveState{ what=147493 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3506): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
,D/WifiP2pService( 3506): InactiveState{ what=139268 }
,I/jxcore-log(10630): ok 66 Cannot call startBroadcasting twice
I/jxcore-log(10630): 
,I/io.jxcore.node.ConnectionHelper(10630): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@1da38d23, channel: 6, state: LISTENING
D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@1da38d23, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cb1e3c6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3fb5f220mSocket: android.net.LocalSocket@34fe07d9 impl:android.net.LocalSocketImpl@2163a59e fd:FileDescriptor[118]
D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@34fe07d9 impl:android.net.LocalSocketImpl@2163a59e fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
,I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager(10702): message : 1
,D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1
,D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10702): Client app is not null!
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10702): stopScan() - queue size =1
,D/BtGatt.ScanManager(10702): filter size is 1
D/BtGatt.ScanManager(10702): delete FilterIndex - 13
D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
,D/WifiP2pService( 3506): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 3506): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10702): Plain text(LSB ~ MSB) = a0 67 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = e2 c6 e7 7c 8d 11 3c 05 f8 cf 2c e6 aa a7 f6 58 
,D/WifiP2pService( 3506): remove client information from framework,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
D/WifiP2pService( 3506): InactiveState{ what=139268 }
D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): stop scan
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log(10630): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
,D/WifiP2pService( 3506): InactiveState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # ThaliEmitter throws on connection to bad peer
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown,
I/jxcore-log(10630): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391068932.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391068932.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@158104c
D/BluetoothSocket(10630): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391068932.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391068932.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=18907cf2-5b8b-4fc0-b0f3-da6eccf09a66
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=18907cf2-5b8b-4fc0-b0f3-da6eccf09a66, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
,D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
,D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): starting multi advertising
,D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=d89f0c65-e561-4575-8b1f-cb481f26e5b4
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=d89f0c65-e561-4575-8b1f-cb481f26e5b4, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService(10702): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
D/BtGatt.ScanManager(10702): handling starting scan
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391068932.10630","ra":"E0:DB:10:14:E2:C0"}
D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391068932.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391068932.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
D/BtGatt.ScanManager(10702): allow scan with filters
D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager(10702): set filter index= 14 for clientIf= 7
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
D/WifiP2pService( 3506): InactiveState{ what=139292 }
D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiP2pService( 3506): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService( 3506): add a new client
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391068932.10630
I/io.jxcore.node.ConnectionHelper(10630): start: OK
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/jxcore-log(10630): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
D/WifiP2pService( 3506): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
I/WifiStateMachine( 3506): callSECApi what=74
D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
I/io.jxcore.node.ConnectionHelper(10630): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper(10630): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/wpa_supplicant(10717): p2p0: P2P: Reject scan trigger since one is already pending
E/io.jxcore.node.ConnectionHelper(10630): connect: Invalid Bluetooth address: foobar
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
D/WifiP2pService( 3506): discovery change broadcast true
,D/WifiP2pService( 3506): InactiveState{ what=139268 }
I/wpa_supplicant(10717): P2P-FIND-STOPPED 
,I/jxcore-log(10630): ok 69 Should not connect to a bad peer
I/jxcore-log(10630): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper(10630): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService( 3506): InactiveState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
,D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@2807d911, channel: 6, state: LISTENING
D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@2807d911, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@158104c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23a0ca76mSocket: android.net.LocalSocket@366a5877 impl:android.net.LocalSocketImpl@35461ce4 fd:FileDescriptor[118]
D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@366a5877 impl:android.net.LocalSocketImpl@35461ce4 fd:FileDescriptor[118]
D/WifiP2pService( 3506): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
,D/BtGatt.AdvertiseManager(10702): message : 1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1
D/WifiP2pService( 3506): InactiveState{ what=139268 }
,D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10702): Client app is not null!
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10702): stopScan() - queue size =1
,D/BtGatt.ScanManager(10702): filter size is 1
D/BtGatt.ScanManager(10702): delete FilterIndex - 14
D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
D/WifiP2pService( 3506): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
,D/WifiP2pService( 3506): P2pEnabledState clear service
W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  (10702): Plain text(LSB ~ MSB) = 1e 63 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = 9f 0b 5b 9f fb d7 93 c3 f5 ce 96 45 ff 92 a8 e8 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
D/WifiP2pService( 3506): remove client information from framework
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
,D/WifiP2pService( 3506): InactiveState{ what=139268 }
D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager(10702): stop scan
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log(10630): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
D/WifiP2pService( 3506): InactiveState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391069403.10630
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391069403.10630","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(10630): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10630): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(10630): bindListen(), new LocalSocket 
D/BluetoothSocket(10630): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10630): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b471802
,D/BluetoothSocket(10630): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): start: OK
,I/io.jxcore.node.ConnectionHelper(10630): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391069403.10630
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): createAdvertiseData: From: 1453391069403.10630 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(10630): E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(10630): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=4bea1e31-e919-44b3-9ae0-644893be0808
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=4bea1e31-e919-44b3-9ae0-644893be0808, clientIf=6
,D/BluetoothLeAdvertiser(10630): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager(10702): message : 0
,D/BtGatt.AdvertiseManager(10702): number of adv instance running0
,D/BtGatt.AdvertiseManager(10702): size of list is =0
,D/BtGatt.AdvertiseManager(10702): starting advertising
,D/BtGatt.AdvertiseManager(10702): isDualWavefalse
,D/BtGatt.GattService(10702): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): starting multi advertising
,D/BtGatt.GattService(10702): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager(10702): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService(10702): registerClient() - UUID=73f2304c-af6e-4b7b-9051-53978af4397e
,D/BtGatt.GattService(10702): onClientRegistered() - UUID=73f2304c-af6e-4b7b-9051-53978af4397e, clientIf=7
,D/BluetoothLeScanner(10630): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService(10702): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
D/BtGatt.ScanManager(10702): handling starting scan
,D/BtGatt.GattService(10702): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): allow scan with filters
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10630): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391069403.10630","ra":"E0:DB:10:14:E2:C0"}
D/BtGatt.ScanManager(10702): client filter size is = 1available filters are = 13
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453391069403.10630","ra":"E0:DB:10:14:E2:C0"}
D/BtGatt.ScanManager(10702): set filter index= 15 for clientIf= 7
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453391069403.10630","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager(10702): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3506): InactiveState{ what=139292 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139292 }
D/WifiP2pService( 3506): P2pEnabledState add service
,D/WifiP2pService( 3506): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(10630): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453391069403.10630
,D/WifiP2pService( 3506): InactiveState{ what=139265 }
D/WifiP2pService( 3506): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3506): callSECApi what=74
D/WifiService( 3506): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3506): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3506): callSECApiBoolean - ID [13]
I/wpa_supplicant(10717): USE_NETWORK : USE_NETWORK OFF
,I/jxcore-log(10630): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log(10630): 
I/wpa_supplicant(10717): p2p0: P2P: Reject scan trigger since one is already pending
,D/io.jxcore.node.ConnectionHelper(10630): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
D/WifiP2pService( 3506): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: Already running
E/io.jxcore.node.ConnectionHelper(10630): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startBlePeerDiscovery: OK
D/io.jxcore.node.ConnectionHelper(10630): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper(10630): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(10630): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
I/jxcore-log(10630): ok 72 Disconnect should fail to a non-existant peer 
I/jxcore-log(10630): 
,I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local service added successfully
I/io.jxcore.node.ConnectionHelper(10630): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): shutdown
D/WifiP2pService( 3506): InactiveState{ what=139268 }
D/BluetoothSocket(10630): close() in, this: android.bluetooth.BluetoothSocket@b9ddf6f, channel: 6, state: LISTENING
D/BluetoothSocket(10630): close() this: android.bluetooth.BluetoothSocket@b9ddf6f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b471802, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@b26247cmSocket: android.net.LocalSocket@12438105 impl:android.net.LocalSocketImpl@26eba55a fd:FileDescriptor[118]
D/BluetoothSocket(10630): Closing mSocket: android.net.LocalSocket@12438105 impl:android.net.LocalSocketImpl@26eba55a fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(10630): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(10630): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10630): onServerStopped
I/wpa_supplicant(10717): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: STARTED
D/BtGatt.AdvertiseManager(10702): message : 1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper(10630): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/WifiP2pService( 3506): InactiveState{ what=147493 }
D/BtGatt.AdvertiseManager(10702): stop advertise for client 6
D/BtGatt.AdvertiseManager(10702):  dualWaveClientIf = 0client.clientIf6
D/WifiP2pService( 3506): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3506): discovery change broadcast false
D/BtGatt.AdvertiseManager(10702): logClientsSet() - status: -1
,D/BtGatt.GattService(10702): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService(10702): Client app is not null!
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: RESTARTING
,D/BtGatt.GattService(10702): unregisterClient() - clientIf=6
D/WifiP2pService( 3506): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService(10702): stopScan() - queue size =1
,D/BtGatt.ScanManager(10702): filter size is 1
D/BtGatt.ScanManager(10702): delete FilterIndex - 15
D/BtGatt.GattService(10702): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(10630): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(10630): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(10630): release: No more listeners, de-initializing...
D/WifiP2pService( 3506): InactiveState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10630): release: No more listeners, de-initializing...
D/WifiP2pService( 3506): P2pEnabledState{ what=139298 }
D/WifiP2pService( 3506): P2pEnabledState clear service
W/bt-smp  (10702): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
,W/bt-smp  (10702): Plain text(LSB ~ MSB) = 8d c9 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  (10702): Encrypted text(LSB ~ MSB) = 2d 4c 50 e8 de e8 27 2d f8 bf 7c 66 a6 9c 75 2f 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10630): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(10630): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log(10630): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log(10630): 
,D/BtGatt.GattService(10702): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/WifiP2pService( 3506): remove client information from framework
,D/WifiP2pService( 3506): InactiveState{ what=139268 }
D/BtGatt.ScanManager(10702): callback done for clientIf - 7 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(10630): Local services cleared successfully
D/BtGatt.ScanManager(10702): stop scan
D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager(10702): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager(10702): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(10630): P2P device discovery stopped successfully
D/WifiP2pService( 3506): InactiveState{ what=139307 }
D/WifiP2pService( 3506): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3506): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(10630): Service requests cleared successfully
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/wpa_supplicant(10717): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1,
,D/WifiP2pService( 3506): InactiveState{ what=147477 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3506): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3506): InactiveState{ what=139283 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3506): DefaultState{ what=139283 }
,D/WifiDisplayController( 3506): Received list of peers.
,D/WifiDisplayController( 3506):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log(10630): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 74 host address should match
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 75 port should match
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 76 USN should have changed from the first one,
,I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # verify that Thali-specific messages are filtered correctly
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 77 irrelevant messages should be ignored
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 78 relevant messages should not be ignored
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 79 messages from this device should be ignored
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #start should fail if called twice in a row
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 80 specific error should be received
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,E/jxcore-log(10630): ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
E/jxcore-log(10630): 
,I/jxcore-log(10630): ok 81 specific error should be received
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log(10630): 
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10594
,I/jxcore-log(10630): ok 82 server should respond with code 200
I/jxcore-log(10630): 
,I/jxcore-log(10630): # setup
I/jxcore-log(10630): 
,I/jxcore-log(10630): # #stop can be called multiple times in a row
I/jxcore-log(10630): 
,D/btif_config_util(10702): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log(10630): # teardown
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 83 should be in stopped state
I/jxcore-log(10630): 
,I/jxcore-log(10630): ok 84 should still be in stopped state
I/jxcore-log(10630): 
,I/jxcore-log(10630): Tests Complete
I/jxcore-log(10630): 
,I/jxcore-log(10630): Total: 0	Passed: 0	Failed: 0
I/jxcore-log(10630): 
,I/jxcore-log(10630): Toggling radios to false
I/jxcore-log(10630): 
,D/BluetoothAdapter(10630): disable()
,I/chromium(10630): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
D/SettingsProvider( 3506): name = bluetooth_on
,I/chromium(10630): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,I/WifiManager(10630): packageName : com.test.thalitest
,D/SecContentProvider( 3506): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3506): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3506): mCursor = null
,D/WifiService( 3506): setWifiEnabled: false pid=10630, uid=10594
D/BluetoothAdapterState(10702): CURRENT_STATE=ON, MSG = USER_TURN_OFF
E/WifiService( 3506): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterProperties(10702): Setting state to 13
I/BluetoothAdapterState(10702): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(10702): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10702): updateAdapterState state is 13
D/SettingsProvider( 3506): name = wifi_on
,I/BluetoothPbapService(10702): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService(10702): Autoconnection is available 
D/BluetoothSocket(10702): close() in, this: android.bluetooth.BluetoothSocket@22385299, channel: 19, state: LISTENING
D/BluetoothSocket(10702): close() this: android.bluetooth.BluetoothSocket@22385299, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ac1f861, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@367bf95emSocket: android.net.LocalSocket@3578013f impl:android.net.LocalSocketImpl@a33ea0c fd:FileDescriptor[72]
D/BluetoothSocket(10702): Closing mSocket: android.net.LocalSocket@3578013f impl:android.net.LocalSocketImpl@a33ea0c fd:FileDescriptor[72]
,D/BluetoothAdapterService(10702): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService(10702): terminating service from this receiver
,W/InputMethodManagerService( 3506): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3506): [BT Setting State] State =13
,I/jxcore-log(10630): Radios toggled
I/jxcore-log(10630): 
,I/jxcore-log(10630): ****TEST TOOK:  ms ****
I/jxcore-log(10630): 
I/jxcore-log(10630): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10630): 
,D/BluetoothTile( 3693):  onBluetoothStateChange:
E/WifiStateMachine( 3506): WifiStateMachine: Leaving Connected state
I/wpa_supplicant(10717): reset timer : RESET_TIMER 0
I/wpa_supplicant(10717): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant(10717): Skip scan - bUseNetwork false
E/WifiStateMachine( 3506): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3506): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3506): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3506): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothTile( 3693):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3693): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 3693):  handleUpdatestate:false name:null
I/SamsungIME( 4454): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 3693):  handleUpdatestate:false name:null
,D/STATUSBAR-QSTileView( 3693): onStateChanged: Bluetooth
,D/StatusBarManagerService( 3506): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,E/WifiStateMachine( 3506): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3506): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3506): do suspend true
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
D/StatusBarManagerService( 3506): setIconVisibility slot=bluetooth visible=false
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/PhoneStatusBar( 3693): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,D/WifiP2pService( 3506): InactiveState{ what=143375 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=143375 }
,E/Zygote  (12301): MountEmulatedStorage()
E/Zygote  (12301): v2
I/libpersona(12301): KNOX_SDCARD checking this for 1000
I/libpersona(12301): KNOX_SDCARD not a persona
,I/SELinux (12301): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3506): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=12301 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12301): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/BluetoothAdapterProperties(10702): onBluetoothDisable()
,D/SecContentProvider( 3506): uri = 3 selection = isDiscoverableEnabled
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,I/BluetoothAdapterState(10702): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
E/Netd    ( 2846): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/BluetoothAdapterProperties(10702): Scan Mode:20
,D/BluetoothAdapterState(10702): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif (10702): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif (10702): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif (10702): cmd socket is not created
E/BtOppRfcommListener(10702): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/WifiStateMachine( 3506): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3506): updateNetworkInfo()
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/bt-btm  (10702): btm_ble_start_auto_conn start : 0, 0
D/btif_config_util(10702): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/SELinux (12301): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/bt-btif (10702): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap(10702): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap(10702): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap(10702): L2CAP - PSM: 0x001b not found for deregistration
,I/WifiTrafficPoller( 3506): evaluateTrafficStatsPolling
,E/WifiConfigStore( 3506): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3506): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3506): updateNetworkInfo()
D/ConnectivityService( 3506): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine( 3506): scanCount==0 - aborting
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,E/WifiStateMachine( 3506): [1,453,391,072,262 ms] noteScanEnd no scan source
,D/WifiP2pService( 3506): InactiveState{ what=131204 }
,D/WifiP2pService( 3506): P2pEnabledState{ what=131204 }
,D/WifiP2pService( 3506): sending p2p connection changed broadcast: FAILED
,E/WifiStateMachine( 3506): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3506): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3506): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService( 3506): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524292
,D/EntConnectivity( 3506): Not allowed due to - mEnabled false
,D/ConnectivityService( 3506): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3506): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3506): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/WifiStateMachine( 3506): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiP2pService( 3506): sending p2p connection changed broadcast: DISCONNECTED
D/TelephonyNetworkFactory( 3979): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiScanningService( 3506): SCAN_AVAILABLE : 1
,D/CSLegacyTypeTracker( 3506): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/WifiScanningService( 3506): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService( 3506): SCAN_AVAILABLE : 1
D/ConnectivityService( 3506): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/RttService( 3506): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 4479): CM callback handler got msg 524292
,D/WifiDisplayController( 3506): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiDisplayController( 3506): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 3506): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,D/WifiDisplayAdapter( 3506): onP2pDisconnected
E/WifiStateMachine( 3506): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent( 3506): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine( 3506): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/IpRemoteDisplayController( 3506): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3506): WfdBridgeServer is already null
,D/WifiDisplayController( 3506): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 3506): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3506): disconnect
D/WifiDisplayController( 3506): updateConnection
D/WifiDisplayController( 3506): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiP2pService( 3506): P2pDisablingState
D/WifiDisplayAdapter( 3506): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService( 3506): P2pDisablingState{ what=147458 }
,D/WifiP2pService( 3506): p2p socket connection lost
,D/WifiP2pService( 3506): P2pDisabledState
,D/WifiP2pService( 3506): P2pDisabledState{ what=139283 }
D/WifiP2pService( 3506): DefaultState{ what=139283 }
,D/WifiDisplayController( 3506): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3506): onP2pDisconnected
D/IpRemoteDisplayController( 3506): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3506): WfdBridgeServer is already null
D/WifiDisplayController( 3506): Received list of peers.
,D/EntConnectivity( 3506): Not allowed due to - mEnabled false
E/WifiStateMachine( 3506): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - enter - invokeEnterMethods
,E/WifiStateMachine( 3506): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/ConnectivityService( 3506): updateNetworkInfo()
D/ConnectivityService( 3506): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3506): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
E/ConnectivityService( 3506): updateNetworkInfo()
E/WifiStateMachine( 3506): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3506): do suspend true
,D/BluetoothSocket(10702): close() in, this: android.bluetooth.BluetoothSocket@3ab27f55, channel: 5, state: LISTENING
D/BluetoothSocket(10702): close() this: android.bluetooth.BluetoothSocket@3ab27f55, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a4a7f86, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@318a4d6amSocket: android.net.LocalSocket@575725b impl:android.net.LocalSocketImpl@293b9af8 fd:FileDescriptor[74]
D/BluetoothSocket(10702): Closing mSocket: android.net.LocalSocket@575725b impl:android.net.LocalSocketImpl@293b9af8 fd:FileDescriptor[74]
,I/BtOppRfcommListener(10702): stopping Accept Thread
D/BluetoothSocket(10702): close() in, this: android.bluetooth.BluetoothSocket@b68bbd1, channel: 12, state: LISTENING
D/BluetoothSocket(10702): close() this: android.bluetooth.BluetoothSocket@b68bbd1, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f13afe0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1977d636mSocket: android.net.LocalSocket@3f0ed937 impl:android.net.LocalSocketImpl@170b6ea4 fd:FileDescriptor[78]
D/BluetoothSocket(10702): Closing mSocket: android.net.LocalSocket@3f0ed937 impl:android.net.LocalSocketImpl@170b6ea4 fd:FileDescriptor[78]
I/BtOppRfcommListener(10702): BluetoothSocket listen thread finished
,D/WifiP2pService( 3506): P2pDisabledState{ what=143375 }
,D/Tethering( 3506): MasterInitialState.processMessage what=3
D/WifiP2pService( 3506): DefaultState{ what=143375 }
D/SmartBondingService( 3506): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3506): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3506): getSBEnabled() enabled =false
D/SmartBondingService( 3506): getSBEnabled() enabled =false
D/SmartBondingService( 3506): getSBEnabled() enabled =false
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,V/NetworkStats( 3506): updateIfacesLocked()
,D/TimaKeyStoreProvider(12301): TimaSignature is unavailable
,D/ActivityThread(12301): Added TimaKeyStore provider
,D/SmartBondingService( 3506): getNetworkEnabled : wifi : true mobile : false
,V/NetworkStats( 3506): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
D/NetworkStatsFactory( 3506): UpdateStatsForKnox
V/NetworkStats( 3506): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/AllShareCastTile( 3693): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3506): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3693): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,E/WifiStateMachine( 3506): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,V/NetworkStats( 3506): performPollLocked() took 15ms
D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine( 3506): stopping supplicant
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
I/wpa_supplicant(10717): p2p0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3506): setWifiState: disabling
I/WifiTrafficPoller( 3506): evaluateTrafficStatsPolling
,D/ResourcesManager(12301): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,W/ResourcesManager(12301): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager(12301): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12301): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
D/SmartBondingService( 3506): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
W/ResourcesManager(12301): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/SecContentProvider2( 3506): uri = 20 selection = getPromptCredentialsEnabled
W/ResourcesManager(12301): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/SecContentProvider2( 3506): mCursor = null
W/ResourcesManager(12301): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12301): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/SmartBondingService( 3506): getNetworkEnabled : wifi : false mobile : false
D/SLocation( 3506): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3693): Wifi onReceive(0)
,D/STATUSBAR-QSTileView( 3693): onStateChanged: Wi-Fi
,D/HotspotTile( 3693): onReceive : 0, 0
E/WifiStateMachine( 3506): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3506): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/MySettingsProvider(12301): DatabaseHelper(Context context):DATABASE_VERSION=1
,E/SQLiteLog(12301): (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/MySettingsProvider(12301): onCreate():(mDB == null)? false:true  =true
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,I/wpa_supplicant(10717): Blacklist: Clear (all) 
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,W/ContextImpl(12301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/bt-l2cap(10702): HC lib lpm enable=0 return 0
W/bt-l2cap(10702): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap(10702): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap(10702): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap(10702): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap(10702): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap(10702): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap(10702): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap(10702): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif (10702): ag scb idx 1 not allocated
W/bt-btif (10702): ag scb idx 2 not allocated
E/bt-btif (10702): BTA AG is already disabled, ignoring ...
,D/bt_userial(10702): RX termination
W/bt_userial(10702): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial(10702): Leaving userial_read_thread()
D/bt_userial(10702): userial_close_reader Joined userial reader thread: 0
,D/bt_hwcfg(10702): hw_epilog_process
I/bt_userial_vendor(10702): device fd = 65 close
,I/GKI_LINUX(10702): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX(10702): GKI_exit_task 0 done
I/GKI_LINUX(10702): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState(10702): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode(10702): isSecureModeOn:false
D/BluetoothAdapterService(10702): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService(10702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.gatt.GattService
,D/BtGatt.DebugUtils(10702): handleDebugAction() action=null
W/BluetoothAdapterService(10702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.GattService(10702): Received stop request...Stopping profile...
,W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService(10702): stop()
D/BtGatt.AdvertiseManager(10702): advertise clients cleared
,I/wpa_supplicant(10717): p2p0: CTRL-EVENT-TERMINATING 
,W/BluetoothAdapterService(10702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/LocalBluetoothProfileManager(12301): PANU : true
D/LocalBluetoothProfileManager(12301): Adding local MAP profile
D/BluetoothMap(12301): Create BluetoothMap proxy object
,W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.a2dp.A2dpService
,I/wpa_supplicant(10717): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant(10717): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant(10717): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant(10717): wlan0: State: DISCONNECTED -> DISCONNECTED
,W/BluetoothAdapterService(10702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService(10702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/HeadsetService(10702): Received stop request...Stopping profile...
W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
,D/AudioService( 3506): onServiceDisconnected: Bluetooth profile: 1
,W/BluetoothAdapterService(10702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService(10702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService(10702): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService(10702): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService(10702): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService(10702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
W/ContextImpl(12301): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService(10702): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService(10702): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
D/Bluetoothsap(12301): bindService called to Bluetooth SAP Service
W/BluetoothAdapterService(10702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/LocalBluetoothProfileManager(12301): LocalBluetoothProfileManager construction complete
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10702): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService(10702): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState(10702): Stopping profile services that were post enabled
E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/AndroidRuntime(12308): 
D/AndroidRuntime(12308): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/A2dpService(10702): Received stop request...Stopping profile...
V/Avrcp   (10702): doQuit
D/A2dpStateMachine(10702): Exit Disconnected: -1
,D/AndroidRuntime(12308): CheckJNI is OFF
D/DockEventReceiver(12301): finishStartingService: stopping service
,D/AndroidRuntime(12308): readGMSProperty: start
D/AndroidRuntime(12308): readGMSProperty: already setted!!
D/Avrcp   (10702): Unregistering previous receiver
,D/BluetoothPan(12301): BluetoothPAN Proxy object connected
D/PanProfile(12301): Bluetooth service connected
,D/AndroidRuntime(12308): readGMSProperty: end
D/AndroidRuntime(12308): addProductProperty: start
D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
,D/BluetoothA2dp( 3506): Proxy object disconnected
D/AudioService( 3506): onServiceDisconnected: Bluetooth profile: 2
D/BluetoothA2dp( 4805): Proxy object disconnected
D/BluetoothNotiBroadcastReceiver(12301): onReceive
,D/BluetoothMap(12301): Proxy object connected
D/MapProfile(12301): Bluetooth service connected
D/Bluetoothsap(12301): BluetoothSAP Proxy object connected
,D/SapProfile(12301): Bluetooth service connected
D/Bluetoothsap(12301): getConnectedDevices()
,D/HidService(10702): Received stop request...Stopping profile...
D/HidService(10702): Stopping Bluetooth HidService
W/BluetoothHidServiceJni(10702): Cleaning up Bluetooth HID Interface...
W/bt-btif (10702): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni(10702): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
,E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(10702): Profile still running: com.android.bluetooth.hid.HidService
I/ActivityManager( 3506): Killing 11262:com.sec.knox.bridge/1000 (adj 13): bgCount ##31
D/HealthService(10702): Received stop request...Stopping profile...
D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
,W/BluetoothHeadsetServiceJni(10702): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni(10702): Cleaning up Bluetooth Handsfree callback object
,D/PanService(10702): Received stop request...Stopping profile...
D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
,D/BluetoothPan( 3506): BluetoothPAN Proxy object disconnected
,D/BluetoothPan(12301): BluetoothPAN Proxy object disconnected
D/BluetoothMapService(10702): Received stop request...Stopping profile...
,D/PanProfile(12301): Bluetooth service disconnected
,D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
,D/BluetoothMap(12301): Proxy object disconnected
,D/MapProfile(12301): Bluetooth service disconnected
,D/SapService(10702): Received stop request...Stopping profile...
D/SapService(10702): Stopping Bluetooth SapService
D/BluetoothAdapterService(10702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1265a4d9
E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(10702): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp(10702): Proxy object disconnected
D/BluetoothAdapterService(10702): Bluetooth A2dp source service disconnected
D/Bluetoothsap(12301): BluetoothSAP Proxy object disconnected
D/SapProfile(12301): Bluetooth service disconnected
I/GKI_LINUX(10702): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX(10702): GKI_exit_task 2 done
I/GKI_LINUX(10702): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   (10702): cleanup
,E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(10702): Profile still running: com.android.bluetooth.map.BluetoothMapService
,E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(10702): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni(10702): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni(10702): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(10702): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni(10702): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni(10702): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig(10702): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(10702): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(308651225)(10702): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni(10702): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni(10702): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterState(10702): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties(10702): Setting state to 10
I/BluetoothAdapterState(10702): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(10702): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10702): updateAdapterState state is 10
,D/BluetoothAdapterService(10702): Autoconnection is available 
D/BluetoothAdapterService(10702): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState(10702): Entering OffState
,D/BluetoothA2dp( 4805): onBluetoothStateChange: up=false
,D/AuthorizationBluetoothService( 4239): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothA2dp( 3506): onBluetoothStateChange: up=false
,D/BluetoothA2dp(10702): onBluetoothStateChange: up=false
I/Hs20UtilService( 6284): Starting #8
,I/Hs20UtilService( 6284): Message received 5007
,D/NearbySettings(12301): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings(12301): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings(12301): MountReceiver.onReceive - Create mPrefHandler
,D/BluetoothMap(12301): onBluetoothStateChange: up=false
,D/NearbySettings(12301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(12301): DMSUtil.isNetworkConnected - flag-null, state-null
,I/wpa_supplicant(10717): Blacklist: Clear (all) 
,I/NearbySettings(12301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/BluetoothPbap(12301): onBluetoothStateChange: up=false
,D/Bluetoothsap(12301): onBluetoothStateChange: up=false
D/Bluetoothsap(12301): Unbinding service...
,D/WifiService( 3506): New client listening to asynchronous messages
,D/BluetoothManagerService( 3506): Broadcasting onBluetoothServiceDown() to 12 receivers.
I/NearbySettings(12301): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(12301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(12301): MountReceiver.onReceive - Set preference state off
,V/NearbySettings(12301): MountReceiver.mPrefHandler - 7002
,D/BluetoothManagerService( 3506): Broadcasting onBluetoothServiceUp() to 0 receivers.
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12356): MountEmulatedStorage()
E/Zygote  (12356): v2
I/libpersona(12356): KNOX_SDCARD checking this for 10160
I/libpersona(12356): KNOX_SDCARD not a persona
,I/SELinux (12356): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3506): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.control.core.sync.scloud.ReceiverSignOut: pid=12356 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,I/SELinux (12356): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/AffinityControl(12308): AffinityControl: registerfunction enter
,E/SELinux (12356): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/InputMethodManagerService( 3506): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3506): [BT Setting State] State =10
I/InputMethodManagerService( 3506): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapter( 3693): 1023154555: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 3693):  onBluetoothPairedDevicesChanged:
,D/BluetoothAdapter( 3693): 1023154555: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 3693): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 3693): 1023154555: getState() :  mService = null. Returning STATE_OFF
,D/STATUSBAR-QSTileView( 3693): onStateChanged: Bluetooth
,D/BluetoothAdapter( 3693): 1023154555: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3693): 1023154555: getState() :  mService = null. Returning STATE_OFF
,I/SamsungIME( 4454): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
D/StatusBarManagerService( 3506): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3506): setIconVisibility slot=bluetooth visible=false
,V/BluetoothEventManager(12301): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/PhoneStatusBar( 3693): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,D/AndroidRuntime(12308): Calling main entry com.android.commands.pm.Pm
D/BluetoothAdapter( 4239): 78629962: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4239): 78629962: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX(10702): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX(10702): GKI_exit_task 1 done
I/GKI_LINUX(10702): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni(10702): cleanupNative: return from cleanup
,I/art     (10702): System.exit called, status: 0
I/AndroidRuntime(10702): VM exiting with result code 0, cleanup skipped.
,D/PackageManager( 3506): START PACKAGE DELETE: observer{768760762}
D/PackageManager( 3506): pkg{<packageName>}
D/PackageManager( 3506): user{0}
D/PackageManager( 3506): caller{2000}
D/PackageManager( 3506): flags{3}
D/PersonaManagerService( 3506): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3506): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3506): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3506): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3506): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager( 3506): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService( 3506): deletePackage- pkg:com.test.thalitest, edmuserId:0
,D/PackageManagerService( 3506): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy( 3506): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3506): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3506): !@killApplicatoin: 10594, uninstall pkg
,D/TimaKeyStoreProvider(12356): TimaSignature is unavailable
,I/ActivityManager( 3506): Force stopping com.test.thalitest appid=10594 user=-1: uninstall pkg
I/ActivityManager( 3506): Killing 10630:com.test.thalitest/u0a594 (adj 0): stop com.test.thalitest
,D/ActivityThread(12356): Added TimaKeyStore provider
,I/ActivityManager( 3506):   Force finishing activity ActivityRecord{3eefa0bc u0 com.test.thalitest/.MainActivity t25}
,W/PackageSettings( 3506): Skipping PackageSetting{17d3ab38 com.example.hello/10563} due to missing metadata
,E/JavaBinder( 3506): !!! FAILED BINDER TRANSACTION !!!
,I/SurfaceFlinger( 2850): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2850): id=12 Removed NainActivit (-2/8)
,D/ResourcesManager(12356): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/WifiService( 3506): Client connection lost with reason: 4
,D/PointerIcon( 3506): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3506): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3506): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3506): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 2850): id=12 Removed NainActivit (-2/8)
,I/ActivityManager( 3506): Process com.android.bluetooth (pid 10702)(adj 0) has died(300,1177)
,W/ResourcesManager(12356): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12356): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12356): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/ActivityManager( 3506): Force stopping com.test.thalitest appid=10594 user=0: pkg removed
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ConnectivityService( 3506): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader( 3506): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 8015): Explicit concurrent mark sweep GC freed 28360(1602KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.181ms total 42.459ms
,W/GeofencerStateMachine( 4239): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4454): mOCRHelper is null
,D/LWLocationManager(11688): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11688): getLastUiLocationId() : mLastUiLocationId = -100
,I/art     ( 4050): Explicit concurrent mark sweep GC freed 1725(85KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.450ms total 63.896ms
,W/ResourceType( 4945): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,W/ResourceType( 4945): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,V/Common  (12356): getScreenSize 1440 2560
,I/art     ( 4479): Explicit concurrent mark sweep GC freed 1944(77KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 31MB/39MB, paused 1.821ms total 93.101ms
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 5900): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/EnterpriseDeviceManagerService( 3506): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3506): Admin package name: com.google.android.gms
I/JAM     (12356): Load The ApaService JNI
,I/JAM     (12356): version: ProfessionalAudio_v1.0.b5
I/JAM     (12356): Try v1.0.b3 ...
,D/Spen    (12356): SpenSdk version level = 55
D/Spen    (12356): SpenSdk jar version = 3.0.243
D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/Zygote  (12378): MountEmulatedStorage()
,E/Zygote  (12378): v2
I/libpersona(12378): KNOX_SDCARD checking this for 10160
I/libpersona(12378): KNOX_SDCARD not a persona
,I/SELinux (12378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3506): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=12378 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,D/Spen    (12356): SpenSdk apk version = 3.0.235
D/Spen    (12356): Server UPDATE Check
,W/linker  (12356): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,I/SELinux (12378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/SPenError(12356): JNI_OnLoad
D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/JNI_Bitmap(12356): Init .. Done
D/SPenSpiDecoder(12356): JNI_OnLoad .. Done
D/SPenError(12356): JNI_OnLoad Success
D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,E/SELinux (12378): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PluginManager(12356): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(12356): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(12356): JNI_OnLoad
,D/Init_SPenSdk_Jni(12356): AndroidSDK: 21
D/Init_SPenSdk_Jni(12356): JNI_OnLoad .. Done
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/Model_ObjectBase_Jni(12356): JNI_OnLoad .. Done
,I/DBG_DM  ( 5900): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
D/Model_ObjectStroke_Jni(12356): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(12356): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni(12356): JNI_OnLoad .. Done
,D/Model_ObjectContainer_Jni(12356): JNI_OnLoad .. Done
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Model_PageDoc_Jni(12356): JNI_OnLoad .. Done
D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Books/Books.apk
,D/Model_NoteDoc_Jni(12356): check build type eng[0]
D/Model_NoteDoc_Jni(12356): JNI_OnLoad .. Done
,D/Model_NoteFile_Jni(12356): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(12356): JNI_OnLoad .. Done
D/Model   (12356): OnLoad class Done
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/spe_log (12356): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library(12356): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(12356): Canvas JNI_OnLoad enter!!
,D/SPen_Library(12356): Canvas JNI_OnLoad Success
D/SPen_Library(12356): TextView JNI_OnLoad enter!!
,D/SPen_Library(12356): TextView JNI_OnLoad Success
D/SPen_Library(12356): Text JNI_OnLoad enter!!
D/SPen_Library(12356): Text JNI_OnLoad Success
D/SPen_Library(12356): FontManager JNI_OnLoad enter!!
D/SPen_Library(12356): FontManager JNI_OnLoad Success
D/SPen_Library(12356): CapturePage JNI_OnLoad enter!!
D/SPen_Library(12356): CapturePage JNI_OnLoad Success
D/SPen_Library(12356): Multi JNI_OnLoad enter!!
,D/SPen_Library(12356): Multi JNI_OnLoad Success
D/SPen_Library(12356): Draw Engine JNI_OnLoad Success
,D/SPen_Library(12356): Brush JNI_OnLoad enter!!
,D/SPen_Library(12356): Brush JNI_OnLoad Success
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/SPen_Library(12356): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(12356): ChineseBrush JNI_OnLoad Success
,D/SPen_Library(12356): InkPen JNI_OnLoad enter!!
,D/SPen_Library(12356): InkPen JNI_OnLoad Success
,D/SPen_Library(12356): Marker JNI_OnLoad enter!!
W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/SPen_Library(12356): Marker JNI_OnLoad Success
,D/SPen_Library(12356): Pencil JNI_OnLoad enter!!
,D/SPen_Library(12356): Pencil JNI_OnLoad Success
,D/SPen_Library(12356): NativePen JNI_OnLoad enter!!
,D/SPen_Library(12356): NativePen JNI_OnLoad Success
,D/TimaKeyStoreProvider(12378): TimaSignature is unavailable
,D/SPen_Library(12356): MontblancFountainPen JNI_OnLoad enter!!
,I/art     ( 3506): Explicit concurrent mark sweep GC freed 47912(2MB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 49MB/65MB, paused 3.148ms total 178.927ms
D/SPen_Library(12356): MontblancFountainPen JNI_OnLoad Success
,D/ResourcesManager( 3506): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/SPen_Library(12356): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library(12356): MontblancCalligraphyPen JNI_OnLoad Success
,D/ActivityThread(12378): Added TimaKeyStore provider
,I/art     ( 3506): WaitForGcToComplete blocked for 105.887ms for cause Explicit
D/SPen_Library(12356): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(12356): MagicPen JNI_OnLoad Success
,D/SPen_Library(12356): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library(12356): ObliquePen JNI_OnLoad Success
D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/SPen_Library(12356): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(12356): FountainPen JNI_OnLoad Success
D/Spen    (12356): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(12356): SPenSdk_init2
D/Init_SPenSdk(12356): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(12356): Total S Pen SDK Directory Size = 0
D/Spen    (12356): initialize complete
,W/linker  (12356): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,I/SignOutReceiver(12356): NETWORK_STATE_CHANGED_ACTION
I/wpa_supplicant(10717): wlan0: CTRL-EVENT-TERMINATING 
D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/ActivityManager( 3506): Killing 10996:com.android.chrome/u0a90 (adj 13): bgCount ##31
,D/SecContentProvider2( 3506): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3506): mCursor = null
D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/WifiStateMachine( 3506): Supplicant connection lost
D/Tethering( 3506): InitialState.processMessage what=4
D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/Tethering( 3506): No numeric data
,D/ResourcesManager(12378): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/NearbySettings(12301): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,E/WifiStateMachine( 3506): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-HAL( 3506): callSECApiBoolean - ID [21]
,D/Tethering( 3506): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 3506): setWifiState: disabled
W/ResourcesManager(12378): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12378): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12378): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,V/NearbySettings(12301): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(12301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/HotspotTile( 3693): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
V/NetworkStats( 3506): performPollLocked(flags=0x1)
,D/HotspotTile( 3693): updateTetherState():false, false
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
D/NetworkStatsFactory( 3506): UpdateStatsForKnox
,I/NearbySettings(12301): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(12301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(12301): MountReceiver.onReceive - Set preference state off
,V/NearbySettings(12301): MountReceiver.mPrefHandler - 7002
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
V/NetworkStats( 3506): performPollLocked() took 9ms
D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
,D/RegisteredServicesCache( 3964): empty dynamic service
,D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3506): currentTimeMillis() cache hit
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 3693): Wifi onReceive(1)
D/HotspotTile( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 3693): onStateChanged: Wi-Fi
D/HotspotTile( 3693): onReceive : 1, 0
,W/Settings( 4239): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/Zygote  (12398): MountEmulatedStorage()
E/Zygote  (12398): v2
I/libpersona(12398): KNOX_SDCARD checking this for 10079
D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
I/libpersona(12398): KNOX_SDCARD not a persona
,I/SELinux (12398): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12398): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12398): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=12398 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/ActivityManager( 3506): Killing 10726:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 13): bgCount ##31
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11688): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SNoteProvider(12378): onCreate enableSnoteSync = true
,D/TimaKeyStoreProvider(12398): TimaSignature is unavailable
,D/ActivityThread(12398): Added TimaKeyStore provider
,D/SNoteProvider(12378): ===query=== 
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/ResourceType( 3506): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,V/Common  (12378): getScreenSize 1440 2560
D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(12398): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11688): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11688): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11688): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/FileShare-Server(12398): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
W/ResourcesManager( 3506): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/ResourcesManager(11688): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
W/ResourcesManager( 3506): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3506): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3506): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/art     ( 3506): Explicit concurrent mark sweep GC freed 11033(544KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.404ms total 193.984ms
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/ActivityManager( 3506): Killing 11277:com.google.android.apps.magazines/u0a136 (adj 13): bgCount ##31
D/ResourcesManager(11688): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/Hs20UtilService( 6284): Starting #9
,I/Hs20UtilService( 6284): Message received 5007
,D/NearbySettings(12301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(12301): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(12301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings(12301): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings(12301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(12301): MountReceiver.onReceive - Set preference state off
,V/NearbySettings(12301): MountReceiver.mPrefHandler - 7002
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,I/SignOutReceiver(12356): NETWORK_STATE_CHANGED_ACTION
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager(11688): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/Hs20UtilService( 6284): Starting #10
,I/Hs20UtilService( 6284): Message received 5011
D/SNoteProvider(12378): ===query=== 
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11688): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
D/PackageManager( 3506): delete codoeFile: 
,I/AASAUninstall( 3506):  com.test.thalitest not target!
,D/PackageManager( 3506): result of delete: 1{768760762}
,D/AndroidRuntime(12308): Shutting down VM
,D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,E/WifiStateMachine( 3506): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,E/WifiStateMachine( 3506): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3506): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/Zygote  (12416): MountEmulatedStorage()
E/Zygote  (12416): v2
I/libpersona(12416): KNOX_SDCARD checking this for 10127
I/libpersona(12416): KNOX_SDCARD not a persona
,I/SELinux (12416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3506): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12416 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12416): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/libprocessgroup( 3506): failed to kill pid 11277: No such process
,D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/TimaKeyStoreProvider(12416): TimaSignature is unavailable
,D/ActivityThread(12416): Added TimaKeyStore provider
,D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager(12416): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/Resources( 3506): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
D/UsbSettingsManager( 3506): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3506): onPackageRemoved : com.test.thalitest
D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/GpsLocationProvider( 3506): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/KeyguardWallpaperUpdator(12416): cancelUpdateWallpaper
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/KeyguardWallpaperUpdator(12416): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12416): stopCheckCategoryVersion
,D/ResourcesManager( 3506): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/SignOutReceiver(12356): WIFI_STATE_CHANGED_ACTION
,D/RCPManagerService( 3506): PackageReceiver onReceive()
,I/HarmonyEASService( 3506): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3506): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3506): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3506): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3506): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3506): uID is 10594
V/EnterpriseBillingPolicy( 3506): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3506): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3506): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3506): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3506): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3506): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3506): getBillingProfileForVpnEngine - end - null
D/ResourcesManager(11688): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/TaskPersister( 3506): removeObsoleteFile: deleting file=25_task.xml
,D/SmartBondingService( 3506): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SLocation( 3506): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/SmartBondingService( 3506): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,W/SLocation( 3506): No Active Data Connection
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/SmartBondingService( 3506): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3506): getSBEnabled() enabled =false
D/SmartBondingService( 3506): getSBEnabled() enabled =false
D/SmartBondingService( 3506): getSBEnabled() enabled =false
,D/SmartBondingService( 3506): getNetworkEnabled : wifi : false mobile : false
,D/SmartBondingService( 3506): getNetworkEnabled : wifi : false mobile : false
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Maps/Maps.apk
,I/ActivityManager( 3506): Killing 11345:com.samsung.android.sconnect/u0a150 (adj 13): bgCount ##31
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/ContextImpl(12301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/DockEventReceiver(12301): finishStartingService: stopping service
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/BluetoothNotiBroadcastReceiver(12301): onReceive
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/ApplicationPolicy( 3506): updateDataUsageMap
,I/ApplicationPolicy( 3506): updateDataUsageMap  idList is null 
,E/Zygote  (12433): MountEmulatedStorage()
D/ResourcesManager(11688): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/Zygote  (12433): v2
I/libpersona(12433): KNOX_SDCARD checking this for 1002
I/libpersona(12433): KNOX_SDCARD not a persona
,I/SELinux (12433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3506): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=12433 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux (12433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12433): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11688): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(11688): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/TimaKeyStoreProvider(12433): TimaSignature is unavailable
,D/ActivityThread(12433): Added TimaKeyStore provider
,D/ResourcesManager(12433): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(12433): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(12433): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni(12433): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig(12433): Adding GattService
D/BtSettings.ProfileConfig(12433): Adding HeadsetService
D/BtSettings.ProfileConfig(12433): Adding A2dpService
,D/BtSettings.ProfileConfig(12433): Adding HidService
D/BtSettings.ProfileConfig(12433): Adding HealthService
D/BtSettings.ProfileConfig(12433): Adding PanService
D/BtSettings.ProfileConfig(12433): Adding BluetoothMapService
D/BtSettings.ProfileConfig(12433): Adding SapService
D/BtSettings.ProfileConfig(12433): Adding HeadsetClientService
D/BtSettings.ProfileConfig(12433): Adding A2dpSinkService
,D/BtSettings.ProfileConfig(12433): Adding SapClientService
D/BtSettings.ProfileConfig(12433): Adding HidDevService
I/BtSettings.ProfileConfig(12433): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1,
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
,D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3506): ret = -1
D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,D/SettingsProvider( 3506): name = bt_svcst_com.broadcom.bt.service.sap.SapService
,D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed,
,D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
,D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
,D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3506): ret = -1
D/SettingsProvider( 3506): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider( 3506): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3506): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3506): selectionArgs: false
D/SettingsProvider( 3506): selectionArgs: 1002
D/SecContentProvider( 3506): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3506): ret = -1
,I/ActivityManager( 3506): Killing 10751:com.android.email/u0a178 (adj 13): bgCount ##31
,D/AuthorizationBluetoothService( 4239): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11688): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12450): MountEmulatedStorage()
,E/Zygote  (12450): v2
I/libpersona(12450): KNOX_SDCARD checking this for 10063
I/libpersona(12450): KNOX_SDCARD not a persona
,I/SELinux (12450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3506): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12450 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12450): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12450): TimaSignature is unavailable
,D/ActivityThread(12450): Added TimaKeyStore provider
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 977us total 25.715ms
,D/ResourcesManager(12450): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 624us total 19.069ms
,D/VRSetupWizardStub/PackageIntentReceiver(12450): onReceive()
,D/VRSetupWizardStub/PackageIntentReceiver(12450): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12450): packagename:com.test.thalitest
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 809us total 19.129ms
,I/KLMS-2.4.521: (11149): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 21 16:44:33 GMT+01:00 2016
,I/KLMS-2.4.521: (11149): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3506): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3506): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/UsbHostManager( 3506): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3506): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3506): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3506): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3506): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3506): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3506): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
,D/UsbHostManager( 3506): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3506): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
,D/UsbHostManager( 3506): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3506): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3506): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3506): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,I/KLMS-2.4.521: (11149): KLMSIntentService(): onCreate()
D/elm:14491(11586): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/KLMS-2.4.521: (11149): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11149): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11149): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/elm:14491(11586): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.4.521: (11149): KLMSIntentService(): PACKAGE_REMOVED
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (11149): KLMSIntentService(): listeningToPackageRemoved().START
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/elm:14491(11586): ElmAgentService : onCreate()
D/elm:14491(11586): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/KLMS-2.4.521: (11149): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/elm:14491(11586): MainReceiver.listeningToPackageRemoved()
D/elm:14491(11586): MDMBridge.getInstance()
D/elm:14491(11586): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(11586): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (12473): MountEmulatedStorage()
E/Zygote  (12473): v2
I/libpersona(12473): KNOX_SDCARD checking this for 1000
I/libpersona(12473): KNOX_SDCARD not a persona
,I/SELinux (12473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12473): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UsbHostManager( 3506): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3506): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,I/ActivityManager( 3506): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=12473 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12473): TimaSignature is unavailable
,D/ActivityThread(12473): Added TimaKeyStore provider
,I/EventHub( 3506): Removing device '/dev/input/event10' due to inotify event
,E/Zygote  (12489): MountEmulatedStorage()
E/Zygote  (12489): v2
I/libpersona(12489): KNOX_SDCARD checking this for 10050
I/libpersona(12489): KNOX_SDCARD not a persona
,I/SELinux (12489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12489): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3506): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12489 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/elm:14491(11586): ElmAgentService : onDestroy().
,I/EventHub( 3506): Removing device '/dev/input/event7' due to inotify event
,I/KLMS-2.4.521: (11149): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.4.521: (11149): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider(12489): TimaSignature is unavailable
,D/ActivityThread(12489): Added TimaKeyStore provider
,I/EventHub( 3506): Removing device '/dev/input/event8' due to inotify event
,D/com.sec.android.service.health.upgrade.UninstallReceiver(11504): onReceive()
,D/ResourcesManager(12473): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,I/com.sec.android.service.health.upgrade.UninstallReceiver(11504): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(11504): onReceive() : package name is not s health. Return !!!
,W/ResourcesManager(12473): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/EventHub( 3506): Removing device '/dev/input/event9' due to inotify event
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12489): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12489): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12489): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12489): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12489): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12489): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12489): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12489): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12489): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManager(12473):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3506):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3506): queryAllProviders():  providerCallBack is not register for 0
I/EventHub( 3506): Removing device '/dev/input/event11' due to inotify event
,E/Zygote  (12504): MountEmulatedStorage()
,E/Zygote  (12504): v2
I/libpersona(12504): KNOX_SDCARD checking this for 10183
I/libpersona(12504): KNOX_SDCARD not a persona
,I/SELinux (12504): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27,
,I/SELinux (12504): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3506): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12504 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,E/SELinux (12504): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3506): Removing device '/dev/input/event12' due to inotify event
,I/PowerManagerService( 3506): [PWL] Off : 180s ago
I/PowerManagerService( 3506): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3506): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3506): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=3506, ws=null) (elapsedTime=1663)
,D/LocationWidgetApplication(11688): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12504): TimaSignature is unavailable
,D/ActivityThread(12504): Added TimaKeyStore provider
,E/Zygote  (12519): MountEmulatedStorage()
,E/Zygote  (12519): v2
I/libpersona(12519): KNOX_SDCARD checking this for 10101
,I/libpersona(12519): KNOX_SDCARD not a persona
,I/EventHub( 3506): Removing device '/dev/input/event13' due to inotify event
,I/SELinux (12519): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12519): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3506): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12519 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12519): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3506): Killing 11132:com.sec.android.fotaclient/u0a12 (adj 13): bgCount ##31
,E/SQLiteLog(12489): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/SQLiteDatabase(12489): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase(12489): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12489): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12489): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12489): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12489): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12489): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12489): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12489): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12489): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12489): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12489): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12489): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12489): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12489): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12489): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase(12489): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase(12489): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12489): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12489): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12489): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12489): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12489): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12489): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12489): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12489): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12489): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12489): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12489): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3506): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3506): Removing device '/dev/input/event14' due to inotify event
,D/ResourcesManager(12504): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/Zygote  (12535): MountEmulatedStorage()
I/libpersona(12535): KNOX_SDCARD checking this for 1000
E/Zygote  (12535): v2
I/libpersona(12535): KNOX_SDCARD not a persona
,I/SELinux (12535): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12535): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3506): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12535 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12535): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PackageManager( 3506): findPreferredActivity: No PreferredActivities set
,D/TimaKeyStoreProvider(12519): TimaSignature is unavailable
,D/ActivityThread(12519): Added TimaKeyStore provider
,I/ActivityManager( 3506): Killing 11390:com.android.mms/u0a52 (adj 13): bgCount ##31
E/SQLiteLog(12504): (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12504): Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
E/SQLiteDatabase(12504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12504): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/SQLiteDatabase(12504): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/SQLiteDatabase(12504): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(12504): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(12504): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12504): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12504): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12504): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12504): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12504): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12504): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12504): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12504): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12504): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12504): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12504): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12504): Shutting down VM
,E/AndroidRuntime(12504): FATAL EXCEPTION: main
E/AndroidRuntime(12504): Process: com.samsung.android.provider.shootingmodeprovider, PID: 12504
E/AndroidRuntime(12504): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12504): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(12504): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(12504): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(12504): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(12504): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(12504): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12504): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12504): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12504): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12504): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12504): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12504): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12504): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12504): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/AndroidRuntime(12504): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/AndroidRuntime(12504): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(12504): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(12504): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(12504): 	... 11 more

```
