#### Test 57132760f6ec045_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
D/BatteryService( 3521): stay LED for fully charged
--------- beginning of main
D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(10993): 
D/AndroidRuntime(10993): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10993): CheckJNI is OFF
D/AndroidRuntime(10993): readGMSProperty: start
D/AndroidRuntime(10993): readGMSProperty: already setted!!
D/AndroidRuntime(10993): readGMSProperty: end
D/AndroidRuntime(10993): addProductProperty: start
E/AffinityControl(10993): AffinityControl: registerfunction enter
D/AndroidRuntime(10993): Calling main entry com.android.commands.am.Am
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
E/Zygote  (11008): MountEmulatedStorage()
I/libpersona(11008): KNOX_SDCARD checking this for 10598
E/Zygote  (11008): v2
I/libpersona(11008): KNOX_SDCARD not a persona
I/SELinux (11008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11008 uid=10598 gids={50598, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11008): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10993): Shutting down VM
D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11008): TimaSignature is unavailable
D/ActivityThread(11008): Added TimaKeyStore provider
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3521): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(11008): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (6/8)
V/ActivityThread( 3997): updateVisibility : ActivityRecord{f30aa0f token=android.os.BinderProxy@f62aac9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3997): onTrimMemory. Level: 20
I/WebViewFactory(11008): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11008): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11008): Loading: webviewchromium
I/LibraryLoader(11008): Time to load native libraries: 3 ms (timestamps 7327-7330)
I/LibraryLoader(11008): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11008): Binding Chromium to main looper Looper (main, tid 1) {3cd34587}
I/LibraryLoader(11008): Expected native library version number "",actual native library version number ""
I/chromium(11008): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11008): Initializing chromium process, renderers=0
W/art     (11008): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(11008): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium(11008): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
D/BluetoothAdapter(11008): 311291060: getState() :  mService = null. Returning STATE_OFF
I/chromium(11008): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11008): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/chromium(11008): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11008): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (11008): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(11008): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11008): CordovaWebView is running on device made by: samsung
W/art     (11008): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11008): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(11008): performCreate Call secproduct feature valuefalse
D/Activity(11008): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(11008): Render dirty regions requested: true
D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
I/SurfaceFlinger( 2849): id=12 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11008): Initialized EGL, version 1.4
I/OpenGLRenderer(11008): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1277669104 
D/OpenGLRenderer(11008): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11008): Enabling debug mode 0
D/mali_winsys(11008): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(11008): updateVisibility : ActivityRecord{3adfeae4 token=android.os.BinderProxy@3d57dffa {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/InputMethodManagerService( 3521): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3521): mDVFSHelper.release()
I/Timeline( 3521): Timeline: Activity_windows_visible id: ActivityRecord{39d15d3e u0 com.test.thalitest/.MainActivity t25} time:357768
W/IInputConnectionWrapper(11008): showStatusIcon on inactive InputConnection
I/Timeline(11008): Timeline: Activity_idle id: android.os.BinderProxy@3d57dffa time:357775
I/chromium(11008): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11008): 
D/JsMessageQueue(11008): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log(11008): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358473472
I/chromium(11008): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11008): Initializing JXcore engine
W/jxcore-log(11008): JXcore engine is ready
,E/auditd  ( 4538): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3521): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3521): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11008): Starting JXcore engine
,W/jxcore-log(11008): Platform android
W/jxcore-log(11008): 
W/jxcore-log(11008): Process ARCH arm
W/jxcore-log(11008): 
,I/jxcore-log(11008): JXcore Cordova bridge is ready!
I/jxcore-log(11008): 
W/jxcore-log(11008): JXcore engine is started
,I/jxcore-log(11008): Toggling radios to true
I/jxcore-log(11008): 
,D/BluetoothAdapter(11008): enable()
,W/ActivityManager( 3521): Permission Denial: getCurrentUser() from pid=11008, uid=10598 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 3521): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 3521): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11008, uid=10598 requires android.permission.INTERACT_ACROSS_USERS
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
,I/WifiManager(11008): packageName : com.test.thalitest
,D/SecContentProvider( 3521): uri = 18 selection = isWifiEnabled
D/WifiService( 3521): New client listening to asynchronous messages
D/SecContentProvider2( 3521): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3521): mCursor = null
,D/WifiService( 3521): setWifiEnabled: true pid=11008, uid=10598
E/WifiService( 3521): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3521): Permission Denial: getCurrentUser() from pid=11008, uid=10598 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3521): Failed getting userId using ActivityManagerNative
W/WifiService( 3521): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11008, uid=10598 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3521): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3521): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3521): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3521): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3521): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3521): name = wifi_on
,I/WifiService( 3521): disconnect: pid=11008, uid=10598
E/WifiStateMachine( 3521): setting operational mode to 1
,E/WifiHW  ( 3521): ##################### set firmware type 0 #####################
,I/jxcore-log(11008): Radios toggled
I/jxcore-log(11008): 
,I/WifiHW  ( 2845): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
I/jxcore-log(11008): My device name is: samsung-SM-N910C
I/jxcore-log(11008): 
,I/WifiHW  ( 2845): module is murata
E/WifiHW  ( 2845): ==========[WIFI] MURATA MODULE ===========
I/WifiHW  ( 2845): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_murata
E/WifiHW  ( 2845): TEMP_FAILURE_RETRY complete
D/SoftapController( 2845): Softap fwReload - Ok
,I/ActivityManager( 3521): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=11079 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,E/Zygote  (11079): MountEmulatedStorage()
I/libpersona(11079): KNOX_SDCARD checking this for 1002
E/Zygote  (11079): v2
I/libpersona(11079): KNOX_SDCARD not a persona
,I/SELinux (11079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11079): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CommandListener( 2845): Setting iface cfg
D/CommandListener( 2845): Trying to bring down wlan0
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/TimaKeyStoreProvider(11079): TimaSignature is unavailable
,D/ActivityThread(11079): Added TimaKeyStore provider
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(11079): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(11079): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni(11079): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig(11079): Adding GattService
,D/BtSettings.ProfileConfig(11079): Adding HeadsetService
D/BtSettings.ProfileConfig(11079): Adding A2dpService
D/BtSettings.ProfileConfig(11079): Adding HidService
D/BtSettings.ProfileConfig(11079): Adding HealthService
D/BtSettings.ProfileConfig(11079): Adding PanService
,D/BtSettings.ProfileConfig(11079): Adding BluetoothMapService
D/BtSettings.ProfileConfig(11079): Adding SapService
D/BtSettings.ProfileConfig(11079): Adding HeadsetClientService
D/BtSettings.ProfileConfig(11079): Adding A2dpSinkService
D/BtSettings.ProfileConfig(11079): Adding SapClientService
D/BtSettings.ProfileConfig(11079): Adding HidDevService
I/BtSettings.ProfileConfig(11079): *********Initializing Bluetooth Profile Settings*******
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
,D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.pan.PanService
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
W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider( 3521): name = bt_svcst_com.broadcom.bt.service.sap.SapService
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
,D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
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
,E/WifiHW  ( 3521): supplicant_name : p2p_supplicant
D/SettingsProvider( 3521): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
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
,D/BluetoothAdapterState(11079): make
,I/bluedroid(11079): init
I/BluetoothAdapterState(11079): Entering OffState
,I/bte_conf(11079): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf(11079): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config(11079): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf(11079): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif (11079): btif_fetch_local_ble_random_bdaddr
I/bluedroid(11079): get_profile_interface socket
I/bluedroid(11079): get_profile_interface map_client
D/BluetoothAdapterService(11079): checkAddrForIOP: Loading from conf
D/BluetoothAdapterService(11079): Inband Ring is supported
I/GKI_LINUX(11079): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties(11079): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(11079): populateRssiValuesNative
I/bluedroid(11079): getModelRssiValues
E/BluetoothServiceJni(11079): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(11079): modelRssiValuesCallback, low, mid, high = -75,-65,127
D/BluetoothAdapterProperties(11079): Name is: Note4-1
D/SettingsProvider( 3521): name = bluetooth_name
,I/bluedroid(11079): config_hci_snoop_log
,D/BluetoothManagerService( 3521): Broadcasting onBluetoothServiceUp() to 11 receivers.
,E/DevicePolicyManagerService( 3521): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3521): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 3521): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState(11079): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties(11079): Setting state to 11
I/BluetoothAdapterState(11079): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(11079): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(11079): updateAdapterState state is 11
,D/BluetoothAdapterService(11079): Autoconnection is available 
D/BluetoothAdapterService(11079): updateAdapterState prevState = 10newState = 11
D/BluetoothSecureManager(11079): getInstant: null
D/BluetoothSecureManager(11079): calling getMethod for getService
D/BluetoothSecureManager(11079): calling getService
W/InputMethodManagerService( 3521): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3521): [BT Setting State] State =11
,D/BluetoothSecureManager(11079): getService return binder: android.os.BinderProxy@1c755e7f
,D/BluetoothSecureManagerService( 3521): isSecureModeEnabled
D/BluetoothSecureManagerService( 3521): getSecureModeSetting, name: secure_mode_enable
D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3690): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BtConfig.SecureMode(11079): isSecureModeOn:false
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService(11079): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
I/SamsungIME( 4405): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService(11079): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService(11079): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/StatusBarManagerService( 3521): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,W/BluetoothAdapterService(11079): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/STATUSBAR-QSTileView( 3690): onStateChanged: Bluetooth
,W/BluetoothAdapterService(11079): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/StatusBarManagerService( 3521): setIconVisibility slot=bluetooth visible=false
W/BluetoothAdapterService(11079): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
I/wpa_supplicant(11094): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant(11094): Successfully initialized wpa_supplicant
I/SecureStorage(11094): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,W/BluetoothAdapterService(11079): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService(11079): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(11079): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(11079): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(11079): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService(11079): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine(11079): make
D/PhoneStatusBar( 3690): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
W/BluetoothAdapterService(11079): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine(11079): StableState(): Entering Off State
W/BluetoothAdapterService(11079): Not skipping com.android.bluetooth.gatt.GattService
,I/BtGatt.JNI(11079): classInitNative(L900): classInitNative: Success!
,D/BtGatt.DebugUtils(11079): handleDebugAction() action=null
W/BluetoothAdapterService(11079): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(11079): Not skipping com.android.bluetooth.hfp.HeadsetService
,V/[CarModeFW](10329): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
D/BtGatt.GattService(11079): Received start request. Starting profile...
D/BtGatt.GattService(11079): start()
I/bluedroid(11079): get_profile_interface gatt
D/BluetoothAdapterService(11079): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd34587
D/BtGatt.AdvertiseManager(11079): advertise manager created
,E/WifiStateMachine( 3521): setWifiState: enabling
,I/SecureStorage(11094): [INFO]: SPID(0x00000000)This device supports Secure Storage
,D/BluetoothAdapterService(11079): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd34587
I/SecureStorage( 2914): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 11094
I/SecureStorage( 2914): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
I/SecureStorage(11094): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant(11094): ssSupport state is = 1
I/wpa_supplicant(11094): >>>>> GET KEY, IV <<<<<
,W/BluetoothAdapterService(11079): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(11079): Not skipping com.android.bluetooth.a2dp.A2dpService
,I/SecureStorage(11094): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage( 2914): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 11094
I/SecureStorage( 2914): [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,W/BluetoothAdapterService(11079): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(11079): Not skipping com.android.bluetooth.hid.HidService
,D/BluetoothNotiBroadcastReceiver( 8399): onReceive
,E/WifiStateMachine( 3521): Supplicant start successful
D/WifiMonitor( 3521): startMonitoring(wlan0) with mConnected = false
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3521): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : false mobile : false
,W/BluetoothAdapterService(11079): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(11079): Not skipping com.android.bluetooth.hdp.HealthService
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-WifiQuickSettingButton( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3690): Wifi onReceive(2)
,D/STATUSBAR-QSTileView( 3690): onStateChanged: Wi-Fi
D/HotspotTile( 3690): onReceive : 2, 0
,W/BluetoothAdapterService(11079): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService(11079): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService(11079): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(11079): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService(11079): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(11079): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService(11079): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService(11079): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(11079): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(11079): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(11079): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(11079): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(11079): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig(11079): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService(11079): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,I/BluetoothAdapterState(11079): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
E/BluetoothAdapterService(1020478855)(11079): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/HeadsetService(11079): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni(11079): classInitNative: succeeds
D/HeadsetStateMachine(11079): make
,E/HeadsetStateMachine(11079): # of Max HF connection is 2
,I/bluedroid(11079): get_profile_interface handsfree
,I/DualScoManager(11079): Instantiating Dual Sco Manager
I/DualScoManager(11079): Set HeadsetServiceHelper
,D/BluetoothAtMessage(11079): createCMTIContentObservers
,D/SettingsProvider( 3521): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine(11079): Enter Disconnected: -2
,E/HeadsetStateMachine(11079): set to mRemoteBrsf = 0
D/BluetoothAdapterService(11079): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd34587
D/HeadsetStateMachine(11079): map size, before remove : 0
D/HeadsetStateMachine(11079): map size, after remove: 0
D/BluetoothA2dp( 3521): Proxy object connected
D/A2dpService(11079): Received start request. Starting profile...
D/BluetoothA2dp( 4802): Proxy object connected
I/BluetoothAvrcpServiceJni(11079): classInitNative: succeeds
V/Avrcp   (11079): make
V/Avrcp   (11079): Avrcp
I/bluedroid(11079): get_profile_interface avrcp
V/Avrcp   (11079): start
,E/RemoteController(11079): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   (11079): ++registerMediaPlayers++
,I/Avrcp   (11079): No of Audio players :: 2
I/Avrcp   (11079): App Package name is com.google.android.music
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/Avrcp   (11079): App pkg name is Google Play Music
I/Avrcp   (11079): Name::Google Play Music
V/Avrcp   (11079): MediaPlayerInfo: mPlayerId=1
I/Avrcp   (11079): App Package name is com.sec.android.app.music
D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   (11079): App pkg name is Music
,I/Avrcp   (11079): Name::Music
V/Avrcp   (11079): MediaPlayerInfo: mPlayerId=2
,I/Avrcp   (11079): No of Video players :: 1
I/Avrcp   (11079): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   (11079): Video App pkg name is Video Player
I/Avrcp   (11079): Name::Video Player
V/Avrcp   (11079): MediaPlayerInfo: mPlayerId=3
I/Avrcp   (11079): Add tempPlayer
V/Avrcp   (11079): MediaPlayerInfo: mPlayerId=4
I/Avrcp   (11079): Total no of players: 4
V/Avrcp   (11079): swapping the samsung player with 1st player
I/Avrcp   (11079):  Updating now playing list upon AVRCP Start
V/Avrcp   (11079): handleMessage, msg=207
D/BluetoothMediaBrowser(11079):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,V/Avrcp   (11079): CurrentAudioFocusPackageName is null
I/Avrcp   (11079): There is no currently selected player ,setting Samsung Music Player ID
I/Avrcp   (11079):  set player publishabilty with player id::1 toBePublished ::true
I/BluetoothA2dpServiceJni(11079): classInitNative: succeeds
D/A2dpStateMachine(11079): make
,I/bluedroid(11079): get_profile_interface a2dp
I/GKI_LINUX(11079): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif (11079): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService(11079): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd34587
,D/A2dpStateMachine(11079): Enter Disconnected: -2
I/BluetoothHidServiceJni(11079): classInitNative: succeeds
,D/HidService(11079): Received start request. Starting profile...
I/bluedroid(11079): get_profile_interface hidhost
D/HidService(11079): setHidService(): set to: null
D/BluetoothAdapterService(11079): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd34587
,I/BluetoothHealthServiceJni(11079): classInitNative: succeeds
,D/HealthService(11079): Received start request. Starting profile...
,D/AuthorizationBluetoothService( 4228): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/bluedroid(11079): get_profile_interface health
D/BluetoothAdapterService(11079): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd34587
,I/BluetoothPanServiceJni(11079): classInitNative(L105): succeeds
,I/Hs20UtilService( 6371): Starting #2
I/Hs20UtilService( 6371): Message received 5011
,D/BluetoothPan( 3521): BluetoothPAN Proxy object connected
,D/BluetoothMediaBrowser(11079): no now playing list
D/BluetoothMediaBrowser(11079):  getNowPlayingId now playing id : -1
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/Avrcp   (11079):  checkNowPlayingList start
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/PanService(11079): Received start request. Starting profile...
D/BluetoothPanServiceJni(11079): initializeNative(L110): pan
I/bluedroid(11079): get_profile_interface pan
D/BluetoothAdapterService(11079): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd34587
,D/BluetoothMapService(11079): Received start request. Starting profile...
,E/Zygote  (11113): MountEmulatedStorage()
E/Zygote  (11113): v2
I/libpersona(11113): KNOX_SDCARD checking this for 10127
I/libpersona(11113): KNOX_SDCARD not a persona
,I/SELinux (11113): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11113): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11113): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=11113 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11113): TimaSignature is unavailable
,D/ActivityThread(11113): Added TimaKeyStore provider
E/Zygote  (11128): MountEmulatedStorage()
E/Zygote  (11128): v2
I/libpersona(11128): KNOX_SDCARD checking this for 10178
I/libpersona(11128): KNOX_SDCARD not a persona
,I/SELinux (11128): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11128): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11128): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=11128 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ResourcesManager(11113): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/TimaKeyStoreProvider(11128): TimaSignature is unavailable
,D/ActivityThread(11128): Added TimaKeyStore provider
,D/ResourcesManager(11128): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(11128): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(11128): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11128): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11128): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(11128): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/KeyguardWallpaperUpdator(11113): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11113): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11113): stopCheckCategoryVersion
,I/SignOutReceiver( 8347): WIFI_STATE_CHANGED_ACTION
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11144): MountEmulatedStorage()
I/libpersona(11144): KNOX_SDCARD checking this for 1000
E/Zygote  (11144): v2
I/libpersona(11144): KNOX_SDCARD not a persona
,I/SELinux (11144): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11144): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11144): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=11144 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 10216:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11144): TimaSignature is unavailable
,D/ActivityThread(11144): Added TimaKeyStore provider
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/ResourcesManager(11144): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/BluetoothAdapterService(11079): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd34587
,I/BluetoothSAPServiceJni(11079): classInitNative(L204): succeeds
,D/SapService(11079): Received start request. Starting profile...
D/BluetoothSAPServiceJni(11079): initializeNative(L209): sap
I/bluedroid(11079): get_profile_interface sap
D/BluetoothAdapterService(11079): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd34587
,D/HeadsetStateMachine(11079): Try to query the phonestate on bind
,I/Telecom ( 3950): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 3950): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 3950): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 3950): Proxy not attached to service
,D/HeadsetStateMachine(11079): Proxy object connected
D/HeadsetPhoneState(11079): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState(11079): sendDeviceDataStateChanged
D/HeadsetStateMachine(11079): Disconnected process message: 11
D/HeadsetPhoneState(11079): Signal level : previous=0 curr=0
D/HeadsetStateMachine(11079): Disconnected process message: 18
V/HeadsetService(11079): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
E/BluetoothAdapterService(1020478855)(11079): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/HeadsetStateMachine(11079): Disconnected process message: 10
D/BluetoothA2dp(11079): Proxy object connected
D/BluetoothAdapterService(11079): Bluetooth A2dp source service connected
E/BluetoothAdapterService(1020478855)(11079): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/HeadsetPhoneState(11079): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
E/BluetoothAdapterService(1020478855)(11079): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/HeadsetStateMachine(11079): Disconnected process message: 11
E/BluetoothAdapterService(1020478855)(11079): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,E/Zygote  (11169): MountEmulatedStorage()
I/libpersona(11169): KNOX_SDCARD checking this for 10082
E/Zygote  (11169): v2
I/libpersona(11169): KNOX_SDCARD not a persona
,I/SELinux (11169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=11169 uid=10082 gids={50082, 9997} abi=armeabi-v7a
E/SELinux (11169): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11182): MountEmulatedStorage()
E/Zygote  (11182): v2
I/libpersona(11182): KNOX_SDCARD checking this for 10186
I/libpersona(11182): KNOX_SDCARD not a persona
,I/SELinux (11182): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc tv.peel.smartremote for broadcast tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver: pid=11182 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/SELinux (11182): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11182): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Killing 9353:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,E/BluetoothAdapterService(1020478855)(11079): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,D/TimaKeyStoreProvider(11169): TimaSignature is unavailable
,D/ActivityThread(11169): Added TimaKeyStore provider
I/ActivityManager( 3521): Killing 8456:com.android.mms/u0a52 (adj 13): bgCount ##31
,E/BluetoothAdapterService(1020478855)(11079): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,E/BluetoothAdapterService(1020478855)(11079): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState(11079): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid(11079): enable
,I/ActivityManager( 3521): Killing 10255:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,I/GKI_LINUX(11079): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid(11079): init
,I/bt_vendor(11079): init
I/bt_vnd_conf(11079): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf(11079): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial(11079): userial_init
,D/TimaKeyStoreProvider(11182): TimaSignature is unavailable
,D/ActivityThread(11182): Added TimaKeyStore provider
,D/CountryDetector( 3521): No listener is left
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 40631(2MB) AllocSpace objects, 48(768KB) LOS objects, 24% free, 48MB/64MB, paused 1.225ms total 84.693ms
,D/ResourcesManager(11169): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(11182): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,W/ResourcesManager(11182): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/bt_userial_vendor(11079): userial vendor open: opening /dev/ttySAC3
,I/bt_userial_vendor(11079): userial_vendor_open():UART is setup
I/bt_userial_vendor(11079): device fd = 65 open
,E/bt_hwcfg(11079): Start CFG HW, HCI reset
D/bt_userial(11079): Entering userial_read_thread()
,W/ActivityManager( 3521): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider(11169): onCreate
D/BadgeProvider(11169): DatabaseHelper
,E/bt_hwcfg(11079): Read Local Name after HCI reset
,D/BadgeProvider(11169): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(11169): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(11169): sendNotify, [notify] : null
D/BadgeProvider(11169): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(11169): update, [BadgeCount] : badgecount=0
D/BadgeProvider(11169): update, [UpdateCount] : 1
,D/Launcher.Model( 3997): reloadBadges entered.
,D/bt_hwcfg(11079): Chipset BCM43569A1
D/bt_hwcfg(11079): Target name = [BCM4358A1]
,I/bt_hwcfg(11079): module_type[murata].
I/bt_hwcfg(11079): module_type[murata] is invalid.
E/bt_hwcfg(11079): patchram path ORG . BCM4358A1
E/bt_hwcfg(11079): patchram path ORG .. BCM4358A1
E/bt_hwcfg(11079): patchram path ORG bcm4358A0_V0033.0000.hcd BCM4358A1
E/bt_hwcfg(11079): patchram path ORG bcm4358A1_V0044.0078.hcd BCM4358A1
I/bt_hwcfg(11079): patch(org) : bcm4358A1_V0044.0078.hcd
I/bt_hwcfg(11079): Found patchfile: /vendor/firmware/bcm4358A1_V0044.0078.hcd
E/bt_hwcfg(11079): ORG patchram base 0044
E/bt_hwcfg(11079): ORG patchram minor 0078
E/bt_hwcfg(11079): fw ver (org)44.78
E/bt_hwcfg(11079): Final Patchram is /vendor/firmware/bcm4358A1_V0044.0078.hcd
,I/bt_hwcfg(11079): Axi patch failure or not include AXI patching
,I/bt_hwcfg(11079): bt vendor lib: set UART baud 3000000
,I/SecureStorage(11094): [INFO]: SPID(0x00000005)Processing data has been completed
,I/WebViewFactory(11182): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11182): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11182): Loading: webviewchromium
,I/LibraryLoader(11182): Time to load native libraries: 5 ms (timestamps 9981-9986)
I/LibraryLoader(11182): Expected native library version number "",actual native library version number ""
,I/SecureStorage(11094): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,V/WebViewChromiumFactoryProvider(11182): Binding Chromium to main looper Looper (main, tid 1) {2bb31ba1}
,I/SecureStorage(11094): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/LibraryLoader(11182): Expected native library version number "",actual native library version number ""
I/chromium(11182): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 11094
I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(11094): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(11094): ssSupport state is = 1
,I/wpa_supplicant(11094): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant(11094): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(11094): SIM READ ERROR
I/wpa_supplicant(11094): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(11094): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(11094): SIM READ ERROR
I/wpa_supplicant(11094): Blacklist: Clear (all) 
,I/wpa_supplicant(11094): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(11094): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant(11094): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(11094): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant(11094): rfkill: Cannot open RFKILL control device
,I/BrowserStartupController(11182): Initializing chromium process, renderers=0
,W/art     (11182): Attempt to remove local handle scope entry from IRT, ignoring
,I/bt_hwcfg(11079): bt vendor lib: set UART baud 115200
I/bt_hwcfg(11079): FW Download delta = 519199
D/bt_hwcfg(11079): Settlement delay -- 100 ms
I/bt_hwcfg(11079): Setting fw settlement delay to 100 
,I/bt_hwcfg(11079): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg(11079): vendor lib fwcfg completed
,I/        (11079): BTE_InitTraceLevels -- TRC_HCI
I/        (11079): BTE_InitTraceLevels -- TRC_L2CAP
I/        (11079): BTE_InitTraceLevels -- TRC_RFCOMM
I/        (11079): BTE_InitTraceLevels -- TRC_AVDT
I/        (11079): BTE_InitTraceLevels -- TRC_AVRC
I/        (11079): BTE_InitTraceLevels -- TRC_A2D
I/        (11079): BTE_InitTraceLevels -- TRC_BNEP
I/        (11079): BTE_InitTraceLevels -- TRC_BTM
I/        (11079): BTE_InitTraceLevels -- TRC_GAP
I/        (11079): BTE_InitTraceLevels -- TRC_PAN
I/        (11079): BTE_InitTraceLevels -- TRC_SAP
I/        (11079): BTE_InitTraceLevels -- TRC_SDP
I/        (11079): BTE_InitTraceLevels -- TRC_GATT
I/        (11079): BTE_InitTraceLevels -- TRC_SMP
I/        (11079): BTE_InitTraceLevels -- TRC_BTAPP
I/        (11079): BTE_InitTraceLevels -- TRC_BTIF
I/        (11079): BTE_InitTraceLevels -- TRC_PROTOCOL
,E/Tethering( 3521): No numeric data
,I/wpa_supplicant(11094): wlan0: Setting scan request: 0 sec 100000 usec
,D/Tethering( 3521): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 3521): forceRefresh() from cache miss
,I/wpa_supplicant(11094): wlan0: State: DISCONNECTED -> DISCONNECTED
,W/chromium(11182): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
D/HotspotTile( 3690): onReceive : android.net.conn.TETHER_STATE_CHANGED
I/SecureStorage(11094): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
D/HotspotTile( 3690): updateTetherState():false, false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 3521): forceRefresh Fail.
V/NetworkStats( 3521): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3521): UpdateStatsForKnox
,V/NetworkStats( 3521): performPollLocked() took 2ms
,D/NtpTrustedTime( 3521): forceRefresh() from cache miss
,D/NtpTrustedTime( 3521): forceRefresh Fail.
,W/chromium(11182): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11182): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
I/chromium(11182): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
I/SecureStorage(11094): [INFO]: SPID(0x00000005)This device supports Secure Storage
I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 11094
I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,I/SecureStorage(11094): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(11094): ssSupport state is = 1
,I/SecureStorage(11094): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,W/bt-l2cap(11079): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  (11079): BTM_SecRegister:p_cb_info->p_le_callback == 0xb39eb9e1 
E/bt-btm  (11079): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb39eb9e1 
I/SecureStorage(11094): [INFO]: SPID(0x00000005)This device supports Secure Storage
I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 11094
I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(11094): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(11094): ssSupport state is = 1
I/wpa_supplicant(11094): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(11094): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(11094): SIM READ ERROR
I/wpa_supplicant(11094): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant(11094): nl80211: Could not configure driver mode
E/wpa_supplicant(11094): p2p0: Failed to initialize driver interface
I/wpa_supplicant(11094): Blacklist: Clear (all) 
,I/SecureStorage(11094): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(11094): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 11094
I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(11094): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(11094): ssSupport state is = 1
I/SecureStorage(11094): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(11094): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 11094
I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(11094): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(11094): ssSupport state is = 1
I/wpa_supplicant(11094): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(11094): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(11094): SIM READ ERROR
I/wpa_supplicant(11094): rfkill: Cannot open RFKILL control device
,W/chromium(11182): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11182): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/wpa_supplicant(11094): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant(11094): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,W/art     (11182): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11182): onDetachedFromWindow called when already detached. Ignoring
,I/wpa_supplicant(11094): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant(11094): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant(11094): Skip scan - bUseNetwork false
,E/WifiStateMachine( 3521): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,E/WifiStateMachine( 3521): setSuspendOptimizations: 2 true
E/WifiStateMachine( 3521): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine( 3521): Supplicant connection established
,D/WifiNative-HAL( 3521): callSECApiBoolean - ID [21]
I/wpa_supplicant(11094): HOTSPOT20_ENABLE called
I/wpa_supplicant(11094): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(11094): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(11094): SIM READ ERROR
I/wpa_supplicant(11094): Blacklist: Clear (all) 
,I/wpa_supplicant(11094): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant(11094): Skip scan - bUseNetwork false
E/WifiStateMachine( 3521): setWifiState: enabled
,D/WifiNative-HAL( 3521): callSECApiInt - ID [210]
,D/WifiConfigStore( 3521): Loading config and enabling all networks 
,D/BluetoothAdapterProperties(11079): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3521): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,E/bt-btif (11079): Calling BTA_HhEnable
,E/bt-btif (11079): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties(11079): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(11079): populateRssiValuesNative
I/bluedroid(11079): getModelRssiValues
E/BluetoothServiceJni(11079): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(11079): modelRssiValuesCallback, low, mid, high = -75,-65,127
,D/BluetoothAdapterProperties(11079): Name is: Note4-1
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/HotspotTile( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3690): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 3690): onStateChanged: Wi-Fi
D/BluetoothAdapterProperties(11079): Scan Mode:20
D/BluetoothAdapterProperties(11079): Discoverable Timeout:120
D/SettingsProvider( 3521): name = bluetooth_name
D/BluetoothAdapterProperties(11079): LE Address is:E0:B7:20:28:C5:81
E/bt-btif (11079): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif (11079): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
D/HotspotTile( 3690): onReceive : 3, 0
E/bt-btif (11079): btif_sock_init: !radio_req && !rfc_init
E/bt-btif (11079): btif_sock_init: !vhci_init
D/IOP_DB_BT(11079): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT(11079): db_open: db_open : handle 3025473552l, read 14063 bytes onto local cache
D/IOP_DB_BT(11079): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT(11079): db_query: result 1
I/        (11079): iop_db_open: iop_db_open status 0
,D/bte_conf(11079): Device ID record 1 : primary
D/bte_conf(11079):   vendorId            = 0075
D/bte_conf(11079):   vendorIdSource      = 0001
D/bte_conf(11079):   product             = 0100
D/bte_conf(11079):   version             = 0200
D/bte_conf(11079):   clientExecutableURL = 
D/bte_conf(11079):   serviceDescription  = 
D/bte_conf(11079):   documentationURL    = 
D/bte_conf(11079): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni(11079): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState(11079): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties(11079): ScanMode =  20
D/BluetoothAdapterProperties(11079): State =  11
,D/SecContentProvider( 3521): uri = 3 selection = isDiscoverableEnabled
D/BluetoothAdapterProperties(11079): Setting state to 12
I/BluetoothAdapterState(11079): Bluetooth adapter state changed: 11-> 12
E/WifiConfigStore( 3521): Not a HS20
,D/BluetoothAdapterProperties(11079): Scan Mode:21
D/BluetoothAdapterProperties(11079): Discoverable Timeout:120
E/WifiConfigStore( 3521): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/SettingsProvider( 3521): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1002
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService(11079): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(11079): updateAdapterState state is 12
,D/BluetoothAdapterService(11079): Autoconnection is available 
D/BluetoothAdapterService(11079): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService(11079): starting service from this receiver
,I/BluetoothAdapterState(11079): Entering On State from state = 11
,D/BluetoothA2dp(11079): onBluetoothStateChange: up=true
,I/WifiStateMachine( 3521): update LTECoexState:0
D/WifiNative-HAL( 3521): callSECApiInt - ID [65]
,D/BluetoothA2dp( 4802): onBluetoothStateChange: up=true
,D/WifiNative-HAL( 3521): callSECApiBoolean - ID [13]
I/wpa_supplicant(11094): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant(11094): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant(11094): reset timer : RESET_TIMER 0
I/wpa_supplicant(11094): P2P: Current p2p state = IDLE
I/wpa_supplicant(11094): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant(11094): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant(11094): First Scan Start
,D/BluetoothA2dp( 3521): onBluetoothStateChange: up=true
,I/ActivityManager( 3521): Killing 10271:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,I/BluetoothPbapService(11079): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,I/wpa_supplicant(11094): Scan requested (ret=0) - scan timeout 30 seconds
,E/bt_h4   (11079): vendor lib postload completed
,W/InputMethodManagerService( 3521): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3521): [BT Setting State] State =12
I/InputMethodManagerService( 3521): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/WifiNative-HAL( 3521): Setting external_sim to 1
,D/WifiStateMachine( 3521): Setting OUI to DA-A1-19
I/WifiNative-HAL( 3521): startHal
E/wifi    ( 3521): getStaticLongField sWifiHalHandle 0x8fa2585c
D/wifi    ( 3521): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x402112
I/WifiNative-HAL( 3521): Could not start hal
,D/BluetoothTile( 3690):  onBluetoothStateChange:
,E/WifiStateMachine( 3521): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,D/BluetoothHeadset( 3950): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@270ffcb9, true
D/BluetoothHeadset( 3950): registerMessageListener
D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3690): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
I/SamsungIME( 4405): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
E/WifiStateMachine( 3521): Attempting to reconnect to wifi network ..
E/native  ( 3521): do suspend true
,D/WifiP2pService( 3521): P2pDisabledState{ what=131203 }
,D/CommandListener( 2845): Setting iface cfg
D/CommandListener( 2845): Trying to bring up p2p0
,D/WifiMonitor( 3521): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 3521): P2pEnablingState
D/WifiP2pService( 3521): P2pEnablingState{ what=147457 }
,D/WifiP2pService( 3521): P2p socket connection successful
D/WifiP2pService( 3521): P2pEnabledState
,D/HeadsetService(11079): registerMessageListener
,D/HeadsetService(11079): registerMessageListener
D/HeadsetStateMachine(11079): Disconnected process message: 70
D/HeadsetStateMachine(11079): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@17d33d62
I/Telecom ( 3950): BluetoothPhoneService: updateHeadsetWithCallState
I/Telecom ( 3950): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/StatusBarManagerService( 3521): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
D/StatusBarManagerService( 3521): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 3690): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
E/WifiStateMachine( 3521): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - currTime: 1453758461801
D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
V/[CarModeFW](10329): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
D/WifiP2pService( 3521): sending p2p connection changed broadcast: IDLE
,D/BluetoothTile( 3690):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 3690): onStateChanged: Bluetooth
D/WifiDisplayController( 3521): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
E/WifiStateMachine( 3521): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/WifiScanningService( 3521): SCAN_AVAILABLE : 3
D/WifiScanningService( 3521): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 3521): SCAN_AVAILABLE : 3
D/RttService( 3521): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiNative-HAL( 3521): startHal
E/wifi    ( 3521): getStaticLongField sWifiHalHandle 0x8e7dd98c
D/wifi    ( 3521): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x6020be
I/WifiNative-HAL( 3521): Could not start hal
E/WifiStateMachine( 3521): set country code pl
E/WifiScanningService( 3521): could not start HAL
D/[CarModeFW](10329): ConnectivityManager-handleMessage INITIAL_STATE_ON
,D/WifiP2pService( 3521): create mNetworkAgent
,D/WifiDisplayController( 3521): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3521): disconnect
D/HeadsetStateMachine(11079): Disconnected process message: 9
D/WifiDisplayController( 3521): updateConnection
D/WifiDisplayController( 3521): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayController( 3521): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/HeadsetStateMachine(11079): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/Hs20UtilService( 6371): Starting #3
,I/Hs20UtilService( 6371): Message received 5011
,I/WifiStateMachine( 3521): callSECApi what=207
,I/AudioHardwareTinyALSA( 2856): setParameters(A2dpSuspended=false)
E/HeadsetStateMachine(11079): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/AllShareCastTile( 3690): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3690): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
I/BluetoothPbapService(11079): Handler(): got msg=1
D/KeyguardWallpaperUpdator(11113): cancelUpdateWallpaper
D/SecContentProvider( 3521): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/KeyguardWallpaperUpdator(11113): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11113): stopCheckCategoryVersion
I/SignOutReceiver( 8347): WIFI_STATE_CHANGED_ACTION
V/BluetoothPbapService(11079): PBAP Service initSocket try: 0
W/BluetoothAdapter(11079): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 3521): Broadcasting onBluetoothServiceUp() to 0 receivers.
D/BluetoothSocket(11079): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket(11079): bindListen(), new LocalSocket 
D/BluetoothSocket(11079): bindListen(), new LocalSocket.getInputStream() 
D/ConnectivityService( 3521): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/BluetoothSocket(11079): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32bcdae
D/BluetoothSocket(11079): channel: 19
D/BluetoothPbapService(11079): PBAP Socket is BluetoothServerSocket
D/ConnectivityService( 3521): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/CSLegacyTypeTracker( 3521): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
D/BluetoothMapMasInstance(11079): set MAP SDP message type : 1
I/wpa_supplicant(11094): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
E/WifiStateMachine( 3521): set frequency band 0
W/BluetoothAdapter(11079): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket(11079): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket(11079): bindListen(), new LocalSocket 
D/BluetoothSocket(11079): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11079): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34e5c74f
D/BluetoothSocket(11079): channel: 5
,W/ContextImpl( 8399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/wpa_supplicant(11094): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine( 3521): setDetailed state send new extra info
,D/WifiNative-HAL( 3521): p2pGetDeviceAddress
D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,D/WifiNative-HAL( 3521): p2pGetDeviceAddress returning 92:b6:86:43:73:1c
D/WifiP2pService( 3521): DeviceAddress: 92:73:1c
D/LocalBluetoothProfileManager( 8399): Adding local A2DP profile
D/WifiDisplayController( 3521): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note4-1
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
D/LocalBluetoothProfileManager( 8399): Adding local HEADSET profile
E/BluetoothHeadset( 8399): BTStateChangeCB is registed
E/WifiStateMachine( 3521): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL( 3521): callSECStringApiVoid - ID [215]
E/WifiNative-HAL( 3521): invaild command id : 215
D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
E/BluetoothHeadset( 8399): BluetoothHeadset service is binded
,D/WifiP2pService( 3521): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 3521): InactiveState
E/ConnectivityService( 3521): updateNetworkInfo()
D/WifiP2pService( 3521): InactiveState{ what=143376 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143376 }
,W/ContextImpl( 8399): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,I/wpa_supplicant(11094): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
D/Bluetoothsap( 8399): bindService called to Bluetooth SAP Service
,D/WifiP2pService( 3521): InactiveState{ what=143376 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143376 }
,D/LocalBluetoothProfileManager( 8399): PANU : true
D/LocalBluetoothProfileManager( 8399): Adding local MAP profile
,D/BluetoothMap( 8399): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 8399): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 8399): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 8399): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 8399): onReceive
,D/BluetoothA2dp( 8399): Proxy object connected
D/A2dpProfile( 8399): Bluetooth service connected
,D/BluetoothAdapterService(11079): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd34587
D/BtConfig.SecureMode(11079): isSecureModeOn:false
,D/HeadsetProfile( 8399): Bluetooth service connected
,D/Bluetoothsap( 8399): BluetoothSAP Proxy object connected
D/SapProfile( 8399): Bluetooth service connected
D/Bluetoothsap( 8399): getConnectedDevices()
D/AuthorizationBluetoothService( 4228): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothInputDevice( 8399): Proxy object connected
D/HidProfile( 8399): Bluetooth service connected
,D/BluetoothPan( 8399): BluetoothPAN Proxy object connected
D/PanProfile( 8399): Bluetooth service connected
,D/BluetoothMap( 8399): Proxy object connected
D/MapProfile( 8399): Bluetooth service connected
D/BluetoothPbap( 8399): Proxy object connected
D/PbapServerProfile( 8399): Bluetooth service connected
,D/NearbySettings( 8399): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8399): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8399): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8399): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 8399): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8399): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/SecContentProvider( 3521): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/WifiService( 3521): New client listening to asynchronous messages
,I/NearbySettings( 8399): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8399): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8399): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8399): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11276): MountEmulatedStorage()
I/libpersona(11276): KNOX_SDCARD checking this for 10079
E/Zygote  (11276): v2
I/libpersona(11276): KNOX_SDCARD not a persona
,I/SELinux (11276): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11276): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=11276 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11276): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BluetoothAdapter(11079): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11079): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
D/BluetoothSocket(11079): bindListen(), new LocalSocket 
D/BluetoothSocket(11079): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11079): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@313dd161
D/BluetoothSocket(11079): channel: 12
I/BtOppRfcommListener(11079): Accept thread started.
,D/TimaKeyStoreProvider(11276): TimaSignature is unavailable
,D/ActivityThread(11276): Added TimaKeyStore provider
,D/ResourcesManager(11276): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(11276): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 3521): Killing 10289:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,I/wpa_supplicant(11094): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant(11094): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant(11094): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant(11094): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant(11094): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3521): [1,453,758,462,344 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3521): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1e05d6ae sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/wpa_supplicant(11094): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant(11094): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant(11094): Associated with C0.AA.48
E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3521): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/wpa_supplicant(11094): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant(11094): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/wpa_supplicant(11094): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant(11094): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant(11094): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant(11094): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(11094): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant(11094): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant(11094): Blacklist: Clear (temp) 
I/wpa_supplicant(11094): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3521): Network connection established
,D/WifiNative-HAL( 3521): callSECApiVoid - ID [50]
E/WifiStateMachine( 3521): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3521): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3521): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine( 3521): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine( 3521): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3521): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 6371): Starting #4
,E/WifiStateMachine( 3521): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine( 3521): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3521): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Hs20UtilService( 6371): Message received 5007
,D/NearbySettings( 8399): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8399): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8399): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8399): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8399): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8399): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8399): MountReceiver.mPrefHandler - 7002
,D/CommandListener( 2845): Setting iface cfg
,I/SignOutReceiver( 8347): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3521): Start Dhcp Watchdog 1
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,E/WifiStateMachine( 3521): Force RSSI Broadcast 1/3
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3521): do suspend false
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/SecContentProvider2( 3521): mCursor = null
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,E/dhcpcd  (11294): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11294): version 5.5.6 starting
,E/dhcpcd  (11294): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11294): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11294): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11294): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (11294): bssid match
,I/dhcpcd  (11294): wlan0: rebinding lease of 192.168.1.124
,I/jxcore-log(11008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11008): 
,I/jxcore-log(11008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11008): 
,I/jxcore-log(11008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11008): 
,I/jxcore-log(11008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11008): 
,I/jxcore-log(11008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11008): 
,I/jxcore-log(11008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11008): 
,I/jxcore-log(11008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11008): 
,I/jxcore-log(11008): Test app app.js loaded
I/jxcore-log(11008): 
I/chromium(11008): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/dhcpcd  (11294): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
I/dhcpcd  (11294): wlan0: leased 192.168.1.124 for 86400 seconds
E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  ( 3521): do suspend true
,D/WifiP2pService( 3521): InactiveState{ what=143375 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3521): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3521): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine( 3521): Not connected state, yet.
,E/WifiStateMachine( 3521): VerifyingLinkState enter
,D/WifiStateMachine( 3521): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine( 3521): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3521): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3521): callSECApiInt - ID [210]
,E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3521): updateNetworkInfo()
,D/ConnectivityService( 3521): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 3521): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 3521): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3521): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3521): Now, connected state.
E/WifiStateMachine( 3521): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/ConnectivityService( 3521): Adding Route [fe80::/64 -> :: wlan0] to network 502
,I/Hs20UtilService( 6371): Starting #5
E/WifiStateMachine( 3521): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService( 3521): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
I/Hs20UtilService( 6371): Message received 5007
I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,D/ConnectivityService( 3521): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,E/ConnectivityService( 3521): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,D/NearbySettings( 8399): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8399): MountReceiver.onReceive - Keep current state
,E/WifiStateMachine( 3521): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3521): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3521): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3521): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/SignOutReceiver( 8347): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 6371): Starting #6
,I/Hs20UtilService( 6371): Message received 5007
,D/NearbySettings( 8399): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8399): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8399): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8399): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8399): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8399): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8399): MountReceiver.mPrefHandler - 7002
,V/        ( 2845): QcRouteController
,I/SignOutReceiver( 8347): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 6371): Starting #7
I/Hs20UtilService( 6371): Message received 5007
,V/        ( 2845): QcRouteController
,D/NearbySettings( 8399): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8399): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3521): callSECApi what=220
D/WifiStateMachine( 3521): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService( 3521): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService( 3521): LTETest block dns file not exists
,D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,E/ConnectivityService( 3521): updateNetworkInfo()
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3521): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3521): rematching NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Checking http://clients3.google.com/generate_204 on "NG700"
,I/System.out( 3521): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3521): (HTTPLog)-Static: isShipBuild true
I/System.out( 3521): (HTTPLog)-Thread-189-490597863: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 3521): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
,D/ConnectivityService( 3521):    accepting network in place of null
,D/ConnectivityService( 3521): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,D/TelephonyNetworkFactory( 3978): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3521): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3521): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3521): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering( 3521): MasterInitialState.processMessage what=3
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,V/NetworkStats( 3521): updateIfacesLocked()
V/NetworkStats( 3521): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3521): forceRefresh() from cache miss
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
D/EntConnectivity( 3521): Not allowed due to - mEnabled false
,D/NetworkStatsFactory( 3521): UpdateStatsForKnox
D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,D/ConnectivityService( 3521): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,V/NetworkStats( 3521): performPollLocked() took 5ms
,I/SignOutReceiver( 8347): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 4464): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3690): updateDataNetType()
D/StatusBar.NetworkController( 3690): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3690): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3690): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/SurfaceFlinger( 2849): id=13 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3521): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521
,D/mali_winsys( 3690): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/System.out( 3521): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NtpTrustedTime( 3521): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1453758471151 mCachedNtpElapsedRealtime : 363821 mCachedNtpCertainty : 12
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 25 Jan 2016 21:47:51 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453758464888], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453758464803]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Validated
,D/ConnectivityService( 3521): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 3521): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3521): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 3521): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524290
,D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 4464): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3690): updateDataNetType()
D/StatusBar.NetworkController( 3690): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3690): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3690): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService( 3521): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
,V/        ( 2845): QcRouteController
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
,D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524295
D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 4464): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 4464): CM callback handler got msg 524295
,D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3521): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3521): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11008): setDiscoveryMode: Mode set to BLE
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,I/jxcore-log(11008): BLE advertisement is supported
I/jxcore-log(11008): 
,D/AlarmManagerService( 3521): Setting time of day to sec=1453758471
D/AlarmManagerService( 3521): Trying to open a file
,D/AlarmManagerService( 3521): File Open Success
,D/AlarmManagerService( 3521): File Close Success
I/AlarmManagerService( 3521): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 3521): waitForAlarm result :65536
,I/DBG_DM  ( 5942): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 5942): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 5942): [IlIIlIIlIllllIlllIII(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/WifiStateMachine( 3521): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,I/DBG_DM  ( 5942): [IlIlllIlllllIlIllllI(403/llllllIllIlIlllIIlIl)] Check completed.
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_SET
,D/SettingsProvider( 3521): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10060
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,I/DBG_DM  ( 5942): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/KeyguardEffectViewUtil( 3690): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3690): isStrongPowerSavingMode() :false
,D/KeyguardEffectViewController( 3690): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3690): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3690): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{11613afa G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3690): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{1dba78ab V.E..... ......I. 0,0-0,0}
,D/VisualEffectParticleEffect( 3690): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{11613afa G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3690): clearEffect
D/WallpaperWidget( 3690): setLockScreenWallpaper()
,D/KeyguardEffectViewUtil( 3690): getCurrentWallpaper() mWallpaperPath :null
,W/Settings( 3521): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,W/SEC_DRM_PLUGIN_Playready( 2854): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1453758465 after conversion: 1453758465
W/SEC_DRM_PLUGIN_Playready( 2854): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1453758471 after conversion: 1453758471
,I/DBG_DM  ( 5942): [IIlIIIlllllIIlIIIlII(72/llllIIIllIlIIIIllllI)] 
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,E/Zygote  (11395): MountEmulatedStorage()
E/Zygote  (11395): v2
I/libpersona(11395): KNOX_SDCARD checking this for 1000
I/libpersona(11395): KNOX_SDCARD not a persona
,I/SELinux (11395): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11395 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (11395): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11395): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 5942): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 5942): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 5942): [IlIIlIIlIllllIlllIII(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 5942): [IlIIlIIlIllllIlllIII(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 5942): [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 5942): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,D/TimaKeyStoreProvider(11395): TimaSignature is unavailable
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(502/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,D/ActivityThread(11395): Added TimaKeyStore provider
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,D/ResourcesManager(11395): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 5942): [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@194c8629
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_LOG(11395): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11395): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11395): new DMDBOpenHelper instance
,I/GoogleURLConnFactory( 4228): Using platform SSLCertificateSocketFactory
,E/Zygote  (11414): MountEmulatedStorage()
E/Zygote  (11414): v2
I/libpersona(11414): KNOX_SDCARD checking this for 10090
I/libpersona(11414): KNOX_SDCARD not a persona
,I/SELinux (11414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11414): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=11414 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/appmanager(:<default>):QuickExperimentControllerImpl(10565): Exposure of experiment com.facebook.http.g.an@25433376 occurred when no user was logged in
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,W/appmanager(:<default>):QuickExperimentControllerImpl(10565): Exposure of experiment com.facebook.http.g.aw@60d2de4 occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(10565): Exposure of experiment com.facebook.http.g.aj@39f0324d occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(10565): Exposure of experiment com.facebook.http.g.a@f271102 occurred when no user was logged in
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8760(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 906us total 24.926ms
,W/appmanager(:<default>):QuickExperimentControllerImpl(10565): Exposure of experiment com.facebook.http.g.k@1c1aa649 occurred when no user was logged in
D/ResourcesManager( 6533): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/TimaKeyStoreProvider(11414): TimaSignature is unavailable
,D/ActivityThread(11414): Added TimaKeyStore provider
,W/ResourcesManager( 6533): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6533): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 346us total 17.043ms
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 344us total 9.750ms
,E/Zygote  (11433): MountEmulatedStorage()
I/libpersona(11433): KNOX_SDCARD checking this for 10050
E/Zygote  (11433): v2
I/libpersona(11433): KNOX_SDCARD not a persona
,I/SELinux (11433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=11433 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux (11433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11433): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/GpsLocationProvider( 3521): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/KeyguardEffectViewUtil( 3690): set current wallpaper info
,D/SettingsProvider( 3521): name = keyguard_current_wallpaper_type
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10060
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/TimaKeyStoreProvider(11433): TimaSignature is unavailable
I/PCWCLIENTTRACE_PushUtil(11395): SPPPushClient is installed : true
,D/ActivityThread(11433): Added TimaKeyStore provider
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 237, CUR = 32
,D/SettingsProvider( 3521): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10060
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
I/System.out(10565): Thread-1446(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/PCWCLIENTTRACE_PushUtil(11395): sales region : global
I/PCWCLIENTTRACE_PushUtil(11395): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11395): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/System.out(10565): Thread-1446(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10565): Thread-1446(ApacheHTTPLog):isShipBuild true
I/System.out(10565): Thread-1446(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/appmanager(:<default>):QuickExperimentControllerImpl(10565): Exposure of experiment com.facebook.http.g.c@15b1be5a occurred when no user was logged in
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10110
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3521): name = keyguard_current_wallpaper_res_id
,D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
,D/SettingsProvider( 3521): selectionArgs: 10060
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
D/ResourcesManager(11414): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/StatusBar-DoNotDistrub( 3690): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 3690): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ResourcesManager(11433): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(11433): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11433): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11433): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11433): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11433): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(11433): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(11433): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11433): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (11454): MountEmulatedStorage()
,E/Zygote  (11454): v2
I/libpersona(11454): KNOX_SDCARD checking this for 10135
,I/libpersona(11454): KNOX_SDCARD not a persona
,I/SELinux (11454): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11454): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11454): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11454 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/StatusBar-DoNotDistrub( 3690): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager( 2856): getOutputsForDevice device 0002 -> 0002
,I/AudioService( 3521): getStreamVolume 5 index 110
,D/StatusBar-DoNotDistrub( 3690): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,D/TimaKeyStoreProvider(11454): TimaSignature is unavailable
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ActivityThread(11454): Added TimaKeyStore provider
,D/SecContentProvider2( 3521): uri = 14 selection = getSealedState
D/SecContentProvider2( 3521): mCursor = null
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ApplicationPolicy( 3521): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 3521): showStatusBarByNotification() mOpenByNotification=false
,D/ResourcesManager(11454): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3690): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,I/dex2oat (11471): ----------------------------------------------------
I/dex2oat (11471): <SS>: S T A R T I N G . . .
I/dex2oat (11471): <SS>: Zip is absent. Canceled.
I/dex2oat (11471): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads110511872.jar --oat-fd=53 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads110511872.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,I/dex2oat (11471): dex2oat took 48.513ms (threads: 8)
,D/PackageManager( 3521): findPreferredActivity: No PreferredActivities set
,D/KeyguardEffectViewUtil( 3690): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3690): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3690): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3690): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3690): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{11613afa G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3690): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{1dba78ab V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3690): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{11613afa G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3690): clearEffect
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/System.out( 6533): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6533): Thread-636(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6533): Thread-636(ApacheHTTPLog):isShipBuild true
I/System.out( 6533): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10202
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10202
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10202
,D/KnoxNotification( 3690): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 3690): ----- inflateViews : modified KnoxViewLocal -----
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,I/MusicStore(11454): Database version: 104
,D/PersonaManager( 3690): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 3690): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3ee8064a
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PersonaManager( 3690): isKioskContainerExistOnDevice
,D/NearbySource(11433): Nearby Source Create!
,I/PhoneStatusBar( 3690): Icon Only
,D/NearbyContext(11433): Nearby Context Create!
,I/qtaguid ( 6533): Tagging socket 53 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6533, getuid(): 10202
,I/qtaguid ( 6533): Tagging socket 58 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6533, getuid(): 10202
,I/qtaguid ( 6533): Tagging socket 59 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6533, getuid(): 10202
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10202
,I/qtaguid ( 6533): Tagging socket 56 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6533, getuid(): 10202
,I/PhenotypeConfigurator( 4228): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11433): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(11433): Samsung link source created
,W/ActivityThread(10565): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 66738(3MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 48MB/64MB, paused 2.001ms total 138.767ms
,I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
,D/PanelView( 3690): There is/are notification(s) 
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
,D/PanelView( 3690): There is/are notification(s) 
,D/DelayedSyncController(11414): Delaying sync.
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityThread( 4464): Failed to find provider info for com.android.contacts.metadata
,I/qtaguid ( 6533): Untagging socket 59
,I/System.out( 6533): Thread-636 calls detatch()
,I/qtaguid ( 6533): Untagging socket 58
I/System.out( 6533): Thread-635 calls detatch()
,I/qtaguid ( 6533): Untagging socket 56
,I/System.out( 6533): Thread-637 calls detatch()
,I/qtaguid ( 6533): Untagging socket 53
,I/System.out( 6533): Thread-638 calls detatch()
,I/System.out(10565): P[5]_NetworkDispatch1 calls detatch()
,D/ContactProvider(11433): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,E/Auth.Api.Credentials( 4464): [CredentialSyncAdapter] Unknown sync event.
,D/ResourcesManager(11454): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11454): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11454): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SyncManager( 3521): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 15771, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 3521): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 397182, reason: UserStart
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10202
,D/ContactProvider(11433): getAllContactInfoList End
,I/syncContacts(11433): thread: 1498, sync time = 162
,V/JNIHelp (11454): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourceType( 4943): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4943): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 6533): Tagging socket 57 with tag 0{0,0} uid -1, pid: 6533, getuid(): 10202
,W/ActivityThread(11454): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11454): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3561896b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11454): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11454): GMSCore installation verified
,I/ActivityManager( 3521): Killing 10305:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,I/ConfigStore(11454): Config Database version: 1
,D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3521): mCursor = null
,I/System.out( 4228): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11454): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/System.out( 4228): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4228): Tagging socket 72 with tag 1000120300000000{268440067,0} uid -1, pid: 4228, getuid(): 10014
,W/DefaultRequestDirector( 6533): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 6533): Untagging socket 57
,I/System.out( 6533): Thread-640 calls detatch()
,E/Volley  ( 6533): [640] xe.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11454): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/qtaguid ( 6533): Tagging socket 57 with tag 0{0,0} uid -1, pid: 6533, getuid(): 10202
,I/qtaguid ( 6533): Tagging socket 70 with tag 0{0,0} uid -1, pid: 6533, getuid(): 10202
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11454): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3521): getStreamVolume 3 index 0
,I/MediaRouter(11454): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,W/DefaultRequestDirector( 6533): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,D/PicasaService(11433): start picasa sync
,D/PicasaService(11433): end picasa sync
I/qtaguid ( 6533): Untagging socket 57
,I/System.out( 6533): Thread-640 calls detatch()
,E/Volley  ( 6533): [640] xe.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,E/YouTube ( 6533): apps.youtube.app.task.YouTubeNetworkTaskService.a:119 Failed to fetch settings
E/YouTube ( 6533): fdv: java.util.concurrent.ExecutionException: wb
E/YouTube ( 6533): 	at fco.a(SourceFile:103)
E/YouTube ( 6533): 	at fcp.c(SourceFile:160)
E/YouTube ( 6533): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:111)
E/YouTube ( 6533): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:49)
E/YouTube ( 6533): 	at emi.run(Unknown Source)
E/YouTube ( 6533): Caused by: java.util.concurrent.ExecutionException: wb
E/YouTube ( 6533): 	at xz.a(SourceFile:117)
E/YouTube ( 6533): 	at xz.get(SourceFile:88)
E/YouTube ( 6533): 	at gky.get(SourceFile:69)
E/YouTube ( 6533): 	at fco.a(SourceFile:99)
E/YouTube ( 6533): 	... 4 more
E/YouTube ( 6533): Caused by: wb
E/YouTube ( 6533): 	at xe.a(SourceFile:141)
E/YouTube ( 6533): 	at gkq.a(SourceFile:49)
E/YouTube ( 6533): 	at wk.run(SourceFile:105)
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor(11454): type=WIFI subType= reason=null isConnected=true
,E/Zygote  (11524): MountEmulatedStorage()
E/Zygote  (11524): v2
I/libpersona(11524): KNOX_SDCARD checking this for 10002
I/libpersona(11524): KNOX_SDCARD not a persona
,I/SELinux (11524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11524): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11524): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11524 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/qtaguid ( 4228): Tagging socket 76 with tag 1000120300000000{268440067,0} uid -1, pid: 4228, getuid(): 10014
,D/TimaKeyStoreProvider(11524): TimaSignature is unavailable
,D/ActivityThread(11524): Added TimaKeyStore provider
,E/Zygote  (11539): MountEmulatedStorage()
E/Zygote  (11539): v2
I/libpersona(11539): KNOX_SDCARD checking this for 10122
I/libpersona(11539): KNOX_SDCARD not a persona
,I/ActivityManager( 3521): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=11539 uid=10122 gids={50122, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11539): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11539): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11539): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(11524): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3521): Killing 10347:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11539): TimaSignature is unavailable
,D/ActivityThread(11539): Added TimaKeyStore provider
,I/NetworkMonitor(11454): type=WIFI subType= reason=null isConnected=true
,D/ResourcesManager(11539): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/ActivityManager( 3521): Killing 10394:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/ChimeraCfgMgr( 4464): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4464): Module APK com.google.android.play.games already loaded
,I/art     ( 4158): Explicit concurrent mark sweep GC freed 1854(67KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 1.977ms total 24.367ms
,I/ActivityManager( 3521): Killing 10410:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,V/AlarmManager( 3521):  next == MAX_VALUE
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11562): MountEmulatedStorage()
E/Zygote  (11562): v2
I/libpersona(11562): KNOX_SDCARD checking this for 1000
I/libpersona(11562): KNOX_SDCARD not a persona
,I/SELinux (11562): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11562): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11562): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11562 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityThread(11539): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
I/GamesSyncServiceMain( 4464): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 4464): Failed to execute periodic sync, missing client context - aborting
,W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/TimaKeyStoreProvider(11562): TimaSignature is unavailable
,D/ActivityThread(11562): Added TimaKeyStore provider
,V/AlarmManager( 3521):  next == MAX_VALUE
,D/ResourcesManager(11562): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/Gmail   (11539): getAccountsCursor
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11589): MountEmulatedStorage()
E/Zygote  (11589): v2
I/libpersona(11589): KNOX_SDCARD checking this for 10123
I/libpersona(11589): KNOX_SDCARD not a persona
,I/SELinux (11589): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11589): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=11589 uid=10123 gids={50123, 9997, 3003} abi=armeabi-v7a
,E/SELinux (11589): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 3521): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 3521): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/DIAGMON_AGENT(11562): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,W/GAV2    (11539): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider(11589): TimaSignature is unavailable
W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   (11539): Observing account changes for notifications
D/ActivityThread(11589): Added TimaKeyStore provider
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Gmail   (11539): Sync started for account: account:61035162
,E/Gmail   (11539): Error finding the version of the Email provider.....
E/Gmail   (11539): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   (11539): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   (11539): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   (11539): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   (11539): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   (11539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   (11539): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   (11539): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration(11539): We do not support migrating this version of the Email provider.
,I/Gmail   (11539): getAccountsCursor
,I/DIAGMON_AGENT(11562): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,E/SQLiteLog(11539): (283) recovered 109 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/DIAGMON_AGENT(11562): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11562): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11562): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/AbstractGoogleClient(11589): Application name is not set. Call Builder#setApplicationName.
,V/AlarmManager( 3521):  next == MAX_VALUE
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (11539): notifyAccountChanged
,I/Gmail   (11539): notifyAccountChanged
,I/Gmail   (11539): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/Gmail   (11539): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,E/Zygote  (11620): MountEmulatedStorage()
I/libpersona(11620): KNOX_SDCARD checking this for 10012
E/Zygote  (11620): v2
I/libpersona(11620): KNOX_SDCARD not a persona
I/SELinux (11620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11620): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11620 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   (11539): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   (11539): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/PhenotypeConfigurator( 4228): Server returned 404
,D/TimaKeyStoreProvider(11620): TimaSignature is unavailable
,D/ActivityThread(11620): Added TimaKeyStore provider
,I/System.out( 4228): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,D/ResourcesManager(11620): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,V/AlarmManager( 3521):  next == MAX_VALUE
,I/System.out( 4228): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4228): Tagging socket 77 with tag 1000040100000000{268436481,0} uid 10014, pid: 4228, getuid(): 10014
,I/Gmail   (11539): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15502, normalSync: true
,I/qtaguid ( 4228): Tagging socket 79 with tag 1000040100000000{268436481,0} uid 10014, pid: 4228, getuid(): 10014
,I/dhcpcd  (11294): wlan0: sending IPv6 Router Solicitation
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 4464): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/Gmail   (11539): getAccountsCursor
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (11539): getAccountsCursor
,I/FOTA_Client(11620): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11620): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11620): [IIIllIIllIlIllIlllII(200/lllIlIlIIIllIIlIllIl)] Polling time is not vaild
,I/FOTA_Client(11620): [com.sec.android.fotaclient.FotaUpdaterReceiver(112/onReceive)] Polling time is already passed. Start device init Immediately
,I/FOTA_Client(11620): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(104/handleMessage)] Update State: Check condition to decide next state: 1
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client(11620): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(121/handleMessage)] Update State: Initialize polling update: 1
,I/FOTA_Client(11620): [lIllIllllIIIlllIlllI(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,E/Zygote  (11641): MountEmulatedStorage()
E/Zygote  (11641): v2
I/libpersona(11641): KNOX_SDCARD checking this for 10021
I/libpersona(11641): KNOX_SDCARD not a persona
,I/SELinux (11641): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/art     ( 4228): Explicit concurrent mark sweep GC freed 74563(4MB) AllocSpace objects, 12(311KB) LOS objects, 34% free, 30MB/46MB, paused 2.462ms total 78.447ms
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SELinux (11641): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11641 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,E/SELinux (11641): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11641): TimaSignature is unavailable
,D/ActivityThread(11641): Added TimaKeyStore provider
,I/FOTA_Client(11620): [llIlllIIIIlIllIIlIIl(31/llIIIIlllllIIllIIllI)] Request Network Connection
,I/FOTA_Client(11620): [lIllIllllIIIlllIlllI(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,I/System.out( 4228): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 4228): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - currTime: 1453758473623
D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,I/FOTA_Client(11620): [com.sec.android.fotaclient.FotaInitUpdateService(352/llllIIIllIlIIIIllllI)] Request NetActionGetPolling
,D/ResourcesManager(11539): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/qtaguid ( 4228): Tagging socket 72 with tag 1000040100000000{268436481,0} uid 10014, pid: 4228, getuid(): 10014
,D/ResourcesManager(11641): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/FOTA_Client(11620): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(82/llIIIIlllllIIllIIllI)] Server time is zero
,W/ResourcesManager(11539): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11539): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/FOTA_Client(11620): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(111/llllIIIllIlIIIIllllI)] Request ServerTime
,I/FOTA_Client(11620): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,I/qtaguid ( 4228): Tagging socket 76 with tag 1000040100000000{268436481,0} uid 10014, pid: 4228, getuid(): 10014
,I/KLMS-2.4.521: (11641): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 25 22:47:53 GMT+01:00 2016
,I/KLMS-2.4.521: (11641): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11641): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11641): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client(11620): [com.sec.android.fota.osp.http.RestClient(277/llIIIIlllllIIllIIllI)] =====================================================================
,I/KLMS-2.4.521: (11641): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11641): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,V/JNIHelp (11539): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/KLMS-2.4.521: (11641): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  (11660): MountEmulatedStorage()
E/Zygote  (11660): v2
I/libpersona(11660): KNOX_SDCARD checking this for 10038
I/libpersona(11660): KNOX_SDCARD not a persona
,I/SELinux (11660): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/System.out(11620): Thread-1528(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11620): Thread-1528(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11620): Thread-1528(ApacheHTTPLog):isShipBuild true
I/System.out(11620): Thread-1528(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux (11660): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11660): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10012
,I/KLMS-2.4.521: (11641): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
I/ActivityManager( 3521): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11660 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11641): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11641): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11641): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11641): StateImplV2(): networkChangeListener().END
,D/TimaKeyStoreProvider(11660): TimaSignature is unavailable
,I/KLMS-2.4.521: (11641): KLMSIntentService(): onDestroy()
,D/ActivityThread(11660): Added TimaKeyStore provider
,I/ActivityManager( 3521): Killing 10426:com.samsung.helphub/1000 (adj 13): bgCount ##31
,W/ActivityThread(11539): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11539): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bb1cc96: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11539): Installed default security provider GmsCore_OpenSSL
,D/ResourcesManager(11660): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11660): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,V/AlarmManager( 3521):  next == MAX_VALUE
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Zygote  (11681): MountEmulatedStorage()
I/libpersona(11681): KNOX_SDCARD checking this for 1000
E/Zygote  (11681): v2
I/libpersona(11681): KNOX_SDCARD not a persona
,I/SELinux (11681): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11681): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11681 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11681): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 10444:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11681): TimaSignature is unavailable
,D/ActivityThread(11681): Added TimaKeyStore provider
,I/System.out(11620): AsyncTask #1 calls detatch()
,I/FOTA_Client(11620): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(139/llllIIIllIlIIIIllllI)] Receive result: success in ServerTime
,D/ResourcesManager(11681): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/FOTA_Client(11620): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,I/FOTA_Client(11620): [com.sec.android.fota.osp.http.RestClient(277/llIIIIlllllIIllIIllI)] =====================================================================
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10012
,I/System.out(11539): Thread-1530(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11539): Thread-1530(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out(11539): Thread-1530(ApacheHTTPLog):isShipBuild true
I/System.out(11539): Thread-1530(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10122
,I/dex2oat (11698): ----------------------------------------------------
I/dex2oat (11698): <SS>: S T A R T I N G . . .
I/dex2oat (11698): <SS>: Zip is absent. Canceled.
,I/qtaguid (11539): Tagging socket 59 with tag 1010000000000000{269484032,0} uid -1, pid: 11539, getuid(): 10122
I/dex2oat (11698): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads927341472.jar --oat-fd=107 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/cache/ads927341472.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:-130, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3521): stay LED for fully charged
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  (11716): MountEmulatedStorage()
,E/Zygote  (11716): v2
I/libpersona(11716): KNOX_SDCARD checking this for 10039
I/libpersona(11716): KNOX_SDCARD not a persona
,I/SELinux (11716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/qtaguid (11539): Tagging socket 63 with tag 1010000000000000{269484032,0} uid -1, pid: 11539, getuid(): 10122
,I/ActivityManager( 3521): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11716 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11716): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,I/dex2oat (11698): dex2oat took 38.008ms (threads: 8)
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8737(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 845us total 23.152ms
,V/HeadsetService(11079): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(11079): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 811us total 18.271ms
,I/System.out(11620): AsyncTask #1 calls detatch()
,D/TimaKeyStoreProvider(11716): TimaSignature is unavailable
,I/ActivityManager( 3521): Killing 10507:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/ActivityThread(11716): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 492us total 14.263ms
,I/FOTA_Client(11620): [lIllIlIlIIIIIIlIlIII(97/llIIIIlllllIIllIIllI)] result is success
,I/FOTA_Client(11620): [IIllIIIIlIlIlIlIllII(78/llIIIIlllllIIllIIllI)] Response Network Connection
,I/FOTA_Client(11620): [com.sec.android.fotaclient.llIIIIlllllIIllIIllI(304/llIIIIlllllIIllIIllI)] Receive result: success in NetActionGetPolling
,W/IdleConnectionHandler(10565): Removing a connection that never existed!
,I/System.out(11589): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(11589): (HTTPLog)-Static: isShipBuild true
I/System.out(11589): (HTTPLog)-Thread-1521-351111801: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(11589): (HTTPLog)-Static: isSBSettingEnabled false
,D/ResourcesManager(11716): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10123
,I/System.out(11589): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (11589): Tagging socket 28 with tag 1100000000000000{285212672,0} uid -1, pid: 11589, getuid(): 10123
,D/SettingsProvider( 3521): name = FOTA_CLIENT_HEARTBEAT_PERIOD
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10012
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/SettingsProvider( 3521): name = FOTA_CLIENT_HEARTBEAT_ADD
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10012
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=10012
,I/FOTA_Client(11620): [IIIllIIllIlIllIlllII(157/llllIIIllIlIIIIllllI)] Calculate next polling time
,E/SPPClientService(11716): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11716): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService(11716): PushLog.txt file is not deleted.
D/SPPClientService(11716): PushLog.txt file is not deleted.
D/SPPClientService(11716): ============PushLog. stop!
,D/btif_config_util(11079): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/PhenotypeConfigurator( 4228): Scheduling Phenotype for one-off execution 9355 seconds from now (1453758474122)
,E/SPPClientService(11716): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,D/SettingsProvider( 3521): name = FOTA_CLIENT_POLLING_TIME
,D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
,D/SettingsProvider( 3521): selectionArgs: 10012
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,E/Zygote  (11740): MountEmulatedStorage()
E/Zygote  (11740): v2
I/libpersona(11740): KNOX_SDCARD checking this for 10045
I/libpersona(11740): KNOX_SDCARD not a persona
,I/SELinux (11740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=11740 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Killing 10476:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
E/SELinux (11740): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11740): TimaSignature is unavailable
,W/BackupManagerService( 3521): dataChanged but no participant pkg='com.android.providers.settings' uid=10012
D/ActivityThread(11740): Added TimaKeyStore provider
,D/GetConfigurationSnapshotOperation( 4228): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/FOTA_Client(11620): [lIllIlIlIIIIIIlIlIII(194/llIIllllIIlllIIIIlll)] Find Firmware version in Version List
,I/FOTA_Client(11620): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(131/handleMessage)] Update State: Need to polling update: 1
,I/FOTA_Client(11620): [com.sec.android.fotaclient.FotaInitUpdateService(359/lllIlIlIIIllIIlIllIl)] request Polling
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 58464(2MB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 48MB/64MB, paused 1.917ms total 153.892ms
,I/FOTA_Client(11620): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(137/handleMessage)] Update State: Finish update init: 1
,D/ResourcesManager(11740): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/WifiStateMachine( 3521): REQUEST_POWER_SAVE_ON
,I/ActivityManager( 3521): Killing 10526:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/SA      (11740): [SSP] onCreated
,I/SA      (11740): [TPM] There is no property file
,I/SA      (11740): [SCU] isHaveSA() - false
,I/SA      (11740): [TPM] getModelProperty : null
I/SA      (11740): [TPM] getCSCProperty : null
,I/SA      (11740): [DM] init START
,I/SA      (11740): [DM] This device is not a Vodafone
,I/PhenotypeFlagCommitter( 4228): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4228): Using platform SSLCertificateSocketFactory
,I/SA      (11740): checkReactivationActive for LOLLIPOP
I/SA      (11740): checkReactivationActive for reactiveActive
I/SA      (11740): setSupportRL : true
,I/SA      (11740): [SCU] isHaveSA() - false
I/SA      (11740): support phone number id : false
,I/SA      (11740): [DM] init END
I/SA      (11740): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11740): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11740): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11740): [SLFUCHKMGR] constructor called
,I/qtaguid (11589): Untagging socket 28
,I/SA      (11740): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11740): [OR] == isSIMCardReady false ==
,I/SA      (11740): [SCU] == networkStateCheck == true
I/SA      (11740): [DM] getCountryCodeFromCSC : PL
I/SA      (11740): isChinaCountryCode : false
I/SA      (11740): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11740): [OR] == networkStateCheck true ==
,I/SA      (11740): [OR] GetMyCountryZoneTask
,I/SA      (11740): [OR] onReceive END
,I/SA      (11740): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5465): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3521): Killing 10542:com.facebook.system/u0a10 (adj 13): bgCount ##31
,E/WifiStateMachine( 3521): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      (11740): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11740): [SSP] query invoked
,I/SA      (11740): [TPMU] GetMccFromDB : null
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/SA      (11740): [SCU] getMccFromPreferece mcc = 260
I/SA      (11740): [TPM] isNoProxy(default) : true
W/ActivityThread(11681): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/Zygote  (11766): MountEmulatedStorage()
I/libpersona(11766): KNOX_SDCARD checking this for 10067
E/Zygote  (11766): v2
I/libpersona(11766): KNOX_SDCARD not a persona
I/System.out(11681): Thread-1547(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11681): Thread-1547(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11681): Thread-1547(ApacheHTTPLog):isShipBuild true
I/System.out(11681): Thread-1547(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/SELinux (11766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
I/SELinux (11766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11766 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11766): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11766): TimaSignature is unavailable
,D/ActivityThread(11766): Added TimaKeyStore provider
,D/ResourcesManager(11766): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,D/CalendarSyncAdapter(11589): Found 0 events marked dirty & lastSynced
,D/PackageManager( 3521): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/System.out(11681): Thread-1547 calls detatch()
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ActivityManager( 3521): Killing 10650:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,I/sCloudBackupApp(11766): sCloudBackupApp Version Info : 4.00.4.KK_APP
,I/SCloudBackupReceiver(11766): Other Intent
,D/accuweather( 5236): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/ActivityManager( 3521): Killing 10686:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/daemonapp( 3771): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5236): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5236): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5236): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5236): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5236): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11783): MountEmulatedStorage()
E/Zygote  (11783): v2
I/libpersona(11783): KNOX_SDCARD checking this for 1000
I/libpersona(11783): KNOX_SDCARD not a persona
,I/SELinux (11783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11783): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11783 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SurfaceFlinger( 2849): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 3521): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3521) eventTime = 367264
,D/PowerManagerService( 3521): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521 (0x0)
D/PowerManagerService( 3521): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3521, ws=WorkSource{10060}) (elapsedTime=3488)
,I/System.out( 4228): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/OpenGLRenderer( 5942): Render dirty regions requested: true
,D/TimaKeyStoreProvider(11783): TimaSignature is unavailable
,D/ActivityThread(11783): Added TimaKeyStore provider
,E/Zygote  (11800): MountEmulatedStorage()
E/Zygote  (11800): v2
I/libpersona(11800): KNOX_SDCARD checking this for 10147
I/libpersona(11800): KNOX_SDCARD not a persona
,I/SELinux (11800): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11800): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=11800 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11800): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 10701:com.android.calendar/u0a164 (adj 13): bgCount ##31
,I/System.out( 4228): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4228): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4228, getuid(): 10014
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=4, Uoast
,D/TimaKeyStoreProvider(11800): TimaSignature is unavailable
,D/ActivityThread(11800): Added TimaKeyStore provider
,D/PowerManagerService( 3521): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521
,D/ResourcesManager(11783): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/OpenGLRenderer( 5942): Initialized EGL, version 1.4
,I/KnoxUsageLogPro(11783): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,D/ResourcesManager(11800): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/KnoxUsageLogPro(11783): premStatus:2
,I/OpenGLRenderer( 5942): HWUI protection enabled for context ,  &this =0xaf822088 ,&mEglDisplay = 1 , &mEglConfig = -1350180592 
,D/OpenGLRenderer( 5942): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 5942): Enabling debug mode 0
,D/mali_winsys( 5942): new_window_surface returns 0x3000,  [616x201]-format:1
,W/ResourcesManager(11800): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(11783): isEulaShown : false
I/KnoxUsageLogPro(11783): KnoxUsageReceiver onReceive : not Processible, just return
,I/qtaguid ( 4228): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 4228, getuid(): 10014
,D/KeyguardWallpaperUpdator(11113): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11113): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11113): stopCheckCategoryVersion
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11828): MountEmulatedStorage()
E/Zygote  (11828): v2
I/libpersona(11828): KNOX_SDCARD checking this for 10136
I/libpersona(11828): KNOX_SDCARD not a persona
,I/SELinux (11828): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11828 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11828): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Killing 10727:com.google.android.gms:car/u0a14 (adj 13): bgCount ##31
E/SELinux (11828): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11828): TimaSignature is unavailable
,D/ActivityThread(11828): Added TimaKeyStore provider
,D/ResourcesManager(11828): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/System.out( 4464): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4464): (HTTPLog)-Static: isShipBuild true
I/System.out( 4464): (HTTPLog)-Thread-316-240165147: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4464): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4464): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4464): Tagging socket 106 with tag 1000010400000000{268435716,0} uid -1, pid: 4464, getuid(): 10014
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4228): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4228): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4228, getuid(): 10014
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11828): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11828): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11828): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11828): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4228): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4228): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4228, getuid(): 10014
,I/qtaguid (11539): Untagging socket 59
I/System.out(11539): SyncAdapterThread-1 calls detatch()
,I/WebViewFactory(11828): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11828): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11828): Loading: webviewchromium
,I/LibraryLoader(11828): Time to load native libraries: 4 ms (timestamps 7697-7701)
I/LibraryLoader(11828): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11828): Binding Chromium to main looper Looper (main, tid 1) {1ca5229d}
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LibraryLoader(11828): Expected native library version number "",actual native library version number ""
I/chromium(11828): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/qtaguid ( 4464): Untagging socket 106
,I/BrowserStartupController(11828): Initializing chromium process, renderers=0
,W/art     (11828): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11828): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11828): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(11828): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(11828): Requires BLUETOOTH permission
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4228): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4228): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4228, getuid(): 10014
,I/System.out( 4228): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4228): Tagging socket 77 with tag 1000040100000000{268436481,0} uid 10014, pid: 4228, getuid(): 10014
,I/NSApplication(11828): Starting up...
,I/ActivityManager( 3521): Killing 10042:com.android.defcontainer/u0a5 (adj 15): bgCount ##31
,I/SA      (11740): [RC New] Execute method=[GET] start
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/SA      (11740): [RC New] Security=[true]
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
I/System.out(11740): Thread-1555(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11740): Thread-1555(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11740): Thread-1555(ApacheHTTPLog):isShipBuild true
I/System.out(11740): Thread-1555(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10045
,E/Zygote  (11921): MountEmulatedStorage()
E/Zygote  (11921): v2
I/libpersona(11921): KNOX_SDCARD checking this for 10150
I/libpersona(11921): KNOX_SDCARD not a persona
,I/SELinux (11921): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11921): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11921): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=11921 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/System.out( 4228): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4228): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4228, getuid(): 10014
,D/TimaKeyStoreProvider(11921): TimaSignature is unavailable
,D/ActivityThread(11921): Added TimaKeyStore provider
,D/ResourcesManager(11921): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(11921): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11921): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11921): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(11921): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(11921): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(11921): PeriphStartReceiver.onReceive - no need to start
,I/System.out( 3521): Thread-147(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3521): Thread-147(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3521): Thread-147(ApacheHTTPLog):isShipBuild true
I/System.out( 3521): Thread-147(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,I/ActivityManager( 3521): Killing 10594:com.android.vending/u0a31 (adj 13): bgCount ##31
,I/CheckinService( 4464): Checkin interval check for package: unspecified last checkin: 1453082886478 min interval config: 0 actual interval: 675588896
,I/CheckinService( 4464): Checking schedule, now: 1453758475388 next: 1453662265351
I/CheckinService( 4464): active receiver: enabled
,I/CheckinService( 4464): Preparing to send checkin request
I/EventLogService( 4464): Accumulating logs since 1453757634443
,I/art     (11539): Explicit concurrent mark sweep GC freed 157231(5MB) AllocSpace objects, 12(215KB) LOS objects, 21% free, 29MB/37MB, paused 1.112ms total 58ms
,I/Gmail   (11539): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15715, normalSync: true
,I/Gmail   (11539): lowestBackward conversation id 0
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10186
,I/iu.SyncManager( 4464): SYNC; picasa accounts
,D/NetworkLogImpl( 4464): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4464): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/art     (11800): Attempt to remove local handle scope entry from IRT, ignoring
,I/iu.UploadsManager( 4464): num queued entries: 0
,I/iu.UploadsManager( 4464): num updated entries: 0
,I/iu.SyncManager( 4464): NEXT; no task
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/Gmail   (11539): notifyAccountChanged
,E/Zygote  (11949): MountEmulatedStorage()
E/Zygote  (11949): v2
I/libpersona(11949): KNOX_SDCARD checking this for 10013
I/libpersona(11949): KNOX_SDCARD not a persona
,I/SELinux (11949): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/Gmail   (11539): getAccountsCursor
,I/ActivityManager( 3521): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=11949 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (11949): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11949): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/Gmail   (11539): notifyAccountChanged
,W/Gmail   (11539): Sync complete for account: account:61035162
V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3521): AsyncTask #4 calls detatch()
W/System.err( 3521): java.io.IOException: Not Found
W/System.err( 3521): 	at a.d.b(Unknown Source)
W/System.err( 3521): 	at a.d.doInBackground(Unknown Source)
W/System.err( 3521): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 3521): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 3521): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3521): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 3521): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 3521): 	at java.lang.Thread.run(Thread.java:818)
,D/TimaKeyStoreProvider(11949): TimaSignature is unavailable
,D/ActivityThread(11949): Added TimaKeyStore provider
,I/Gmail   (11539): getAccountsCursor
,I/ActivityManager( 3521): Killing 11169:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10147
,D/ResourcesManager( 4228): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GCM     ( 4228): GCM config loaded
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 41404(2MB) AllocSpace objects, 6(119KB) LOS objects, 24% free, 48MB/64MB, paused 2.011ms total 162.796ms
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager(11949): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/DelayedSyncController(11414): Delaying sync.
,I/CheckinRequestBuilder( 4464): Checkin reason type: 12 attempt count: 1
,D/WifiService( 3521): New client listening to asynchronous messages
,E/ActivityThread( 4464): Failed to find provider info for com.google.android.wearable.settings
,I/GoogleURLConnFactory( 4464): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4464): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4464): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4464): Tagging socket 119 with tag 1000210100000000{268443905,0} uid -1, pid: 4464, getuid(): 10014
,D/WaitQueueForNetworkActivate(11949): notifyNetworkActivated
,I/SA      (11740): [RC New] [v2liruge] api execute + 689
I/SA      (11740): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11740): AsyncTask #1 calls detatch()
,W/ContextImpl(11949): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3521): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/SA      (11740): [TPMU] getNetworkMcc : 
,I/qtaguid ( 4464): Tagging socket 122 with tag 1000210100000000{268443905,0} uid -1, pid: 4464, getuid(): 10014
,I/SA      (11740): [SCU] saveMccToPreferece Start
I/SA      (11740): [SCU] RegionMCC : 260
I/SA      (11740): [SSP] query invoked
,I/SA      (11740): [TPMU] GetMccFromDB : null
,I/SA      (11740): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11740): [SCU] saveMccToPreferece End
,I/SA      (11740): [RC New] executeRequest [v2liruge] end. 723
I/SA      (11740): [RC New] Execute end
,I/SA      (11740): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11740): [OR] GetMyCountryZoneTask Success
,D/ResourcesManager( 4464): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/hcjo    (11949): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(11949): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine(11949): exit::IDLE
D/InitializeManagerStateMachine(11949): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(11949): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(11949): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(11949): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11949): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(11949): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11949): entry::SUCCESS
D/hcjo    (11949): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    (11949): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/FOTA_Client(11620): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/System.out( 4228): (HTTPLog)-Static: isSBSettingEnabled false
,I/splitIntent( 3521): Split this intent : android.intent.action.TIME_SET !!   mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=17 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/qtaguid ( 4228): Tagging socket 72 with tag 1000040100000000{268436481,0} uid 10014, pid: 4228, getuid(): 10014
I/splitIntent( 3521): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/Volley  (11949): RestApi Request Add : 2307
,E/Zygote  (11986): MountEmulatedStorage()
,E/Zygote  (11986): v2
I/libpersona(11986): KNOX_SDCARD checking this for 10052
I/libpersona(11986): KNOX_SDCARD not a persona
,I/SELinux (11986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=11986 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/SELinux (11986): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12001): MountEmulatedStorage()
E/Zygote  (12001): v2
I/libpersona(12001): KNOX_SDCARD checking this for 10164
I/libpersona(12001): KNOX_SDCARD not a persona
,I/SELinux (12001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12001): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=12001 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11986): TimaSignature is unavailable
,D/ActivityThread(11986): Added TimaKeyStore provider
,I/KLMS-2.4.521: (11641): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Mon Jan 25 22:47:56 GMT+01:00 2016
,D/daemonapp( 3771): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3771): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3771): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.4.521: (11641): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(12001): TimaSignature is unavailable
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/ActivityThread(12001): Added TimaKeyStore provider
,D/daemonapp( 3771): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/ResourcesManager(11986): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(11986): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/daemonapp( 3771): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/ResourcesManager(11986): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11986): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11986): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11986): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(11986): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/daemonapp( 3771): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 3771): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3771): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
,D/comsamsunglog( 3771): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3771): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 3771): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 3771): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/Zygote  (12017): MountEmulatedStorage()
I/libpersona(12017): KNOX_SDCARD checking this for 10036
E/Zygote  (12017): v2
I/libpersona(12017): KNOX_SDCARD not a persona
I/KLMS-2.4.521: (11641): KLMSIntentService(): onCreate()
,I/SELinux (12017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (11641): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SELinux (12017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12017): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11641): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/ActivityManager( 3521): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/com.cigna.mobile.coach.CoachBroadcastReceiver: pid=12017 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/KLMS-2.4.521: (11641): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.4.521: (11641): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.4.521: (11641): StateImplV2(): dateTimeChanged().START : Mon Jan 25 22:47:56 GMT+01:00 2016
D/daemonapp( 3771): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 3771): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3771): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3771): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 3771): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/TimaKeyStoreProvider(12017): TimaSignature is unavailable
,E/daemonapp( 3771): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/ActivityThread(12017): Added TimaKeyStore provider
,D/ResourcesManager(12001): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/KLMS-2.4.521: (11641): StateImplV2(): dateTimeChanged().END
,D/comdaemonstockapp( 3771): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 3771): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,W/ResourcesManager(12001): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12001): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12001): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12001): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (11641): KLMSIntentService(): onDestroy()
,D/Mms/MmsApp(11986): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(11986): init before art
,D/Mms/ArtClassLoader(11986): init [DONE] art
,D/Mms/TelephonyPermission(11986): start operation mode monitor
,D/ResourcesManager(11986): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11986): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(12017): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/CheckinService( 4464): Checkin interval check for package: unspecified last checkin: 1453082886478 min interval config: 0 actual interval: 675589652
,D/Mms/TelephonyPermission(11986): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(11986): isDefault true
,D/Mms/MmsApp(11986): onCreate() com.android.mms
,D/Mms/MmsApp(11986): [start]    initCountryIso consume time = 50.118083
,D/CountryDetector( 3521): The first listener is added
,D/daemonapp( 3771): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/MmsApp(11986): [end]    initCountryIso consume time = 18.592334
D/Mms/MmsConfig(11986): [start]    MmsConfig.init() consume time = 0.070375
,D/Mms/MmsConfig(11986): before partial update
,D/Mms/MmsConfig(11986): Load Resize quality : 80
,D/Mms/MmsConfig(11986):  enable multiwindow = true
,D/SecurityLogAgent(11144): KnoxConfiguration : Current State = 0
,D/SecurityLogAgent(11144): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent(11144): StateMachine : Initialized
,D/SecurityLogAgent(11144): StateMachine : Changed Current State = 0
,D/SecurityLogAgent(11144): StateMachine : Current State = 0
,E/Mms/MessageUtils(11986): setCountryDetector : update country detector info 
E/Mms/MessageUtils(11986): updateCountryIso : update country iso info 
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/Mms/PackageInfo(11986): com.sec.imsservice is not installed
D/Mms/MmsConfig(11986): [end]    init() consume time = 46.706291
,D/Mms/Contact(11986): [start]    init() consume time = 5.974709
,E/Zygote  (12049): MountEmulatedStorage()
E/Zygote  (12049): v2
I/libpersona(12049): KNOX_SDCARD checking this for 10191
I/libpersona(12049): KNOX_SDCARD not a persona
,I/SELinux (12049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/Mms/Contact(11986): [end]    init consume time = 10.043041
,E/SELinux (12049): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=12049 uid=10191 gids={50191, 9997} abi=armeabi-v7a
,D/Mms/DraftCache(11986): [start]    rebuildCache consume time = 9.740792
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): checkState() : APP TYPE = Full
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 865us total 20.900ms
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
D/TP/MmsSmsProvider( 3978): query,matched:13, calling pid = 11986
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/Mms/TelephonyUtils(11986): getSubId from simSlot 0, return Value = -1
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/TP/MmsSmsProvider( 3978): match 13:Elapsed time : 2.590 ms
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/TP/MmsSmsProvider( 3978): query,matched:12, calling pid = 11986
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12049): TimaSignature is unavailable
,D/Mms/DownloadManager(11986): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11986): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11986): auto download without roaming -> true
D/Mms/DownloadManager(11986): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/ActivityThread(12049): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 3978): match 12:Elapsed time : 3.479 ms
,E/Mms/TelephonyUtils(11986): subID is null or 0 length, so get DefaultSubId!!
,D/Mms/TelephonyUtils(11986): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(11986): roaming -> false (slotId = 1)
D/Mms/DownloadManager(11986): [NotificationTransaction] getAutoDownloadState simSlot : 1
,D/Mms/DownloadManager(11986): auto download without roaming -> true
D/Mms/DownloadManager(11986): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(11986): auto download during roaming secondary -> false
D/Mms/DownloadManager(11986): mAutoDownload ------> true
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 804us total 20.526ms
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 301us total 8.581ms
,E/Zygote  (12068): MountEmulatedStorage()
I/libpersona(12068): KNOX_SDCARD checking this for 10019
E/Zygote  (12068): v2
I/libpersona(12068): KNOX_SDCARD not a persona
,I/SELinux (12068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=12068 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/Mms/DraftCache(11986): [end]    rebuildCache consume time = 62.886083
,D/TimaKeyStoreProvider(12068): TimaSignature is unavailable
,D/ActivityThread(12068): Added TimaKeyStore provider
,D/ResourcesManager(12049): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,D/Mms/MmsApp(11986): [end]    onCreate() consume time = 16.860917
,W/ResourcesManager(12049): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/InitializeManagerStateMachine(11949): exit::SUCCESS
D/InitializeManagerStateMachine(11949): entry::IDLE
,D/Mms/DownloadManager(11986): Service state changed: Bundle[mParcelledData.dataSize=692]
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/System.out(11949): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(11949): (HTTPLog)-Static: isShipBuild true
I/System.out(11949): (HTTPLog)-Thread-1585-766090878: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(11949): (HTTPLog)-Static: isSBSettingEnabled false
,D/Mms/DownloadManager(11986): roaming ------> false, mSimSlot = 0
,D/Mms/Conversation(11986): [start]    init() consume time = 10.123792
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10013
,D/ResourcesManager(12068): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/Zygote  (12092): MountEmulatedStorage()
I/libpersona(12092): KNOX_SDCARD checking this for 10069
E/Zygote  (12092): v2
I/libpersona(12092): KNOX_SDCARD not a persona
I/SELinux (12092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/Mms/TelephonyUtils(11986): getSubId from simSlot 0, return Value = -1
,I/SELinux (12092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12092): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=12092 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Mms/DownloadManager(11986): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11986): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11986): auto download without roaming -> true
D/Mms/DownloadManager(11986): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(11986): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 3978): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 3978): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12092): TimaSignature is unavailable
,D/ActivityThread(12092): Added TimaKeyStore provider
,E/SQLiteLog( 3978): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3978): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3978): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3978): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3978): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3978): (284) automatic index on im_threads(normal_thread_id)
,E/Zygote  (12107): MountEmulatedStorage()
E/Zygote  (12107): v2
I/libpersona(12107): KNOX_SDCARD checking this for 10014
I/libpersona(12107): KNOX_SDCARD not a persona
,I/SELinux (12107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/TP/MmsSmsProvider( 3978): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 3978): need read changed broadcast:false
,I/SELinux (12107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12107): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=12107 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12107): TimaSignature is unavailable
,D/ActivityThread(12107): Added TimaKeyStore provider
,D/Mms/Conversation(11986): [end]    init consume time = 44.492333
D/Mms/MessagingNotification(11986): [start]    init() consume time = 0.096292
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/System.out(11949): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (11949): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 11949, getuid(): 10013
,I/ActivityManager( 3521): Killing 10329:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/Mms/MessagingNotification(11986): [end]    init consume time = 10.681041
,D/Mms/SpamFilter(11986): [start]    SpamFilter fill() begin consume time = 1.630875
,D/Mms/Synchronizer(11986): [start]    doSync consume time = 1.213042
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthServiceInstalled() : HealthService is Installed.
D/TP/MmsSmsProvider( 3978): update uri: content://mms-sms/db_synchronization
D/TP/MmsSmsProvider( 3978): query,matched:400, calling pid = 11986
V/TP/MmsSmsProvider( 3978): syncDBData start
,V/TP/MmsSmsProvider( 3978): syncDBData sms end
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
V/TP/MmsSmsProvider( 3978): syncDBData mms end
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/TP/MmsSmsProvider( 3978): syncDBData end
D/Mms/Synchronizer(11986): [end]    doSync consume time = 7.824042
,D/Mms/SpamFilter(11986): [end]    SpamFilter fill() finished consume time = 0.691291
,D/TP/MmsSmsProvider( 3978): query,matched:0, calling pid = 11986
V/TP/MmsSmsProvider( 3978): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3978): match 0:Elapsed time : 1.513 ms
,D/ResourcesManager(12092): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,D/com.sec.android.service.health.keyManager.KeyManager(12017): Current encrypted state : -1
,D/ResourcesManager(12107): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/SecSQLiteOpenHelper(12017): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(12017): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(12017): Open platform.db in secure mode
,D/SecSQLiteDatabase(12017): Android Version: 5.0.1
D/SecSQLiteDatabase(12017): Load library secsqlite.so for Android 5.0.1
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(12107): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12107): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SecSQLiteDatabase(12017): openSecureDatabase...
,I/SecSQLiteDatabase(12017): private openSecureDatabase...
I/SecSQLiteConnectionPool(12017): OpenSecure
I/SecSQLiteConnectionPool(12017): OpenSecure with password
I/SecSQLiteConnectionPool(12017): openSecureConnectionLocked
,I/SecSQLiteDatabase(12017): ...private openSecureDatabase
,I/SecSQLiteDatabase(12017): ...openSecureDatabase
,E/Zygote  (12124): MountEmulatedStorage()
E/Zygote  (12124): v2
I/libpersona(12124): KNOX_SDCARD checking this for 10082
I/libpersona(12124): KNOX_SDCARD not a persona
,I/SELinux (12124): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12124): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12124): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12124 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12124): TimaSignature is unavailable
,D/ActivityThread(12124): Added TimaKeyStore provider
,I/ActivityManager( 3521): Killing 10667:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,I/ActivityManager( 3521): Killing 11276:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31
,D/accuweather( 5236): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/ResourcesManager(12124): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,I/ActivityManager( 3521): Killing 8399:com.android.settings/1000 (adj 13): bgCount ##31
I/ Time Manager (12092): Time Difference not stored. TIME_DIFFERENCE
,D/accuweather( 5236): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/SQLiteLog(12017): (26) statement aborts at 0: [PRAGMA user_version;] file is encrypted or is not a database
,E/SecDefaultDatabaseErrorHandler(12017): Corruption reported by sqlite on database: /data/data/com.sec.android.app.shealth/databases/platform.db
E/SecDefaultDatabaseErrorHandler(12017): backup the database file: /data/data/com.sec.android.app.shealth/databases/platform.db
D/SecSQLiteOpenHelper(12017): ...getDatabaseLocked(b,b,pwd)
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider(12124): onCreate
,D/BadgeProvider(12124): DatabaseHelper
,I/qtaguid (11949): Untagging socket 26
,E/Zygote  (12141): MountEmulatedStorage()
E/Zygote  (12141): v2
I/libpersona(12141): KNOX_SDCARD checking this for 10094
I/libpersona(12141): KNOX_SDCARD not a persona
,I/SELinux (12141): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12141): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=12141 uid=10094 gids={50094, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12141): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/hcjo    (11949): AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
D/WifiService( 3521): Client connection lost with reason: 4
,I/SecureStorage(12068): [INFO]: SPID(0x00000000)Processing data
,D/TimaKeyStoreProvider(12141): TimaSignature is unavailable
,D/ActivityThread(12141): Added TimaKeyStore provider
,I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Credentials: uid 10019, gid 10019, pid 12068
I/SecureStorage( 2914): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,D/hcjo    (11949): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
D/hcjo    (11949): AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
D/hcjo    (11949): SelfUpdateManager:IDLE:execute
,D/Mms/MessagingNotification(11986): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 3978): query,matched:26, calling pid = 11986
,D/TP/SmsProvider( 3978): match 26:Elapsed time : 2.254 ms
,D/ResourcesManager(12141): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/hcjo    (11949): SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
,W/ResourcesManager(12141): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager(12141): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12141): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12141): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12141): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12141): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 3978): query,matched:6, calling pid = 11986
,D/TP/MmsSmsProvider( 3978): match 6:Elapsed time : 1.512 ms
,I/Mms/ReservationManager(11986): ReservationManager()
I/Mms/ReservationManager(11986): resetAfterConnected()
,D/TP/MmsSmsProvider( 3978): query,matched:7, calling pid = 11986
,D/TP/MmsSmsProvider( 3978): match 7:Elapsed time : 2.990 ms
,I/MultiDex(12107): VM with version 2.1.0 has multidex support
I/MultiDex(12107): install
I/MultiDex(12107): VM has multidex support, MultiDex support library is disabled.
,I/Mms/ReservationManager(11986): getReservedSendMessageCount(): retMessageCount=0
,E/AclDataUtils(11800): Circle ID not found for type: 9
,I/Volley  (11949): RestApi Request Add : 2346
,I/System.out(11949): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out(11949): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (11949): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 11949, getuid(): 10013
,V/JNIHelp (12107): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12107): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12107): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@87137b0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12107): Installed default security provider GmsCore_OpenSSL
,I/PowerManagerService( 3521): [PWL] Off : 275s ago
I/PowerManagerService( 3521): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3521): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3521): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=3521, ws=WorkSource{10147}) (elapsedTime=2094)
I/PowerManagerService( 3521): [PWL]       PARTIAL_WAKE_LOCK              'Checkin Service' (uid=10014, pid=4464, ws=WorkSource{10014 com.google.android.gms}) (elapsedTime=1332)
I/PowerManagerService( 3521): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/subscribedfeeds/com.google/eM_ADDR' (uid=1000, pid=3521, ws=WorkSource{10014}) (elapsedTime=954)
I/PowerManagerService( 3521): [PWL]       PARTIAL_WAKE_LOCK              'SyncLoopWakeLock' (uid=1000, pid=3521, ws=null) (elapsedTime=0)
,V/AlarmManager( 3521): waitForAlarm result :4
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 20352(1097KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.986ms total 119.381ms
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12160): MountEmulatedStorage()
,E/Zygote  (12160): v2
,I/libpersona(12160): KNOX_SDCARD checking this for 10028
I/libpersona(12160): KNOX_SDCARD not a persona
,I/SELinux (12160): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12160): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=12160 uid=10028 gids={50028, 9997} abi=armeabi-v7a
,E/SELinux (12160): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (12107): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     (12107): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/TimaKeyStoreProvider(12160): TimaSignature is unavailable
,D/ActivityThread(12160): Added TimaKeyStore provider
,I/ActivityManager( 3521): Killing 8347:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
,D/ResourcesManager(12160): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,D/SettingsProvider( 3521): name = next_alarm_formatted
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10094
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,W/ResourcesManager(12160): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/WVCdm   ( 2856): Instantiating CDM.
,I/WVCdm   ( 2856): CdmEngine::OpenSession
,I/WVCdm   ( 2856): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   ( 2856): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
I/qtaguid ( 4464): Untagging socket 119
,I/OMACP   (12160): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/NativeLibraryUtils(12107): Install completed successfully. count=14 extracted=0
,I/GoogleURLConnFactory(12107): Using platform SSLCertificateSocketFactory
,E/wv_dash ( 2856): No saved usage table. Creating new table.
,D/Mms/Omacp(11986): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/PCWCLIENTTRACE_SYSTEMReceiver(11395): mConnectivityHandler : connected
,I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/OMACP   (12160): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,E/Zygote  (12180): MountEmulatedStorage()
E/Zygote  (12180): v2
I/libpersona(12180): KNOX_SDCARD checking this for 10106
I/libpersona(12180): KNOX_SDCARD not a persona
,I/SELinux (12180): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12180): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,W/PCWCLIENTTRACE_AccountUtil(11395): [hasSamungAccount] - No Samsung Account
I/ActivityManager( 3521): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12180 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (12180): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 10565:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12180): TimaSignature is unavailable
,D/ActivityThread(12180): Added TimaKeyStore provider
,I/System.out(12107): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out(12107): (HTTPLog)-Static: isShipBuild true
I/System.out(12107): (HTTPLog)-Thread-1620-640175304: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/CSTORAGE(11395): ================================================
I/CSTORAGE(11395):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11395): ================================================
I/System.out(12107): (HTTPLog)-Static: isSBSettingEnabled false
I/PCWCLIENTTRACE_SecurePreferencesJNI(11395): [GetString-S]
,E/art     (11395): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11395): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11395): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11395): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11395): sales region : global
I/PCWCLIENTTRACE_PushUtil(11395): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11395): [ensureRegistration] - No Samsung account
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/System.out(12107): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (12107): Tagging socket 30 with tag 1000180300000000{268441603,0} uid 10014, pid: 12107, getuid(): 10014
,D/Mms/ArtClassLoader(11986): init before art
D/Mms/ArtClassLoader(11986): init [DONE] art
D/Mms/PerformanceUtils(11986): link cahcing start
,I/ActivityManager( 3521): Killing 11395:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,D/ResourcesManager(12180): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,I/qtaguid (12107): Tagging socket 34 with tag 1000180300000000{268441603,0} uid 10014, pid: 12107, getuid(): 10014
,D/elm:14491(12180): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491(12180): ELMEngine.ELMEngine( context ).
,D/elm:14491(12180): MDMBridge.setEnterpriseBridge()
,D/elm:14491(12180): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/Mms/PerformanceUtils(11986): link cahcing done
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12180): ElmAgentService : onCreate()
,D/elm:14491(12180): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14491(12180): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491(12180): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491(12180): ModuleBase.ModifySetAlarm()
D/elm:14491(12180): MDMBridge.getInstance()
D/elm:14491(12180): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (12203): MountEmulatedStorage()
E/Zygote  (12203): v2
I/libpersona(12203): KNOX_SDCARD checking this for 10163
I/libpersona(12203): KNOX_SDCARD not a persona
,I/SELinux (12203): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12203): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12203): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=12203 uid=10163 gids={50163, 9997} abi=armeabi-v7a
,D/elm:14491(12180): ElmAgentService : onDestroy().
,I/qtaguid (11949): Untagging socket -1
,I/qtaguid (11949): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid (11949): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger(11949): untagSocket(-1) failed with errno -9
,D/TimaKeyStoreProvider(12203): TimaSignature is unavailable
,D/hcjo    (11949): SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
D/ActivityThread(12203): Added TimaKeyStore provider
D/hcjo    (11949): AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/hcjo    (11949): SellerAppAutoUpdate:clearFlag
,D/SellerAppAutoUpdateManagerStateMachine(11949): execute::IDLE:EXECUTE
D/SellerAppAutoUpdateManagerStateMachine(11949): exit::IDLE
D/SellerAppAutoUpdateManagerStateMachine(11949): entry::TOKENCHECK
,D/SellerAppAutoUpdateManagerStateMachine(11949): execute::TOKENCHECK:TOKEN_RECEIVED
D/SellerAppAutoUpdateManagerStateMachine(11949): exit::TOKENCHECK
D/SellerAppAutoUpdateManagerStateMachine(11949): entry::FAILED
D/hcjo    (11949): AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
D/SellerAppAutoUpdateManagerStateMachine(11949): exit::FAILED
D/SellerAppAutoUpdateManagerStateMachine(11949): entry::IDLE
,E/Zygote  (12219): MountEmulatedStorage()
E/Zygote  (12219): v2
I/libpersona(12219): KNOX_SDCARD checking this for 10195
I/libpersona(12219): KNOX_SDCARD not a persona
,I/SELinux (12219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=12219 uid=10195 gids={50195, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/SELinux (12219): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 11454:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,D/ResourcesManager(12203): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(12203): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12203): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12219): TimaSignature is unavailable
,D/ActivityThread(12219): Added TimaKeyStore provider
,I/ActivityManager( 3521): Killing 11433:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/ResourcesManager(12219): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/qtaguid (12107): Untagging socket 30
,I/ActivityManager( 3521): Killing 11524:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,I/SecureStorage( 2914): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
,D/WVCdm   ( 2856): OEMCrypto_Initialize Level 1 success. I will use level 1.
,W/ResourcesManager(12219): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,W/BaseAppContext( 4228): Using Auth Proxy for data requests.
,E/BaseAppContext( 4228): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/WVCdm   ( 2856): CdmEngine::QueryKeyControlInfo
,W/WVCdm   ( 2856): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   ( 2856): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   ( 2856): CdmEngine::GenerateKeyRequest
,W/WVCdm   ( 2856): CdmLicense::PrepareKeyRequest: unexpected HDCP max capability version 255
,D/WVCdm   ( 2856): PrepareKeyRequest: nonce=2974488954
,I/System.out( 4228): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4228): Tagging socket 77 with tag 1000040100000000{268436481,0} uid 10014, pid: 4228, getuid(): 10014
,I/dhcpcd  (11294): wlan0: sending IPv6 Router Solicitation
,I/WVCdm   ( 2856): CdmEngine::CloseSession
,I/WVCdm   ( 2856): L3 Terminate.
,I/SecureStorage(12068): [INFO]: SPID(0x00000006)Processing data has been completed
,I/SecureStorage(12068): [INFO]: SPID(0x00000006)Skip using SecureStorageExceptionJNI
,I/SecSQLiteOpenHelper(12017): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper(12017): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(12017): Open platform.db in secure mode
I/SecSQLiteDatabase(12017): openSecureDatabase...
I/SecSQLiteDatabase(12017): private openSecureDatabase...
I/SecSQLiteConnectionPool(12017): OpenSecure
I/SecSQLiteConnectionPool(12017): OpenSecure with password
I/SecSQLiteConnectionPool(12017): openSecureConnectionLocked
I/SecSQLiteDatabase(12017): ...private openSecureDatabase
I/SecSQLiteDatabase(12017): ...openSecureDatabase
,I/jxcore-log(11008): --= Surplus to requirements =--
I/jxcore-log(11008): 
I/jxcore-log(11008): ****TEST TOOK:  ms ****
I/jxcore-log(11008): 
I/jxcore-log(11008): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11008): 
,I/PlayMovies(12219): SyncService$SyncAdapter.onPerformSync:252 Skipping sync for 515013DC511638B0584069811EF28701C0771BF5
,D/PlayMovies(12219): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,I/SecSQLiteOpenHelper(12017): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(12017): ...getDatabaseLocked(b,b,pwd)
,D/PlayMovies(12219): TransferService.onCreate:52 creating transfer service
,D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/AudioCapabilities(12219): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities(12219): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities(12219): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities(12219): Unsupported mime audio/x-ima
,W/VideoCapabilities(12219): Unrecognized profile/level 32768/2 for video/mp4v-es
,D/-----SIC-----(12017): ------------------skip TGH
,W/VideoCapabilities(12219): Unsupported mime video/wvc1
,I/SecSQLiteOpenHelper(12017): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(12017): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(12017): Open platform.db in secure mode
I/SecSQLiteDatabase(12017): openSecureDatabase...
I/SecSQLiteDatabase(12017): private openSecureDatabase...
I/SecSQLiteConnectionPool(12017): OpenSecure
I/SecSQLiteConnectionPool(12017): OpenSecure with password
I/SecSQLiteConnectionPool(12017): openSecureConnectionLocked
I/SecSQLiteDatabase(12017): ...private openSecureDatabase
I/SecSQLiteDatabase(12017): ...openSecureDatabase
W/VideoCapabilities(12219): Unsupported mime video/x-ms-wmv
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.videos/files/Movies/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12219): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.videos/files/Movies
,I/WVCdm   ( 2856): CdmEngine::QueryStatus
I/WVCdm   ( 2856): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   ( 2856): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/SecSQLiteOpenHelper(12017): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(12017): ...getDatabaseLocked(b,b,pwd)
,W/VideoCapabilities(12219): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities(12219): Unsupported mime video/wvc1
,W/VideoCapabilities(12219): Unsupported mime video/x-ms-wmv
,D/ResourcesManager( 4464): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/wv_dash ( 2856): No saved usage table. Creating new table.
,W/VideoCapabilities(12219): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities(12219): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities(12219): Unsupported mime video/sorenson
,W/VideoCapabilities(12219): Unsupported mime video/mp43
,W/AudioCapabilities(12219): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities(12219): Unsupported mime audio/mpeg-L2
,D/WVCdm   ( 2856): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   ( 2856): L3 Terminate.
,W/VideoCapabilities(12219): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/ResourcesManager( 4464): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12017): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,I/VideoCapabilities(12219): Unsupported profile 4 for video/mp4v-es
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12017): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer(12017): decode(34, 20909908, 4230)
,V/MediaPlayerService( 2856): decode(26, 20909908, 4230)
,I/art     ( 4464): Explicit concurrent mark sweep GC freed 45941(2MB) AllocSpace objects, 53(1207KB) LOS objects, 33% free, 31MB/47MB, paused 2.067ms total 98.327ms
,V/MediaPlayerService( 2856): player type = 3
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20909908, 4230)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
,V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
,I/AudioPlayer( 2856): First fillBuffer call!!
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
,V/MediaPlayerService( 2856): wait for playback complete
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(12017): decode(35, 20763080, 15440)
,V/MediaPlayerService( 2856): decode(26, 20763080, 15440)
V/MediaPlayerService( 2856): player type = 3
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
I/dex2oat (12286): ----------------------------------------------------
I/dex2oat (12286): <SS>: S T A R T I N G . . .
I/dex2oat (12286): <SS>: Zip is absent. Canceled.
,V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
I/dex2oat (12286): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20763080, 15440)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,D/ResourcesManager( 4464): creating new AssetManager and set to /system/app/Videos/Videos.apk
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
,V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
V/MediaPlayerService( 2856): wait for playback complete
,I/SO_AGENT(11660): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/dex2oat (12286): dex2oat took 30.934ms (threads: 8)
,I/SA      (11740): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/System.out( 4228): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
,I/System.out( 4228): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4228): Tagging socket 59 with tag 1000060200000000{268436994,0} uid 10014, pid: 4228, getuid(): 10014
,V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,D/AndroidRuntime(12279): 
D/AndroidRuntime(12279): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/AudioPlayer( 2856): reset out
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
,I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
D/AndroidRuntime(12279): CheckJNI is OFF
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
D/AndroidRuntime(12279): readGMSProperty: start
D/AndroidRuntime(12279): readGMSProperty: already setted!!
V/AwesomePlayer( 2856): reset_l()
,V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/AwesomePlayer( 2856): destructor
D/AndroidRuntime(12279): readGMSProperty: end
D/AndroidRuntime(12279): addProductProperty: start
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(12017): decode(37, 20807608, 9226)
,V/MediaPlayerService( 2856): decode(26, 20807608, 9226)
,V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20807608, 9226)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae820470, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthServiceInstalled() : HealthService is Installed.
V/AwesomePlayer( 2856): prepareAsync
,V/MediaPlayerService( 2856): wait for prepare
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
,I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthServiceInstalled() : HealthService is Installed.
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
,V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12017): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/AdaptiveEventManager( 3690): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3690): M updateContainers()
D/AdaptiveEventContainerSmall( 3690): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3690): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3690): pedoEvent == null
,D/AdaptiveEventManager( 3690): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3690): M updateContainers()
D/AdaptiveEventContainerSmall( 3690): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3690): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3690): pedoEvent == null
,I/ActivityManager( 3521): Killing 11562:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,W/ResourcesManager( 4464): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,E/DatabaseUtils( 3521): Writing exception to parcel
E/DatabaseUtils( 3521): java.lang.NullPointerException: key == null
E/DatabaseUtils( 3521): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils( 3521): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils( 3521): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils( 3521): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:376)
E/DatabaseUtils( 3521): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils( 3521): 	at android.os.Binder.execTransact(Binder.java:446)
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/ActivityManager( 3521): Killing 11681:com.policydm/1000 (adj 13): bgCount ##31
,I/qtaguid ( 4228): Tagging socket 69 with tag 1000060200000000{268436994,0} uid 10014, pid: 4228, getuid(): 10014
,I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
,V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xae820470, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 2856): notify(0xae820470, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae820470, 1, 0, 0)
V/AudioCache( 2856): prepared
,V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
,V/AwesomePlayer( 2856): play
,V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,W/System.err(12017): java.lang.NumberFormatException: Invalid int: "null"
W/System.err(12017): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err(12017): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err(12017): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err(12017): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:498)
W/System.err(12017): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1242)
W/System.err(12017): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12017): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(12017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae820470, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
,I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
V/MediaPlayerService( 2856): wait for playback complete
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae820470, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae820470, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
,V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae820470, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,I/AudioPlayer( 2856): reset out
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
W/System.err(10237): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
,V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
,W/System.err(10237): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err(10237): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err(10237): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err(10237): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err(10237): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
W/System.err(10237): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
W/System.err(10237): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
W/System.err(10237): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10237): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10237): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10237): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10237): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10237): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10237): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,I/splitIntent( 3521): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/MediaPlayer(12017): decode(36, 20914220, 4890)
,V/MediaPlayerService( 2856): decode(26, 20914220, 4890)
,V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20914220, 4890)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d380, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb020d380, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d380, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d380, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d380, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
E/AffinityControl(12279): AffinityControl: registerfunction enter
,V/MediaPlayerService( 2856): wait for playback complete
,I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d380, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d380, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d380, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(12017): decode(39, 20840384, 17329)
V/MediaPlayerService( 2856): decode(26, 20840384, 17329)
V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20840384, 17329)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/AndroidRuntime(12279): Calling main entry com.android.commands.pm.Pm
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
V/MediaPlayerService( 2856): wait for playback complete
D/PackageManager( 3521): START PACKAGE DELETE: observer{295692181}
D/PackageManager( 3521): pkg{<packageName>}
D/PackageManager( 3521): user{0}
D/PackageManager( 3521): caller{2000}
D/PackageManager( 3521): flags{3}
D/PersonaManagerService( 3521): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3521): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3521): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3521): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3521): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3521): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 3521): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3521): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3521): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3521): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3521): !@killApplicatoin: 10598, uninstall pkg
I/ActivityManager( 3521): Force stopping com.test.thalitest appid=10598 user=-1: uninstall pkg
I/ActivityManager( 3521): Killing 11008:com.test.thalitest/u0a598 (adj 0): stop com.test.thalitest
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
I/ActivityManager( 3521):   Force finishing activity ActivityRecord{39d15d3e u0 com.test.thalitest/.MainActivity t25}
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (6/9)
I/SurfaceFlinger( 2849): id=12 Removed NainActivit (-2/9)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
V/AudioCache( 2856): notify(0xb236c380, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(12017): decode(40, 20740576, 6644)
V/MediaPlayerService( 2856): decode(26, 20740576, 6644)
V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20740576, 6644)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
V/MediaPlayerService( 2856): wait for playback complete
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
D/WVMDrmPlugIn( 2854): WVMDrmPlugin::onInitialize : 1697
D/WVMDrmPlugIn( 2854): WVMDrmPlugin::onSetOnInfoListener : add 1697
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,D/WVMDrmPlugIn( 2854): WVMDrmPlugin::onGetSupportInfo : 0
V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb020d420, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
I/WVCdm   ( 2856): CdmEngine::OpenSession
I/WVCdm   ( 2856): Level3 Library Sep 25 2014 17:10:03
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(12017): decode(41, 20816916, 23389)
V/MediaPlayerService( 2856): decode(26, 20816916, 23389)
V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
W/WVCdm   ( 2856): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20816916, 23389)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
V/MediaPlayerService( 2856): wait for playback complete
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
E/wv_dash ( 2856): No saved usage table. Creating new table.
W/PackageSettings( 3521): Skipping PackageSetting{24ea4152 com.example.hello/10563} due to missing metadata
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
,D/WVCdm   ( 2856): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/ActivityManager( 3521): Force stopping com.test.thalitest appid=10598 user=0: pkg removed
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,I/SurfaceFlinger( 2849): id=14 Removed Uoast (7/8)
,I/SurfaceFlinger( 2849): id=14 Removed Uoast (-2/8)
,I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/MediaPlayer(12017): decode(42, 20706272, 8154)
,I/GAV2    (11539): Thread[GAThread,5,main]: No campaign data found.
V/MediaPlayerService( 2856): decode(26, 20706272, 8154)
,V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20706272, 8154)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
I/WVCdm   ( 2856): CdmEngine::QueryKeyControlInfo
,D/PowerManagerService( 3521): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3521) eventTime = 370827
,D/PowerManagerService( 3521): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521 (0x0)
,D/PowerManagerService( 3521): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3521, ws=WorkSource{1000}) (elapsedTime=3489)
,W/WVCdm   ( 2856): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
W/WVCdm   ( 2856): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
I/WVCdm   ( 2856): CdmEngine::GenerateKeyRequest
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,W/WVCdm   ( 2856): CdmLicense::PrepareKeyRequest: unexpected HDCP max capability version 255
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/WifiService( 3521): Client connection lost with reason: 4
,D/WVCdm   ( 2856): PrepareKeyRequest: nonce=594723627
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2856): notify(0xb236c380, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer( 2856): First fillBuffer call!!
,I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AudioCache( 2856): notify(0xb236c380, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
V/MediaPlayerService( 2856): wait for playback complete
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(12017): decode(43, 20679752, 4804)
,V/MediaPlayerService( 2856): decode(26, 20679752, 4804)
,V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20679752, 4804)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2856): notify(0xaef5b060, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
,V/MediaPlayerService( 2856): wait for playback complete
I/AudioPlayer( 2856): First fillBuffer call!!
I/art     ( 8033): Explicit concurrent mark sweep GC freed 29203(1638KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.200ms total 43.966ms
,I/qtaguid ( 4228): Untagging socket 59
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x84, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/art     ( 4050): Explicit concurrent mark sweep GC freed 1878(94KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.363ms total 46.590ms
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(12017): decode(44, 20649204, 9400)
V/MediaPlayerService( 2856): decode(26, 20649204, 9400)
,V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20649204, 9400)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,V/MediaPlayer(12017): decode(50, 20722624, 4112)
,V/MediaPlayerService( 2856): decode(38, 20722624, 4112)
,V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(38, 20722624, 4112)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/MediaPlayerService( 2856): wait for playback complete
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 2856): notify(0xaf0202e0, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
I/AudioPlayer( 2856): First fillBuffer call!!
,V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk,
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/MediaPlayerService( 2856): wait for playback complete
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x86, OMX_CommandStateSet, OMX_StateIdle)
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
,I/InputReader( 3521): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/GeofencerStateMachine( 4228): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4405): mOCRHelper is null
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x85, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
V/MediaPlayer(12017): decode(45, 20857804, 52024)
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
V/MediaPlayerService( 2856): decode(26, 20857804, 52024)
,V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
,V/AwesomePlayer( 2856): setDefault
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20857804, 52024)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
,I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,W/ResourceType( 4943): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4943): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
V/MediaPlayerService( 2856): wait for playback complete
,I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
,E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,I/Mms/MmsApp(11986):  start initViewCache mms
,I/ActivityManager( 3521): Killing 11766:com.samsung.android.scloud.backup/u0a67 (adj 13): bgCount ##31
,D/Mms/ComposeMessageFragment(11986): [start]    fillCache consume time = 1944.163167
D/Mms/ComposeMessageFragment(11986): fillCache, easy = false
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 31268(2MB) AllocSpace objects, 8(128KB) LOS objects, 24% free, 48MB/64MB, paused 1.888ms total 138.078ms
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2673/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 5942): [llIIIllllIIIlIIIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 7, 0, 0)
,V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xae91b420, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x87, OMX_CommandStateSet, OMX_StateIdle)
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,I/AudioPlayer( 2856): reset out
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/SecVideoCapture( 2856): reset
,V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
,V/AwesomePlayer( 2856): reset_l()
I/DBG_DM  ( 5942): [com.wssyncmldm.DMSecBroadcastReceiver(194/onReceive)] sec.fota.polling.intent.RECEIVE
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,I/DBG_DM  ( 5942): [com.wssyncmldm.DMSecBroadcastReceiver(556/llllIIIllIlIIIIllllI)] nMode : 0
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,V/MediaPlayer(12017): decode(46, 20722624, 4112)
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
V/MediaPlayerService( 2856): decode(26, 20722624, 4112)
I/libpersona(12390): KNOX_SDCARD checking this for 10101
E/Zygote  (12390): MountEmulatedStorage()
I/libpersona(12390): KNOX_SDCARD not a persona
E/Zygote  (12390): v2
,V/MediaPlayerService( 2856): player type = 3
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20722624, 4112)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
I/SELinux (12390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Books/Books.apk
,I/SELinux (12390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate,
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
,I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0),
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare,
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
E/SELinux (12390): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Chrome/Chrome.apk,
V/AwesomePlayer( 2856): onPrepareAsyncEvent,
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset,
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder,
V/AwesomePlayer( 2856): checkOffloadExceptions is true
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0,
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Drive/Drive.apk,
I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk,
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/DBG_DM  ( 5942): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(211/llIIIIlllllIIllIIllI)] ,
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/ActivityManager( 3521): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=12390 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1,
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 200, 973, 0)
V/AudioCache( 2856): ignored
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(3786/IllIIlllIllIIIIIllII)] Wifi_Only_flag : true
I/DBG_DM  ( 5942): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
I/DBG_DM  ( 5942): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(236/llIIIIlllllIIllIIllI)] bWifiOnly flag : true
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/TimaKeyStoreProvider(12390): TimaSignature is unavailable
D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3521): mCursor = null
D/ActivityThread(12390): Added TimaKeyStore provider
D/RegisteredServicesCache( 3965): empty dynamic service
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/GCoreUlr( 4228): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Music2/Music2.apk
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
,E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/MediaPlayerService( 2856): wait for playback complete
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
,V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
,I/DBG_DM  ( 5942): [llIIIllllIIIlIIIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x88, OMX_CommandStateSet, OMX_StateIdle)
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
I/DBG_DM  ( 5942): [IIllIIIIlIlIlIlIllII(1845/lIlIIlIlIIlIlIIIIlll)] bUpdateProcessing : false
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/AbsListView(11986): Get MotionRecognitionManager
I/DBG_DM  ( 5942): [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 5942): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/PackageManager( 3521): delete codoeFile: 
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/AudioPlayer( 2856): reset out
I/AASAUninstall( 3521):  com.test.thalitest not target!
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
,D/PackageManager( 3521): result of delete: 1{295692181}
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
D/MotionRecognitionService( 3521):  ssp status : true
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/MediaPlayer(12017): decode(47, 20785700, 21825)
,V/MediaPlayerService( 2856): decode(26, 20785700, 21825)
D/AndroidRuntime(12279): Shutting down VM
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/Mms/ComposeMessageFragment(11986): [end]    fillCache consume time = 105.0765
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/talkback/talkback.apk
V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Videos/Videos.apk
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20785700, 21825)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,I/GCoreUlr( 4228): DispatchingService.onCreate()
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
,I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
,I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
,V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/ResourcesManager(12390): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/EnterpriseDeviceManagerService( 3521): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3521): Admin package name: com.google.android.gms
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.android.launcher2.Launcher
I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2856): wait for playback complete
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/DBG_DM  ( 5942): [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
E/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@194c8629
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaef5b060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x89, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,D/RCPManagerService( 3521): PackageReceiver onReceive()
,I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
I/HarmonyEASService( 3521): onReceive : android.intent.action.PACKAGE_REMOVED for 0
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : true
,D/KnoxMUMContainerPolicy( 3521): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
V/MediaPlayer(12017): decode(48, 20684636, 21552)
D/BackupManagerService( 3521): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/MediaPlayerService( 2856): decode(25, 20684636, 21552)
D/JobSchedulerService( 3521): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3521): uID is 10598
V/EnterpriseBillingPolicy( 3521): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3521): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3521): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - personal application - profile null
V/MediaPlayerService( 2856): player type = 3
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3521): getBillingProfileForVpnEngine - start - com.test.thalitest
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
V/EnterpriseBillingPolicyStorage( 3521): getBillingProfileForVpnEngine - end - null
V/AwesomePlayer( 2856): setDefault
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(25, 20684636, 21552)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,I/DBG_DM  ( 5942): [com.wssyncmldm.XDMService(919/IIIIllIlIIlIIIIlllIl)] UI_id:223
,D/TaskPersister( 3521): removeObsoleteFile: deleting file=25_task.xml
W/ContextImpl( 5942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.IIIIllIlIIlIIIIlllIl:925 com.wssyncmldm.XDMService.IllIlIIIIlIIlIIIllIl:75 com.wssyncmldm.IIIIllIlIIlIIIIlllIl.handleMessage:1256 
,W/ContextImpl( 5942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1608 android.app.ContextImpl.startActivity:1597 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.IIIIllIlIIlIIIIlllIl:925 com.wssyncmldm.XDMService.IllIlIIIIlIIlIIIllIl:75 
I/Timeline( 5942): Timeline: Activity_launch_request id:com.wssyncmldm time:371180
,E/PersonaManagerService( 3521): inState():  stateMachine is null !!
I/PersonaManagerService( 3521): PersonaId don't exist
I/ActivityManager( 3521): do not start freezing screen for locked container getKeyguardshowstate = false
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/ActivityManager( 3521): START u0 {act=223 flg=0x14000000 cmp=com.wssyncmldm/.ui.XUIDialogActivity} from uid 1000 on display 0
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
V/MediaPlayerService( 2856): wait for playback complete
,I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf0202e0, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x8a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(12017): decode(49, 20778600, 7017)
V/MediaPlayerService( 2856): decode(26, 20778600, 7017)
,V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
,V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
,V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20778600, 7017)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
I/WVCdm   ( 2856): CdmEngine::CloseSession
I/WVCdm   ( 2856): L3 Terminate.
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
,V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
,V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l,
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 5, 0, 0)
V/AudioCache( 2856): ignored
,V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
W/ResourceType( 3521): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/ActivityManager( 3521): mDVFSHelper.acquire()
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
,V/MediaPlayerService( 2856): wait for playback complete
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
W/ResourcesManager( 3521): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): addBatteryData
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xaf020060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x8b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3521): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/DocsApplication(12390): Installing DEX configuration.
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 3521): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3521): onPackageRemoved : com.test.thalitest
,D/DexInstaller(12390): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12390): Provided clientMode=RELEASE, packageInfo=PackageInfo{682f61c com.google.android.apps.docs}
,D/TAG     (12390): onCreate()
,I/UsageStatsService( 3521): User[0] Flushing usage stats to disk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/CrossAppStateProvider(12390): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/Activity( 5942): performCreate Call secproduct feature valuefalse
D/Activity( 5942): performCreate Call debug elastic valuetrue
,E/Zygote  (12425): MountEmulatedStorage()
E/Zygote  (12425): v2
I/libpersona(12425): KNOX_SDCARD checking this for 10125
I/libpersona(12425): KNOX_SDCARD not a persona
,I/SELinux (12425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=12425 uid=10125 gids={50125, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/Mms/BubbleViewCache(11986): fillCache bubble = 8
,I/SELinux (12425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/GCoreUlr( 4228): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,E/SELinux (12425): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIDialogActivity(2236/onResume)] 
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIDialogActivity(2278/llIIIIlllllIIllIIllI)] id 223
,I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/daily/1453161600000 to /data/system/usagestats/0/daily/1453161606353
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 559us total 10.465ms
,I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/daily/1453248000000 to /data/system/usagestats/0/daily/1453248006353
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/daily/1453334400000 to /data/system/usagestats/0/daily/1453334406353
,I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/daily/1453680000000 to /data/system/usagestats/0/daily/1453680006353
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/weekly/1451519893056 to /data/system/usagestats/0/weekly/1451519899409
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/weekly/1451519952327 to /data/system/usagestats/0/weekly/1451519958680
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/weekly/1452124752327 to /data/system/usagestats/0/weekly/1452124758680
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/weekly/1452729545761 to /data/system/usagestats/0/weekly/1452729552114
,I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/weekly/1452729600000 to /data/system/usagestats/0/weekly/1452729606353
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/weekly/1453334400000 to /data/system/usagestats/0/weekly/1453334406353
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1438585425653 to /data/system/usagestats/0/monthly/1438585432006
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1441151770722 to /data/system/usagestats/0/monthly/1441151777075
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1443743770722 to /data/system/usagestats/0/monthly/1443743777075
,I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1443743805180 to /data/system/usagestats/0/monthly/1443743811533
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1443743813275 to /data/system/usagestats/0/monthly/1443743819628
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1446335813275 to /data/system/usagestats/0/monthly/1446335819628
,I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1446335820187 to /data/system/usagestats/0/monthly/1446335826540
,I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1446335864846 to /data/system/usagestats/0/monthly/1446335871199
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1448927852394 to /data/system/usagestats/0/monthly/1448927858747
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1448927911238 to /data/system/usagestats/0/monthly/1448927917591
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1451519893056 to /data/system/usagestats/0/monthly/1451519899409
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1451519952327 to /data/system/usagestats/0/monthly/1451519958680
,I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/monthly/1451520000000 to /data/system/usagestats/0/monthly/1451520006353
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/yearly/1439449425653 to /data/system/usagestats/0/yearly/1439449432006
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/yearly/1450655904549 to /data/system/usagestats/0/yearly/1450655910902
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/yearly/1450655952327 to /data/system/usagestats/0/yearly/1450655958680
I/UsageStatsDatabase( 3521): Moving file /data/system/usagestats/0/yearly/1450656000000 to /data/system/usagestats/0/yearly/1450656006353
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 495us total 9.573ms
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,I/UsageStatsService( 3521): User[0] Rollover scheduled @ 2016-01-26 01:00:00(1453766400000)
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 499us total 8.629ms
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/Timeline( 5942): Timeline: Activity_launch_request id:com.wssyncmldm time:371333
I/GCoreUlr( 4228): Unbound from all location providers
I/GCoreUlr( 4228): Place inference reporting - stopped
,E/PersonaManagerService( 3521): inState():  stateMachine is null !!
I/PersonaManagerService( 3521): PersonaId don't exist
I/ActivityManager( 3521): do not start freezing screen for locked container getKeyguardshowstate = false
D/TimaKeyStoreProvider(12425): TimaSignature is unavailable
,D/ActivityThread(12425): Added TimaKeyStore provider
,I/SyncAdapterService(11828): Ignoring sync request for non-current account
,I/ActivityManager( 3521): START u0 {flg=0x4000000 cmp=com.wssyncmldm/.ui.XUIInstallConfirmActivity} from uid 1000 on display 0
,W/ActivityManager( 3521): mDVFSHelper.acquire()
,D/ResourcesManager(12425): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,I/GCoreUlr( 4228): DispatchingService.onDestroy()
I/GCoreUlr( 4228): Stopping handler for UlrDispSvcFast
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.llIllIIIIllIIlIIlIll(252/llllIIIllIlIIIIllllI)] 
,D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIDialogActivity(2228/onPause)] 
,W/ResourcesManager(12425): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3521): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,I/GCoreUlr( 4228): Unbound from all location providers
I/GCoreUlr( 4228): Place inference reporting - stopped
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(80/onCreate)] Postpone Count : 10
,I/CheckinRequestBuilder( 4464): Classify the device as Phone.
,I/art     ( 4158): Explicit concurrent mark sweep GC freed 3858(155KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 1.068ms total 55.924ms
,I/Babel   (12425): MmsConfig: mnc/mcc: 0/0
I/Babel   (12425): MmsConfig.loadMmsSettings
I/Babel   (12425): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
I/Babel   (12425): MmsConfig.loadFromDatabase
E/SQLiteLog(12425): (28) failed to open "/data/data/com.google.android.talk/databases/apn.db" with flag (131138) and mode_t (0) due to error (30)
,D/ResourcesManager(12425): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/AudioCapabilities(12425): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities(12425): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities(12425): Unsupported mime audio/x-ms-wma
,E/SQLiteDatabase(12425): Failed to open database '/data/data/com.google.android.talk/databases/apn.db'.
E/SQLiteDatabase(12425): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12425): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12425): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12425): 	at bvm.y(PG:497)
E/SQLiteDatabase(12425): 	at bvm.b(PG:466)
E/SQLiteDatabase(12425): 	at bvn.run(PG:209)
E/AndroidRuntime(12425): FATAL EXCEPTION: Thread-1665
E/AndroidRuntime(12425): Process: com.google.android.talk, PID: 12425
E/AndroidRuntime(12425): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12425): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12425): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12425): 	at bvm.y(PG:497)
E/AndroidRuntime(12425): 	at bvm.b(PG:466)
E/AndroidRuntime(12425): 	at bvn.run(PG:209)
,W/AudioCapabilities(12425): Unsupported mime audio/x-ima
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
,W/VideoCapabilities(12425): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities(12425): Unsupported mime video/wvc1
,W/VideoCapabilities(12425): Unsupported mime video/x-ms-wmv
,W/Settings(12425): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Process (12425): Sending signal. PID: 12425 SIG: 9
,E/DropBoxManagerService( 3521): Can't write: system_app_crash
E/DropBoxManagerService( 3521): java.io.FileNotFoundException: /data/system/dropbox/drop194.tmp: open failed: EROFS (Read-only file system)
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
,E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IlIllIIIIllllllIlIIl(llIIIIlllllIIllIIllI:5285)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.,database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IlIllIIIIllllllIlIIl(llIIIIlllllIIllIIllI:5285)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:91)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
,E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:58)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:1434)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2401)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:1316)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIIlIlIlIllIlIIllI(llIIIIlllllIIllIIllI:5265)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:99)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5269/IIIIIlIlIlIllIlIIllI)] java.lang.NullPointerException: Attempt to invoke virtual method 'int android.database.sqlite.SQLiteDatabase.update(java.lang.String, android.content.ContentValues, java.lang.String, java.lang.String[])' on a null object reference
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:536)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:536)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
E/SQLiteLog(10379): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog(10379): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIllIIllIIIlllIlIIll(llIIIIlllllIIllIIllI:5021)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:537)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIllIIllIIIlllIlIIll(llIIIIlllllIIllIIllI:5021)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:537)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/AndroidRuntime(10379): FATAL EXCEPTION: IntentService[CalendarProviderIntentService]
E/AndroidRuntime(10379): Process: com.android.providers.calendar, PID: 10379
E/AndroidRuntime(10379): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime(10379): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime(10379): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime(10379): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime(10379): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime(10379): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime(10379): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime(10379): 	at com.android.providers.calendar.CalendarAlarmManager.runScheduleNextAlarm(CalendarAlarmManager.java:210)
E/AndroidRuntime(10379): 	at com.android.providers.calendar.CalendarProviderIntentService.onHandleIntent(CalendarProviderIntentService.java:45)
E/AndroidRuntime(10379): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(10379): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10379): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10379): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActiv,ity.onCreate(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityT,hread.java:2759)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.android.providers.calendar
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/Process (10379): Sending signal. PID: 10379 SIG: 9
I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
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
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:536)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:239)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/UsbHostManager( 3521): displayNotification : [02h,02h,01h]
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:536)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:239)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
I/splitIntent( 3521): Split this intent : com.google.android.gms.INITIALIZE !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIllIIllIIIlllIlIIll(llIIIIlllllIIllIIllI:5021)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:537)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:239)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIllIIllIIIlllIlIIll(llIIIIlllllIIllIIllI:5021)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:537)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:239)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
D/UsbHostManager( 3521): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3521): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3521): displayNotification : [0ah,00h,01h]
I/splitIntent( 3521): finish to split intent : com.google.android.gms.INITIALIZE !! Enqueue -> schedule it!!
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
D/UsbHostManager( 3521): usbDeviceRemoved : /dev/bus/usb/001/003
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:239)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:239)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3521): displayNotification : [09h,00h,00h]
E/UsbHostManager( 3521): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3521): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:536)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:316)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLite,OpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:536)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:316)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
I/ActivityManager( 3521): Process com.google.android.talk (pid 12425)(adj 9) has died(265,1061)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIllIIllIIIlllIlIIll(llIIIIlllllIIllIIllI:5021)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:537)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:316)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIllIIllIIIlllIlIIll(llIIIIlllllIIllIIllI:5021)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:537)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:316)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
D/Launcher( 3997): onRestart, Launcher: 320123683
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:316)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onCreate(llIIIIlllllIIllIIllI:316)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performCreate(Activity.java:6289)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1119)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2647)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2759)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/PowerManagerService( 3521): [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'ScheduleNextAlarmWakeLock' (uid=10047, pid=10379, ws=null) (elapsedTime=57)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
D/Activity( 5942): performCreate Call secproduct feature valuefalse
D/Activity( 5942): performCreate Call debug elastic valuetrue
D/Launcher( 3997): onStart, Launcher: 320123683
D/Launcher.HomeView( 3997): onStart
I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
D/Launcher.HomeView( 3997): onStop
V/ActivityThread( 3997): updateVisibility : ActivityRecord{f30aa0f token=android.os.BinderProxy@f62aac9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/AuthorizationBluetoothService( 4228): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/ActivityThread( 3997): updateVisibility : ActivityRecord{f30aa0f token=android.os.BinderProxy@f62aac9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3997): onTrimMemory. Level: 20
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:463)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:463)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
I/ActivityManager( 3521): Process com.android.providers.calendar (pid 10379)(adj 5) has died(265,1061)
W/ActivityManager( 3521): Scheduling restart of crashed service com.android.providers.calendar/.CalendarProviderIntentService in 1000ms
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1064)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2583)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:536)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.lIIllllllIlllllIlIIl(llIIIIlllllIIllIIllI:5101)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:464)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1064)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2583)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:536)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.lIIllllllIlllllIlIIl(llIIIIlllllIIllIIllI:5101)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:464)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
D/UsbHostManager( 3521): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3521): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:465)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:465)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 10
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IlIllIIIIllllllIlIIl(llIIIIlllllIIllIIllI:5285)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:470)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.d,atabase.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IlIllIIIIllllllIlIIl(llIIIIlllllIIllIIllI:5285)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:470)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:536)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:478)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:536)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:478)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3521): Removing device '/dev/input/event10' due to inotify event
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIllIIllIIIlllIlIIll(llIIIIlllllIIllIIllI:5021)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:537)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:478)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.datab,ase.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIllIIllIIIlllIlIIll(llIIIIlllllIIllIIllI:5021)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:537)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:478)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:478)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 594,2): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:478)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2764)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.access$900(ActivityThread.java:178)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 5942): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 5942): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 5942): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,E/SQLiteLog(12390): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3521): Removing device '/dev/input/event7' due to inotify event
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,E/SQLiteDatabase(12390): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12390): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12390): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12390): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12390): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12390): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12390): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12390): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12390): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12390): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12390): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12390): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12390): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12390): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12390): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12390): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12390): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12390): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12390): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12390): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12390): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12390): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12390): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12390): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12390): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12390): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12390): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12390): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12390): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12390): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12390): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12390): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12390): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12390): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(12390): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12390): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12390): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12390): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12390): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12390): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12390): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12390): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12390): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12390): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12390): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12390): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12390): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12390): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12390): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12390): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12390): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12390): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12390): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12390): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12390): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12390): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12390): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12390): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12390): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12390): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12390): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12390): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12390): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12390): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12390): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12390): 	at aEV.a(Gelly,InjectorStore.java:130)
E/SQLiteOpenHelper(12390): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12390): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12390): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12390): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12390): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12390): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12390): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12390): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12390): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12390): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12390): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12390): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12390): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12390): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12390): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12390): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12390): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12390): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12390): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12390): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12390): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12390): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12390): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12390): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12390): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12390): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12390): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12390): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12390): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12390): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12390): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12390): Opened ClientFlag.db in read-only mode
D/WearableService( 4228): callingUid 10014, callindPid: 4228
,I/EventHub( 3521): Removing device '/dev/input/event8' due to inotify event
,I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/LocationInitializer( 4464): Restart initialization of location
,E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/MDM     ( 4228): [296] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/SQLiteLog(12390): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:463)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteDatabase(12390): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12390): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12390): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12390): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12390): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12390): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12390): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12390): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12390): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/AndroidRuntime(12390): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12390): Process: com.google.android.apps.docs, PID: 12390
E/AndroidRuntime(12390): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12390): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12390): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12390): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12390): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12390): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12390): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12390): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12390): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12390): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12390): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12390): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12390): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12390): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12390): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12390): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12390): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12390): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12390): 	at aFp.run(AbstractDatabaseInstance.java:471)
,I/EventHub( 3521): Removing device '/dev/input/event9' due to inotify event
,E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:463)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
,V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1064)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2583)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:536)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.lIIllllllIlllllIlIIl(llIIIIlllllIIllIIllI:5101)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:464)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/,SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1064)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2583)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:536)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.lIIllllllIlllllIlIIl(llIIIIlllllIIllIIllI:5101)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:464)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
E/DropBoxManagerService( 3521): Can't write: system_app_crash
E/DropBoxManagerService( 3521): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
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
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
E/SQLiteLog(12390): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:465)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteDatabase(12390): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12390): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnection.,open(SQLiteConnection.java:228)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12390): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12390): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12390): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12390): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12390): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(12390): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(12390): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12390): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12390): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12390): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12390): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12390): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12390): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12390): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12390): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12390): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12390): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:465)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12390): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12390): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12390): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12390): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12390): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12390): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12390): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(12390): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(12390): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12390): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12390): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12390): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12390): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12390): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12390): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12390): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12390): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12390): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12390): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12390): Opened ClientFlag.db in read-only mode
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/EventHub( 3521): Removing device '/dev/input/event11' due to inotify event
I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 10
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IlIllIIIIllllllIlIIl(llIIIIlllllIIllIIllI:5285)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:470)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IlIllIIIIllllllIlIIl(llIIIIlllllIIllIIllI:5285)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:470)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
I/Process (12390): Sending signal. PID: 12390 SIG: 9
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:536)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:478)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IllIIIIllIllIIllllll(llIIIIlllllIIllIIllI:5222)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:536)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:478)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIllIIllIIIlllIlIIll(llIIIIlllllIIllIIllI:5021)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:537)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:478)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIllIIllIIIlllIlIIll(llIIIIlllllIIllIIllI:5021)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:537)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:478)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
,I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 5942): (28) failed to open "/data/data/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5942): Failed to open database '/data/data/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteDatabase( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:478)
E/SQLiteDatabase( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteDatabase( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteDatabase( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 5942): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 5942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 5942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:542)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.db.file.XDB.llllIIlIlIIIIllIlIIl(llIIIIlllllIIllIIllI:5244)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteOpenHelper( 5942): 	at com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume(llIIIIlllllIIllIIllI:478)
E/SQLiteOpenHelper( 5942): 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1255)
E/SQLiteOpenHelper( 5942): 	at android.app.Activity.performResume(Activity.java:6412)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3385)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3427)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1493)
E/SQLiteOpenHelper( 5942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 5942): Opened wssdmdatabase.db in read-only mode
I/DBG_DM  ( 5942): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 5942): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 5942): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
I/EventHub( 3521): Removing device '/dev/input/event12' due to inotify event
I/DBG_DM  ( 5942): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
I/DBG_DM  ( 5942): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
W/ActivityManager( 3521): Activity pause timeout for ActivityRecord{3952cb93 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t26}
,I/EventHub( 3521): Removing device '/dev/input/event13' due to inotify event
,I/ActivityManager( 3521): Process com.google.android.apps.docs (pid 12390)(adj 0) has died(289,1064)
,W/ActivityManager( 3521): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService in 1000ms
,I/EventHub( 3521): Removing device '/dev/input/event14' due to inotify event
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/splitIntent( 3521): Queue : backgroundsplit_1 intent com.google.android.gms.INITIALIZE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
,V/ActivityThread( 5942): updateVisibility : ActivityRecord{47e4611 token=android.os.BinderProxy@7af8cbc {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,V/GLSActivity( 4228): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }

```
