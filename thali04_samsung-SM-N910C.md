#### Test 565307121a686b7_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/SSRM:n  ( 3512): SIOP:: AP = 250, PST = 270, CUR = 24
D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3512): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3512): Plugged
I/MotionRecognitionService( 3512): setPowerConnected  = true
D/BatteryService( 3512): stay LED for fully charged
--------- beginning of main
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime(10695): 
D/AndroidRuntime(10695): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10695): CheckJNI is OFF
D/AndroidRuntime(10695): readGMSProperty: start
D/AndroidRuntime(10695): readGMSProperty: already setted!!
D/AndroidRuntime(10695): readGMSProperty: end
D/AndroidRuntime(10695): addProductProperty: start
E/AffinityControl(10695): AffinityControl: registerfunction enter
D/AndroidRuntime(10695): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3512): inState():  stateMachine is null !!
I/PersonaManagerService( 3512): PersonaId don't exist
I/ActivityManager( 3512): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3512): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3512): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3512): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3512): mDVFSHelper.acquire()
D/FocusedStackFrame( 3512): Set to : 0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/Zygote  (10713): MountEmulatedStorage()
E/Zygote  (10713): v2
I/libpersona(10713): KNOX_SDCARD checking this for 10590
I/libpersona(10713): KNOX_SDCARD not a persona
I/SELinux (10713): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3512): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=10713 uid=10590 gids={50590, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (10713): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10713): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10695): Shutting down VM
D/PointerIcon( 3512): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3512): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3512): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3512): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(10713): TimaSignature is unavailable
D/ActivityThread(10713): Added TimaKeyStore provider
V/WindowOrientationListener( 3512): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3512): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3512): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3512): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3512): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(10713): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 4000): updateVisibility : ActivityRecord{2dc42ea1 token=android.os.BinderProxy@2708c58b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4000): onTrimMemory. Level: 20
I/WebViewFactory(10713): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10713): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10713): Loading: webviewchromium
I/LibraryLoader(10713): Time to load native libraries: 4 ms (timestamps 5191-5195)
I/LibraryLoader(10713): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10713): Binding Chromium to main looper Looper (main, tid 1) {1dd9be59}
,I/LibraryLoader(10713): Expected native library version number "",actual native library version number ""
I/chromium(10713): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10713): Initializing chromium process, renderers=0
,W/art     (10713): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10713): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10713): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10713): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10713): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothAdapter(10713): 529226270: getState() :  mService = null. Returning STATE_OFF
,W/chromium(10713): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10713): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10713): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10713): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(10713): CordovaWebView is running on device made by: samsung
,W/art     (10713): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10713): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(10713): performCreate Call secproduct feature valuefalse
D/Activity(10713): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(10713): Render dirty regions requested: true
,D/ActivityManager( 3512): post active user change for 0
D/KnoxTimeoutHandler( 3512): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3512): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3512): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3512): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3512): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3512): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3512): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3512): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(10713): Initialized EGL, version 1.4
,I/OpenGLRenderer(10713): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278643952 
,D/OpenGLRenderer(10713): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10713): Enabling debug mode 0
,D/mali_winsys(10713): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(10713): updateVisibility : ActivityRecord{22d086ce token=android.os.BinderProxy@2d9b1734 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3512): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3512): mDVFSHelper.release()
,I/Timeline( 3512): Timeline: Activity_windows_visible id: ActivityRecord{ded13a3 u0 com.test.thalitest/.MainActivity t25} time:135574
,W/IInputConnectionWrapper(10713): showStatusIcon on inactive InputConnection
,I/Timeline(10713): Timeline: Activity_idle id: android.os.BinderProxy@2d9b1734 time:135581
,D/JsMessageQueue(10713): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(10713): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10713): 
,D/jxcore_app_log(10713): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358476672
,I/chromium(10713): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/art     (10713): Background sticky concurrent mark sweep GC freed 73570(7MB) AllocSpace objects, 14(2MB) LOS objects, 15% free, 35MB/42MB, paused 1.824ms total 104.294ms
,W/jxcore-log(10713): Initializing JXcore engine
W/jxcore-log(10713): JXcore engine is ready
,E/auditd  ( 4539): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3512): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3512): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10713): Starting JXcore engine
,W/jxcore-log(10713): Platform android
W/jxcore-log(10713): 
W/jxcore-log(10713): Process ARCH arm
W/jxcore-log(10713): 
,I/jxcore-log(10713): JXcore Cordova bridge is ready!
I/jxcore-log(10713): 
W/jxcore-log(10713): JXcore engine is started
,I/jxcore-log(10713): Toggling radios to true
I/jxcore-log(10713): 
,D/BluetoothAdapter(10713): enable()
,W/ActivityManager( 3512): Permission Denial: getCurrentUser() from pid=10713, uid=10590 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 3512): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 3512): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10713, uid=10590 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 3512): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/BluetoothManagerService( 3512): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2160)
W/BluetoothManagerService( 3512): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService( 3512): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 3512): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService( 3512): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3512): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 3512): name = bluetooth_on
,E/DevicePolicyManagerService( 3512): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3512): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/WifiManager(10713): packageName : com.test.thalitest
,D/SecContentProvider( 3512): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3512): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3512): mCursor = null
D/WifiService( 3512): New client listening to asynchronous messages
,D/WifiService( 3512): setWifiEnabled: true pid=10713, uid=10590
E/WifiService( 3512): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3512): Permission Denial: getCurrentUser() from pid=10713, uid=10590 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3512): Failed getting userId using ActivityManagerNative
W/WifiService( 3512): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10713, uid=10590 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3512): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3512): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3512): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3512): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3512): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3512): name = wifi_on
,E/WifiStateMachine( 3512): setting operational mode to 1
,E/WifiHW  ( 3512): ##################### set firmware type 0 #####################
I/WifiService( 3512): disconnect: pid=10713, uid=10590
,I/jxcore-log(10713): Radios toggled
I/jxcore-log(10713): 
E/Zygote  (10784): MountEmulatedStorage()
E/Zygote  (10784): v2
I/libpersona(10784): KNOX_SDCARD checking this for 1002
I/libpersona(10784): KNOX_SDCARD not a persona
,I/jxcore-log(10713): My device name is: samsung-SM-N910C
I/jxcore-log(10713): 
I/SELinux (10784): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10784): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/WifiHW  ( 2845): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,I/ActivityManager( 3512): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=10784 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
E/SELinux (10784): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WifiHW  ( 2845): module is murata
E/WifiHW  ( 2845): ==========[WIFI] MURATA MODULE ===========
I/WifiHW  ( 2845): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_murata
E/WifiHW  ( 2845): TEMP_FAILURE_RETRY complete
D/SoftapController( 2845): Softap fwReload - Ok
,D/CommandListener( 2845): Setting iface cfg
D/CommandListener( 2845): Trying to bring down wlan0
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8720(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 482us total 10.213ms
D/CommandListener( 2845): Clearing all IP addresses on wlan0
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 462us total 7.986ms
,D/TimaKeyStoreProvider(10784): TimaSignature is unavailable
,D/ActivityThread(10784): Added TimaKeyStore provider
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 479us total 8.378ms
,D/ResourcesManager(10784): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(10784): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(10784): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni(10784): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig(10784): Adding GattService
,D/BtSettings.ProfileConfig(10784): Adding HeadsetService
D/BtSettings.ProfileConfig(10784): Adding A2dpService
D/BtSettings.ProfileConfig(10784): Adding HidService
,D/BtSettings.ProfileConfig(10784): Adding HealthService
D/BtSettings.ProfileConfig(10784): Adding PanService
D/BtSettings.ProfileConfig(10784): Adding BluetoothMapService
D/BtSettings.ProfileConfig(10784): Adding SapService
D/BtSettings.ProfileConfig(10784): Adding HeadsetClientService
D/BtSettings.ProfileConfig(10784): Adding A2dpSinkService
D/BtSettings.ProfileConfig(10784): Adding SapClientService
D/BtSettings.ProfileConfig(10784): Adding HidDevService
I/BtSettings.ProfileConfig(10784): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3512): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3512): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3512): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3512): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3512): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3512): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3512): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3512): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3512): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3512): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,E/WifiHW  ( 3512): supplicant_name : p2p_supplicant
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3512): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3512): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/wpa_supplicant(10800): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant(10800): Successfully initialized wpa_supplicant
,I/SecureStorage(10800): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage(10800): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage( 2917): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10800
I/SecureStorage( 2917): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
I/SecureStorage(10800): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant(10800): ssSupport state is = 1
D/BluetoothAdapterState(10784): make
I/wpa_supplicant(10800): >>>>> GET KEY, IV <<<<<
I/bluedroid(10784): init
I/SecureStorage(10800): [INFO]: SPID(0x00000000)Processing data
I/BluetoothAdapterState(10784): Entering OffState
I/SecureStorage( 2917): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10800
I/SecureStorage( 2917): [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
I/bte_conf(10784): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf(10784): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config(10784): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf(10784): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
E/bt-btif (10784): btif_fetch_local_ble_random_bdaddr
I/bluedroid(10784): get_profile_interface socket
I/bluedroid(10784): get_profile_interface map_client
D/BluetoothAdapterService(10784): checkAddrForIOP: Loading from conf
D/BluetoothAdapterService(10784): Inband Ring is supported
I/GKI_LINUX(10784): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties(10784): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10784): populateRssiValuesNative
I/bluedroid(10784): getModelRssiValues
E/BluetoothServiceJni(10784): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10784): modelRssiValuesCallback, low, mid, high = -75,-65,127
D/BluetoothAdapterProperties(10784): Name is: Note4-1
D/SettingsProvider( 3512): name = bluetooth_name
I/bluedroid(10784): config_hci_snoop_log
D/BluetoothManagerService( 3512): Broadcasting onBluetoothServiceUp() to 11 receivers.
,E/DevicePolicyManagerService( 3512): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3512): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 3512): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState(10784): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties(10784): Setting state to 11
I/BluetoothAdapterState(10784): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(10784): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10784): updateAdapterState state is 11
D/BluetoothAdapterService(10784): Autoconnection is available 
D/BluetoothAdapterService(10784): updateAdapterState prevState = 10newState = 11
D/BluetoothSecureManager(10784): getInstant: null
D/BluetoothSecureManager(10784): calling getMethod for getService
D/BluetoothSecureManager(10784): calling getService
D/BluetoothSecureManager(10784): getService return binder: android.os.BinderProxy@1cd3df91
W/InputMethodManagerService( 3512): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3512): [BT Setting State] State =11
D/BluetoothSecureManagerService( 3512): isSecureModeEnabled
,E/WifiStateMachine( 3512): setWifiState: enabling
,D/BluetoothTile( 3693):  onBluetoothPairedDevicesChanged:
I/SamsungIME( 4463): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothTile( 3693): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothSecureManagerService( 3512): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode(10784): isSecureModeOn:false
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService(10784): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10784): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10784): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService(10784): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10784): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10784): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService(10784): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10784): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
D/StatusBarManagerService( 3512): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
W/BluetoothAdapterService(10784): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/StatusBarManagerService( 3512): setIconVisibility slot=bluetooth visible=false
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10784): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10784): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
D/STATUSBAR-QSTileView( 3693): onStateChanged: Bluetooth
E/WifiStateMachine( 3512): Supplicant start successful
D/WifiMonitor( 3512): startMonitoring(wlan0) with mConnected = false
D/PhoneStatusBar( 3693): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,W/BluetoothAdapterService(10784): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine(10784): make
,I/BluetoothBondStateMachine(10784): StableState(): Entering Off State
W/BluetoothAdapterService(10784): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/SmartBondingService( 3512): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
W/BluetoothAdapterService(10784): Not skipping com.android.bluetooth.gatt.GattService
D/SLocation( 3512): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-WifiQuickSettingButton( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3693): Wifi onReceive(2)
D/HotspotTile( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 3693): onStateChanged: Wi-Fi
D/HotspotTile( 3693): onReceive : 2, 0
,D/SmartBondingService( 3512): getNetworkEnabled : wifi : false mobile : false
,V/[CarModeFW](10119): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
W/BluetoothAdapterService(10784): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10784): Not skipping com.android.bluetooth.hfp.HeadsetService
I/BtGatt.JNI(10784): classInitNative(L900): classInitNative: Success!
,D/BtGatt.DebugUtils(10784): handleDebugAction() action=null
D/BtGatt.GattService(10784): Received start request. Starting profile...
D/BtGatt.GattService(10784): start()
I/bluedroid(10784): get_profile_interface gatt
D/BluetoothAdapterService(10784): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd9be59
D/BtGatt.AdvertiseManager(10784): advertise manager created
,W/BluetoothAdapterService(10784): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10784): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BluetoothAdapterService(10784): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd9be59
,D/HeadsetService(10784): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni(10784): classInitNative: succeeds
D/HeadsetStateMachine(10784): make
,E/HeadsetStateMachine(10784): # of Max HF connection is 2
W/BluetoothAdapterService(10784): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(10784): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService(10784): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10784): Not skipping com.android.bluetooth.hdp.HealthService
I/bluedroid(10784): get_profile_interface handsfree
,W/BluetoothAdapterService(10784): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10784): Not skipping com.android.bluetooth.pan.PanService
,D/BluetoothNotiBroadcastReceiver( 7946): onReceive
,W/BluetoothAdapterService(10784): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10784): Not skipping com.android.bluetooth.map.BluetoothMapService
I/DualScoManager(10784): Instantiating Dual Sco Manager
I/DualScoManager(10784): Set HeadsetServiceHelper
D/BluetoothAtMessage(10784): createCMTIContentObservers
,W/BluetoothAdapterService(10784): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10784): Not skipping com.broadcom.bt.service.sap.SapService
,D/SettingsProvider( 3512): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
W/BluetoothAdapterService(10784): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10784): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10784): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10784): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10784): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10784): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10784): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig(10784): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService(10784): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState(10784): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine(10784): Enter Disconnected: -2
,E/HeadsetStateMachine(10784): set to mRemoteBrsf = 0
,D/BluetoothAdapterService(10784): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd9be59
E/BluetoothAdapterService(500809305)(10784): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/HeadsetStateMachine(10784): map size, before remove : 0
D/HeadsetStateMachine(10784): map size, after remove: 0
,D/BluetoothA2dp( 4926): Proxy object connected
D/BluetoothA2dp( 3512): Proxy object connected
,D/A2dpService(10784): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni(10784): classInitNative: succeeds
V/Avrcp   (10784): make
V/Avrcp   (10784): Avrcp
I/bluedroid(10784): get_profile_interface avrcp
,V/Avrcp   (10784): start
,E/RemoteController(10784): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   (10784): ++registerMediaPlayers++
,I/Avrcp   (10784): No of Audio players :: 2
I/Avrcp   (10784): App Package name is com.google.android.music
,D/ResourcesManager(10784): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   (10784): App pkg name is Google Play Music
,I/Avrcp   (10784): Name::Google Play Music
V/Avrcp   (10784): MediaPlayerInfo: mPlayerId=1
I/Avrcp   (10784): App Package name is com.sec.android.app.music
,D/ResourcesManager(10784): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   (10784): App pkg name is Music
I/Avrcp   (10784): Name::Music
V/Avrcp   (10784): MediaPlayerInfo: mPlayerId=2
,I/Avrcp   (10784): No of Video players :: 1
I/Avrcp   (10784): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager(10784): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   (10784): Video App pkg name is Video Player
,I/Avrcp   (10784): Name::Video Player
V/Avrcp   (10784): MediaPlayerInfo: mPlayerId=3
I/Avrcp   (10784): Add tempPlayer
V/Avrcp   (10784): MediaPlayerInfo: mPlayerId=4
I/Avrcp   (10784): Total no of players: 4
V/Avrcp   (10784): swapping the samsung player with 1st player
I/Avrcp   (10784):  Updating now playing list upon AVRCP Start
V/Avrcp   (10784): handleMessage, msg=207
D/BluetoothMediaBrowser(10784):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,V/Avrcp   (10784): CurrentAudioFocusPackageName is null
I/Avrcp   (10784): There is no currently selected player ,setting Samsung Music Player ID
I/Avrcp   (10784):  set player publishabilty with player id::1 toBePublished ::true
I/BluetoothA2dpServiceJni(10784): classInitNative: succeeds
D/A2dpStateMachine(10784): make
,I/bluedroid(10784): get_profile_interface a2dp
I/GKI_LINUX(10784): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif (10784): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService(10784): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd9be59
D/A2dpStateMachine(10784): Enter Disconnected: -2
,I/BluetoothHidServiceJni(10784): classInitNative: succeeds
D/HeadsetStateMachine(10784): Proxy object connected
,D/HeadsetStateMachine(10784): Try to query the phonestate on bind
,I/Telecom ( 3952): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 3952): BluetoothPhoneService: updateHeadsetWithCallState
,D/BluetoothMediaBrowser(10784): no now playing list
D/BluetoothMediaBrowser(10784):  getNowPlayingId now playing id : -1
D/Avrcp   (10784):  checkNowPlayingList start
,I/Telecom ( 3952): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 3952): Proxy not attached to service
,D/HidService(10784): Received start request. Starting profile...
I/bluedroid(10784): get_profile_interface hidhost
D/HidService(10784): setHidService(): set to: null
D/BluetoothAdapterService(10784): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd9be59
I/BluetoothHealthServiceJni(10784): classInitNative: succeeds
,D/HealthService(10784): Received start request. Starting profile...
,I/bluedroid(10784): get_profile_interface health
D/BluetoothAdapterService(10784): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd9be59
D/HeadsetPhoneState(10784): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState(10784): sendDeviceDataStateChanged
D/HeadsetStateMachine(10784): Disconnected process message: 11
D/HeadsetPhoneState(10784): Signal level : previous=0 curr=0
D/HeadsetStateMachine(10784): Disconnected process message: 18
I/BluetoothPanServiceJni(10784): classInitNative(L105): succeeds
,D/BluetoothPan( 3512): BluetoothPAN Proxy object connected
,D/PanService(10784): Received start request. Starting profile...
D/BluetoothPanServiceJni(10784): initializeNative(L110): pan
I/bluedroid(10784): get_profile_interface pan
,D/BluetoothAdapterService(10784): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd9be59
,D/AuthorizationBluetoothService( 4245): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothMapService(10784): Received start request. Starting profile...
,I/Hs20UtilService( 6368): Starting #2
,I/Hs20UtilService( 6368): Message received 5011
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10819): MountEmulatedStorage()
E/Zygote  (10819): v2
I/libpersona(10819): KNOX_SDCARD checking this for 10178
I/libpersona(10819): KNOX_SDCARD not a persona
,I/SELinux (10819): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10819): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10819): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=10819 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10834): MountEmulatedStorage()
E/Zygote  (10834): v2
I/libpersona(10834): KNOX_SDCARD checking this for 10127
I/libpersona(10834): KNOX_SDCARD not a persona
,I/SELinux (10834): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10834): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=10834 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (10834): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10819): TimaSignature is unavailable
,D/ActivityThread(10819): Added TimaKeyStore provider
,D/ResourcesManager(10819): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(10819): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(10819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10819): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10819): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10819): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10819): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(10834): TimaSignature is unavailable
,D/ActivityThread(10834): Added TimaKeyStore provider
,D/ResourcesManager(10834): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(10834): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(10834): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10834): stopCheckCategoryVersion
,I/SignOutReceiver( 8376): WIFI_STATE_CHANGED_ACTION
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10850): MountEmulatedStorage()
I/libpersona(10850): KNOX_SDCARD checking this for 1000
E/Zygote  (10850): v2
I/libpersona(10850): KNOX_SDCARD not a persona
,I/SELinux (10850): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10850): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10850): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/ActivityManager( 3512): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=10850 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(10850): TimaSignature is unavailable
,D/ActivityThread(10850): Added TimaKeyStore provider
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,D/BluetoothAdapterService(10784): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd9be59
,D/ResourcesManager(10850): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/BluetoothSAPServiceJni(10784): classInitNative(L204): succeeds
,E/Zygote  (10873): MountEmulatedStorage()
E/Zygote  (10873): v2
I/libpersona(10873): KNOX_SDCARD checking this for 10082
I/libpersona(10873): KNOX_SDCARD not a persona
,I/SELinux (10873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/SapService(10784): Received start request. Starting profile...
D/BluetoothSAPServiceJni(10784): initializeNative(L209): sap
I/bluedroid(10784): get_profile_interface sap
D/BluetoothAdapterService(10784): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd9be59
E/BluetoothAdapterService(500809305)(10784): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp(10784): Proxy object connected
D/BluetoothAdapterService(10784): Bluetooth A2dp source service connected
E/BluetoothAdapterService(500809305)(10784): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/HeadsetStateMachine(10784): Disconnected process message: 10
I/SELinux (10873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/HeadsetPhoneState(10784): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine(10784): Disconnected process message: 11
,E/SELinux (10873): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=10873 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/BluetoothAdapterService(500809305)(10784): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(500809305)(10784): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(500809305)(10784): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,I/ActivityManager( 3512): Killing 9945:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,E/BluetoothAdapterService(500809305)(10784): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(500809305)(10784): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/BluetoothAdapterState(10784): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid(10784): enable
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
I/GKI_LINUX(10784): gki_task_entry task_id=0 [BTU] starting
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
I/bt_hci_bdroid(10784): init
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/bt_vendor(10784): init
I/bt_vnd_conf(10784): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf(10784): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial(10784): userial_init
,E/Zygote  (10892): MountEmulatedStorage()
E/Zygote  (10892): v2
I/libpersona(10892): KNOX_SDCARD checking this for 10186
I/libpersona(10892): KNOX_SDCARD not a persona
,I/SELinux (10892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10892): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc tv.peel.smartremote for broadcast tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver: pid=10892 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 3512): Killing 9962:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/9962/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(10873): TimaSignature is unavailable
D/ActivityThread(10873): Added TimaKeyStore provider
,I/ActivityManager( 3512): Killing 9988:com.osp.app.signin/u0a45 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10892): TimaSignature is unavailable
,D/ActivityThread(10892): Added TimaKeyStore provider
,D/ResourcesManager(10873): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(10892): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,W/ResourcesManager(10892): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/BadgeProvider(10873): onCreate
,D/BadgeProvider(10873): DatabaseHelper
,D/BadgeProvider(10873): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(10873): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10873): sendNotify, [notify] : null
D/BadgeProvider(10873): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10873): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10873): update, [UpdateCount] : 1
,D/Launcher.Model( 4000): reloadBadges entered.
,I/bt_userial_vendor(10784): userial vendor open: opening /dev/ttySAC3
,I/bt_userial_vendor(10784): userial_vendor_open():UART is setup
I/bt_userial_vendor(10784): device fd = 65 open
E/bt_hwcfg(10784): Start CFG HW, HCI reset
D/bt_userial(10784): Entering userial_read_thread()
,E/bt_hwcfg(10784): Read Local Name after HCI reset
,W/ActivityManager( 3512): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/bt_hwcfg(10784): Chipset BCM43569A1
D/bt_hwcfg(10784): Target name = [BCM4358A1]
,I/bt_hwcfg(10784): module_type[murata].
I/bt_hwcfg(10784): module_type[murata] is invalid.
E/bt_hwcfg(10784): patchram path ORG . BCM4358A1
E/bt_hwcfg(10784): patchram path ORG .. BCM4358A1
E/bt_hwcfg(10784): patchram path ORG bcm4358A0_V0033.0000.hcd BCM4358A1
E/bt_hwcfg(10784): patchram path ORG bcm4358A1_V0044.0078.hcd BCM4358A1
I/bt_hwcfg(10784): patch(org) : bcm4358A1_V0044.0078.hcd
I/bt_hwcfg(10784): Found patchfile: /vendor/firmware/bcm4358A1_V0044.0078.hcd
E/bt_hwcfg(10784): ORG patchram base 0044
E/bt_hwcfg(10784): ORG patchram minor 0078
E/bt_hwcfg(10784): fw ver (org)44.78
E/bt_hwcfg(10784): Final Patchram is /vendor/firmware/bcm4358A1_V0044.0078.hcd
,I/bt_hwcfg(10784): Axi patch failure or not include AXI patching
,I/bt_hwcfg(10784): bt vendor lib: set UART baud 3000000
,I/WebViewFactory(10892): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(10892): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(10892): Loading: webviewchromium
,I/LibraryLoader(10892): Time to load native libraries: 6 ms (timestamps 7917-7923)
I/LibraryLoader(10892): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10892): Binding Chromium to main looper Looper (main, tid 1) {1f19bfa3}
,I/LibraryLoader(10892): Expected native library version number "",actual native library version number ""
I/chromium(10892): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10892): Initializing chromium process, renderers=0
,W/art     (10892): Attempt to remove local handle scope entry from IRT, ignoring
,I/SecureStorage(10800): [INFO]: SPID(0x00000005)Processing data has been completed
,W/chromium(10892): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10892): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10892): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46768 len=2953
I/chromium(10892): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:229524 len:643667
,I/SecureStorage(10800): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10800): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10800
I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10800): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10800): ssSupport state is = 1
,I/wpa_supplicant(10800): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant(10800): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10800): SIM READ ERROR
I/wpa_supplicant(10800): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10800): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10800): SIM READ ERROR
I/wpa_supplicant(10800): Blacklist: Clear (all) 
I/wpa_supplicant(10800): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10800): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant(10800): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10800): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
I/wpa_supplicant(10800): rfkill: Cannot open RFKILL control device
,W/chromium(10892): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10892): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10892): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10892): onDetachedFromWindow called when already detached. Ignoring
,I/ActivityManager( 3512): Killing 9252:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,I/bt_hwcfg(10784): bt vendor lib: set UART baud 115200
I/bt_hwcfg(10784): FW Download delta = 500832
D/bt_hwcfg(10784): Settlement delay -- 100 ms
I/bt_hwcfg(10784): Setting fw settlement delay to 100 
,I/bt_hwcfg(10784): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg(10784): vendor lib fwcfg completed
,I/        (10784): BTE_InitTraceLevels -- TRC_HCI
I/        (10784): BTE_InitTraceLevels -- TRC_L2CAP
I/        (10784): BTE_InitTraceLevels -- TRC_RFCOMM
I/        (10784): BTE_InitTraceLevels -- TRC_AVDT
I/        (10784): BTE_InitTraceLevels -- TRC_AVRC
I/        (10784): BTE_InitTraceLevels -- TRC_A2D
I/        (10784): BTE_InitTraceLevels -- TRC_BNEP
I/        (10784): BTE_InitTraceLevels -- TRC_BTM
I/        (10784): BTE_InitTraceLevels -- TRC_GAP
I/        (10784): BTE_InitTraceLevels -- TRC_PAN
I/        (10784): BTE_InitTraceLevels -- TRC_SAP
I/        (10784): BTE_InitTraceLevels -- TRC_SDP
I/        (10784): BTE_InitTraceLevels -- TRC_GATT
I/        (10784): BTE_InitTraceLevels -- TRC_SMP
I/        (10784): BTE_InitTraceLevels -- TRC_BTAPP
I/        (10784): BTE_InitTraceLevels -- TRC_BTIF
I/        (10784): BTE_InitTraceLevels -- TRC_PROTOCOL
,W/bt-l2cap(10784): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  (10784): BTM_SecRegister:p_cb_info->p_le_callback == 0xb39eb9e1 
E/bt-btm  (10784): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb39eb9e1 
,E/Tethering( 3512): No numeric data
,D/Tethering( 3512): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 3512): forceRefresh() from cache miss
,D/HotspotTile( 3693): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3693): updateTetherState():false, false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 3512): forceRefresh Fail.
V/NetworkStats( 3512): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3512): UpdateStatsForKnox
,V/NetworkStats( 3512): performPollLocked() took 2ms
,D/NtpTrustedTime( 3512): forceRefresh() from cache miss
,D/NtpTrustedTime( 3512): forceRefresh Fail.
,I/wpa_supplicant(10800): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant(10800): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage(10800): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10800): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10800
I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10800): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10800): ssSupport state is = 1
,I/SecureStorage(10800): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,D/BluetoothAdapterProperties(10784): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif (10784): Calling BTA_HhEnable
,E/bt-btif (10784): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties(10784): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10784): populateRssiValuesNative
I/bluedroid(10784): getModelRssiValues
E/BluetoothServiceJni(10784): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10784): modelRssiValuesCallback, low, mid, high = -75,-65,127
I/SecureStorage(10800): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10800
I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10800): [INFO]: SPID(0x00000005)SS Daemon is running
,I/wpa_supplicant(10800): ssSupport state is = 1
I/wpa_supplicant(10800): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
D/BluetoothAdapterProperties(10784): Name is: Note4-1
E/wpa_supplicant(10800): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10800): SIM READ ERROR
I/wpa_supplicant(10800): rfkill: Cannot open RFKILL control device
E/wpa_supplicant(10800): nl80211: Could not configure driver mode
E/wpa_supplicant(10800): p2p0: Failed to initialize driver interface
I/wpa_supplicant(10800): Blacklist: Clear (all) 
D/BluetoothAdapterProperties(10784): Scan Mode:20
D/BluetoothAdapterProperties(10784): Discoverable Timeout:120
D/SettingsProvider( 3512): name = bluetooth_name
D/BluetoothAdapterProperties(10784): LE Address is:E0:B7:20:28:C5:81
E/bt-btif (10784): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif (10784): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif (10784): btif_sock_init: !radio_req && !rfc_init
E/bt-btif (10784): btif_sock_init: !vhci_init
D/IOP_DB_BT(10784): db_open: file /etc/bluetooth/iop_bt.db
I/SecureStorage(10800): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,D/IOP_DB_BT(10784): db_open: db_open : handle 3025502224l, read 14063 bytes onto local cache
D/IOP_DB_BT(10784): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT(10784): db_query: result 1
I/        (10784): iop_db_open: iop_db_open status 0
D/bte_conf(10784): Device ID record 1 : primary
D/bte_conf(10784):   vendorId            = 0075
D/bte_conf(10784):   vendorIdSource      = 0001
D/bte_conf(10784):   product             = 0100
D/bte_conf(10784):   version             = 0200
D/bte_conf(10784):   clientExecutableURL = 
D/bte_conf(10784):   serviceDescription  = 
D/bte_conf(10784):   documentationURL    = 
D/bte_conf(10784): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni(10784): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState(10784): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties(10784): ScanMode =  20
D/BluetoothAdapterProperties(10784): State =  11
,D/SecContentProvider( 3512): uri = 3 selection = isDiscoverableEnabled
D/BluetoothAdapterProperties(10784): Setting state to 12
I/BluetoothAdapterState(10784): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties(10784): Scan Mode:21
D/BluetoothAdapterProperties(10784): Discoverable Timeout:120
D/SettingsProvider( 3512): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 1002
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService(10784): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10784): updateAdapterState state is 12
,I/SecureStorage(10800): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10800
I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10800): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10800): ssSupport state is = 1
I/SecureStorage(10800): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
D/BluetoothAdapterService(10784): Autoconnection is available 
D/BluetoothAdapterService(10784): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService(10784): starting service from this receiver
D/BluetoothA2dp( 3512): onBluetoothStateChange: up=true
,I/BluetoothAdapterState(10784): Entering On State from state = 11
,D/BluetoothA2dp( 4926): onBluetoothStateChange: up=true
,D/BluetoothA2dp(10784): onBluetoothStateChange: up=true
,I/SecureStorage(10800): [INFO]: SPID(0x00000005)This device supports Secure Storage
I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10800
I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,I/SecureStorage(10800): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10800): ssSupport state is = 1
I/BluetoothPbapService(10784): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
W/InputMethodManagerService( 3512): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/wpa_supplicant(10800): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
I/InputMethodManagerService( 3512): [BT Setting State] State =12
E/wpa_supplicant(10800): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
I/InputMethodManagerService( 3512): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
E/wpa_supplicant(10800): SIM READ ERROR
I/wpa_supplicant(10800): rfkill: Cannot open RFKILL control device
,D/BluetoothTile( 3693):  onBluetoothStateChange:
,D/BluetoothTile( 3693):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3693): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,I/SamsungIME( 4463): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,E/bt_h4   (10784): vendor lib postload completed
,D/BluetoothHeadset( 3952): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@4dd27fb, true
,D/BluetoothHeadset( 3952): registerMessageListener
,D/StatusBarManagerService( 3512): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/PhoneStatusBar( 3693): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
D/StatusBarManagerService( 3512): setIconVisibility slot=bluetooth visible=true
,D/BluetoothTile( 3693):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 3693): onStateChanged: Bluetooth
,D/HeadsetService(10784): registerMessageListener
D/HeadsetService(10784): registerMessageListener
D/HeadsetStateMachine(10784): Disconnected process message: 70
D/HeadsetStateMachine(10784): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1f4f95c
I/Telecom ( 3952): BluetoothPhoneService: updateHeadsetWithCallState
I/Telecom ( 3952): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,V/[CarModeFW](10119): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](10119): ConnectivityManager-handleMessage INITIAL_STATE_ON
,D/HeadsetStateMachine(10784): Disconnected process message: 9
W/ContextImpl( 7946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/HeadsetStateMachine(10784): mNumActive: 0 mNumHeld: 0 mCallState: 6
,I/BluetoothPbapService(10784): Handler(): got msg=1
,D/BluetoothManagerService( 3512): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/SecContentProvider( 3512): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/AudioHardwareTinyALSA( 2854): setParameters(A2dpSuspended=false)
E/HeadsetStateMachine(10784): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/LocalBluetoothProfileManager( 7946): Adding local A2DP profile
,V/BluetoothPbapService(10784): PBAP Service initSocket try: 0
,W/BluetoothAdapter(10784): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance(10784): set MAP SDP message type : 1
D/BluetoothSocket(10784): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket(10784): bindListen(), new LocalSocket 
D/BluetoothSocket(10784): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10784): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f864f48
D/BluetoothSocket(10784): channel: 19
D/BluetoothPbapService(10784): PBAP Socket is BluetoothServerSocket
,I/wpa_supplicant(10800): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant(10800): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,W/BluetoothAdapter(10784): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10784): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket(10784): bindListen(), new LocalSocket 
D/BluetoothSocket(10784): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10784): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3207e1e1
D/BluetoothSocket(10784): channel: 5
,I/wpa_supplicant(10800): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant(10800): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant(10800): Skip scan - bUseNetwork false
,E/WifiStateMachine( 3512): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,E/WifiStateMachine( 3512): setSuspendOptimizations: 2 true
,E/WifiStateMachine( 3512): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine( 3512): Supplicant connection established
D/WifiNative-HAL( 3512): callSECApiBoolean - ID [21]
I/wpa_supplicant(10800): HOTSPOT20_ENABLE called
I/wpa_supplicant(10800): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10800): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10800): SIM READ ERROR
I/wpa_supplicant(10800): Blacklist: Clear (all) 
I/art     ( 3512): Explicit concurrent mark sweep GC freed 31759(1955KB) AllocSpace objects, 12(192KB) LOS objects, 24% free, 48MB/64MB, paused 1.226ms total 83.229ms
,D/LocalBluetoothProfileManager( 7946): Adding local HEADSET profile
,E/BluetoothHeadset( 7946): BTStateChangeCB is registed
,I/wpa_supplicant(10800): wlan0: Setting scan request: 0 sec 0 usec
,E/BluetoothHeadset( 7946): BluetoothHeadset service is binded
,W/ContextImpl( 7946): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 7946): bindService called to Bluetooth SAP Service
,I/wpa_supplicant(10800): Skip scan - bUseNetwork false
E/WifiStateMachine( 3512): setWifiState: enabled
D/WifiNative-HAL( 3512): callSECApiInt - ID [210]
,D/WifiConfigStore( 3512): Loading config and enabling all networks 
,D/SmartBondingService( 3512): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3512): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService( 3512): getNetworkEnabled : wifi : true mobile : false
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3693): Wifi onReceive(3)
,D/HotspotTile( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 3693): onStateChanged: Wi-Fi
D/HotspotTile( 3693): onReceive : 3, 0
,D/LocalBluetoothProfileManager( 7946): PANU : true
D/LocalBluetoothProfileManager( 7946): Adding local MAP profile
,D/BluetoothMap( 7946): Create BluetoothMap proxy object
,E/WifiConfigStore( 3512): Not a HS20
,E/WifiConfigStore( 3512): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/LocalBluetoothProfileManager( 7946): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 7946): LocalBluetoothProfileManager construction complete
,I/WifiStateMachine( 3512): update LTECoexState:0
D/WifiNative-HAL( 3512): callSECApiInt - ID [65]
,D/DockEventReceiver( 7946): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 7946): onReceive
D/BluetoothA2dp( 7946): Proxy object connected
,D/A2dpProfile( 7946): Bluetooth service connected
,D/WifiNative-HAL( 3512): callSECApiBoolean - ID [13]
I/wpa_supplicant(10800): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant(10800): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant(10800): reset timer : RESET_TIMER 0
I/wpa_supplicant(10800): P2P: Current p2p state = IDLE
I/wpa_supplicant(10800): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant(10800): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant(10800): First Scan Start
,D/BluetoothAdapterService(10784): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd9be59
D/BtConfig.SecureMode(10784): isSecureModeOn:false
,I/wpa_supplicant(10800): Scan requested (ret=0) - scan timeout 30 seconds
D/HeadsetProfile( 7946): Bluetooth service connected
,D/WifiNative-HAL( 3512): Setting external_sim to 1
,D/Bluetoothsap( 7946): BluetoothSAP Proxy object connected
,D/WifiStateMachine( 3512): Setting OUI to DA-A1-19
I/WifiNative-HAL( 3512): startHal
E/wifi    ( 3512): getStaticLongField sWifiHalHandle 0x8fa6385c
D/wifi    ( 3512): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x30209a
I/WifiNative-HAL( 3512): Could not start hal
D/SapProfile( 7946): Bluetooth service connected
D/Bluetoothsap( 7946): getConnectedDevices()
,D/AuthorizationBluetoothService( 4245): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/WifiStateMachine( 3512): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,D/BluetoothInputDevice( 7946): Proxy object connected
D/HidProfile( 7946): Bluetooth service connected
,E/WifiStateMachine( 3512): Attempting to reconnect to wifi network ..
E/native  ( 3512): do suspend true
D/BluetoothPan( 7946): BluetoothPAN Proxy object connected
,D/PanProfile( 7946): Bluetooth service connected
,D/WifiP2pService( 3512): P2pDisabledState{ what=131203 }
,D/CommandListener( 2845): Setting iface cfg
D/CommandListener( 2845): Trying to bring up p2p0
,D/WifiMonitor( 3512): startMonitoring(p2p0) with mConnected = true
E/WifiStateMachine( 3512): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiStateMachine( 3512): updateConfiguredNetworkExpiration - currTime: 1453241305933
D/WifiStateMachine( 3512): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/WifiP2pService( 3512): P2pEnablingState
D/WifiP2pService( 3512): P2pEnablingState{ what=147457 }
D/WifiP2pService( 3512): P2p socket connection successful
,D/WifiScanningService( 3512): SCAN_AVAILABLE : 3
D/WifiP2pService( 3512): P2pEnabledState
D/WifiScanningService( 3512): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 3512): startHal
E/wifi    ( 3512): getStaticLongField sWifiHalHandle 0x8e81b98c
D/wifi    ( 3512): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x30207e
I/WifiNative-HAL( 3512): Could not start hal
E/WifiScanningService( 3512): could not start HAL
D/RttService( 3512): SCAN_AVAILABLE : 3
E/WifiStateMachine( 3512): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3512): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/RttService( 3512): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,I/Hs20UtilService( 6368): Starting #3
E/WifiStateMachine( 3512): set country code pl
,I/Hs20UtilService( 6368): Message received 5011
D/WifiP2pService( 3512): sending p2p connection changed broadcast: IDLE
,E/WifiStateMachine( 3512): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
I/WifiStateMachine( 3512): callSECApi what=207
D/BluetoothMap( 7946): Proxy object connected
D/MapProfile( 7946): Bluetooth service connected
D/BluetoothPbap( 7946): Proxy object connected
D/PbapServerProfile( 7946): Bluetooth service connected
,D/WifiDisplayController( 3512): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiP2pService( 3512): create mNetworkAgent
,D/WifiDisplayController( 3512): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3512): disconnect
D/WifiDisplayController( 3512): updateConnection
D/WifiDisplayController( 3512): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SecContentProvider( 3512): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/KeyguardWallpaperUpdator(10834): cancelUpdateWallpaper
,D/WifiDisplayController( 3512): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardWallpaperUpdator(10834): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10834): stopCheckCategoryVersion
,D/AllShareCastTile( 3693): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3693): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,W/BluetoothAdapter(10784): getBluetoothService() called with no BluetoothManagerCallback
,I/SignOutReceiver( 8376): WIFI_STATE_CHANGED_ACTION
,D/BluetoothSocket(10784): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
D/BluetoothSocket(10784): bindListen(), new LocalSocket 
D/BluetoothSocket(10784): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10784): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29e94763
D/BluetoothSocket(10784): channel: 12
I/BtOppRfcommListener(10784): Accept thread started.
,D/ConnectivityService( 3512): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 3512): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 3512): updateNetworkInfo()
D/ConnectivityService( 3512): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/wpa_supplicant(10800): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
E/CSLegacyTypeTracker( 3512): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,E/WifiStateMachine( 3512): set frequency band 0
,D/NearbySettings( 7946): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 7946): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 7946): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 7946): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 7946): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 7946): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3512): New client listening to asynchronous messages
,I/NearbySettings( 7946): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7946): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7946): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7946): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant(10800): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/WifiStateMachine( 3512): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3512): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine( 3512): setDetailed state send new extra info
,D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
D/WifiNative-HAL( 3512): p2pGetDeviceAddress
D/WifiNative-HAL( 3512): p2pGetDeviceAddress returning 92:b6:86:43:73:1c
,E/Zygote  (10979): MountEmulatedStorage()
E/Zygote  (10979): v2
I/libpersona(10979): KNOX_SDCARD checking this for 10079
I/libpersona(10979): KNOX_SDCARD not a persona
,I/SELinux (10979): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3512): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=10979 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10979): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10979): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiP2pService( 3512): DeviceAddress: 92:73:1c
E/WifiStateMachine( 3512): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL( 3512): callSECStringApiVoid - ID [215]
E/WifiNative-HAL( 3512): invaild command id : 215
D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
,D/WifiDisplayController( 3512): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note4-1
D/WifiDisplayController( 3512):  deviceAddress: 92:b6:86:43:73:1c
D/WifiDisplayController( 3512):  primary type: 10-0050F204-5
D/WifiDisplayController( 3512):  secondary type: null
D/WifiDisplayController( 3512):  wps: 0
D/WifiDisplayController( 3512):  grpcapab: 0
D/WifiDisplayController( 3512):  devcapab: 0
D/WifiDisplayController( 3512):  status: 3
D/WifiDisplayController( 3512):  wfdInfo: null
D/WifiDisplayController( 3512):  groupownerAddress: null
D/WifiDisplayController( 3512):  GOdeviceName: null
D/WifiDisplayController( 3512):  interfaceAddress: 
D/WifiDisplayController( 3512):  SConnectInfo : null
,D/WifiP2pService( 3512): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 3512): InactiveState
E/ConnectivityService( 3512): updateNetworkInfo()
D/WifiP2pService( 3512): InactiveState{ what=143376 }
D/WifiP2pService( 3512): P2pEnabledState{ what=143376 }
,D/TimaKeyStoreProvider(10979): TimaSignature is unavailable
D/ActivityThread(10979): Added TimaKeyStore provider
I/wpa_supplicant(10800): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
D/WifiP2pService( 3512): InactiveState{ what=143376 }
D/WifiP2pService( 3512): P2pEnabledState{ what=143376 }
,D/ResourcesManager(10979): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(10979): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 3512): Killing 7859:com.android.mms/u0a52 (adj 13): bgCount ##31
,D/CountryDetector( 3512): No listener is left
,I/wpa_supplicant(10800): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant(10800): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant(10800): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant(10800): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant(10800): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3512): [1,453,241,306,483 ms] noteScanEnd no scan source
E/WifiStateMachine( 3512): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@249b628c sup_state=SCANNING debouncing=false
E/WifiStateMachine( 3512): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3512): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
I/wpa_supplicant(10800): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant(10800): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3512): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3512): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3512): setDetailed state send new extra info"NG700"
I/wpa_supplicant(10800): Associated with C0.AA.48
D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
I/jxcore-log(10713): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(10713): 
,I/jxcore-log(10713): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(10713): 
,I/jxcore-log(10713): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(10713): 
,I/jxcore-log(10713): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(10713): 
,I/jxcore-log(10713): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(10713): 
,I/jxcore-log(10713): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(10713): 
,I/jxcore-log(10713): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(10713): 
,I/jxcore-log(10713): Test app app.js loaded
I/jxcore-log(10713): 
,I/chromium(10713): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10713): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(10713): BLE advertisement is supported
I/jxcore-log(10713): 
,I/wpa_supplicant(10800): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant(10800): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3512): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3512): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
,I/wpa_supplicant(10800): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant(10800): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant(10800): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3512): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3512): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant(10800): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(10800): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant(10800): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant(10800): Blacklist: Clear (temp) 
I/wpa_supplicant(10800): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3512): Network connection established
,D/WifiNative-HAL( 3512): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3512): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3512): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3512): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 3512): hsengiv:checkWhatTypeOfNetwork and the value is false
E/WifiStateMachine( 3512): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid null
D/ConnectivityService( 3512): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 3512): L2ConnectedState "NG700" nid=0
E/ConnectivityService( 3512): updateNetworkInfo()
E/WifiConfigStore( 3512): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3512): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine( 3512): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3512): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3512): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/ProcessCpuTracker( 3512): Skipping unknown process pid 11000
,D/CommandListener( 2845): Setting iface cfg
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3512): Start Dhcp Watchdog 1
,D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
,E/WifiStateMachine( 3512): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3512): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/Hs20UtilService( 6368): Starting #4
,I/Hs20UtilService( 6368): Message received 5007
,D/NearbySettings( 7946): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 7946): DMSUtil.isNetworkConnected - flag-null, state-null
,E/WifiStateMachine( 3512): Force RSSI Broadcast 1/3
,I/NearbySettings( 7946): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 7946): DMSUtil.isNetworkConnected - P2P: IDLE
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
I/NearbySettings( 7946): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7946): MountReceiver.onReceive - Set preference state off
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,V/NearbySettings( 7946): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver( 8376): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3512): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3512): do suspend false
,D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
D/WifiP2pService( 3512): InactiveState{ what=143375 }
,D/WifiP2pService( 3512): P2pEnabledState{ what=143375 }
,E/dhcpcd  (11015): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11015): version 5.5.6 starting
,E/dhcpcd  (11015): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11015): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11015): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11015): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (11015): bssid match
,I/dhcpcd  (11015): wlan0: rebinding lease of 192.168.1.124
,I/ActivityManager( 3512): Killing 10036:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,D/SSRM:n  ( 3512): SIOP:: AP = 270, PST = 266, CUR = 43
,I/PowerManagerService( 3512): [PWL] Off : 50s ago
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:-96, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryService( 3512): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10784): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dhcpcd  (11015): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (11015): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3512): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3512): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3512): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3512): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/btif_config_util(10784): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/PackageManager( 3512): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/WifiStateMachine( 3512): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3512): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  ( 3512): do suspend true,
,D/WifiP2pService( 3512): InactiveState{ what=143375 }
,D/WifiP2pService( 3512): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3512): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3512): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3512): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3512): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine( 3512): Not connected state, yet.
,E/WifiStateMachine( 3512): VerifyingLinkState enter
,D/WifiStateMachine( 3512): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine( 3512): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3512): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
,D/WifiNative-HAL( 3512): callSECApiInt - ID [210]
,E/WifiStateMachine( 3512): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3512): updateNetworkInfo()
,D/ConnectivityService( 3512): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 3512): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 3512): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3512): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3512): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3512): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3512): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine( 3512): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3512): Now, connected state.
E/WifiStateMachine( 3512): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 6368): Starting #5
,D/NearbySettings( 7946): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 3512): Adding Route [fe80::/64 -> :: wlan0] to network 502
E/WifiStateMachine( 3512): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/Hs20UtilService( 6368): Message received 5007
,I/WifiTrafficPoller( 3512): evaluateTrafficStatsPolling
,D/ConnectivityService( 3512): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,I/NearbySettings( 7946): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3512): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,E/ConnectivityService( 3512): Unexpected mtu value: 0, wlan0
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3512): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/        ( 2845): QcRouteController
,I/WifiTrafficPoller( 3512): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3512): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3512): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3512): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,V/        ( 2845): QcRouteController
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/SignOutReceiver( 8376): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 6368): Starting #6
,I/Hs20UtilService( 6368): Message received 5007
,V/        ( 2845): QcRouteController
D/NearbySettings( 7946): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 7946): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 7946): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 7946): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7946): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7946): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7946): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver( 8376): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 6368): Starting #7
,D/NearbySettings( 7946): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 7946): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 6368): Message received 5007
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/WifiStateMachine( 3512): callSECApi what=220
D/WifiStateMachine( 3512): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/SignOutReceiver( 8376): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3512): route cmd failed: 
W/NetworkManagementService( 3512): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '52 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 52 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3512): '
W/NetworkManagementService( 3512): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3512): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3512): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3512): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3512): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3512): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3512): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3512): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6313)
W/NetworkManagementService( 3512): 	at com.android.server.ConnectivityService.access$2700(ConnectivityService.java:231)
W/NetworkManagementService( 3512): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2449)
W/NetworkManagementService( 3512): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3512): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3512): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3512): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService( 3512): LTETest block dns file not exists
D/ConnectivityService( 3512): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
E/ConnectivityService( 3512): updateNetworkInfo()
E/ConnectivityService( 3512): updateNetworkInfo()
D/ConnectivityService( 3512): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3512): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): Connected
D/ConnectivityService( 3512): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): Checking http://clients3.google.com/generate_204 on "NG700"
I/SurfaceFlinger( 2849): id=13 createSurf (1x1),1 flag=4, Uoast
I/System.out( 3512): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3512): (HTTPLog)-Static: isShipBuild true
I/System.out( 3512): (HTTPLog)-Thread-187-198672711: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3512): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
D/PowerManagerService( 3512): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3512
D/ConnectivityService( 3512):    accepting network in place of null
D/ConnectivityService( 3512): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/TelephonyNetworkFactory( 3981): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/mali_winsys( 3693): new_window_surface returns 0x3000,  [1120x201]-format:1
E/CSLegacyTypeTracker( 3512): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3512): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService( 3512): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 3512): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering( 3512): MasterInitialState.processMessage what=3
D/SmartBondingService( 3512): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3512): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3512): getSBEnabled() enabled =false
D/SmartBondingService( 3512): getSBEnabled() enabled =false
D/SmartBondingService( 3512): getSBEnabled() enabled =false
V/NetworkStats( 3512): updateIfacesLocked()
V/NetworkStats( 3512): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3512): UpdateStatsForKnox
D/NtpTrustedTime( 3512): forceRefresh() from cache miss
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
D/ConnectivityService( 3512): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/SmartBondingService( 3512): getNetworkEnabled : wifi : true mobile : false
V/NetworkStats( 3512): performPollLocked() took 6ms
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 4483): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
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
,D/NtpTrustedTime( 3512): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1453241313436 mCachedNtpElapsedRealtime : 145442 mCachedNtpCertainty : 19
,D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
V/NetworkStats( 3512): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
,I/System.out( 3512): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 22:08:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453241312554], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453241312519]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): Validated
,D/ConnectivityService( 3512): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 3512): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 3512): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService( 3512): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 4483): CM callback handler got msg 524290
,D/ConnectivityService( 3512): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3512): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3512): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3512): SmartBondingReceiver: wifi is connected
,D/SmartBondingService( 3512): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/SmartBondingService( 3512): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3512): getSBEnabled() enabled =false
,D/SmartBondingService( 3512): getSBEnabled() enabled =false
,D/SmartBondingService( 3512): getSBEnabled() enabled =false
,I/DBG_DM  ( 5959): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 5959): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
,D/SmartBondingService( 3512): getNetworkEnabled : wifi : true mobile : false
,D/AlarmManagerService( 3512): Setting time of day to sec=1453241313
,D/AlarmManagerService( 3512): Trying to open a file
,D/AlarmManagerService( 3512): File Open Success
,D/AlarmManagerService( 3512): File Close Success
,I/AlarmManagerService( 3512): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 3512): waitForAlarm result :65536
,I/DBG_DM  ( 5959): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 5959): [IlIIlIIlIllllIlllIII(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 5959): [IlIlllIlllllIlIllllI(403/llllllIllIlIlllIIlIl)] Check completed.
,D/WifiStateMachine( 3512): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,I/DBG_DM  ( 5959): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_SET
,D/SettingsProvider( 3512): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 10060
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,I/DBG_DM  ( 5959): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/KeyguardEffectViewUtil( 3693): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3693): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3693): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{155b9a34 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{3934b05d V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3693): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{155b9a34 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3693): clearEffect
D/WallpaperWidget( 3693): setLockScreenWallpaper()
,D/KeyguardEffectViewUtil( 3693): getCurrentWallpaper() mWallpaperPath :null
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11137): MountEmulatedStorage()
E/Zygote  (11137): v2
I/libpersona(11137): KNOX_SDCARD checking this for 1000
I/libpersona(11137): KNOX_SDCARD not a persona
,I/SELinux (11137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3512): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11137 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (11137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11137): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Settings( 3512): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DBG_DM  ( 5959): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5959): [IIlIIIlllllIIlIIIlII(72/llllIIIllIlIIIIllllI)] 
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/SEC_DRM_PLUGIN_Playready( 2853): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1453241312 after conversion: 1453241312
W/SEC_DRM_PLUGIN_Playready( 2853): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1453241314 after conversion: 1453241314
,D/TimaKeyStoreProvider(11137): TimaSignature is unavailable
,D/ActivityThread(11137): Added TimaKeyStore provider
,I/DBG_DM  ( 5959): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 5959): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,W/appmanager(:<default>):QuickExperimentControllerImpl(10394): Exposure of experiment com.facebook.http.g.an@34003693 occurred when no user was logged in
,I/DBG_DM  ( 5959): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 5959): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,D/ResourcesManager(11137): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/DBG_DM  ( 5959): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 5959): [IlIIlIIlIllllIlllIII(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,W/appmanager(:<default>):QuickExperimentControllerImpl(10394): Exposure of experiment com.facebook.http.g.aw@37cce6c9 occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(10394): Exposure of experiment com.facebook.http.g.aj@3905b1ce occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(10394): Exposure of experiment com.facebook.http.g.a@16eda8ef occurred when no user was logged in
,I/DBG_DM  ( 5959): [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/PCWCLIENTTRACE_LOG(11137): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11137): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11137): new DMDBOpenHelper instance
,I/DBG_DM  ( 5959): [IlIIlIIlIllllIlllIII(1907/lllIlIlIIIllIIlIllIl)] 
,W/appmanager(:<default>):QuickExperimentControllerImpl(10394): Exposure of experiment com.facebook.http.g.k@21cf1cda occurred when no user was logged in
,I/DBG_DM  ( 5959): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 5959): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,I/DBG_DM  ( 5959): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(502/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/GoogleURLConnFactory( 4245): Using platform SSLCertificateSocketFactory
,I/PCWCLIENTTRACE_PushUtil(11137): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11137): sales region : global
I/PCWCLIENTTRACE_PushUtil(11137): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11137): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  (11163): MountEmulatedStorage()
E/Zygote  (11163): v2
I/libpersona(11163): KNOX_SDCARD checking this for 10090
I/libpersona(11163): KNOX_SDCARD not a persona
,I/SELinux (11163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=11163 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11163): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 6724): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/DBG_DM  ( 5959): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5959): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6724): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6724): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(11163): TimaSignature is unavailable
,D/ActivityThread(11163): Added TimaKeyStore provider
,E/Zygote  (11180): MountEmulatedStorage()
E/Zygote  (11180): v2
I/libpersona(11180): KNOX_SDCARD checking this for 10135
I/libpersona(11180): KNOX_SDCARD not a persona
,I/SELinux (11180): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/DBG_DM  ( 5959): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/SELinux (11180): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11180): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11180 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 5959): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 5959): [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,E/DBG_DM  ( 5959): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 5959): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@324405eb
,I/System.out(10394): Thread-1434(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(10394): Thread-1434(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10394): Thread-1434(ApacheHTTPLog):isShipBuild true
I/System.out(10394): Thread-1434(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/appmanager(:<default>):QuickExperimentControllerImpl(10394): Exposure of experiment com.facebook.http.g.c@1f3bc6e7 occurred when no user was logged in
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10110
,D/TimaKeyStoreProvider(11180): TimaSignature is unavailable
,D/ActivityThread(11180): Added TimaKeyStore provider
,I/DBG_DM  ( 5959): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
D/ResourcesManager(11163): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11199): MountEmulatedStorage()
E/Zygote  (11199): v2
I/libpersona(11199): KNOX_SDCARD checking this for 10050
I/libpersona(11199): KNOX_SDCARD not a persona
,I/SELinux (11199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=11199 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (11199): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/GpsLocationProvider( 3512): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider(11199): TimaSignature is unavailable
D/ActivityThread(11199): Added TimaKeyStore provider
D/ResourcesManager(11180): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/DBG_DM  ( 5959): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ResourcesManager(11199): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(11199): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11199): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(11199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11199): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,E/ActivityThread( 4483): Failed to find provider info for com.android.contacts.metadata
,W/ResourcesManager(11199): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(11199): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11199): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/KeyguardEffectViewUtil( 3693): set current wallpaper info
,D/SettingsProvider( 3512): name = keyguard_current_wallpaper_type
,D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 10060
,D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
I/PhenotypeConfigurator( 4245): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/SyncManager( 3512): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 15772, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 3512): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 178690, reason: UserStart
,W/ResourceType( 4958): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4958): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/dex2oat (11218): ----------------------------------------------------
I/dex2oat (11218): <SS>: S T A R T I N G . . .
I/dex2oat (11218): <SS>: Zip is absent. Canceled.
I/dex2oat (11218): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1844153020.jar --oat-fd=54 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1844153020.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/MusicStore(11180): Database version: 104
,D/SecContentProvider2( 3512): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3512): mCursor = null
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3512): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 10060
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,I/DBG_DM  ( 5959): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3512): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 10060
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,W/BackupManagerService( 3512): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/ResourcesManager(11180): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/StatusBar-DoNotDistrub( 3693): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 3693): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager(11180): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11180): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SecContentProvider2( 3512): uri = 14 selection = getSealedState
,D/SecContentProvider2( 3512): mCursor = null
,D/StatusBar-DoNotDistrub( 3693): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager( 2854): getOutputsForDevice device 0002 -> 0002
,I/AudioService( 3512): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 3693): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService( 3512): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
D/ApplicationPolicy( 3512): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
D/WindowManager( 3512): showStatusBarByNotification() mOpenByNotification=false
V/ApplicationPolicy( 3512): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/DBG_DM  ( 5959): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,D/ResourcesManager( 3693): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,I/DBG_DM  ( 5959): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/dex2oat (11218): dex2oat took 76.601ms (threads: 8)
,V/JNIHelp (11180): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/DelayedSyncController(11163): Delaying sync.
,D/PackageManager( 3512): findPreferredActivity: No PreferredActivities set
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/DBG_DM  ( 5959): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/DBG_DM  ( 5959): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DBG_DM  ( 5959): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,W/ActivityThread(11180): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11180): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b3fbb1d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11180): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11180): GMSCore installation verified
,I/ConfigStore(11180): Config Database version: 1
,D/NearbySource(11199): Nearby Source Create!
,D/NearbyContext(11199): Nearby Context Create!
,D/KnoxNotification( 3693): ----- inflateViews : modified publicViewLocal -----
I/System.out( 4245): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4245): Tagging socket 55 with tag 1000120300000000{268440067,0} uid -1, pid: 4245, getuid(): 10014
,D/KnoxNotification( 3693): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 3693): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 3693): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3951eb04
,D/PersonaManager( 3693): isKioskContainerExistOnDevice
D/PersonaManager( 3693): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3693): Icon Only
,I/StatusBar( 3693): Icon Only
,D/PanelView( 3693): There is/are notification(s) 
D/PanelView( 3693): There is/are notification(s) 
,D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
,D/KeyguardEffectViewUtil( 3693): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3693): isStrongPowerSavingMode() :false
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
D/KeyguardEffectViewController( 3693): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{155b9a34 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{3934b05d V.E..... ......I. 0,0-0,0}
W/ContextImpl(11199): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/VisualEffectParticleEffect( 3693): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{155b9a34 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3693): clearEffect
D/SLinkSource(11199): Samsung link source created
,W/ActivityThread(10394): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Auth.Api.Credentials( 4483): [CredentialSyncAdapter] Unknown sync event.
,D/ContactProvider(11199): getAllContactInfoList Start
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11180): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/PanelView( 3693): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11180): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11180): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ContactProvider(11199): getAllContactInfoList End
,I/syncContacts(11199): thread: 1488, sync time = 82
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 3512): Killing 10058:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/System.out(10394): P[5]_NetworkDispatch1 calls detatch()
,I/qtaguid ( 4245): Tagging socket 71 with tag 1000120300000000{268440067,0} uid -1, pid: 4245, getuid(): 10014
,D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3512): getStreamVolume 3 index 0
,I/MediaRouter(11180): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager( 3512): Killing 10079:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor(11180): type=WIFI subType= reason=null isConnected=true
,I/art     ( 3512): Explicit concurrent mark sweep GC freed 73339(3MB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 49MB/65MB, paused 2.041ms total 147.772ms
,E/Zygote  (11259): MountEmulatedStorage()
,E/Zygote  (11259): v2
I/libpersona(11259): KNOX_SDCARD checking this for 10002
I/libpersona(11259): KNOX_SDCARD not a persona
,I/SELinux (11259): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11259): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11259): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11259 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 848us total 23.067ms
,D/TimaKeyStoreProvider(11259): TimaSignature is unavailable
,D/ActivityThread(11259): Added TimaKeyStore provider
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.398ms total 19.982ms
,D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(11259): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3512): Killing 10099:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,I/NetworkMonitor(11180): type=WIFI subType= reason=null isConnected=true
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.031ms total 15.653ms
,I/System.out( 6724): Thread-680(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6724): Thread-680(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6724): Thread-680(ApacheHTTPLog):isShipBuild true
I/System.out( 6724): Thread-680(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/ActivityManager( 3512): Killing 10144:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10202
,I/qtaguid ( 6724): Tagging socket 53 with tag 0{0,0} uid -1, pid: 6724, getuid(): 10202
,D/PicasaService(11199): start picasa sync
,D/PicasaService(11199): end picasa sync
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11283): MountEmulatedStorage()
E/Zygote  (11283): v2
I/libpersona(11283): KNOX_SDCARD checking this for 1000
I/libpersona(11283): KNOX_SDCARD not a persona
,I/SELinux (11283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11283): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11283 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3512): Killing 10202:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11283): TimaSignature is unavailable
,D/ActivityThread(11283): Added TimaKeyStore provider
,D/ResourcesManager(11283): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11283): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DefaultRequestDirector( 6724): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 6724): Untagging socket 53
I/System.out( 6724): Thread-680 calls detatch()
,E/Volley  ( 6724): [680] xe.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,I/qtaguid ( 6724): Tagging socket 53 with tag 0{0,0} uid -1, pid: 6724, getuid(): 10202
,I/qtaguid ( 6724): Tagging socket 57 with tag 0{0,0} uid -1, pid: 6724, getuid(): 10202
,I/DIAGMON_AGENT(11283): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11283): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11283): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11283): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/DelayedSyncController(11163): Delaying sync.
,W/art     (10283): Attempt to remove local handle scope entry from IRT, ignoring
,W/DefaultRequestDirector( 6724): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 6724): Untagging socket 53
,I/System.out( 6724): Thread-680 calls detatch()
E/Volley  ( 6724): [680] xe.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10147
,W/PhenotypeConfigurator( 4245): Server returned 404
,E/YouTube ( 6724): apps.youtube.app.task.YouTubeNetworkTaskService.a:119 Failed to fetch settings
E/YouTube ( 6724): fdv: java.util.concurrent.ExecutionException: wb
E/YouTube ( 6724): 	at fco.a(SourceFile:103)
E/YouTube ( 6724): 	at fcp.c(SourceFile:160)
E/YouTube ( 6724): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:111)
E/YouTube ( 6724): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:49)
E/YouTube ( 6724): 	at emi.run(Unknown Source)
E/YouTube ( 6724): Caused by: java.util.concurrent.ExecutionException: wb
E/YouTube ( 6724): 	at xz.a(SourceFile:117)
E/YouTube ( 6724): 	at xz.get(SourceFile:88)
E/YouTube ( 6724): 	at gky.get(SourceFile:69)
E/YouTube ( 6724): 	at fco.a(SourceFile:99)
E/YouTube ( 6724): 	... 4 more
E/YouTube ( 6724): Caused by: wb
E/YouTube ( 6724): 	at xe.a(SourceFile:141)
E/YouTube ( 6724): 	at gkq.a(SourceFile:49)
E/YouTube ( 6724): 	at wk.run(SourceFile:105)
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11316): MountEmulatedStorage()
E/Zygote  (11316): v2
I/libpersona(11316): KNOX_SDCARD checking this for 10012
I/libpersona(11316): KNOX_SDCARD not a persona
,I/SELinux (11316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11316 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11316): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11316): TimaSignature is unavailable
,D/ActivityThread(11316): Added TimaKeyStore provider
,D/ChimeraCfgMgr( 4483): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4483): Module APK com.google.android.play.games already loaded
,D/ResourcesManager(11316): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/GamesSyncServiceMain( 4483): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 4483): Failed to execute periodic sync, missing client context - aborting
,I/FOTA_Client(11316): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11316): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11316): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  (11015): wlan0: sending IPv6 Router Solicitation
,E/Zygote  (11336): MountEmulatedStorage()
I/libpersona(11336): KNOX_SDCARD checking this for 10021
E/Zygote  (11336): v2
I/libpersona(11336): KNOX_SDCARD not a persona
,I/SELinux (11336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11336): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11336 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3512): Killing 10187:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11336): TimaSignature is unavailable
,D/ActivityThread(11336): Added TimaKeyStore provider
,D/ResourcesManager(11336): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11336): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 23:08:35 GMT+01:00 2016
,I/KLMS-2.4.521: (11336): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11336): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11336): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11336): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11336): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11336): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11336): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11336): StateImplV2(): networkChangeListener().START
,E/Zygote  (11353): MountEmulatedStorage()
E/Zygote  (11353): v2
I/libpersona(11353): KNOX_SDCARD checking this for 10038
I/libpersona(11353): KNOX_SDCARD not a persona
,I/SELinux (11353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (11336): NetworkChangeOperations(): uploadRequestLog().START 
,I/SELinux (11353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11353 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11336): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11336): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11336): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider(11353): TimaSignature is unavailable
,D/ActivityThread(11353): Added TimaKeyStore provider
,I/ActivityManager( 3512): Killing 10220:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/ResourcesManager(11353): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11353): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 4245): Vacuum at: now=1453241315528 tag=VacuumService
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11375): MountEmulatedStorage()
E/Zygote  (11375): v2
I/libpersona(11375): KNOX_SDCARD checking this for 1000
I/libpersona(11375): KNOX_SDCARD not a persona
,I/SELinux (11375): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11375): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11375): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11375 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3512): Killing 10235:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,D/TimaKeyStoreProvider(11375): TimaSignature is unavailable
,D/ActivityThread(11375): Added TimaKeyStore provider
,D/ResourcesManager(11375): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/System.out( 4245): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4245): Tagging socket 76 with tag 1000040100000000{268436481,0} uid 10014, pid: 4245, getuid(): 10014
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/qtaguid ( 4245): Tagging socket 79 with tag 1000040100000000{268436481,0} uid 10014, pid: 4245, getuid(): 10014
,E/Zygote  (11396): MountEmulatedStorage()
E/Zygote  (11396): v2
I/libpersona(11396): KNOX_SDCARD checking this for 10039
I/libpersona(11396): KNOX_SDCARD not a persona
,I/SELinux (11396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11396): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11396 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3512): Killing 10250:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11396): TimaSignature is unavailable
,D/ActivityThread(11396): Added TimaKeyStore provider
,D/ResourcesManager(11396): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(11396): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11396): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService(11396): PushLog.txt file is not deleted.
D/SPPClientService(11396): PushLog.txt file is not deleted.
,D/SPPClientService(11396): ============PushLog. stop!
E/SPPClientService(11396): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11414): MountEmulatedStorage()
E/Zygote  (11414): v2
I/libpersona(11414): KNOX_SDCARD checking this for 10045
I/libpersona(11414): KNOX_SDCARD not a persona
,I/SELinux (11414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3512): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=11414 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11414): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Killing 10334:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11414): TimaSignature is unavailable
,D/ActivityThread(11414): Added TimaKeyStore provider
,D/ResourcesManager(11414): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (11414): [SSP] onCreated
,I/SA      (11414): [TPM] There is no property file
,I/SA      (11414): [SCU] isHaveSA() - false
,I/SA      (11414): [TPM] getModelProperty : null
I/SA      (11414): [TPM] getCSCProperty : null
,I/SA      (11414): [DM] init START
,I/SA      (11414): [DM] This device is not a Vodafone
,I/SA      (11414): checkReactivationActive for LOLLIPOP
,I/SA      (11414): checkReactivationActive for reactiveActive
I/SA      (11414): setSupportRL : true
,I/SA      (11414): [SCU] isHaveSA() - false
I/SA      (11414): support phone number id : false
,I/SA      (11414): [DM] init END
I/SA      (11414): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11414): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11414): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11414): [SLFUCHKMGR] constructor called
,I/SA      (11414): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11414): [OR] == isSIMCardReady false ==
,I/SA      (11414): [SCU] == networkStateCheck == true
I/SA      (11414): [DM] getCountryCodeFromCSC : PL
I/SA      (11414): isChinaCountryCode : false
I/SA      (11414): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11414): [OR] == networkStateCheck true ==
,I/SA      (11414): [OR] GetMyCountryZoneTask
,I/SA      (11414): [OR] onReceive END
,I/SA      (11414): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5470): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11414): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11414): [SSP] query invoked
D/WifiStateMachine( 3512): updateConfiguredNetworkExpiration - currTime: 1453241315968
D/WifiStateMachine( 3512): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,I/SA      (11414): [TPMU] GetMccFromDB : null
I/SA      (11414): [SCU] getMccFromPreferece mcc = 260
I/SA      (11414): [TPM] isNoProxy(default) : true
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11437): MountEmulatedStorage()
,E/Zygote  (11437): v2
I/libpersona(11437): KNOX_SDCARD checking this for 10067
I/libpersona(11437): KNOX_SDCARD not a persona
,I/SELinux (11437): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11437): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11437 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (11437): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Killing 10353:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11437): TimaSignature is unavailable
,D/ActivityThread(11437): Added TimaKeyStore provider
,D/ResourcesManager(11437): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,E/AclDataUtils(10283): Circle ID not found for type: 9
,I/dex2oat (11455): ----------------------------------------------------
I/dex2oat (11455): <SS>: S T A R T I N G . . .
I/dex2oat (11455): <SS>: Zip is absent. Canceled.
,I/dex2oat (11455): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads2083481924.jar --oat-fd=97 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/cache/ads2083481924.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/sCloudBackupApp(11437): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11437): Other Intent
,I/ActivityManager( 3512): Killing 10370:com.facebook.system/u0a10 (adj 13): bgCount ##31
,W/IdleConnectionHandler(10394): Removing a connection that never existed!
,D/accuweather( 5259): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/dex2oat (11455): dex2oat took 42.357ms (threads: 8)
,I/ActivityManager( 3512): Killing 10475:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 10
,D/accuweather( 5259): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5259): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5259): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5259): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5259): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5259): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11467): MountEmulatedStorage()
I/libpersona(11467): KNOX_SDCARD checking this for 1000
E/Zygote  (11467): v2
I/libpersona(11467): KNOX_SDCARD not a persona
,I/SELinux (11467): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11467): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3512): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11467 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11467): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11467): TimaSignature is unavailable
,D/ActivityThread(11467): Added TimaKeyStore provider
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11467): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(11467): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(11467): premStatus:2
,I/KnoxUsageLogPro(11467): isEulaShown : false
I/KnoxUsageLogPro(11467): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(10834): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(10834): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10834): stopCheckCategoryVersion
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11483): MountEmulatedStorage()
,E/Zygote  (11483): v2
I/libpersona(11483): KNOX_SDCARD checking this for 10136
I/libpersona(11483): KNOX_SDCARD not a persona
,I/SELinux (11483): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11483): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11483 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11483): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Killing 10511:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11483): TimaSignature is unavailable
,D/ActivityThread(11483): Added TimaKeyStore provider
,D/ResourcesManager(11483): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/WifiStateMachine( 3512): REQUEST_POWER_SAVE_ON
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/SA      (11414): [RC New] Execute method=[GET] start
,E/WifiStateMachine( 3512): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      (11414): [RC New] Security=[true]
,I/System.out(11414): Thread-1530(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11414): Thread-1530(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11414): Thread-1530(ApacheHTTPLog):isShipBuild true
I/System.out(11414): Thread-1530(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10045
,I/WebViewFactory(11483): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11483): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11483): Loading: webviewchromium
,I/LibraryLoader(11483): Time to load native libraries: 5 ms (timestamps 8812-8817)
I/LibraryLoader(11483): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11483): Binding Chromium to main looper Looper (main, tid 1) {f9ef6bf}
,I/LibraryLoader(11483): Expected native library version number "",actual native library version number ""
,I/chromium(11483): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11483): Initializing chromium process, renderers=0
,W/art     (11483): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11483): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11483): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium(11483): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
W/AudioManagerAndroid(11483): Requires BLUETOOTH permission
,I/art     ( 3512): Explicit concurrent mark sweep GC freed 47865(2MB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 48MB/64MB, paused 1.940ms total 144.482ms
,I/SurfaceFlinger( 2849): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 3512): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3512) eventTime = 148959
D/PowerManagerService( 3512): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3512 (0x0)
D/PowerManagerService( 3512): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3512, ws=WorkSource{10060}) (elapsedTime=3614)
,I/NSApplication(11483): Starting up...
,D/OpenGLRenderer( 5959): Render dirty regions requested: true
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3512): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3512
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/OpenGLRenderer( 5959): Initialized EGL, version 1.4
,E/Zygote  (11566): MountEmulatedStorage()
E/Zygote  (11566): v2
I/libpersona(11566): KNOX_SDCARD checking this for 10150
I/libpersona(11566): KNOX_SDCARD not a persona
,I/SELinux (11566): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/OpenGLRenderer( 5959): HWUI protection enabled for context ,  &this =0xaf622088 ,&mEglDisplay = 1 , &mEglConfig = -1352277744 
,I/ActivityManager( 3512): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=11566 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/OpenGLRenderer( 5959): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 5959): Enabling debug mode 0
I/SELinux (11566): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11566): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/mali_winsys( 5959): new_window_surface returns 0x3000,  [616x201]-format:1
,I/ActivityManager( 3512): Killing 10526:com.android.calendar/u0a164 (adj 13): bgCount ##31
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8745(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 843us total 23.814ms
,D/TimaKeyStoreProvider(11566): TimaSignature is unavailable
,D/ActivityThread(11566): Added TimaKeyStore provider
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 967us total 18.851ms
,D/ResourcesManager(11566): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(11566): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11566): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11566): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/System.out( 4483): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4483): (HTTPLog)-Static: isShipBuild true
I/System.out( 4483): (HTTPLog)-Thread-316-849302090: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4483): (HTTPLog)-Static: isSBSettingEnabled false
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.224ms total 20.087ms
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4483): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4483): Tagging socket 97 with tag 1000010400000000{268435716,0} uid -1, pid: 4483, getuid(): 10014
,D/QuickConnect(11566): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect(11566): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(11566): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,I/ActivityManager( 3512): Killing 9806:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,I/iu.SyncManager( 4483): SYNC; picasa accounts
,D/NetworkLogImpl( 4483): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4483): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4483): num queued entries: 0
,I/iu.UploadsManager( 4483): num updated entries: 0
,I/iu.SyncManager( 4483): NEXT; no task
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/qtaguid ( 4483): Untagging socket 97
,E/Zygote  (11589): MountEmulatedStorage()
E/Zygote  (11589): v2
I/libpersona(11589): KNOX_SDCARD checking this for 10013
I/libpersona(11589): KNOX_SDCARD not a persona
,I/SELinux (11589): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11589): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11589): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=11589 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11589): TimaSignature is unavailable
,D/ActivityThread(11589): Added TimaKeyStore provider
,D/ResourcesManager(11589): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/WaitQueueForNetworkActivate(11589): notifyNetworkActivated
,W/ContextImpl(11589): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3512): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/SA      (11414): [RC New] [v2liruge] api execute + 657
I/SA      (11414): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11414): AsyncTask #1 calls detatch()
,I/System.out( 3512): Thread-148(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3512): Thread-148(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3512): Thread-148(ApacheHTTPLog):isShipBuild true
I/System.out( 3512): Thread-148(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
,I/SA      (11414): [TPMU] getNetworkMcc : 
,I/SA      (11414): [SCU] saveMccToPreferece Start
I/SA      (11414): [SCU] RegionMCC : 260
I/SA      (11414): [SSP] query invoked
,I/SA      (11414): [TPMU] GetMccFromDB : null
I/SA      (11414): [SCU] getMccFromPreferece mcc = 260
I/SA      (11414): [SCU] saveMccToPreferece End
,I/SA      (11414): [RC New] executeRequest [v2liruge] end. 707
I/SA      (11414): [RC New] Execute end
I/SA      (11414): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11414): [OR] GetMyCountryZoneTask Success
,D/ResourcesManager( 4245): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GCM     ( 4245): GCM config loaded
,D/hcjo    (11589): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(11589): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(11589): exit::IDLE
D/InitializeManagerStateMachine(11589): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(11589): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine(11589): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(11589): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11589): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(11589): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11589): entry::SUCCESS
D/hcjo    (11589): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (11589): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,I/FOTA_Client(11316): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/splitIntent( 3512): Split this intent : android.intent.action.TIME_SET !!   mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=17 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,I/splitIntent( 3512): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/hcjo    (11589): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (11589): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/FOTA_Client(11316): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/InitializeManagerStateMachine(11589): exit::SUCCESS
D/InitializeManagerStateMachine(11589): entry::IDLE
,E/Zygote  (11613): MountEmulatedStorage()
,E/Zygote  (11613): v2
I/libpersona(11613): KNOX_SDCARD checking this for 10052
I/libpersona(11613): KNOX_SDCARD not a persona
,I/SELinux (11613): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11613): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11613): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=11613 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11626): MountEmulatedStorage()
E/Zygote  (11626): v2
I/libpersona(11626): KNOX_SDCARD checking this for 10164
I/libpersona(11626): KNOX_SDCARD not a persona
I/SELinux (11626): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11626): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11626): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=11626 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11613): TimaSignature is unavailable
,D/ActivityThread(11613): Added TimaKeyStore provider
,I/KLMS-2.4.521: (11336): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Jan 19 23:08:37 GMT+01:00 2016
,D/daemonapp( 3776): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3776): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.4.521: (11336): KLMSAbstractReciever(): onReceive().END.
,D/TimaKeyStoreProvider(11626): TimaSignature is unavailable
,D/ActivityThread(11626): Added TimaKeyStore provider
D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11336): KLMSIntentService(): onCreate()
D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
I/KLMS-2.4.521: (11336): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (11336): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/daemonapp( 3776): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 3776): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3776): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
D/comsamsunglog( 3776): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3776): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 3776): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.4.521: (11336): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,E/Zygote  (11644): MountEmulatedStorage()
I/libpersona(11644): KNOX_SDCARD checking this for 10036
E/Zygote  (11644): v2
I/libpersona(11644): KNOX_SDCARD not a persona
I/SELinux (11644): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3512): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/com.cigna.mobile.coach.CoachBroadcastReceiver: pid=11644 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/daemonapp( 3776): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
I/SELinux (11644): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11644): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11336): KLMSIntentService(): TIME_CHANGED
,D/ResourcesManager(11613): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(11613): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/daemonapp( 3776): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 3776): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
W/ResourcesManager(11613): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11613): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11613): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(11613): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/daemonapp( 3776): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/KLMS-2.4.521: (11336): StateImplV2(): dateTimeChanged().START : Tue Jan 19 23:08:37 GMT+01:00 2016
,E/daemonapp( 3776): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/ResourcesManager(11626): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/TimaKeyStoreProvider(11644): TimaSignature is unavailable
,D/ActivityThread(11644): Added TimaKeyStore provider
,W/ResourcesManager(11626): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/KLMS-2.4.521: (11336): StateImplV2(): dateTimeChanged().END
,W/ResourcesManager(11626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(11626): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/comdaemonstockapp( 3776): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 3776): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
I/KLMS-2.4.521: (11336): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3512): Killing 10422:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/ResourcesManager(11644): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/CheckinService( 4483): Checkin interval check for package: unspecified last checkin: 1453082886478 min interval config: 0 actual interval: 158431204
,D/Mms/MmsApp(11613): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(11613): init before art
,D/Mms/ArtClassLoader(11613): init [DONE] art
,D/Mms/TelephonyPermission(11613): start operation mode monitor
,I/System.out( 3512): AsyncTask #4 calls detatch()
,W/System.err( 3512): java.io.IOException: Not Found
,D/ResourcesManager(11613): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
W/System.err( 3512): 	at a.d.b(Unknown Source)
W/System.err( 3512): 	at a.d.doInBackground(Unknown Source)
W/System.err( 3512): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 3512): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 3512): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3512): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 3512): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 3512): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager(11613): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission(11613): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(11613): isDefault true
,D/Mms/MmsApp(11613): onCreate() com.android.mms
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/MmsApp(11613): [start]    initCountryIso consume time = 39.821959
,D/CountryDetector( 3512): The first listener is added
,D/Mms/MmsApp(11613): [end]    initCountryIso consume time = 9.006625
,D/Mms/MmsConfig(11613): [start]    MmsConfig.init() consume time = 0.065166
,D/Mms/MmsConfig(11613): before partial update
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsConfig(11613): Load Resize quality : 80
,D/Mms/MmsConfig(11613):  enable multiwindow = true
,E/Zygote  (11672): MountEmulatedStorage()
E/Mms/MessageUtils(11613): setCountryDetector : update country detector info 
E/Mms/MessageUtils(11613): updateCountryIso : update country iso info 
,E/Zygote  (11672): v2
I/libpersona(11672): KNOX_SDCARD checking this for 10047
I/libpersona(11672): KNOX_SDCARD not a persona
,I/SELinux (11672): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3512): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=11672 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11672): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11672): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SecurityLogAgent(10850): KnoxConfiguration : Current State = 0
,D/SecurityLogAgent(10850): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent(10850): StateMachine : Initialized
,D/SecurityLogAgent(10850): StateMachine : Changed Current State = 0
,D/SecurityLogAgent(10850): StateMachine : Current State = 0
,D/Mms/PackageInfo(11613): com.sec.imsservice is not installed
,D/Mms/MmsConfig(11613): [end]    init() consume time = 48.92125
,D/Mms/Contact(11613): [start]    init() consume time = 1.541917
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11691): MountEmulatedStorage()
E/Zygote  (11691): v2
I/libpersona(11691): KNOX_SDCARD checking this for 10191
I/libpersona(11691): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider(11672): TimaSignature is unavailable
,I/SELinux (11691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3512): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=11691 uid=10191 gids={50191, 9997} abi=armeabi-v7a
,D/ActivityThread(11672): Added TimaKeyStore provider
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): checkState() : APP TYPE = Full
,I/SELinux (11691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11691): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/Contact(11613): [end]    init consume time = 23.129958
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
D/Mms/DraftCache(11613): [start]    rebuildCache consume time = 5.19325
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/Mms/TelephonyUtils(11613): getSubId from simSlot 0, return Value = -1
D/TP/MmsSmsProvider( 3981): query,matched:13, calling pid = 11613
,D/TP/MmsSmsProvider( 3981): match 13:Elapsed time : 3.074 ms
D/Mms/DownloadManager(11613): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11613): [NotificationTransaction] getAutoDownloadState simSlot : 0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
D/Mms/DownloadManager(11613): auto download without roaming -> true
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
D/Mms/DownloadManager(11613): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Mms/TelephonyUtils(11613): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(11613): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(11613): roaming -> false (slotId = 1)
D/Mms/DownloadManager(11613): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(11613): auto download without roaming -> true
D/Mms/DownloadManager(11613): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(11613): auto download during roaming secondary -> false
D/Mms/DownloadManager(11613): mAutoDownload ------> true
,D/TimaKeyStoreProvider(11691): TimaSignature is unavailable
,D/ResourcesManager(11672): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
D/ActivityThread(11691): Added TimaKeyStore provider
,E/Zygote  (11709): MountEmulatedStorage()
E/Zygote  (11709): v2
I/libpersona(11709): KNOX_SDCARD checking this for 10019
I/libpersona(11709): KNOX_SDCARD not a persona
,W/ResourcesManager(11672): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/SELinux (11709): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11709): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11709): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=11709 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/TP/MmsSmsProvider( 3981): query,matched:12, calling pid = 11613
,D/TP/MmsSmsProvider( 3981): match 12:Elapsed time : 1.773 ms
,D/Mms/MmsApp(11613): [end]    onCreate() consume time = 51.488792
,D/Mms/Conversation(11613): [start]    init() consume time = 2.363292
,D/Mms/DraftCache(11613): [end]    rebuildCache consume time = 1.725333
D/TP/MmsSmsProvider( 3981): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 3981): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,I/CalendarProvider2(11672): CalendarProvider2.onCreate() called
,D/TimaKeyStoreProvider(11709): TimaSignature is unavailable
,D/ActivityThread(11709): Added TimaKeyStore provider
,D/ResourcesManager(11691): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
,W/ResourcesManager(11691): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 3981): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 3981): need read changed broadcast:false
,D/Mms/Conversation(11613): [end]    init consume time = 17.911958
,D/ResourcesManager(11709): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/Mms/MessagingNotification(11613): [start]    init() consume time = 1.432167
,D/Mms/DownloadManager(11613): Service state changed: Bundle[mParcelledData.dataSize=692]
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/Mms/DownloadManager(11613): roaming ------> false, mSimSlot = 0
,D/Mms/TelephonyUtils(11613): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(11613): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11613): [NotificationTransaction] getAutoDownloadState simSlot : 0
,D/Mms/DownloadManager(11613): auto download without roaming -> true
D/Mms/DownloadManager(11613): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(11613): mAutoDownload ------> true
,E/Zygote  (11726): MountEmulatedStorage()
E/Zygote  (11726): v2
I/libpersona(11726): KNOX_SDCARD checking this for 10069
I/libpersona(11726): KNOX_SDCARD not a persona
,I/SELinux (11726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=11726 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11726): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Killing 10873:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,I/ActivityManager( 3512): Killing 10119:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/Mms/MessagingNotification(11613): [end]    init consume time = 35.500083
,D/Mms/Synchronizer(11613): [start]    doSync consume time = 2.210167
,D/TP/MmsSmsProvider( 3981): query,matched:0, calling pid = 11613
V/TP/MmsSmsProvider( 3981): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3981): match 0:Elapsed time : 1.404 ms
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/TP/MmsSmsProvider( 3981): update uri: content://mms-sms/db_synchronization
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthServiceInstalled() : HealthService is Installed.
V/TP/MmsSmsProvider( 3981): syncDBData start
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthServiceInstalled() : HealthService is Installed.
,V/TP/MmsSmsProvider( 3981): syncDBData sms end
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/TP/MmsSmsProvider( 3981): syncDBData mms end
,V/TP/MmsSmsProvider( 3981): syncDBData end
D/TimaKeyStoreProvider(11726): TimaSignature is unavailable
,D/Mms/Synchronizer(11613): [end]    doSync consume time = 10.842417
,D/ActivityThread(11726): Added TimaKeyStore provider
,D/Mms/SpamFilter(11613): [start]    SpamFilter fill() begin consume time = 3.680291
,D/com.sec.android.service.health.keyManager.KeyManager(11644): Current encrypted state : -1
,E/JavaBinder(11613): !!! FAILED BINDER TRANSACTION !!!
,D/Mms/MessagingNotification(11613): checkBadgeCount unreadCount=0 badgeCount=0
,I/SecSQLiteOpenHelper(11644): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper(11644): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11644): Open platform.db in secure mode
,D/SecSQLiteDatabase(11644): Android Version: 5.0.1
D/SecSQLiteDatabase(11644): Load library secsqlite.so for Android 5.0.1
,D/TP/MmsSmsProvider( 3981): query,matched:400, calling pid = 11613
,D/TP/SmsProvider( 3981): query,matched:26, calling pid = 11613
,D/TP/SmsProvider( 3981): match 26:Elapsed time : 1.316 ms
,D/ResourcesManager(11726): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,I/SecSQLiteDatabase(11644): openSecureDatabase...
,I/SecSQLiteDatabase(11644): private openSecureDatabase...
,I/SecSQLiteConnectionPool(11644): OpenSecure
I/SecSQLiteConnectionPool(11644): OpenSecure with password
I/SecSQLiteConnectionPool(11644): openSecureConnectionLocked
,I/SecSQLiteDatabase(11644): ...private openSecureDatabase
I/SecSQLiteDatabase(11644): ...openSecureDatabase
,D/Mms/SpamFilter(11613): [end]    SpamFilter fill() finished consume time = 33.789709
,D/TP/MmsSmsProvider( 3981): query,matched:6, calling pid = 11613
,D/TP/MmsSmsProvider( 3981): match 6:Elapsed time : 1.539 ms
,I/Mms/ReservationManager(11613): ReservationManager()
,I/Mms/ReservationManager(11613): resetAfterConnected()
,D/TP/MmsSmsProvider( 3981): query,matched:7, calling pid = 11613
,D/TP/MmsSmsProvider( 3981): match 7:Elapsed time : 3.529 ms
,I/Mms/ReservationManager(11613): getReservedSendMessageCount(): retMessageCount=0
,E/SQLiteLog(11644): (26) statement aborts at 0: [PRAGMA user_version;] file is encrypted or is not a database
,E/SecDefaultDatabaseErrorHandler(11644): Corruption reported by sqlite on database: /data/data/com.sec.android.app.shealth/databases/platform.db
E/SecDefaultDatabaseErrorHandler(11644): backup the database file: /data/data/com.sec.android.app.shealth/databases/platform.db
,D/SecSQLiteOpenHelper(11644): ...getDatabaseLocked(b,b,pwd)
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11749): MountEmulatedStorage()
E/Zygote  (11749): v2
I/libpersona(11749): KNOX_SDCARD checking this for 10028
I/libpersona(11749): KNOX_SDCARD not a persona
,I/SELinux (11749): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3512): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=11749 uid=10028 gids={50028, 9997} abi=armeabi-v7a
I/SELinux (11749): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11749): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Killing 10494:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/accuweather( 5259): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,I/ActivityManager( 3512): Killing 10979:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31
,D/accuweather( 5259): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ Time Manager (11726): Time Difference not stored. TIME_DIFFERENCE
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/SecureStorage(11709): [INFO]: SPID(0x00000000)Processing data
,D/TimaKeyStoreProvider(11749): TimaSignature is unavailable
,D/ActivityThread(11749): Added TimaKeyStore provider
,I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Credentials: uid 10019, gid 10019, pid 11709
I/SecureStorage( 2917): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/Zygote  (11764): MountEmulatedStorage()
E/Zygote  (11764): v2
I/libpersona(11764): KNOX_SDCARD checking this for 10094
I/libpersona(11764): KNOX_SDCARD not a persona
,I/SELinux (11764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3512): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=11764 uid=10094 gids={50094, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11764): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Killing 7946:com.android.settings/1000 (adj 13): bgCount ##31
,D/ResourcesManager(11749): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,D/TimaKeyStoreProvider(11764): TimaSignature is unavailable
,D/ActivityThread(11764): Added TimaKeyStore provider
,W/ResourcesManager(11749): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager(11764): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,W/ResourcesManager(11764): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager(11764): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11764): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11764): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(11764): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11764): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/OMACP   (11749): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/WifiService( 3512): Client connection lost with reason: 4
,D/Mms/Omacp(11613): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/Mms/ArtClassLoader(11613): init before art
D/Mms/ArtClassLoader(11613): init [DONE] art
,D/Mms/PerformanceUtils(11613): link cahcing start
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   (11749): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/Mms/PerformanceUtils(11613): link cahcing done
,D/SettingsProvider( 3512): name = next_alarm_formatted
D/SettingsProvider( 3512): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3512): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3512): selectionArgs: false
D/SettingsProvider( 3512): selectionArgs: 10094
D/SecContentProvider( 3512): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3512): ret = -1
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11782): MountEmulatedStorage()
,E/Zygote  (11782): v2
I/libpersona(11782): KNOX_SDCARD checking this for 10106
I/libpersona(11782): KNOX_SDCARD not a persona
,I/SELinux (11782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3512): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11782 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
I/SELinux (11782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3512): Killing 8376:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
E/SELinux (11782): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8721(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 814us total 20.524ms
,D/TimaKeyStoreProvider(11782): TimaSignature is unavailable
,D/ActivityThread(11782): Added TimaKeyStore provider
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 806us total 17.786ms
,D/ResourcesManager(11782): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/elm:14491(11782): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491(11782): ELMEngine.ELMEngine( context ).
,D/elm:14491(11782): MDMBridge.setEnterpriseBridge()
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 615us total 19.198ms
,D/elm:14491(11782): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/elm:14491(11782): ElmAgentService : onCreate()
,D/elm:14491(11782): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14491(11782): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491(11782): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491(11782): ModuleBase.ModifySetAlarm()
D/elm:14491(11782): MDMBridge.getInstance()
D/elm:14491(11782): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (11799): MountEmulatedStorage()
E/Zygote  (11799): v2
I/libpersona(11799): KNOX_SDCARD checking this for 10163
I/libpersona(11799): KNOX_SDCARD not a persona
,I/SELinux (11799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=11799 uid=10163 gids={50163, 9997} abi=armeabi-v7a
,E/SELinux (11799): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/elm:14491(11782): ElmAgentService : onDestroy().
,I/ActivityManager( 3512): Killing 10394:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11799): TimaSignature is unavailable
,D/ActivityThread(11799): Added TimaKeyStore provider
,D/ResourcesManager(11799): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(11799): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11799): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/ActivityManager( 3512): Killing 11137:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,I/SecureStorage( 2917): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(11709): [INFO]: SPID(0x00000006)Processing data has been completed
,I/SecureStorage(11709): [INFO]: SPID(0x00000006)Skip using SecureStorageExceptionJNI
,I/SecSQLiteOpenHelper(11644): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11644): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11644): Open platform.db in secure mode
I/SecSQLiteDatabase(11644): openSecureDatabase...
I/SecSQLiteDatabase(11644): private openSecureDatabase...
I/SecSQLiteConnectionPool(11644): OpenSecure
I/SecSQLiteConnectionPool(11644): OpenSecure with password
I/SecSQLiteConnectionPool(11644): openSecureConnectionLocked
I/SecSQLiteDatabase(11644): ...private openSecureDatabase
I/SecSQLiteDatabase(11644): ...openSecureDatabase
,I/CalendarProvider2(11672): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager( 3512): Killing 11180:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,I/SecSQLiteOpenHelper(11644): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11644): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/-----SIC-----(11644): ------------------skip TGH
,I/SecSQLiteOpenHelper(11644): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11644): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11644): Open platform.db in secure mode
I/SecSQLiteDatabase(11644): openSecureDatabase...
I/SecSQLiteDatabase(11644): private openSecureDatabase...
I/SecSQLiteConnectionPool(11644): OpenSecure
I/SecSQLiteConnectionPool(11644): OpenSecure with password
I/SecSQLiteConnectionPool(11644): openSecureConnectionLocked
I/SecSQLiteDatabase(11644): ...private openSecureDatabase
I/SecSQLiteDatabase(11644): ...openSecureDatabase
,I/SecSQLiteOpenHelper(11644): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11644): ...getDatabaseLocked(b,b,pwd)
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11644): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11644): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer(11644): decode(34, 20909908, 4230)
,V/AlarmManager( 3512): waitForAlarm result :4
,V/MediaPlayerService( 2854): decode(24, 20909908, 4230)
,V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
,V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
,V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20909908, 4230)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
,V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
,V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/SO_AGENT(11353): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 5, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
,I/SA      (11414): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2854): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 6, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
I/AudioPlayer( 2854): First fillBuffer call!!
V/MediaPlayerService( 2854): wait for playback complete
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2854): onCheckAudioStatus
V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2854): addBatteryData
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
,I/AudioPlayer( 2854): reset out
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
,V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
,V/MediaPlayer(11644): decode(35, 20763080, 15440)
,V/MediaPlayerService( 2854): decode(24, 20763080, 15440)
,V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
,V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20763080, 15440)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
,V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder',
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 2854): notify(0xae721740, 5, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
,V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2854): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 6, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
I/AudioPlayer( 2854): First fillBuffer call!!
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2854): wait for playback complete
,I/ActivityManager( 3512): Killing 11259:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthServiceInstalled() : HealthService is Installed.
,V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2854): onCheckAudioStatus
V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2854): addBatteryData
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
D/AdaptiveEventManager( 3693): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
D/AdaptiveEventManager( 3693): M updateContainers()
D/AdaptiveEventContainerSmall( 3693): C updatePedoContainer()
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
D/AdaptiveEventContainerSmall( 3693): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3693): pedoEvent == null
,D/AdaptiveEventManager( 3693): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/AdaptiveEventManager( 3693): M updateContainers()
D/AdaptiveEventContainerSmall( 3693): C updatePedoContainer()
,D/AdaptiveEventContainerSmall( 3693): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3693): pedoEvent == null
,I/AudioPlayer( 2854): reset out
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
,V/AwesomePlayer( 2854): reset_l(),
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
I/ActivityManager( 3512): Killing 11199:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
,W/System.err(10014): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted,
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
,V/MediaPlayer(11644): decode(36, 20807608, 9226)
V/MediaPlayerService( 2854): decode(24, 20807608, 9226)
V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
,V/AwesomePlayer( 2854): constructor
W/System.err(10014): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
,V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20807608, 9226)
V/AwesomePlayer( 2854): reset_l(),
,V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 8, 0, 0)
V/AudioCache( 2854): ignored
,V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
,V/MediaPlayerService( 2854): wait for prepare
W/System.err(10014): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err(10014): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err(10014): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err(10014): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
W/System.err(10014): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
,W/System.err(10014): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
W/System.err(10014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10014): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10014): 	,at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10014): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10014): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10014): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10014): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 5, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2854): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 6, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
V/MediaPlayerService( 2854): wait for playback complete
,I/AudioPlayer( 2854): First fillBuffer call!!
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
V/AwesomePlayer( 2854): onCheckAudioStatus
V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): addBatteryData
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
I/AudioPlayer( 2854): reset out
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/MediaPlayer(11644): decode(37, 20914220, 4890)
V/MediaPlayerService( 2854): decode(24, 20914220, 4890)
V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20914220, 4890)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 5, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2854): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 6, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
V/MediaPlayerService( 2854): wait for playback complete
I/AudioPlayer( 2854): First fillBuffer call!!
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
W/System.err(11644): java.lang.NumberFormatException: Invalid int: "null"
W/System.err(11644): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err(11644): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err(11644): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err(11644): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:498)
W/System.err(11644): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1242)
W/System.err(11644): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11644): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11644): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
V/AwesomePlayer( 2854): onCheckAudioStatus
V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2854): addBatteryData
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2854): notify(0xb040f240, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
I/AudioPlayer( 2854): reset out
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/MediaPlayer(11644): decode(38, 20840384, 17329)
V/MediaPlayerService( 2854): decode(24, 20840384, 17329)
V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20840384, 17329)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 5, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2854): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 6, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
I/AudioPlayer( 2854): First fillBuffer call!!
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
V/MediaPlayerService( 2854): wait for playback complete
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
V/AwesomePlayer( 2854): onCheckAudioStatus
V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2854): addBatteryData
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
I/AudioPlayer( 2854): reset out
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/MediaPlayer(11644): decode(39, 20740576, 6644)
V/MediaPlayerService( 2854): decode(24, 20740576, 6644)
V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20740576, 6644)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 5, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2854): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 6, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
I/AudioPlayer( 2854): First fillBuffer call!!
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2854): wait for playback complete
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
V/AwesomePlayer( 2854): onCheckAudioStatus
V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2854): addBatteryData
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
I/AudioPlayer( 2854): reset out
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/MediaPlayer(11644): decode(41, 20816916, 23389)
V/MediaPlayerService( 2854): decode(24, 20816916, 23389)
V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20816916, 23389)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 5, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2854): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 6, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
I/AudioPlayer( 2854): First fillBuffer call!!
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
V/MediaPlayerService( 2854): wait for playback complete
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
V/AwesomePlayer( 2854): onCheckAudioStatus
V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2854): addBatteryData
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
I/AudioPlayer( 2854): reset out
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/MediaPlayer(11644): decode(43, 20706272, 8154)
V/MediaPlayerService( 2854): decode(24, 20706272, 8154)
V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20706272, 8154)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 5, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
I/art     ( 3512): Explicit concurrent mark sweep GC freed 27574(1539KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 48MB/64MB, paused 1.551ms total 149.542ms
I/splitIntent( 3512): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2854): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 6, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
I/AudioPlayer( 2854): First fillBuffer call!!
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
V/AwesomePlayer( 2854): onCheckAudioStatus
V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/MediaPlayerService( 2854): wait for playback complete
V/AwesomePlayer( 2854): addBatteryData
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
,I/AudioPlayer( 2854): reset out
,V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
,V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
,E/DatabaseUtils( 3512): Writing exception to parcel
E/DatabaseUtils( 3512): java.lang.NullPointerException: key == null
E/DatabaseUtils( 3512): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils( 3512): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils( 3512): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils( 3512): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:376)
,E/DatabaseUtils( 3512): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils( 3512): 	at android.os.Binder.execTransact(Binder.java:446)
V/MediaPlayer(11644): decode(42, 20679752, 4804)
V/MediaPlayerService( 2854): decode(24, 20679752, 4804)
V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
,V/StagefrightPlayer( 2854): initCheck
V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20679752, 4804)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2854): notify(0xb040f240, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
,V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
,I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
,V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
,V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 5, 0, 0)
,V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
,V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2854): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 6, 0, 0)
,V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
V/MediaPlayerService( 2854): wait for playback complete
,I/dhcpcd  (11015): wlan0: sending IPv6 Router Solicitation
,I/AudioPlayer( 2854): First fillBuffer call!!
,I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2854): onCheckAudioStatus
V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 7, 0, 0)
V/AudioCache( 2854): ignored
,V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2854): addBatteryData
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2854): notify(0xb040f240, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x84, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
,I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
I/AudioPlayer( 2854): reset out
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
,I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/MediaPlayer(11644): decode(44, 20649204, 9400)
,V/MediaPlayerService( 2854): decode(24, 20649204, 9400)
V/MediaPlayerService( 2854): player type = 3
,V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
,V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20649204, 9400)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/MediaPlayer(11644): decode(51, 20722624, 4112)
V/MediaPlayerService( 2854): decode(34, 20722624, 4112)
,V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
,V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
,V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/AwesomePlayer( 2854): reset_l()
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/MediaPlayerService( 2854): wait for prepare
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
V/AwesomePlayer( 2854): setAudioSink
,V/StagefrightPlayer( 2854): setDataSource(34, 20722624, 4112)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
,V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
,V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
,V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
,I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 5, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 2854): notify(0xb040f060, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2854): notify(0xb040f1f0, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 5, 0, 0)
,V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start,
V/StagefrightPlayer( 2854): start
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:1, 1, 0
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2854): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 6, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
I/AudioPlayer( 2854): First fillBuffer call!!
V/MediaPlayerService( 2854): wait for playback complete
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
,E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream,
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2854): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 6, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
V/MediaPlayerService( 2854): wait for playback complete
,I/AudioPlayer( 2854): First fillBuffer call!!
V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
V/AwesomePlayer( 2854): onCheckAudioStatus
V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2854): addBatteryData
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x86, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
I/AudioPlayer( 2854): reset out
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
V/AwesomePlayer( 2854): onCheckAudioStatus
,V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache( 2854): notify(0xb040f060, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2854): addBatteryData
,V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x85, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/libpersona(11885): KNOX_SDCARD checking this for 10022
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/libpersona(11885): KNOX_SDCARD not a persona
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
E/Zygote  (11885): MountEmulatedStorage()
E/Zygote  (11885): v2
,I/AudioPlayer( 2854): reset out
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
,V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
,V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/MediaPlayer(11644): decode(45, 20857804, 52024)
,V/MediaPlayerService( 2854): decode(24, 20857804, 52024)
I/SELinux (11885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,V/MediaPlayerService( 2854): player type = 3
I/ActivityManager( 3512): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=11885 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20857804, 52024)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
I/SELinux (11885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11885): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
,V/AwesomePlayer( 2854): prepareAsync
V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
,I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 5, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2854): open(48000, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 6, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
I/AudioPlayer( 2854): First fillBuffer call!!
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,V/MediaPlayerService( 2854): wait for playback complete
,D/TimaKeyStoreProvider(11885): TimaSignature is unavailable
,D/ActivityThread(11885): Added TimaKeyStore provider
,D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(11885): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11885): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11885): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
V/AwesomePlayer( 2854): onCheckAudioStatus
V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2854): addBatteryData
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
,V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xae721740, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x87, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
,I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
,I/AudioPlayer( 2854): reset out
,V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
,V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/MediaPlayer(11644): decode(46, 20722624, 4112)
V/MediaPlayerService( 2854): decode(24, 20722624, 4112)
,V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
,V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20722624, 4112)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
,V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
I/LocationWidgetApplication(11885): onCreate() : start
D/LocationWidgetApplication(11885): countryCode = POLAND
V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
,V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
,V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
,V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 5, 0, 0)
V/AudioCache( 2854): ignored
,V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 2854): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 6, 0, 0)
V/AudioCache( 2854): ignored
,V/AwesomePlayer( 2854): addBatteryData
I/AudioPlayer( 2854): First fillBuffer call!!
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
,E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2854): wait for playback complete
V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
V/AwesomePlayer( 2854): onCheckAudioStatus
,V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
,V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2854): addBatteryData
,V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f420, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x88, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
D/LocationWidgetUtils(11885): getUpcommingInstances() start: 1453241319512, end: 1453762799999
D/LocationWidgetUtils(11885): getUpcommingInstances() DB begin time >= start:1453241319512, DB begin time <= end:1453762799999
I/AudioPlayer( 2854): reset out
,V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
,V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/MediaPlayer(11644): decode(47, 20785700, 21825)
V/MediaPlayerService( 2854): decode(24, 20785700, 21825)
V/MediaPlayerService( 2854): player type = 3
,V/AwesomePlayer( 2854): setDefault
,V/AwesomePlayer( 2854): constructor
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
,V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20785700, 21825)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
,V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
,V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate,
V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
V/MediaPlayerService( 2854): wait for prepare
,V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
,I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
,V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 5, 0, 0)
,V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 1, 0, 0)
V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
,V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2854): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 6, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): addBatteryData
I/AudioPlayer( 2854): First fillBuffer call!!
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,V/MediaPlayerService( 2854): wait for playback complete
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
V/AwesomePlayer( 2854): onCheckAudioStatus
V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2854): addBatteryData
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
,V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f240, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x89, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
,I/AudioPlayer( 2854): reset out
,V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
D/com.sec.android.service.health.cp.common.HttpConnectionConstants(11644): RegionGroup for  is null
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
,V/MediaPlayer(11644): decode(48, 20684636, 21552)
V/MediaPlayerService( 2854): decode(24, 20684636, 21552)
,V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
,V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20684636, 21552)
,V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
,V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
V/AwesomePlayer( 2854): prepareAsync
,V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
,I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthServiceInstalled() : HealthService is Installed.
,I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,D/SHealthUpgrade(SHealthUpgradeUtil)(11644): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 200, 973, 0)
,V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 5, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 1, 0, 0)
,V/AudioCache( 2854): prepared
V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:2, 1, 0
,I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2854): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 6, 0, 0)
V/AudioCache( 2854): ignored
,V/AwesomePlayer( 2854): addBatteryData
I/AudioPlayer( 2854): First fillBuffer call!!
,I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
V/MediaPlayerService( 2854): wait for playback complete
,D/LocationManagerService( 3512): getProviders()=[]
D/LocationManagerService( 3512): getProviders()=[passive]
E/SQLiteLog(11672): (284) automatic index on view_events(_id)
D/LocationManagerService( 3512): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2854): onCheckAudioStatus
,V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache( 2854): notify(0xb040f1f0, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2854): addBatteryData
,V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f1f0, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x8a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
,I/AudioPlayer( 2854): reset out
,V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/MediaPlayer(11644): decode(49, 20778600, 7017)
V/MediaPlayerService( 2854): decode(24, 20778600, 7017)
,V/MediaPlayerService( 2854): player type = 3
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): constructor
V/AwesomePlayer( 2854): setDefault
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): StagefrightPlayer
V/AwesomePlayer( 2854): setListener
V/StagefrightPlayer( 2854): initCheck
V/AwesomePlayer( 2854): setAudioSink
V/StagefrightPlayer( 2854): setDataSource(24, 20778600, 7017)
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
,V/AwesomePlayer( 2854): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2854): mBitrate = -1 bits/sec
I/OggExtractor( 2854): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2854): current audio track index (0) is added to vector
V/AwesomePlayer( 2854): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2854): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2854): prepare
,V/AwesomePlayer( 2854): prepareAsync
V/MediaPlayerService( 2854): wait for prepare
V/AwesomePlayer( 2854): onPrepareAsyncEvent
I/SecMediaClock( 2854): SecMediaClock constructor
I/SecMediaClock( 2854): reset
I/SecVideoCapture( 2854): SecVideoCapture constructor
I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): initAudioDecoder
,V/AwesomePlayer( 2854): checkOffloadExceptions is true
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2854): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2854): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16,
I/AwesomePlayer( 2854): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2854): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2854): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2854): finishAsyncPrepare_l
V/AwesomePlayer( 2854): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2854): notify(0xb040f060, 200, 973, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 2854): notify(0xb040f060, 5, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 1, 0, 0)
V/AudioCache( 2854): prepared
,V/AudioCache( 2854): wait - success
V/MediaPlayerService( 2854): start
V/StagefrightPlayer( 2854): start
V/AwesomePlayer( 2854): play
V/AwesomePlayer( 2854): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2854): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2854): >>>UHQA initOutputFormat 16
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2854): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 2854): open(44100, 2, 0x0, 1, 0)
D/LWLocationManager(11885): mPrivacy is null
D/CalendarAlarmManager(11672): sys current time:1453241319615
,V/AwesomePlayer( 2854): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 6, 0, 0)
V/AudioCache( 2854): ignored
,V/AwesomePlayer( 2854): addBatteryData
I/AudioPlayer( 2854): First fillBuffer call!!
I/AudioPlayer( 2854): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2854): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,V/MediaPlayerService( 2854): wait for playback complete
D/CalendarAlarmManager(11672): reminder amount:0
W/ContextImpl(11885): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2854): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2854): onCheckAudioStatus
,V/AwesomePlayer( 2854): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2854): onStreamDone
V/AwesomePlayer( 2854): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2854): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 2, 0, 0)
V/AudioCache( 2854): playback complete - thread will wake up later
,V/AwesomePlayer( 2854): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 7, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2854): addBatteryData
V/AudioCache( 2854): wait - success
V/StagefrightPlayer( 2854): reset
,V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2854): notify(0xb040f060, 8, 0, 0)
V/AudioCache( 2854): ignored
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stop() sendCommand(0x8b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2854): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2854): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2854): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2854): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2854): ~OggSource --
I/OggExtractor( 2854): ~OggExtractor ++
I/OggExtractor( 2854): ~MyVorbisExtractor ++ 
I/OggExtractor( 2854): ~MyVorbisExtractor --
I/OggExtractor( 2854): ~OggExtractor --
,I/AudioPlayer( 2854): reset out
V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2854): SecVideoCapture destructor
,I/SecVideoCapture( 2854): reset
V/AwesomePlayer( 2854): mSecCapture clear
I/SecMediaClock( 2854): SecMediaClock destructor
V/AwesomePlayer( 2854): mSecMediaClock clear
V/StagefrightPlayer( 2854): ~StagefrightPlayer
,V/StagefrightPlayer( 2854): reset
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
,V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
V/AwesomePlayer( 2854): destructor
V/AwesomePlayer( 2854): reset_l()
V/AwesomePlayer( 2854): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2854): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2854): mAudioTrackVector clear
,V/AwesomePlayer( 2854): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2854): mSecCapture clear
V/AwesomePlayer( 2854): mSecMediaClock clear
,D/ContextFramework:PrivacyManager(11885): Service for PrivacyManager is connected
,D/BluetoothManager(11644): getConnectedDevices
D/BluetoothManager(11644): getConnectedDevices
,D/BluetoothManager(11644): getConnectedDevices
,D/LWLocationManager(11885): Privacy service : STATUS_PLACE
D/LWLocationManager(11885): updateLocationStatus()
,I/LocationWidgetFuctionData(11885): readDB
,D/BluetoothManager(11644): getConnectedDevices
,I/LocationWidgetFuctionData(11885): selectedAppSize: 3
,I/LocationWidgetFuctionData(11885): configPlaceList aroundMeItems
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/BluetoothManager(11644): getConnectedDevices
,E/Zygote  (11933): MountEmulatedStorage()
E/Zygote  (11933): v2
I/libpersona(11933): KNOX_SDCARD checking this for 10003
I/libpersona(11933): KNOX_SDCARD not a persona
,I/SELinux (11933): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3512): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=11933 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
I/SELinux (11933): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11933): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothManager(11644): getConnectedDevices
,I/ActivityManager( 3512): Killing 11283:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11933): TimaSignature is unavailable
,D/ActivityThread(11933): Added TimaKeyStore provider
,I/ActivityManager( 3512): Killing 11375:com.policydm/1000 (adj 13): bgCount ##31
,D/ResourcesManager(11933): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/UserAnalysis.PlaceProvider(11933): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager(11933): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(11933): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(11933): Create SecureDbHelper
,D/IntelligenceServiceApplication(11933): onCreate()
,I/Mms/MmsApp(11613):  start initViewCache mms
,D/Mms/ComposeMessageFragment(11613): [start]    fillCache consume time = 1892.135292
D/Mms/ComposeMessageFragment(11613): fillCache, easy = false
,I/LocationWidgetFuctionData(11885): selectedAppSize: 3
,I/LocationWidgetFuctionData(11885): selectedAppSize: 3
,I/LocationWidgetFuctionData(11885): selectedAppSize: 3
,I/LocationWidgetFuctionData(11885): selectedAppSize: 3
,D/AbsListView(11613): Get MotionRecognitionManager
,D/MotionRecognitionService( 3512):  ssp status : true
,D/Mms/ComposeMessageFragment(11613): [end]    fillCache consume time = 98.171833
,E/LWLocationManager(11885): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(11885): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(11885): setShouldUpdateLocationId
D/LWLocationManager(11885): setShouldUpdateLocationId return false
D/LWLocationManager(11885): setShouldUpdateLocationId
D/LWLocationManager(11885): setShouldUpdateLocationId return false
D/LWLocationManager(11885): setShouldUpdateLocationId
D/LWLocationManager(11885): setShouldUpdateLocationId return false
D/LWLocationManager(11885): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,D/Mms/BubbleViewCache(11613): fillCache bubble = 8
,I/SurfaceFlinger( 2849): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3512): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3512) eventTime = 152314
,D/PowerManagerService( 3512): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3512 (0x0)
D/PowerManagerService( 3512): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3512, ws=WorkSource{1000}) (elapsedTime=3309)
,I/GAV4    (11483): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:n  ( 3512): SIOP:: AP = 270, PST = 260, CUR = -96
,W/ProcessCpuTracker( 3512): Skipping unknown process pid 11974
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3512): online:4, current avg:-59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10784): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dhcpcd  (11015): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11015): wlan0: no IPv6 Routers available
,I/GAV3    (11644): Thread[GAThread,5,main]: No campaign data found.
,D/PreloadUpdateManagerStateMachine(11589): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(11589): exit::IDLE
D/PreloadUpdateManagerStateMachine(11589): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (11589): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  (11589): RestApi Request Add : 2307
,I/System.out(11589): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(11589): (HTTPLog)-Static: isShipBuild true
I/System.out(11589): (HTTPLog)-Thread-1556-839869910: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(11589): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10013
,I/System.out(11589): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (11589): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 11589, getuid(): 10013
,I/qtaguid (11589): Untagging socket 26
,D/hcjo    (11589): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    (11589): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine(11589): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine(11589): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(11589): entry::REQ_UPDATE_CHECK
,I/Volley  (11589): RestApi Request Add : 2315
,I/System.out(11589): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out(11589): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (11589): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 11589, getuid(): 10013
,I/qtaguid (11589): Untagging socket -1
,I/qtaguid (11589): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid (11589): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger(11589): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine(11589): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine(11589): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine(11589): entry::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine(11589): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine(11589): entry::FINISH
,D/PreloadUpdateManagerStateMachine(11589): exit::FINISH
,D/PreloadUpdateManagerStateMachine(11589): entry::IDLE
,E/Watchdog( 3512): !@Sync 5
,D/SSRM:n  ( 3512): SIOP:: AP = 260, PST = 260, CUR = -59,
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10784): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3512): [PWL] Off : 75s ago
,V/AlarmManager( 3512): waitForAlarm result :8
,D/SSRM:n  ( 3512): SIOP:: AP = 250, PST = 260, CUR = 11,
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryService( 3512): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10784): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3512): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ClearcutLoggerApiImpl( 4245): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 259, CUR = 36
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,D/BatteryService( 3512): stay LED for fully charged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10784): Disconnected process message: 10
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3512): !@Sync 6
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 255, CUR = 42
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3512): stay LED for fully charged
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10784): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3512): [PWL] Off : 105s ago
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 251, CUR = 43
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3512): stay LED for fully charged
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10784): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3512): waitForAlarm result :4
,E/ActivityThread( 4483): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3512): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 178690, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager( 3512): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 271967, reason: UserStart
,W/ResourceType( 4958): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4958): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3512): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3512): mCursor = null
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 249, CUR = 40
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10784): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3512): waitForAlarm result :4
,I/EventLogService( 4483): Aggregate from 1453239547388 (log), 1453239547388 (data)
,E/Watchdog( 3512): !@Sync 7
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 248, CUR = 39
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3512): stay LED for fully charged
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10784): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3512): waitForAlarm result :8
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 246, CUR = 37
,I/PowerManagerService( 3512): [PWL] Off : 140s ago
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10784): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3512): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3512): SIOP:: AP = 230, PST = 243, CUR = 33
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10784): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3512): !@Sync 8
,D/SSRM:n  ( 3512): SIOP:: AP = 230, PST = 240, CUR = 32
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10784): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3512): SIOP:: AP = 230, PST = 238, CUR = 32
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10784): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10784): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(10713): --= Surplus to requirements =--
I/jxcore-log(10713): 
I/jxcore-log(10713): ****TEST TOOK:  ms ****
I/jxcore-log(10713): 
I/jxcore-log(10713): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10713): 
,D/AndroidRuntime(12283): 
D/AndroidRuntime(12283): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12283): CheckJNI is OFF
,D/AndroidRuntime(12283): readGMSProperty: start
D/AndroidRuntime(12283): readGMSProperty: already setted!!
,D/AndroidRuntime(12283): readGMSProperty: end
D/AndroidRuntime(12283): addProductProperty: start
,E/AffinityControl(12283): AffinityControl: registerfunction enter
,D/AndroidRuntime(12283): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3512): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3512): START PACKAGE DELETE: observer{165550913}
D/PackageManager( 3512): pkg{<packageName>}
D/PackageManager( 3512): user{0}
D/PackageManager( 3512): caller{2000}
D/PackageManager( 3512): flags{3}
D/PersonaManagerService( 3512): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3512): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3512): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3512): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3512): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3512): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3512): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3512): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3512): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3512): !@killApplicatoin: 10590, uninstall pkg
,I/ActivityManager( 3512): Force stopping com.test.thalitest appid=10590 user=-1: uninstall pkg
I/ActivityManager( 3512): Killing 10713:com.test.thalitest/u0a590 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3512):   Force finishing activity ActivityRecord{ded13a3 u0 com.test.thalitest/.MainActivity t25}
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (-2/8)
,D/PointerIcon( 3512): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3512): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3512): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3512): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3512): Skipping PackageSetting{358018d0 com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3512): Force stopping com.test.thalitest appid=10590 user=0: pkg removed
,D/ResourcesManager( 3512): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/WifiService( 3512): Client connection lost with reason: 4
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader( 3512): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/GeofencerStateMachine( 4245): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,E/SamsungIME( 4463): mOCRHelper is null
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/art     ( 4483): Explicit concurrent mark sweep GC freed 3983(222KB) AllocSpace objects, 2(32KB) LOS objects, 20% free, 31MB/39MB, paused 1.914ms total 67.905ms
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
D/LWLocationManager(11885): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11885): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/art     ( 8004): Explicit concurrent mark sweep GC freed 26788(1535KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 991us total 73.397ms
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/art     ( 4050): Explicit concurrent mark sweep GC freed 2483(119KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.013ms total 79.904ms
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/Zygote  (12304): MountEmulatedStorage()
E/Zygote  (12304): v2
I/libpersona(12304): KNOX_SDCARD checking this for 10063
I/libpersona(12304): KNOX_SDCARD not a persona
I/SELinux (12304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/SELinux (12304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3512): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12304 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12304): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,W/SQLiteConnectionPool( 4483): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ResourcesManager( 3512): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,W/ResourceType( 4958): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4958): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/TimaKeyStoreProvider(12304): TimaSignature is unavailable
,D/ActivityThread(12304): Added TimaKeyStore provider
,D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(12304): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/SecContentProvider2( 3512): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3512): mCursor = null
,D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12304): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12304): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12304): packagename:com.test.thalitest
,D/RegisteredServicesCache( 3966): empty dynamic service
,D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/KLMS-2.4.521: (11336): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 23:10:41 GMT+01:00 2016
,I/KLMS-2.4.521: (11336): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3512): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3512): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/elm:14491(11782): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/EnterpriseDeviceManagerService( 3512): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3512): Admin package name: com.google.android.gms
,I/KLMS-2.4.521: (11336): KLMSIntentService(): onCreate()
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/KLMS-2.4.521: (11336): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11336): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/KLMS-2.4.521: (11336): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11336): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (11336): KLMSIntentService(): listeningToPackageRemoved().START
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/KLMS-2.4.521: (11336): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/RCPManager(11467):  in createShortcut() for packageName: com.test.thalitest userId0
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/RCPManagerService( 3512):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3512): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Books/Books.apk
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,I/art     ( 3512): Explicit concurrent mark sweep GC freed 43162(3MB) AllocSpace objects, 51(3MB) LOS objects, 24% free, 49MB/65MB, paused 4.456ms total 181.941ms
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  (12323): MountEmulatedStorage()
E/Zygote  (12323): v2
I/libpersona(12323): KNOX_SDCARD checking this for 10050
I/libpersona(12323): KNOX_SDCARD not a persona
,I/SELinux (12323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3512): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12323 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux (12323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12323): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11885): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PackageManager( 3512): delete codoeFile: 
,I/AASAUninstall( 3512):  com.test.thalitest not target!
,D/PackageManager( 3512): result of delete: 1{165550913}
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/AndroidRuntime(12283): Shutting down VM
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/TimaKeyStoreProvider(12323): TimaSignature is unavailable
,D/ActivityThread(12323): Added TimaKeyStore provider
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/Zygote  (12339): MountEmulatedStorage()
E/Zygote  (12339): v2
I/libpersona(12339): KNOX_SDCARD checking this for 10160
I/libpersona(12339): KNOX_SDCARD not a persona
,I/SELinux (12339): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3512): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=12339 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,I/SELinux (12339): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12339): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11885): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11885): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11885): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11885): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/KLMS-2.4.521: (11336): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/TimaKeyStoreProvider(12339): TimaSignature is unavailable
,D/ActivityThread(12339): Added TimaKeyStore provider
,E/Zygote  (12354): MountEmulatedStorage()
E/Zygote  (12354): v2
I/libpersona(12354): KNOX_SDCARD checking this for 10101
I/libpersona(12354): KNOX_SDCARD not a persona
D/ResourcesManager(12323): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/SELinux (12354): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(11885): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/ActivityManager( 3512): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12354 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12354): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/ResourcesManager(12323): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12323): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12323): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/SELinux (12354): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ResourcesManager(12323): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12323): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12323): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/elm:14491(11782): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
W/ResourcesManager(12323): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager(11885): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/ResourcesManager(12323): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (11336): KLMSIntentService(): onDestroy()
,D/elm:14491(11782): ElmAgentService : onCreate()
,D/elm:14491(11782): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(11782): MainReceiver.listeningToPackageRemoved()
D/elm:14491(11782): MDMBridge.getInstance()
D/elm:14491(11782): MDMBridge.getAllLicenseInfoFromSDK()
,D/com.sec.android.service.health.upgrade.UninstallReceiver(11709): onReceive()
,D/elm:14491(11782): MDMBridge.getAllLicenseInfoFromSDK()
I/com.sec.android.service.health.upgrade.UninstallReceiver(11709): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
,D/TimaKeyStoreProvider(12354): TimaSignature is unavailable
D/com.sec.android.service.health.upgrade.UninstallReceiver(11709): onReceive() : package name is not s health. Return !!!
,D/ActivityThread(12354): Added TimaKeyStore provider
,D/ResourcesManager(12339): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/LocationWidgetApplication(11885): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/ResourcesManager(12339): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12339): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/elm:14491(11782): ElmAgentService : onDestroy().
,D/ResourcesManager(11885): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourceType( 3512): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(12354): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(11885): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Zygote  (12370): MountEmulatedStorage()
E/Zygote  (12370): v2
I/libpersona(12370): KNOX_SDCARD checking this for 1000
I/libpersona(12370): KNOX_SDCARD not a persona
,I/SELinux (12370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/SELinux (12370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12370 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Killing 11437:com.samsung.android.scloud.backup/u0a67 (adj 13): bgCount ##31
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 3512): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3512): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3512): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3512): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/TimaKeyStoreProvider(12370): TimaSignature is unavailable
,D/ActivityThread(12370): Added TimaKeyStore provider
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,V/Common  (12339): getScreenSize 1440 2560
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/RCPManagerService( 3512): PackageReceiver onReceive()
,I/HarmonyEASService( 3512): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/KnoxMUMContainerPolicy( 3512): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3512): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3512): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3512): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3512): uID is 10590
V/EnterpriseBillingPolicy( 3512): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3512): getProfileForApplication - enter
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/EnterpriseBillingPolicyStorage( 3512): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3512): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3512): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3512): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 3512): getBillingProfileForVpnEngine - end - null
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/JAM     (12339): Load The ApaService JNI
,I/JAM     (12339): version: ProfessionalAudio_v1.0.b5
I/JAM     (12339): Try v1.0.b3 ...
D/Spen    (12339): SpenSdk version level = 55
D/Spen    (12339): SpenSdk jar version = 3.0.243
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/Spen    (12339): SpenSdk apk version = 3.0.235
D/Spen    (12339): Server UPDATE Check
,W/linker  (12339): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
D/SPenError(12339): JNI_OnLoad
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
D/JNI_Bitmap(12339): Init .. Done
D/PackageManager( 3512): findPreferredActivity: No PreferredActivities set
D/SPenSpiDecoder(12339): JNI_OnLoad .. Done
D/SPenError(12339): JNI_OnLoad Success
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PluginManager(12339): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(12339): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(12339): JNI_OnLoad
D/Init_SPenSdk_Jni(12339): AndroidSDK: 21
D/Init_SPenSdk_Jni(12339): JNI_OnLoad .. Done
,D/Model_ObjectBase_Jni(12339): JNI_OnLoad .. Done
D/Model_ObjectStroke_Jni(12339): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(12339): JNI_OnLoad .. Done
D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/Model_ObjectText_Jni(12339): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(12339): JNI_OnLoad .. Done
D/Model_PageDoc_Jni(12339): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni(12339): check build type eng[0]
D/Model_NoteDoc_Jni(12339): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(12339): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(12339): JNI_OnLoad .. Done
D/Model   (12339): OnLoad class Done
,D/ResourcesManager(12370): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/spe_log (12339): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library(12339): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(12339): Canvas JNI_OnLoad enter!!
,D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/SPen_Library(12339): Canvas JNI_OnLoad Success
D/SPen_Library(12339): TextView JNI_OnLoad enter!!
,D/SPen_Library(12339): TextView JNI_OnLoad Success
D/SPen_Library(12339): Text JNI_OnLoad enter!!
D/SPen_Library(12339): Text JNI_OnLoad Success
D/SPen_Library(12339): FontManager JNI_OnLoad enter!!
D/SPen_Library(12339): FontManager JNI_OnLoad Success
D/SPen_Library(12339): CapturePage JNI_OnLoad enter!!
D/SPen_Library(12339): CapturePage JNI_OnLoad Success
D/SPen_Library(12339): Multi JNI_OnLoad enter!!
,D/SPen_Library(12339): Multi JNI_OnLoad Success
D/SPen_Library(12339): Draw Engine JNI_OnLoad Success
,D/SPen_Library(12339): Brush JNI_OnLoad enter!!
I/libpersona(12391): KNOX_SDCARD checking this for 10160
E/Zygote  (12391): MountEmulatedStorage()
I/libpersona(12391): KNOX_SDCARD not a persona
E/Zygote  (12391): v2
D/SPen_Library(12339): Brush JNI_OnLoad Success
,D/SPen_Library(12339): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(12339): ChineseBrush JNI_OnLoad Success
I/SELinux (12391): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/SPen_Library(12339): InkPen JNI_OnLoad enter!!
D/SPen_Library(12339): InkPen JNI_OnLoad Success
,D/SPen_Library(12339): Marker JNI_OnLoad enter!!
I/ActivityManager( 3512): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=12391 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,D/SPen_Library(12339): Marker JNI_OnLoad Success
,D/SPen_Library(12339): Pencil JNI_OnLoad enter!!
I/SELinux (12391): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/SPen_Library(12339): Pencil JNI_OnLoad Success
,D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
D/SPen_Library(12339): NativePen JNI_OnLoad enter!!
E/SELinux (12391): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SPen_Library(12339): NativePen JNI_OnLoad Success
,D/DocsApplication(12354): Installing DEX configuration.
D/SPen_Library(12339): MontblancFountainPen JNI_OnLoad enter!!
D/SPen_Library(12339): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library(12339): MontblancCalligraphyPen JNI_OnLoad enter!!
D/SPen_Library(12339): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library(12339): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(12339): MagicPen JNI_OnLoad Success
,D/SPen_Library(12339): ObliquePen JNI_OnLoad enter!!
D/SPen_Library(12339): ObliquePen JNI_OnLoad Success
,D/SPen_Library(12339): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(12339): FountainPen JNI_OnLoad Success
D/Spen    (12339): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(12339): SPenSdk_init2
D/Init_SPenSdk(12339): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(12339): Total S Pen SDK Directory Size = 0
D/Spen    (12339): initialize complete
,W/linker  (12339): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/TaskPersister( 3512): removeObsoleteFile: deleting file=25_task.xml
D/UsbSettingsManager( 3512): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3512): onPackageRemoved : com.test.thalitest
,D/DexInstaller(12354): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12354): Provided clientMode=RELEASE, packageInfo=PackageInfo{33198846 com.google.android.apps.docs}
,I/PCWCLIENTTRACE_LOG(12370): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12370): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12370): new DMDBOpenHelper instance
,D/TAG     (12354): onCreate()
,D/CrossAppStateProvider(12354): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12391): TimaSignature is unavailable
,D/ActivityThread(12391): Added TimaKeyStore provider
,D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,E/Zygote  (12409): MountEmulatedStorage()
E/Zygote  (12409): v2
I/libpersona(12409): KNOX_SDCARD checking this for 10183
I/libpersona(12409): KNOX_SDCARD not a persona
,I/SELinux (12409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12409): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12409 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 3512): Killing 11163:com.android.chrome/u0a90 (adj 13): bgCount ##31
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/Books/Books.apk
,I/PCWCLIENTTRACE_PushUtil(12370): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12370): sales region : global
I/PCWCLIENTTRACE_PushUtil(12370): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12370): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 3512): Killing 10834:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 13): bgCount ##31
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(12391): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,E/Zygote  (12423): MountEmulatedStorage()
E/Zygote  (12423): v2
I/libpersona(12423): KNOX_SDCARD checking this for 10035
I/libpersona(12423): KNOX_SDCARD not a persona
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/SELinux (12423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ResourcesManager(12391): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12391): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12391): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12409): TimaSignature is unavailable
,I/ActivityManager( 3512): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12423 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
D/ActivityThread(12409): Added TimaKeyStore provider
,I/ActivityManager( 3512): Killing 11483:com.google.android.apps.magazines/u0a136 (adj 13): bgCount ##31
,I/SELinux (12423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,E/SELinux (12423): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 884us total 25.693ms
D/NearbySource(12323): Nearby Source Create!
D/NearbyContext(12323): Nearby Context Create!
,D/ResourcesManager(12409): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.109ms total 17.520ms
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12323): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(12323): Samsung link source created
,D/TimaKeyStoreProvider(12423): TimaSignature is unavailable
,D/ActivityThread(12423): Added TimaKeyStore provider
,D/UsbHostManager( 3512): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,D/UsbHostManager( 3512): displayNotification : [02h,02h,01h]
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 485us total 15.881ms
D/UsbHostManager( 3512): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
,D/UsbHostManager( 3512): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3512): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
E/SQLiteLog(12409): (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
D/UsbHostManager( 3512): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3512): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3512): displayNotification : [0ah,00h,01h]
,E/SQLiteDatabase(12409): Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
E/SQLiteDatabase(12409): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12409): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12409): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12409): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/SQLiteDatabase(12409): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/SQLiteDatabase(12409): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(12409): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12409): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12409): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12409): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12409): Shutting down VM
,E/AndroidRuntime(12409): FATAL EXCEPTION: main
E/AndroidRuntime(12409): Process: com.samsung.android.provider.shootingmodeprovider, PID: 12409
E/AndroidRuntime(12409): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12409): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(12409): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(12409): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(12409): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(12409): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(12409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12409): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12409): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12409): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12409): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12409): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12409): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12409): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12409): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/AndroidRuntime(12409): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/AndroidRuntime(12409): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(12409): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(12409): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(12409): 	... 11 more
,D/UsbHostManager( 3512): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3512): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3512): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/UsbHostManager( 3512): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3512): displayNotification : [09h,00h,00h]
,V/ApplicationPolicy( 3512): isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(12423): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
E/SQLiteLog(12323): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12323): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12323): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12323): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12323): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12323): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12323): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12323): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12323): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12323): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12323): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12323): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12323): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12323): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12323): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12323): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12323): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12323): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12323): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12323): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12323): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12323): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12323): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12323): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12323): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12323): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12323): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12323): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12323): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12323): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12323): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12323): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12323): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12323): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12323): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12323): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12323): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12323): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12323): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12323): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12323): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12323): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12323): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12323): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12323): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12323): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12323): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12323): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12323): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12323): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12323): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12323): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12323): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12323): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12323): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12323): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12323): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12323): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12323): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12323): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12323): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12323): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12323): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12323): Opened local.db in read-only mode
,D/ContactProvider(12323): getAllContactInfoList Start
D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SNoteProvider(12391): onCreate enableSnoteSync = true
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/DropBoxManagerService( 3512): Can't write: system_app_crash
E/DropBoxManagerService( 3512): java.io.FileNotFoundException: /data/system/dropbox/drop193.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3512): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3512): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3512): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3512): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3512): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3512): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3512): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3512): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3512): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3512): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3512): 	... 5 more
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/UsbHostManager( 3512): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3512): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,E/Zygote  (12450): MountEmulatedStorage()
E/Zygote  (12450): v2
I/libpersona(12450): KNOX_SDCARD checking this for 10190
I/libpersona(12450): KNOX_SDCARD not a persona
,I/SELinux (12450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
I/ActivityManager( 3512): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12450 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/SELinux (12450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12450): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3512): Removing device '/dev/input/event10' due to inotify event
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/PowerManagerService( 3512): [PWL] Off : 180s ago
,I/FeatureConfig(12423): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 3512): Killing 10283:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,D/SNoteProvider(12391): ===query=== 
,E/SQLiteLog(12391): (28) failed to open "/data/user/0/com.samsung.android.snote/databases/Snote.db" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3512): Removing device '/dev/input/event7' due to inotify event
,I/Process (12409): Sending signal. PID: 12409 SIG: 9
,E/SQLiteDatabase(12391): Failed to open database '/data/user/0/com.samsung.android.snote/databases/Snote.db'.
E/SQLiteDatabase(12391): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12391): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12391): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12391): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
E/SQLiteDatabase(12391): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
E/SQLiteDatabase(12391): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
E/SQLiteDatabase(12391): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(12391): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(12391): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(12391): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(12391): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(12391): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(12391): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(12391): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(12391): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(12391): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(12391): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(12391): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(12391): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(12391): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(12391): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/System.err(12391): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(12391): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(12391): 	at android.database.sqlite.SQLiteOpenHelper.get,WritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(12391): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
W/System.err(12391): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
W/System.err(12391): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
W/System.err(12391): 	at android.content.ContentProvider.query(ContentProvider.java:987)
W/System.err(12391): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err(12391): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
W/System.err(12391): 	at android.os.Binder.execTransact(Binder.java:446)
D/SNoteProvider(12391): message = not an error (code 0): Could not open the database in read/write mode.
,D/TimaKeyStoreProvider(12450): TimaSignature is unavailable
,D/ActivityThread(12450): Added TimaKeyStore provider
,D/MtpClient(12323): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12323): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,I/EventHub( 3512): Removing device '/dev/input/event8' due to inotify event
D/SNoteProvider(12391): ===query=== 
,E/SQLiteLog(12391): (28) failed to open "/data/user/0/com.samsung.android.snote/databases/Snote.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12391): Failed to open database '/data/user/0/com.samsung.android.snote/databases/Snote.db'.
E/SQLiteDatabase(12391): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12391): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12391): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12391): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12391): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
E/SQLiteDatabase(12391): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
E/SQLiteDatabase(12391): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
E/SQLiteDatabase(12391): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(12391): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(12391): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(12391): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(12391): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(12391): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(12391): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(12391): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(12391): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(12391): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(12391): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(12391): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(12391): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(12391): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(12391): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
W/System.err(12391): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
,W/System.err(12391): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(12391): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(12391): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
W/System.err(12391): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
W/System.err(12391): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
W/System.err(12391): 	at android.content.ContentProvider.query(ContentProvider.java:987)
W/System.err(12391): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err(12391): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
W/System.err(12391): 	at android.os.Binder.execTransact(Binder.java:446)
D/SNoteProvider(12391): message = not an error (code 0): Could not open the database in read/write mode.
D/ResourcesManager(12423): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/SharedPreferencesImpl(12323): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
W/ResourcesManager(12423): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/Common  (12391): getScreenSize 1440 2560
W/ResourcesManager(12423): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12423): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(12423): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Mms/FreeMessageStatusReceiver(11613): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(11885): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(12423): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/EventHub( 3512): Removing device '/dev/input/event9' due to inotify event
,W/ResourcesManager(12423): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(12423): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/EventHub( 3512): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager(11885): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/Mms/FreeMessageReceiverService(11613): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(11613): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/ResourcesManager(12423): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12423): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager(12450): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
W/ResourcesManager(12423): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/ActivityManager( 3512): Process com.samsung.android.provider.shootingmodeprovider (pid 12409)(adj 9) has died(325,1127)
,I/EventHub( 3512): Removing device '/dev/input/event12' due to inotify event
,D/ResourcesManager(12423): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12423): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12450): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12450): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,D/ResourcesManager(12423): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/EventHub( 3512): Removing device '/dev/input/event13' due to inotify event
I/TapandpayWidget:Utils(12450): Clear T&P info.
,W/ResourcesManager(12423): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(12423): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(12423): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12423): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager(11885): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12450): Widget is not attached.
,D/SSRM:n  ( 3512): SIOP:: AP = 230, PST = 236, CUR = 31
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3512): Removing device '/dev/input/event14' due to inotify event
,D/ResourcesManager(12423): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12423): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (12473): MountEmulatedStorage()
,E/Zygote  (12473): v2
I/libpersona(12473): KNOX_SDCARD checking this for 1000
I/libpersona(12473): KNOX_SDCARD not a persona
,I/SELinux (12473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.android.settings for broadcast com.android.settings/.TactileAssistBroadcastReceiver: pid=12473 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12473): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12423): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ContactProvider(12323): getAllContactInfoList End
,I/syncContacts(12323): thread: 1628, sync time = 529
,I/ActivityManager( 3512): Killing 11566:com.samsung.android.sconnect/u0a150 (adj 13): bgCount ##31
,W/ResourcesManager(12423): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12423): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12423): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12423): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12423): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SQLiteLog(11644): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog(11644): (3850) statement aborts at 19: [delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"] disk I/O error
,D/ResourcesManager(12423): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/TimaKeyStoreProvider(12473): TimaSignature is unavailable
,D/ActivityThread(12473): Added TimaKeyStore provider
E/SQLiteQuery(11644): exception: disk I/O error (code 3850); query: delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"
,W/ResourcesManager(12423): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12423): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 4483): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4483): Clearing selected account for com.test.thalitest

```
