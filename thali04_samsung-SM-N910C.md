#### Test 506502784dae475_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,E/Watchdog( 3528): !@Sync 4
--------- beginning of main
D/AndroidRuntime(10673): 
D/AndroidRuntime(10673): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10673): CheckJNI is OFF
D/AndroidRuntime(10673): readGMSProperty: start
D/AndroidRuntime(10673): readGMSProperty: already setted!!
D/AndroidRuntime(10673): readGMSProperty: end
D/AndroidRuntime(10673): addProductProperty: start
E/AffinityControl(10673): AffinityControl: registerfunction enter
D/AndroidRuntime(10673): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3528): inState():  stateMachine is null !!
I/PersonaManagerService( 3528): PersonaId don't exist
I/ActivityManager( 3528): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3528): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3528): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3528): mDVFSHelper.acquire()
D/FocusedStackFrame( 3528): Set to : 0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/Zygote  (10693): MountEmulatedStorage()
I/libpersona(10693): KNOX_SDCARD checking this for 10479
E/Zygote  (10693): v2
I/libpersona(10693): KNOX_SDCARD not a persona
I/SELinux (10693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=10693 uid=10479 gids={50479, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (10693): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10673): Shutting down VM
D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
I/art     ( 2877): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 423us total 10.449ms
D/TimaKeyStoreProvider(10693): TimaSignature is unavailable
D/ActivityThread(10693): Added TimaKeyStore provider
V/WindowOrientationListener( 3528): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3528): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3528): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3528): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3528): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 351us total 8.393ms
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 516us total 8.458ms
D/ResourcesManager(10693): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2850): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2850): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 3997): updateVisibility : ActivityRecord{1e5cc7e3 token=android.os.BinderProxy@3b89717d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3997): onTrimMemory. Level: 20
I/WebViewFactory(10693): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10693): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10693): Loading: webviewchromium
I/LibraryLoader(10693): Time to load native libraries: 3 ms (timestamps 3699-3702)
I/LibraryLoader(10693): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(10693): Binding Chromium to main looper Looper (main, tid 1) {a372751}
I/LibraryLoader(10693): Expected native library version number "",actual native library version number ""
I/chromium(10693): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(10693): Initializing chromium process, renderers=0
W/art     (10693): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(10693): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium(10693): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(10693): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10693): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter(10693): 555522998: getState() :  mService = null. Returning STATE_OFF
W/chromium(10693): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(10693): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10693): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10693): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(10693): CordovaWebView is running on device made by: samsung
,W/art     (10693): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10693): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(10693): performCreate Call secproduct feature valuefalse
D/Activity(10693): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(10693): Render dirty regions requested: true
D/ActivityManager( 3528): post active user change for 0
D/KnoxTimeoutHandler( 3528): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3528): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2850): id=12 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(10693): Initialized EGL, version 1.4
I/OpenGLRenderer(10693): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278643952 
D/OpenGLRenderer(10693): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10693): Enabling debug mode 0
D/mali_winsys(10693): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(10693): updateVisibility : ActivityRecord{2ce15e66 token=android.os.BinderProxy@faf3b8c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3528): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper(10693): showStatusIcon on inactive InputConnection
,I/Timeline(10693): Timeline: Activity_idle id: android.os.BinderProxy@faf3b8c time:133944
W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 3528): Timeline: Activity_windows_visible id: ActivityRecord{38a9c26c u0 com.test.thalitest/.MainActivity t25} time:133980
W/ActivityManager( 3528): mDVFSHelper.release()
,D/JsMessageQueue(10693): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(10693): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10693): 
,D/SSRM:n  ( 3528): SIOP:: AP = 270, PST = 293, CUR = 36
,D/jxcore_app_log(10693): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361621760
D/JX-Cordova(10693): jxcore cordova android initializing
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-674
D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/jxcore-log(10693): Initializing JXcore engine
W/jxcore-log(10693): JXcore engine is ready
,W/jxcore-log(10693): Starting JXcore engine
,E/auditd  ( 4523): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3528): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3528): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10693): Platform android
W/jxcore-log(10693): 
W/jxcore-log(10693): Process ARCH arm
W/jxcore-log(10693): 
,I/jxcore-log(10693): JXcore Cordova bridge is ready!
I/jxcore-log(10693): 
W/jxcore-log(10693): JXcore engine is started
,I/Choreographer(10693): Skipped 55 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log(10693): Toggling radios to true
I/jxcore-log(10693): 
,D/BluetoothAdapter(10693): enable()
,W/ActivityManager( 3528): Permission Denial: getCurrentUser() from pid=10693, uid=10479 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 3528): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 3528): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10693, uid=10479 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 3528): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/BluetoothManagerService( 3528): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2160)
W/BluetoothManagerService( 3528): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService( 3528): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 3528): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService( 3528): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3528): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 3528): name = bluetooth_on
,E/DevicePolicyManagerService( 3528): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3528): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,I/WifiManager(10693): packageName : com.test.thalitest
,D/WifiService( 3528): New client listening to asynchronous messages
D/SecContentProvider( 3528): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3528): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3528): mCursor = null
,D/WifiService( 3528): setWifiEnabled: true pid=10693, uid=10479
E/WifiService( 3528): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3528): Permission Denial: getCurrentUser() from pid=10693, uid=10479 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3528): Failed getting userId using ActivityManagerNative
W/WifiService( 3528): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10693, uid=10479 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3528): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3528): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3528): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3528): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3528): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3528): name = wifi_on
,E/WifiStateMachine( 3528): setting operational mode to 1
,E/WifiHW  ( 3528): ##################### set firmware type 0 #####################
I/WifiService( 3528): disconnect: pid=10693, uid=10479
,I/jxcore-log(10693): Radios toggled
I/jxcore-log(10693): 
I/WifiHW  ( 2845): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
E/Zygote  (10763): MountEmulatedStorage()
E/Zygote  (10763): v2
I/libpersona(10763): KNOX_SDCARD checking this for 1002
I/libpersona(10763): KNOX_SDCARD not a persona
,I/SELinux (10763): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/WifiHW  ( 2845): module is murata
E/WifiHW  ( 2845): ==========[WIFI] MURATA MODULE ===========
I/WifiHW  ( 2845): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_murata
E/WifiHW  ( 2845): TEMP_FAILURE_RETRY complete
D/SoftapController( 2845): Softap fwReload - Ok
,I/SELinux (10763): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10763): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=10763 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/CommandListener( 2845): Setting iface cfg
D/CommandListener( 2845): Trying to bring down wlan0
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/TimaKeyStoreProvider(10763): TimaSignature is unavailable
,D/ActivityThread(10763): Added TimaKeyStore provider
,D/ResourcesManager(10763): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(10763): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(10763): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni(10763): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig(10763): Adding GattService
,D/BtSettings.ProfileConfig(10763): Adding HeadsetService
D/BtSettings.ProfileConfig(10763): Adding A2dpService
D/BtSettings.ProfileConfig(10763): Adding HidService
D/BtSettings.ProfileConfig(10763): Adding HealthService
,D/BtSettings.ProfileConfig(10763): Adding PanService
D/BtSettings.ProfileConfig(10763): Adding BluetoothMapService
D/BtSettings.ProfileConfig(10763): Adding SapService
D/BtSettings.ProfileConfig(10763): Adding HeadsetClientService
D/BtSettings.ProfileConfig(10763): Adding A2dpSinkService
D/BtSettings.ProfileConfig(10763): Adding SapClientService
D/BtSettings.ProfileConfig(10763): Adding HidDevService
I/BtSettings.ProfileConfig(10763): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3528): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
E/WifiHW  ( 3528): supplicant_name : p2p_supplicant
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/wpa_supplicant(10778): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant(10778): Successfully initialized wpa_supplicant
,I/SecureStorage(10778): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,D/BluetoothAdapterState(10763): make
,I/bluedroid(10763): init
I/BluetoothAdapterState(10763): Entering OffState
,I/bte_conf(10763): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf(10763): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config(10763): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf(10763): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif (10763): btif_fetch_local_ble_random_bdaddr
I/bluedroid(10763): get_profile_interface socket
I/bluedroid(10763): get_profile_interface map_client
I/SecureStorage(10778): [INFO]: SPID(0x00000000)This device supports Secure Storage
,D/BluetoothAdapterService(10763): checkAddrForIOP: Loading from conf
,I/SecureStorage( 2916): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10778
I/SecureStorage( 2916): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
I/SecureStorage(10778): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant(10778): ssSupport state is = 1
I/wpa_supplicant(10778): >>>>> GET KEY, IV <<<<<
,D/BluetoothAdapterService(10763): Inband Ring is supported
,I/SecureStorage(10778): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage( 2916): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10778
I/SecureStorage( 2916): [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,I/GKI_LINUX(10763): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties(10763): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10763): populateRssiValuesNative
I/bluedroid(10763): getModelRssiValues
E/BluetoothServiceJni(10763): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10763): modelRssiValuesCallback, low, mid, high = -75,-65,127
,D/BluetoothAdapterProperties(10763): Name is: Note4-1
,D/SettingsProvider( 3528): name = bluetooth_name
,I/bluedroid(10763): config_hci_snoop_log
,D/BluetoothManagerService( 3528): Broadcasting onBluetoothServiceUp() to 11 receivers.
,E/DevicePolicyManagerService( 3528): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3528): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 3528): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState(10763): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties(10763): Setting state to 11
I/BluetoothAdapterState(10763): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(10763): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10763): updateAdapterState state is 11
,D/BluetoothAdapterService(10763): Autoconnection is available 
D/BluetoothAdapterService(10763): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager(10763): getInstant: null
,D/BluetoothSecureManager(10763): calling getMethod for getService
D/BluetoothSecureManager(10763): calling getService
D/BluetoothSecureManager(10763): getService return binder: android.os.BinderProxy@19666f89
,D/BluetoothSecureManagerService( 3528): isSecureModeEnabled
,D/BluetoothSecureManagerService( 3528): getSecureModeSetting, name: secure_mode_enable
D/BluetoothTile( 3689):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3689): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BtConfig.SecureMode(10763): isSecureModeOn:false
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService(10763): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10763): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10763): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService(10763): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,I/SamsungIME( 4446): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/StatusBarManagerService( 3528): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3528): setIconVisibility slot=bluetooth visible=false
,W/BluetoothAdapterService(10763): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10763): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/PhoneStatusBar( 3689): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,D/STATUSBAR-QSTileView( 3689): onStateChanged: Bluetooth
,W/InputMethodManagerService( 3528): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3528): [BT Setting State] State =11
,W/BluetoothAdapterService(10763): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10763): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10763): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService(10763): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10763): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService(10763): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine(10763): make
,I/BluetoothBondStateMachine(10763): StableState(): Entering Off State
W/BluetoothAdapterService(10763): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService(10763): Not skipping com.android.bluetooth.gatt.GattService
,E/WifiStateMachine( 3528): setWifiState: enabling
,V/[CarModeFW](10126): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,W/BluetoothAdapterService(10763): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10763): Not skipping com.android.bluetooth.hfp.HeadsetService
I/BtGatt.JNI(10763): classInitNative(L900): classInitNative: Success!
E/WifiStateMachine( 3528): Supplicant start successful
,D/WifiMonitor( 3528): startMonitoring(wlan0) with mConnected = false
,D/BtGatt.DebugUtils(10763): handleDebugAction() action=null
D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/BtGatt.GattService(10763): Received start request. Starting profile...
D/BtGatt.GattService(10763): start()
I/bluedroid(10763): get_profile_interface gatt
,D/BluetoothAdapterService(10763): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a372751
D/BtGatt.AdvertiseManager(10763): advertise manager created
D/SLocation( 3528): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-WifiQuickSettingButton( 3689): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3689): Wifi onReceive(2)
,D/STATUSBAR-QSTileView( 3689): onStateChanged: Wi-Fi
,D/HotspotTile( 3689): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 3689): onReceive : 2, 0
,D/SmartBondingService( 3528): getNetworkEnabled : wifi : false mobile : false
,W/BluetoothAdapterService(10763): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10763): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BluetoothAdapterService(10763): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a372751
,D/HeadsetService(10763): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni(10763): classInitNative: succeeds
D/HeadsetStateMachine(10763): make
,W/BluetoothAdapterService(10763): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(10763): Not skipping com.android.bluetooth.hid.HidService
,E/HeadsetStateMachine(10763): # of Max HF connection is 2
,W/BluetoothAdapterService(10763): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10763): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService(10763): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10763): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService(10763): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10763): Not skipping com.android.bluetooth.map.BluetoothMapService
,I/bluedroid(10763): get_profile_interface handsfree
,D/BluetoothNotiBroadcastReceiver( 7605): onReceive
,W/BluetoothAdapterService(10763): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,I/DualScoManager(10763): Instantiating Dual Sco Manager
I/DualScoManager(10763): Set HeadsetServiceHelper
D/BluetoothAtMessage(10763): createCMTIContentObservers
W/BluetoothAdapterService(10763): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService(10763): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService(10763): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10763): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3528): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
W/BluetoothAdapterService(10763): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10763): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
W/BluetoothAdapterService(10763): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3528): ret = -1
W/BluetoothAdapterService(10763): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig(10763): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService(10763): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState(10763): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine(10763): Enter Disconnected: -2
,D/BluetoothAdapterService(10763): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a372751
E/BluetoothAdapterService(171386705)(10763): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,E/HeadsetStateMachine(10763): set to mRemoteBrsf = 0
,D/BluetoothA2dp( 4803): Proxy object connected
D/BluetoothA2dp( 3528): Proxy object connected
,D/A2dpService(10763): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni(10763): classInitNative: succeeds
V/Avrcp   (10763): make
V/Avrcp   (10763): Avrcp
I/bluedroid(10763): get_profile_interface avrcp
,D/HeadsetStateMachine(10763): map size, before remove : 0
D/HeadsetStateMachine(10763): map size, after remove: 0
,V/Avrcp   (10763): start
,E/RemoteController(10763): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   (10763): ++registerMediaPlayers++
,I/Avrcp   (10763): No of Audio players :: 2
I/Avrcp   (10763): App Package name is com.google.android.music
,D/ResourcesManager(10763): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   (10763): App pkg name is Google Play Music
,I/Avrcp   (10763): Name::Google Play Music
V/Avrcp   (10763): MediaPlayerInfo: mPlayerId=1
I/Avrcp   (10763): App Package name is com.sec.android.app.music
,D/ResourcesManager(10763): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   (10763): App pkg name is Music
I/Avrcp   (10763): Name::Music
V/Avrcp   (10763): MediaPlayerInfo: mPlayerId=2
,I/Avrcp   (10763): No of Video players :: 1
I/Avrcp   (10763): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager(10763): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   (10763): Video App pkg name is Video Player
,I/Avrcp   (10763): Name::Video Player
V/Avrcp   (10763): MediaPlayerInfo: mPlayerId=3
I/Avrcp   (10763): Add tempPlayer
V/Avrcp   (10763): MediaPlayerInfo: mPlayerId=4
I/Avrcp   (10763): Total no of players: 4
V/Avrcp   (10763): swapping the samsung player with 1st player
I/Avrcp   (10763):  Updating now playing list upon AVRCP Start
V/Avrcp   (10763): handleMessage, msg=207
D/BluetoothMediaBrowser(10763):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,V/Avrcp   (10763): CurrentAudioFocusPackageName is null
I/Avrcp   (10763): There is no currently selected player ,setting Samsung Music Player ID
I/Avrcp   (10763):  set player publishabilty with player id::1 toBePublished ::true
I/BluetoothA2dpServiceJni(10763): classInitNative: succeeds
D/A2dpStateMachine(10763): make
,I/bluedroid(10763): get_profile_interface a2dp,
I/GKI_LINUX(10763): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif (10763): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService(10763): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a372751
,D/A2dpStateMachine(10763): Enter Disconnected: -2
I/BluetoothHidServiceJni(10763): classInitNative: succeeds
,D/HidService(10763): Received start request. Starting profile...
I/bluedroid(10763): get_profile_interface hidhost
D/HidService(10763): setHidService(): set to: null
D/BluetoothAdapterService(10763): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a372751
,I/BluetoothHealthServiceJni(10763): classInitNative: succeeds
D/HealthService(10763): Received start request. Starting profile...
,I/bluedroid(10763): get_profile_interface health
D/BluetoothAdapterService(10763): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a372751
,D/HeadsetStateMachine(10763): Try to query the phonestate on bind
,I/Telecom ( 3950): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 3950): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 3950): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 3950): Proxy not attached to service
,I/BluetoothPanServiceJni(10763): classInitNative(L105): succeeds
,D/BluetoothMediaBrowser(10763): no now playing list
D/BluetoothMediaBrowser(10763):  getNowPlayingId now playing id : -1
D/Avrcp   (10763):  checkNowPlayingList start
,D/BluetoothPan( 3528): BluetoothPAN Proxy object connected
,D/PanService(10763): Received start request. Starting profile...
D/BluetoothPanServiceJni(10763): initializeNative(L110): pan
I/bluedroid(10763): get_profile_interface pan
,D/BluetoothAdapterService(10763): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a372751
D/HeadsetStateMachine(10763): Proxy object connected
D/HeadsetPhoneState(10763): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState(10763): sendDeviceDataStateChanged
D/HeadsetPhoneState(10763): Signal level : previous=0 curr=0
D/HeadsetStateMachine(10763): Disconnected process message: 11
D/HeadsetStateMachine(10763): Disconnected process message: 18
,D/BluetoothMapService(10763): Received start request. Starting profile...
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10795): MountEmulatedStorage()
E/Zygote  (10795): v2
I/libpersona(10795): KNOX_SDCARD checking this for 10178
I/libpersona(10795): KNOX_SDCARD not a persona
,I/SELinux (10795): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10795): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=10795 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux (10795): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10795): TimaSignature is unavailable
,D/ActivityThread(10795): Added TimaKeyStore provider
,D/ResourcesManager(10795): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(10795): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(10795): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(10795): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10795): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10795): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10795): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3528): exchangeData() failure , invalid userId
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/BluetoothAdapterService(10763): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a372751
,I/BluetoothSAPServiceJni(10763): classInitNative(L204): succeeds
,D/SapService(10763): Received start request. Starting profile...
D/BluetoothSAPServiceJni(10763): initializeNative(L209): sap
I/bluedroid(10763): get_profile_interface sap
D/BluetoothAdapterService(10763): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a372751
E/BluetoothAdapterService(171386705)(10763): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp(10763): Proxy object connected
D/BluetoothAdapterService(10763): Bluetooth A2dp source service connected
E/BluetoothAdapterService(171386705)(10763): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(171386705)(10763): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/HeadsetStateMachine(10763): Disconnected process message: 10
E/BluetoothAdapterService(171386705)(10763): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,D/HeadsetPhoneState(10763): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine(10763): Disconnected process message: 11
,E/Zygote  (10818): MountEmulatedStorage()
E/Zygote  (10818): v2
I/libpersona(10818): KNOX_SDCARD checking this for 10082
I/libpersona(10818): KNOX_SDCARD not a persona
,I/SELinux (10818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10818): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=10818 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/BluetoothAdapterService(171386705)(10763): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,D/AuthorizationBluetoothService( 4229): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/BluetoothAdapterService(171386705)(10763): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(171386705)(10763): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/BluetoothAdapterState(10763): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid(10763): enable
,I/bt_hci_bdroid(10763): init
,I/bt_vendor(10763): init
I/GKI_LINUX(10763): gki_task_entry task_id=0 [BTU] starting
I/bt_vnd_conf(10763): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf(10763): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial(10763): userial_init
,I/Hs20UtilService( 6284): Starting #2
,I/Hs20UtilService( 6284): Message received 5011
,D/TimaKeyStoreProvider(10818): TimaSignature is unavailable
,D/ActivityThread(10818): Added TimaKeyStore provider
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10837): MountEmulatedStorage()
I/libpersona(10837): KNOX_SDCARD checking this for 10127
E/Zygote  (10837): v2
I/libpersona(10837): KNOX_SDCARD not a persona
,I/SELinux (10837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10837): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=10837 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 9991:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10837): TimaSignature is unavailable
,D/ActivityThread(10837): Added TimaKeyStore provider
,D/ResourcesManager(10818): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(10837): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/BadgeProvider(10818): onCreate
D/BadgeProvider(10818): DatabaseHelper
,D/KeyguardWallpaperUpdator(10837): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(10837): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10837): stopCheckCategoryVersion
,D/BadgeProvider(10818): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/SignOutReceiver(10346): WIFI_STATE_CHANGED_ACTION
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider(10818): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10818): sendNotify, [notify] : null
D/BadgeProvider(10818): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10818): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10818): update, [UpdateCount] : 1
,D/Launcher.Model( 3997): reloadBadges entered.
,E/Zygote  (10854): MountEmulatedStorage()
I/libpersona(10854): KNOX_SDCARD checking this for 1000
E/Zygote  (10854): v2
I/libpersona(10854): KNOX_SDCARD not a persona
,I/SELinux (10854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10854): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=10854 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 9126:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,W/ActivityManager( 3528): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/bt_userial_vendor(10763): userial vendor open: opening /dev/ttySAC3
I/bt_userial_vendor(10763): userial_vendor_open():UART is setup
I/bt_userial_vendor(10763): device fd = 65 open
E/bt_hwcfg(10763): Start CFG HW, HCI reset
D/bt_userial(10763): Entering userial_read_thread()
,D/TimaKeyStoreProvider(10854): TimaSignature is unavailable
,D/ActivityThread(10854): Added TimaKeyStore provider
,E/bt_hwcfg(10763): Read Local Name after HCI reset
,D/ResourcesManager(10854): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/bt_hwcfg(10763): Chipset BCM43569A1
D/bt_hwcfg(10763): Target name = [BCM4358A1]
,I/bt_hwcfg(10763): module_type[murata].
I/bt_hwcfg(10763): module_type[murata] is invalid.
E/bt_hwcfg(10763): patchram path ORG . BCM4358A1
E/bt_hwcfg(10763): patchram path ORG .. BCM4358A1
E/bt_hwcfg(10763): patchram path ORG bcm4358A0_V0033.0000.hcd BCM4358A1
E/bt_hwcfg(10763): patchram path ORG bcm4358A1_V0044.0078.hcd BCM4358A1
I/bt_hwcfg(10763): patch(org) : bcm4358A1_V0044.0078.hcd
I/bt_hwcfg(10763): Found patchfile: /vendor/firmware/bcm4358A1_V0044.0078.hcd
E/bt_hwcfg(10763): ORG patchram base 0044
E/bt_hwcfg(10763): ORG patchram minor 0078
E/bt_hwcfg(10763): fw ver (org)44.78
E/bt_hwcfg(10763): Final Patchram is /vendor/firmware/bcm4358A1_V0044.0078.hcd
,E/Zygote  (10873): MountEmulatedStorage()
E/Zygote  (10873): v2
I/libpersona(10873): KNOX_SDCARD checking this for 10186
I/libpersona(10873): KNOX_SDCARD not a persona
,I/SELinux (10873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/bt_hwcfg(10763): Axi patch failure or not include AXI patching
,I/SELinux (10873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc tv.peel.smartremote for broadcast tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver: pid=10873 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/SELinux (10873): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Killing 9641:com.android.mms/u0a52 (adj 13): bgCount ##31
,I/bt_hwcfg(10763): bt vendor lib: set UART baud 3000000
,D/TimaKeyStoreProvider(10873): TimaSignature is unavailable
,D/ActivityThread(10873): Added TimaKeyStore provider
,D/ResourcesManager(10873): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,W/ResourcesManager(10873): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CountryDetector( 3528): No listener is left
,I/SecureStorage(10778): [INFO]: SPID(0x00000005)Processing data has been completed
,I/SecureStorage(10778): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10778): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10778
I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10778): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10778): ssSupport state is = 1
,I/wpa_supplicant(10778): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10778): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10778): SIM READ ERROR
I/wpa_supplicant(10778): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10778): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10778): SIM READ ERROR
I/wpa_supplicant(10778): Blacklist: Clear (all) 
,I/wpa_supplicant(10778): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10778): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant(10778): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10778): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant(10778): rfkill: Cannot open RFKILL control device
,I/WebViewFactory(10873): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(10873): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(10873): Loading: webviewchromium
,I/LibraryLoader(10873): Time to load native libraries: 4 ms (timestamps 5763-5767)
I/LibraryLoader(10873): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10873): Binding Chromium to main looper Looper (main, tid 1) {10011db}
,I/LibraryLoader(10873): Expected native library version number "",actual native library version number ""
I/chromium(10873): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10873): Initializing chromium process, renderers=0
,W/art     (10873): Attempt to remove local handle scope entry from IRT, ignoring
,I/bt_hwcfg(10763): bt vendor lib: set UART baud 115200
I/bt_hwcfg(10763): FW Download delta = 456753
D/bt_hwcfg(10763): Settlement delay -- 100 ms
I/bt_hwcfg(10763): Setting fw settlement delay to 100 
,I/bt_hwcfg(10763): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg(10763): vendor lib fwcfg completed
,I/        (10763): BTE_InitTraceLevels -- TRC_HCI
I/        (10763): BTE_InitTraceLevels -- TRC_L2CAP
I/        (10763): BTE_InitTraceLevels -- TRC_RFCOMM
I/        (10763): BTE_InitTraceLevels -- TRC_AVDT
I/        (10763): BTE_InitTraceLevels -- TRC_AVRC
I/        (10763): BTE_InitTraceLevels -- TRC_A2D
I/        (10763): BTE_InitTraceLevels -- TRC_BNEP
I/        (10763): BTE_InitTraceLevels -- TRC_BTM
I/        (10763): BTE_InitTraceLevels -- TRC_GAP
I/        (10763): BTE_InitTraceLevels -- TRC_PAN
I/        (10763): BTE_InitTraceLevels -- TRC_SAP
I/        (10763): BTE_InitTraceLevels -- TRC_SDP
I/        (10763): BTE_InitTraceLevels -- TRC_GATT
I/        (10763): BTE_InitTraceLevels -- TRC_SMP
I/        (10763): BTE_InitTraceLevels -- TRC_BTAPP
I/        (10763): BTE_InitTraceLevels -- TRC_BTIF
I/        (10763): BTE_InitTraceLevels -- TRC_PROTOCOL
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/bt-l2cap(10763): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  (10763): BTM_SecRegister:p_cb_info->p_le_callback == 0xb39eb9e1 
E/bt-btm  (10763): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb39eb9e1 
,I/wpa_supplicant(10778): wlan0: Setting scan request: 0 sec 100000 usec
,W/chromium(10873): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
E/Tethering( 3528): No numeric data
,D/Tethering( 3528): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 3528): forceRefresh() from cache miss
,D/HotspotTile( 3689): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3689): updateTetherState():false, false
,W/chromium(10873): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10873): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 0 for uid 1000
I/chromium(10873): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
,D/NtpTrustedTime( 3528): forceRefresh Fail.
,V/NetworkStats( 3528): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3528): UpdateStatsForKnox
,V/NetworkStats( 3528): performPollLocked() took 3ms
,D/NtpTrustedTime( 3528): forceRefresh() from cache miss
,D/NtpTrustedTime( 3528): forceRefresh Fail.
,I/wpa_supplicant(10778): wlan0: State: DISCONNECTED -> DISCONNECTED
I/SecureStorage(10778): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10778): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10778
I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10778): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10778): ssSupport state is = 1
,I/SecureStorage(10778): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10778): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10778
I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10778): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10778): ssSupport state is = 1
I/wpa_supplicant(10778): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10778): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10778): SIM READ ERROR
I/wpa_supplicant(10778): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant(10778): nl80211: Could not configure driver mode
E/wpa_supplicant(10778): p2p0: Failed to initialize driver interface
I/wpa_supplicant(10778): Blacklist: Clear (all) 
,I/SecureStorage(10778): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,W/chromium(10873): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10873): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/SecureStorage(10778): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10778
I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10778): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10778): ssSupport state is = 1
I/SecureStorage(10778): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10778): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10778
I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10778): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10778): ssSupport state is = 1
I/wpa_supplicant(10778): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10778): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10778): SIM READ ERROR
I/wpa_supplicant(10778): rfkill: Cannot open RFKILL control device
W/art     (10873): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10873): onDetachedFromWindow called when already detached. Ignoring
,D/BluetoothAdapterProperties(10763): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,I/wpa_supplicant(10778): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant(10778): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,E/bt-btif (10763): Calling BTA_HhEnable
E/bt-btif (10763):                : sec: 0x1086, service name [] (up to 21 chars saved
D/BluetoothAdapterProperties(10763): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10763): populateRssiValuesNative
I/bluedroid(10763): getModelRssiValues
E/BluetoothServiceJni(10763): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10763): modelRssiValuesCallback, low, mid, high = -75,-65,127
,D/BluetoothAdapterProperties(10763): Name is: Note4-1
D/SettingsProvider( 3528): name = bluetooth_name
,D/BluetoothAdapterProperties(10763): Scan Mode:20
D/BluetoothAdapterProperties(10763): Discoverable Timeout:120
D/BluetoothAdapterProperties(10763): LE Address is:E0:B7:20:28:C5:81
E/bt-btif (10763): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif (10763): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif (10763): btif_sock_init: !radio_req && !rfc_init
E/bt-btif (10763): btif_sock_init: !vhci_init
D/IOP_DB_BT(10763): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT(10763): db_open: db_open : handle 3025481744l, read 14063 bytes onto local cache
D/IOP_DB_BT(10763): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT(10763): db_query: result 1
I/        (10763): iop_db_open: iop_db_open status 0
,D/bte_conf(10763): Device ID record 1 : primary
D/bte_conf(10763):   vendorId            = 0075
D/bte_conf(10763):   vendorIdSource      = 0001
D/bte_conf(10763):   product             = 0100
D/bte_conf(10763):   version             = 0200
D/bte_conf(10763):   clientExecutableURL = 
D/bte_conf(10763):   serviceDescription  = 
D/bte_conf(10763):   documentationURL    = 
D/bte_conf(10763): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni(10763): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState(10763): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties(10763): ScanMode =  20
D/BluetoothAdapterProperties(10763): State =  11
,D/SecContentProvider( 3528): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties(10763): Setting state to 12
I/BluetoothAdapterState(10763): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties(10763): Scan Mode:21
D/BluetoothAdapterProperties(10763): Discoverable Timeout:120
,D/SettingsProvider( 3528): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService(10763): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10763): updateAdapterState state is 12
,D/BluetoothAdapterService(10763): Autoconnection is available 
D/BluetoothAdapterService(10763): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService(10763): starting service from this receiver
D/BluetoothA2dp(10763): onBluetoothStateChange: up=true
D/BluetoothA2dp( 3528): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 4803): onBluetoothStateChange: up=true
,I/BluetoothAdapterState(10763): Entering On State from state = 11
,W/InputMethodManagerService( 3528): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3528): [BT Setting State] State =12
I/InputMethodManagerService( 3528): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/BluetoothPbapService(10763): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothTile( 3689):  onBluetoothStateChange:
,D/BluetoothTile( 3689):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3689): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,E/bt_h4   (10763): vendor lib postload completed
,I/SamsungIME( 4446): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothHeadset( 3950): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@edd8533, true
,D/BluetoothHeadset( 3950): registerMessageListener
,D/StatusBarManagerService( 3528): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3528): setIconVisibility slot=bluetooth visible=true
,D/PhoneStatusBar( 3689): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/HeadsetService(10763): registerMessageListener
,D/HeadsetService(10763): registerMessageListener
D/HeadsetStateMachine(10763): Disconnected process message: 70
D/HeadsetStateMachine(10763): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2c35d387
D/BluetoothTile( 3689):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 3689): onStateChanged: Bluetooth
I/Telecom ( 3950): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 3950): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,V/[CarModeFW](10126): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](10126): ConnectivityManager-handleMessage INITIAL_STATE_ON
,D/HeadsetStateMachine(10763): Disconnected process message: 9
D/HeadsetStateMachine(10763): mNumActive: 0 mNumHeld: 0 mCallState: 6
,I/wpa_supplicant(10778): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant(10778): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant(10778): Skip scan - bUseNetwork false
,I/BluetoothPbapService(10763): Handler(): got msg=1
,D/BluetoothManagerService( 3528): Broadcasting onBluetoothServiceUp() to 0 receivers.
,E/WifiStateMachine( 3528): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
E/WifiStateMachine( 3528): setSuspendOptimizations: 2 true
E/WifiStateMachine( 3528): mSuspendOptNeedsDisabled 0
,I/AudioHardwareTinyALSA( 2858): setParameters(A2dpSuspended=false)
,E/HeadsetStateMachine(10763): terminateScoUsingVirtualVoiceCall:No present call to terminate
,E/WifiStateMachine( 3528): Supplicant connection established
D/WifiNative-HAL( 3528): callSECApiBoolean - ID [21]
,I/wpa_supplicant(10778): HOTSPOT20_ENABLE called
I/wpa_supplicant(10778): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10778): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10778): SIM READ ERROR
I/wpa_supplicant(10778): Blacklist: Clear (all) 
,I/wpa_supplicant(10778): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant(10778): Skip scan - bUseNetwork false
E/WifiStateMachine( 3528): setWifiState: enabled
,D/WifiNative-HAL( 3528): callSECApiInt - ID [210]
,D/WifiConfigStore( 3528): Loading config and enabling all networks 
D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3528): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3689): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3689): Wifi onReceive(3)
,D/HotspotTile( 3689): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 3689): onStateChanged: Wi-Fi
D/HotspotTile( 3689): onReceive : 3, 0
,E/WifiConfigStore( 3528): Not a HS20
,E/WifiConfigStore( 3528): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/WifiStateMachine( 3528): update LTECoexState:0
D/WifiNative-HAL( 3528): callSECApiInt - ID [65]
,D/WifiNative-HAL( 3528): callSECApiBoolean - ID [13]
,I/wpa_supplicant(10778): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant(10778): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant(10778): reset timer : RESET_TIMER 0
I/wpa_supplicant(10778): P2P: Current p2p state = IDLE
I/wpa_supplicant(10778): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant(10778): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant(10778): First Scan Start
,I/wpa_supplicant(10778): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL( 3528): Setting external_sim to 1
D/WifiStateMachine( 3528): Setting OUI to DA-A1-19
I/WifiNative-HAL( 3528): startHal
E/wifi    ( 3528): getStaticLongField sWifiHalHandle 0x8f86d85c
D/wifi    ( 3528): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x600ae2
I/WifiNative-HAL( 3528): Could not start hal
,E/WifiStateMachine( 3528): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine( 3528): Attempting to reconnect to wifi network ..
E/native  ( 3528): do suspend true
,E/WifiStateMachine( 3528): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiStateMachine( 3528): updateConfiguredNetworkExpiration - currTime: 1449751087563
D/WifiP2pService( 3528): P2pDisabledState{ what=131203 }
D/WifiStateMachine( 3528): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/WifiScanningService( 3528): SCAN_AVAILABLE : 3
D/WifiScanningService( 3528): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 3528): SCAN_AVAILABLE : 3
D/RttService( 3528): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,I/WifiNative-HAL( 3528): startHal
E/wifi    ( 3528): getStaticLongField sWifiHalHandle 0x8e62598c
D/wifi    ( 3528): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0xc00ad6
I/WifiNative-HAL( 3528): Could not start hal
E/WifiScanningService( 3528): could not start HAL
D/CommandListener( 2845): Setting iface cfg
D/CommandListener( 2845): Trying to bring up p2p0
,D/WifiMonitor( 3528): startMonitoring(p2p0) with mConnected = true
E/WifiStateMachine( 3528): set country code pl
,D/WifiP2pService( 3528): P2pEnablingState
D/WifiP2pService( 3528): P2pEnablingState{ what=147457 }
D/WifiP2pService( 3528): P2p socket connection successful
,D/WifiP2pService( 3528): P2pEnabledState
D/WifiP2pService( 3528): sending p2p connection changed broadcast: IDLE
,E/WifiStateMachine( 3528): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 3528): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiP2pService( 3528): create mNetworkAgent
,D/WifiDisplayController( 3528): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3528): disconnect
D/WifiDisplayController( 3528): updateConnection
D/WifiDisplayController( 3528): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3528): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 3689): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3689): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,I/wpa_supplicant(10778): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/WifiStateMachine( 3528): set frequency band 0
,D/ConnectivityService( 3528): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 3528): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 3528): updateNetworkInfo()
D/ConnectivityService( 3528): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/CSLegacyTypeTracker( 3528): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,I/art     ( 3528): Explicit concurrent mark sweep GC freed 41066(2MB) AllocSpace objects, 13(208KB) LOS objects, 24% free, 48MB/64MB, paused 3.689ms total 101.673ms
,D/SecContentProvider( 3528): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/ActivityManager( 3528): Killing 10043:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,D/SmartBondingService( 3528): getNetworkEnabled : wifi : true mobile : false
,I/wpa_supplicant(10778): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,V/BluetoothPbapService(10763): PBAP Service initSocket try: 0
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine( 3528): setDetailed state send new extra info
,W/BluetoothAdapter(10763): getBluetoothService() called with no BluetoothManagerCallback
D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,D/BluetoothMapMasInstance(10763): set MAP SDP message type : 1
,D/WifiNative-HAL( 3528): p2pGetDeviceAddress
D/WifiNative-HAL( 3528): p2pGetDeviceAddress returning 92:b6:86:43:73:1c
,D/BluetoothSocket(10763): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket(10763): bindListen(), new LocalSocket 
D/BluetoothSocket(10763): bindListen(), new LocalSocket.getInputStream() 
D/WifiP2pService( 3528): DeviceAddress: 92:73:1c
D/BluetoothSocket(10763): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31122123
D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,D/WifiDisplayController( 3528): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note4-1
D/WifiDisplayController( 3528):  deviceAddress: 92:b6:86:43:73:1c
D/WifiDisplayController( 3528):  primary type: 10-0050F204-5
D/WifiDisplayController( 3528):  secondary type: null
D/WifiDisplayController( 3528):  wps: 0
D/WifiDisplayController( 3528):  grpcapab: 0
D/WifiDisplayController( 3528):  devcapab: 0
D/WifiDisplayController( 3528):  status: 3
D/WifiDisplayController( 3528):  wfdInfo: null
D/WifiDisplayController( 3528):  groupownerAddress: null
D/WifiDisplayController( 3528):  GOdeviceName: null
D/WifiDisplayController( 3528):  interfaceAddress: 
D/WifiDisplayController( 3528):  SConnectInfo : null
,D/BluetoothSocket(10763): channel: 19
D/BluetoothPbapService(10763): PBAP Socket is BluetoothServerSocket
W/ContextImpl( 7605): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/BluetoothAdapter(10763): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10763): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket(10763): bindListen(), new LocalSocket 
D/BluetoothSocket(10763): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10763): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ee2f620
D/BluetoothSocket(10763): channel: 5
,D/WifiP2pService( 3528): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 3528): InactiveState
,D/WifiP2pService( 3528): InactiveState{ what=143376 }
D/WifiP2pService( 3528): P2pEnabledState{ what=143376 }
D/LocalBluetoothProfileManager( 7605): Adding local A2DP profile
,I/wpa_supplicant(10778): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService( 3528): updateNetworkInfo()
D/WifiP2pService( 3528): InactiveState{ what=143376 }
D/LocalBluetoothProfileManager( 7605): Adding local HEADSET profile
D/WifiP2pService( 3528): P2pEnabledState{ what=143376 }
,E/BluetoothHeadset( 7605): BTStateChangeCB is registed
,E/BluetoothHeadset( 7605): BluetoothHeadset service is binded
,W/ContextImpl( 7605): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 7605): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 7605): PANU : true
D/LocalBluetoothProfileManager( 7605): Adding local MAP profile
,D/BluetoothMap( 7605): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 7605): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 7605): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 7605): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 7605): onReceive
D/BluetoothA2dp( 7605): Proxy object connected
D/A2dpProfile( 7605): Bluetooth service connected
,D/BluetoothAdapterService(10763): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a372751
D/BtConfig.SecureMode(10763): isSecureModeOn:false
,D/HeadsetProfile( 7605): Bluetooth service connected
,D/AuthorizationBluetoothService( 4229): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/Bluetoothsap( 7605): BluetoothSAP Proxy object connected
,D/SapProfile( 7605): Bluetooth service connected
D/Bluetoothsap( 7605): getConnectedDevices()
,D/BluetoothInputDevice( 7605): Proxy object connected
D/HidProfile( 7605): Bluetooth service connected
,I/Hs20UtilService( 6284): Starting #3
,D/BluetoothPan( 7605): BluetoothPAN Proxy object connected
D/PanProfile( 7605): Bluetooth service connected
,I/Hs20UtilService( 6284): Message received 5011
I/WifiStateMachine( 3528): callSECApi what=207
,E/WifiStateMachine( 3528): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL( 3528): callSECStringApiVoid - ID [215]
E/WifiNative-HAL( 3528): invaild command id : 215
,D/BluetoothMap( 7605): Proxy object connected
D/MapProfile( 7605): Bluetooth service connected
D/BluetoothPbap( 7605): Proxy object connected
,D/PbapServerProfile( 7605): Bluetooth service connected
,D/KeyguardWallpaperUpdator(10837): cancelUpdateWallpaper
,D/SecContentProvider( 3528): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/KeyguardWallpaperUpdator(10837): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10837): stopCheckCategoryVersion
,I/SignOutReceiver(10346): WIFI_STATE_CHANGED_ACTION
,W/BluetoothAdapter(10763): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10763): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
D/BluetoothSocket(10763): bindListen(), new LocalSocket 
D/BluetoothSocket(10763): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10763): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@220561aa
D/BluetoothSocket(10763): channel: 12
I/BtOppRfcommListener(10763): Accept thread started.
,D/NearbySettings( 7605): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 7605): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 7605): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 7605): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 7605): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 7605): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3528): New client listening to asynchronous messages
,I/NearbySettings( 7605): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7605): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7605): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7605): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10957): MountEmulatedStorage()
I/libpersona(10957): KNOX_SDCARD checking this for 10079
E/Zygote  (10957): v2
I/libpersona(10957): KNOX_SDCARD not a persona
,I/SELinux (10957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10957): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=10957 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10957): TimaSignature is unavailable
,D/ActivityThread(10957): Added TimaKeyStore provider
,D/ResourcesManager(10957): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(10957): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 3528): Killing 10059:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,I/wpa_supplicant(10778): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant(10778): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant(10778): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant(10778): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant(10778): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3528): [1,449,751,088,115 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3528): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@6a06177 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,I/wpa_supplicant(10778): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant(10778): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant(10778): Associated with C0.AA.48
E/WifiStateMachine( 3528): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,I/wpa_supplicant(10778): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant(10778): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,I/wpa_supplicant(10778): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant(10778): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant(10778): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant(10778): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(10778): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant(10778): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant(10778): Blacklist: Clear (temp) 
I/wpa_supplicant(10778): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3528): Network connection established
,D/WifiNative-HAL( 3528): callSECApiVoid - ID [50]
E/WifiStateMachine( 3528): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3528): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3528): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3528): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine( 3528): L2ConnectedState "NG700" nid=0
D/ConnectivityService( 3528): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3528): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3528): updateNetworkInfo()
E/WifiConfigStore( 3528): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3528): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine( 3528): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3528): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3528): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Hs20UtilService( 6284): Starting #4
,I/Hs20UtilService( 6284): Message received 5007
,D/NearbySettings( 7605): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 7605): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 7605): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 7605): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7605): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7605): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7605): MountReceiver.mPrefHandler - 7002
,D/CommandListener( 2845): Setting iface cfg
,I/SignOutReceiver(10346): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3528): Start Dhcp Watchdog 1
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,E/WifiStateMachine( 3528): Force RSSI Broadcast 1/3
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3528): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3528): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3528): do suspend false
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3528): InactiveState{ what=143375 }
D/SecContentProvider2( 3528): mCursor = null
D/WifiP2pService( 3528): P2pEnabledState{ what=143375 }
,E/dhcpcd  (10975): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (10975): version 5.5.6 starting
,E/dhcpcd  (10975): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (10975): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (10975): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (10975): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (10975): bssid match
,I/dhcpcd  (10975): wlan0: rebinding lease of 192.168.1.124
,I/dhcpcd  (10975): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
I/dhcpcd  (10975): wlan0: leased 192.168.1.124 for 86400 seconds
E/WifiStateMachine( 3528): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine( 3528): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine( 3528): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3528): do suspend true
D/WifiP2pService( 3528): InactiveState{ what=143375 }
D/WifiP2pService( 3528): P2pEnabledState{ what=143375 }
E/WifiStateMachine( 3528): WifiStateMachine DHCP successful
E/WifiStateMachine( 3528): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3528): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3528): Not connected state, yet.
E/WifiStateMachine( 3528): VerifyingLinkState enter
D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3528): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3528): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3528): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3528): callSECApiInt - ID [210]
E/WifiStateMachine( 3528): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3528): updateNetworkInfo()
D/ConnectivityService( 3528): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3528): Adding iface wlan0 to network 502
D/WifiWatchdogStateMachine( 3528): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3528): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3528): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3528): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3528): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
E/WifiStateMachine( 3528): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3528): Now, connected state.
E/WifiStateMachine( 3528): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
E/WifiStateMachine( 3528): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/WifiTrafficPoller( 3528): evaluateTrafficStatsPolling
D/ConnectivityService( 3528): Adding Route [fe80::/64 -> :: wlan0] to network 502
D/ConnectivityService( 3528): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
E/WifiStateMachine( 3528): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
E/WifiStateMachine( 3528): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/Hs20UtilService( 6284): Starting #5
D/ConnectivityService( 3528): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
I/WifiTrafficPoller( 3528): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3528): callSECApiVoid - ID [212]
E/ConnectivityService( 3528): Unexpected mtu value: 0, wlan0
I/Hs20UtilService( 6284): Message received 5007
I/WifiStateMachine( 3528): REQUEST_POWER_SAVE_ON
V/        ( 2845): QcRouteController
D/NearbySettings( 7605): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
I/NearbySettings( 7605): MountReceiver.onReceive - Keep current state
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
V/        ( 2845): QcRouteController
V/        ( 2845): QcRouteController
V/        ( 2845): QcRouteController
I/SignOutReceiver(10346): NETWORK_STATE_CHANGED_ACTION
V/        ( 2845): QcRouteController
I/Hs20UtilService( 6284): Starting #6
I/Hs20UtilService( 6284): Message received 5007
V/        ( 2845): QcRouteController
D/NearbySettings( 7605): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 7605): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 7605): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 7605): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7605): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7605): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7605): MountReceiver.mPrefHandler - 7002
V/        ( 2845): QcRouteController
V/        ( 2845): QcRouteController
I/SignOutReceiver(10346): NETWORK_STATE_CHANGED_ACTION
I/Hs20UtilService( 6284): Starting #7
I/Hs20UtilService( 6284): Message received 5007
V/        ( 2845): QcRouteController
D/NearbySettings( 7605): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 7605): MountReceiver.onReceive - Keep current state
D/ConnectivityService( 3528): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 3528): LTETest block dns file not exists
I/WifiStateMachine( 3528): callSECApi what=220
D/WifiStateMachine( 3528): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
D/ConnectivityService( 3528): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
E/ConnectivityService( 3528): updateNetworkInfo()
D/ConnectivityService( 3528): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3528): updateNetworkInfo()
D/ConnectivityService( 3528): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3528): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 3528):    accepting network in place of null
D/ConnectivityService( 3528): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/TelephonyNetworkFactory( 3980): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/System.out( 3528): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3528): (HTTPLog)-Static: isShipBuild true
I/System.out( 3528): (HTTPLog)-Thread-188-1008455444: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3528): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
E/CSLegacyTypeTracker( 3528): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3528): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 3528): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/EntConnectivity( 3528): Not allowed due to - mEnabled false
D/ConnectivityService( 3528): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Validated
D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/Tethering( 3528): MasterInitialState.processMessage what=3
D/NtpTrustedTime( 3528): forceRefresh() from cache miss
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
V/NetworkStats( 3528): updateIfacesLocked()
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
V/NetworkStats( 3528): performPollLocked(flags=0x1)
D/SmartBondingService( 3528): getNetworkEnabled : wifi : true mobile : false
D/NetworkStatsFactory( 3528): UpdateStatsForKnox
D/ConnectivityService( 3528): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3528): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524290
D/ConnectivityService( 3528): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): 0
D/ConnectivityService( 3528): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3689): updateDataNetType()
V/NetworkStats( 3528): performPollLocked() took 7ms
D/StatusBar.NetworkController( 3689): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3689): updateLTEICONDataNetType:0
D/ConnectivityManager.CallbackHandler( 4478): CM callback handler got msg 524290
D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 4478): CM callback handler got msg 524290
D/StatusBar.NetworkController( 3689): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
I/SignOutReceiver(10346): NETWORK_STATE_CHANGED_ACTION
D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3689): updateDataNetType()
D/StatusBar.NetworkController( 3689): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3689): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 3689): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
I/SurfaceFlinger( 2850): id=13 createSurf (1x1),1 flag=4, Uoast
D/PowerManagerService( 3528): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3528
D/mali_winsys( 3689): new_window_surface returns 0x3000,  [1120x201]-format:1
D/NtpTrustedTime( 3528): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449751090789 mCachedNtpElapsedRealtime : 139343 mCachedNtpCertainty : 8
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
V/NetworkStats( 3528): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3528): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3528): SmartBondingReceiver: wifi ap is changed, init speed ratio
,I/DBG_DM  ( 5926): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 5926): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 5926): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 5926): [IlIIlIIlIllllIlllIII(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 5926): [IlIlllIlllllIlIllllI(403/llllllIllIlIlllIIlIl)] Check completed.
,D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/SmartBondingService( 3528): getNetworkEnabled : wifi : true mobile : false
,D/AlarmManagerService( 3528): Setting time of day to sec=1449751091
D/AlarmManagerService( 3528): Trying to open a file
I/DBG_DM  ( 5926): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 5926): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/AlarmManagerService( 3528): File Open Success
,D/AlarmManagerService( 3528): File Close Success
I/AlarmManagerService( 3528): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 3528): waitForAlarm result :65536
I/DBG_DM  ( 5926): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5926): [IIlIIIlllllIIlIIIlII(72/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 5926): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 5926): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
,I/DBG_DM  ( 5926): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 5926): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 5926): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,D/WifiStateMachine( 3528): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.TIME_SET
,D/KeyguardEffectViewController( 3689): onReceive action : android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 3689): handleTimeUpdate
D/SettingsProvider( 3528): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 10060
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/KeyguardEffectViewUtil( 3689): isPowerSavingMode() :false
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/KeyguardEffectViewUtil( 3689): isStrongPowerSavingMode() :false
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/KeyguardEffectViewController( 3689): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/VisualEffectParticleEffect( 3689): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3689): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{e201e8c G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3689): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{3943d9d5 V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3689): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{e201e8c G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3689): clearEffect
D/WallpaperWidget( 3689): setLockScreenWallpaper()
D/KeyguardEffectViewUtil( 3689): getCurrentWallpaper() mWallpaperPath :null
,E/Zygote  (11037): MountEmulatedStorage()
E/Zygote  (11037): v2
I/libpersona(11037): KNOX_SDCARD checking this for 1000
I/libpersona(11037): KNOX_SDCARD not a persona
,I/SELinux (11037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3528): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11037 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (11037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11037): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Settings( 3528): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
W/SEC_DRM_PLUGIN_Playready( 2857): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1449751090 after conversion: 1449751090
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
W/SEC_DRM_PLUGIN_Playready( 2857): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1449751091 after conversion: 1449751091
,V/AlarmManager( 3528): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 3528): <AppSync3 Whitelist>
V/AlarmManager( 3528): (AppSync) ### 0 added ###
,I/DBG_DM  ( 5926): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
,E/Zygote  (11054): MountEmulatedStorage()
I/libpersona(11054): KNOX_SDCARD checking this for 10090
E/Zygote  (11054): v2
I/libpersona(11054): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider(11037): TimaSignature is unavailable
I/SELinux (11054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ActivityThread(11037): Added TimaKeyStore provider
,I/DBG_DM  ( 5926): [IlIIlIIlIllllIlllIII(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
I/SELinux (11054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11054): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5926): [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/ActivityManager( 3528): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=11054 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 5926): [IlIIlIIlIllllIlllIII(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 5926): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,I/DBG_DM  ( 5926): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11054): TimaSignature is unavailable
,D/ActivityThread(11054): Added TimaKeyStore provider
,E/Zygote  (11069): MountEmulatedStorage()
E/Zygote  (11069): v2
I/libpersona(11069): KNOX_SDCARD checking this for 10050
I/libpersona(11069): KNOX_SDCARD not a persona
,I/SELinux (11069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/DBG_DM  ( 5926): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(502/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/SELinux (11069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11069): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=11069 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/GpsLocationProvider( 3528): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 5926): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5926): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,D/ResourcesManager(11054): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11037): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,E/ActivityThread( 4478): Failed to find provider info for com.android.contacts.metadata
,D/TimaKeyStoreProvider(11069): TimaSignature is unavailable
,D/ActivityThread(11069): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG(11037): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11037): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11037): new DMDBOpenHelper instance
,D/ResourcesManager(11069): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(11069): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11069): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11069): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/SyncManager( 3528): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 16013, reason: UserStart, SyncResult: databaseError: true stats []
W/ResourcesManager(11069): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SyncManager( 3528): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 171332, reason: UserStart
W/ResourcesManager(11069): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
I/DBG_DM  ( 5926): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,W/ResourcesManager(11069): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/DBG_DM  ( 5926): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 5926): [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
E/DBG_DM  ( 5926): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,W/ResourcesManager(11069): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/DBG_DM  ( 5926): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@27dbac7f
,W/ResourcesManager(11069): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/DBG_DM  ( 5926): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,W/ResourceType( 4945): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4945): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11037): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11037): sales region : global
I/PCWCLIENTTRACE_PushUtil(11037): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11037): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 5926): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/KeyguardEffectViewUtil( 3689): set current wallpaper info
,D/SettingsProvider( 3528): name = keyguard_current_wallpaper_type
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 10060
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,I/jxcore-log(10693): Test app app.js loaded
I/jxcore-log(10693): 
,E/Zygote  (11089): MountEmulatedStorage()
I/libpersona(11089): KNOX_SDCARD checking this for 10135
E/Zygote  (11089): v2
I/libpersona(11089): KNOX_SDCARD not a persona
,I/ActivityManager( 3528): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11089 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11089): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/Choreographer(10693): Skipped 294 frames!  The application may be doing too much work on its main thread.
,I/DBG_DM  ( 5926): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2( 3528): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3528): mCursor = null
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8754(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 550us total 21.221ms
,D/TimaKeyStoreProvider(11089): TimaSignature is unavailable
,D/ActivityThread(11089): Added TimaKeyStore provider
,D/SecContentProvider2( 3528): uri = 14 selection = getSealedState
D/SecContentProvider2( 3528): mCursor = null
,D/ApplicationPolicy( 3528): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3528): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 3528): showStatusBarByNotification() mOpenByNotification=false
,I/DBG_DM  ( 5926): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 642us total 9.416ms
,D/ResourcesManager( 3689): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,I/DBG_DM  ( 5926): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/ResourcesManager(11089): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 275us total 9.235ms
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3528): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 10060
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,D/PackageManager( 3528): findPreferredActivity: No PreferredActivities set
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3528): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 10060
,D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,I/chromium(10693): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/BackupManagerService( 3528): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/StatusBar-DoNotDistrub( 3689): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 3689): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar-DoNotDistrub( 3689): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager( 2858): getOutputsForDevice device 0002 -> 0002
I/AudioService( 3528): getStreamVolume 5 index 110
I/DBG_DM  ( 5926): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
D/StatusBar-DoNotDistrub( 3689): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
I/DBG_DM  ( 5926): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/chromium(10693): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/DBG_DM  ( 5926): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,D/NearbySource(11069): Nearby Source Create!
D/NearbyContext(11069): Nearby Context Create!
,V/GLSActivity( 4229): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/VacuumService( 4229): Vacuum at: now=1449751091541 tag=VacuumService
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11069): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(11069): Samsung link source created
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.TIME_TICK
E/Auth.Api.Credentials( 4478): [CredentialSyncAdapter] Unknown sync event.
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/DelayedSyncController(11054): Delaying sync.
,D/KnoxNotification( 3689): ----- inflateViews : modified publicViewLocal -----
,D/ContactProvider(11069): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/KnoxNotification( 3689): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 3689): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 3689): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@4d6895c
,D/PersonaManager( 3689): isKioskContainerExistOnDevice
D/PersonaManager( 3689): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3689): Icon Only
,I/MusicStore(11089): Database version: 104
,I/StatusBar( 3689): Icon Only
,I/ActivityManager( 3528): Killing 10077:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
D/PanelView( 3689): There is/are notification(s) 
D/PanelView( 3689): There is/are notification(s) 
D/PersonaManager( 3689): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3689): Icon Only
I/StatusBar( 3689): Icon Only
D/PanelView( 3689): There is/are notification(s) 
,D/KeyguardEffectViewUtil( 3689): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3689): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3689): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
D/VisualEffectParticleEffect( 3689): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3689): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{e201e8c G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3689): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{3943d9d5 V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3689): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{e201e8c G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3689): clearEffect
D/KeyguardUpdateMonitor( 3689): handleTimeUpdate
D/KeyguardEffectViewController( 3689): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3689): *** don't update sliding image ***
,V/GLSActivity( 4229): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ContactProvider(11069): getAllContactInfoList End
,I/syncContacts(11069): thread: 1488, sync time = 75
,D/ResourcesManager(11089): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11089): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11089): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11089): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/PanelView( 3689): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,W/ActivityThread(11089): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11089): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39183c95: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11089): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11089): GMSCore installation verified
,I/ConfigStore(11089): Config Database version: 1
,I/ActivityManager( 3528): Killing 10093:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,D/PicasaService(11069): start picasa sync
,D/PicasaService(11069): end picasa sync
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11089): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/ContextImpl(11089): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11089): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3528): getStreamVolume 3 index 0
,I/MediaRouter(11089): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor(11089): type=WIFI subType= reason=null isConnected=true
,E/Zygote  (11136): MountEmulatedStorage()
E/Zygote  (11136): v2
I/libpersona(11136): KNOX_SDCARD checking this for 10002
I/libpersona(11136): KNOX_SDCARD not a persona
,I/SELinux (11136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3528): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11136 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11136): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11089): type=WIFI subType= reason=null isConnected=true
,D/TimaKeyStoreProvider(11136): TimaSignature is unavailable
,D/ActivityThread(11136): Added TimaKeyStore provider
,V/GLSActivity( 4229): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager(11136): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,V/GLSActivity( 4229): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 3528): Killing 10151:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11158): MountEmulatedStorage()
E/Zygote  (11158): v2
I/libpersona(11158): KNOX_SDCARD checking this for 1000
I/libpersona(11158): KNOX_SDCARD not a persona
,I/SELinux (11158): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11158): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11158): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11158 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/DelayedSyncController(11054): Delaying sync.
,D/TimaKeyStoreProvider(11158): TimaSignature is unavailable
,D/ActivityThread(11158): Added TimaKeyStore provider
,W/art     (10293): Attempt to remove local handle scope entry from IRT, ignoring
,D/ResourcesManager(11158): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10147
,I/DIAGMON_AGENT(11158): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11158): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11158): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11158): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11158): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11185): MountEmulatedStorage()
E/Zygote  (11185): v2
I/libpersona(11185): KNOX_SDCARD checking this for 10012
I/libpersona(11185): KNOX_SDCARD not a persona
,I/SELinux (11185): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3528): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11185 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11185): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11185): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11185): TimaSignature is unavailable
,D/ActivityThread(11185): Added TimaKeyStore provider
,D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3528): Killing 10209:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/FOTA_Client(11185): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11185): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/ActivityManager( 3528): Killing 10194:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,I/FOTA_Client(11185): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11201): MountEmulatedStorage()
E/Zygote  (11201): v2
I/libpersona(11201): KNOX_SDCARD checking this for 10021
I/libpersona(11201): KNOX_SDCARD not a persona
,I/SELinux (11201): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11201): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11201): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11201 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 10229:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11201): TimaSignature is unavailable
,D/ActivityThread(11201): Added TimaKeyStore provider
,D/ResourcesManager(11201): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11201): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 13:38:12 GMT+01:00 2015
,I/KLMS-2.4.521: (11201): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11201): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11201): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11201): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11201): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11201): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11201): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11201): StateImplV2(): networkChangeListener().START
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (11201): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11201): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11201): StateImplV2(): networkChangeListener().END
,E/Zygote  (11222): MountEmulatedStorage()
I/libpersona(11222): KNOX_SDCARD checking this for 10038
E/Zygote  (11222): v2
I/libpersona(11222): KNOX_SDCARD not a persona
,I/SELinux (11222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11222 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
E/SELinux (11222): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11201): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3528): Killing 10246:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11222): TimaSignature is unavailable
,D/ActivityThread(11222): Added TimaKeyStore provider
,D/ResourcesManager(11222): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11222): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11238): MountEmulatedStorage()
I/libpersona(11238): KNOX_SDCARD checking this for 1000
E/Zygote  (11238): v2
I/libpersona(11238): KNOX_SDCARD not a persona
,I/SELinux (11238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11238 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11238): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Killing 10261:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11238): TimaSignature is unavailable
,D/ActivityThread(11238): Added TimaKeyStore provider
,D/ResourcesManager(11238): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11258): MountEmulatedStorage()
I/libpersona(11258): KNOX_SDCARD checking this for 10039
E/Zygote  (11258): v2
I/libpersona(11258): KNOX_SDCARD not a persona
,I/SELinux (11258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11258): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11258 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 10366:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11258): TimaSignature is unavailable
,D/ActivityThread(11258): Added TimaKeyStore provider
,D/ResourcesManager(11258): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(11258): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11258): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService(11258): PushLog.txt file is not deleted.
D/SPPClientService(11258): PushLog.txt file is not deleted.
D/SPPClientService(11258): ============PushLog. stop!
,E/SPPClientService(11258): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11276): MountEmulatedStorage()
E/Zygote  (11276): v2
I/libpersona(11276): KNOX_SDCARD checking this for 10045
I/libpersona(11276): KNOX_SDCARD not a persona
,I/SELinux (11276): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11276): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=11276 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11276): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Killing 10384:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11276): TimaSignature is unavailable
,D/ActivityThread(11276): Added TimaKeyStore provider
,D/ResourcesManager(11276): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (11276): [SSP] onCreated
,I/SA      (11276): [TPM] There is no property file
,I/SA      (11276): [SCU] isHaveSA() - false
,I/SA      (11276): [TPM] getModelProperty : null
I/SA      (11276): [TPM] getCSCProperty : null
,I/SA      (11276): [DM] init START
,I/SA      (11276): [DM] This device is not a Vodafone
,I/SA      (11276): checkReactivationActive for LOLLIPOP
I/SA      (11276): checkReactivationActive for reactiveActive
I/SA      (11276): setSupportRL : true
,I/SA      (11276): [SCU] isHaveSA() - false
I/SA      (11276): support phone number id : false
,I/SA      (11276): [DM] init END
I/SA      (11276): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11276): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11276): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11276): [SLFUCHKMGR] constructor called
,I/art     ( 3528): Explicit concurrent mark sweep GC freed 83086(4MB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 48MB/64MB, paused 1.497ms total 89.328ms
,I/SA      (11276): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11276): [OR] == isSIMCardReady false ==
,I/SA      (11276): [SCU] == networkStateCheck == true
,I/SA      (11276): [DM] getCountryCodeFromCSC : PL
I/SA      (11276): isChinaCountryCode : false
I/SA      (11276): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11276): [OR] == networkStateCheck true ==
,I/SA      (11276): [OR] GetMyCountryZoneTask
,I/SA      (11276): [OR] onReceive END
,I/ActivityManager( 3528): Killing 10401:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/SA      (11276): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3714): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11276): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11276): [SSP] query invoked
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,I/SA      (11276): [TPMU] GetMccFromDB : null
,E/Zygote  (11298): MountEmulatedStorage()
I/libpersona(11298): KNOX_SDCARD checking this for 10067
E/Zygote  (11298): v2
I/libpersona(11298): KNOX_SDCARD not a persona
,I/SELinux (11298): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11298): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11298 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11298): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      (11276): [SCU] getMccFromPreferece mcc = 260
I/SA      (11276): [TPM] isNoProxy(default) : true
,D/TimaKeyStoreProvider(11298): TimaSignature is unavailable
,D/ActivityThread(11298): Added TimaKeyStore provider
,D/ResourcesManager(11298): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(11298): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11298): Other Intent
,I/ActivityManager( 3528): Killing 10417:com.facebook.system/u0a10 (adj 13): bgCount ##31
,D/accuweather( 5229): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 5229): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5229): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5229): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5229): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5229): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5229): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11314): MountEmulatedStorage()
E/Zygote  (11314): v2
I/libpersona(11314): KNOX_SDCARD checking this for 1000
I/libpersona(11314): KNOX_SDCARD not a persona
,I/SELinux (11314): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11314): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11314): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11314 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11314): TimaSignature is unavailable
,D/ActivityThread(11314): Added TimaKeyStore provider
,E/WifiStateMachine( 3528): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3528): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2845): QcRouteController
,D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
,D/ResourcesManager(11314): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11314): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3528): route cmd failed: 
W/NetworkManagementService( 3528): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '56 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 56 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3528): '
W/NetworkManagementService( 3528): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3528): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3528): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3528): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3528): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3528): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3528): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3528): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3528): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3528): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524295
D/ConnectivityService( 3528): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 4478): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 4478): CM callback handler got msg 524295
I/KnoxUsageLogPro(11314): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(11314): premStatus:2
I/KnoxUsageLogPro(11314): isEulaShown : false
I/KnoxUsageLogPro(11314): KnoxUsageReceiver onReceive : not Processible, just return
D/KeyguardWallpaperUpdator(10837): cancelUpdateWallpaper
D/KeyguardWallpaperUpdator(10837): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10837): stopCheckCategoryVersion
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/Zygote  (11332): MountEmulatedStorage()
I/libpersona(11332): KNOX_SDCARD checking this for 10136
E/Zygote  (11332): v2
I/libpersona(11332): KNOX_SDCARD not a persona
I/SELinux (11332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11332): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11332 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3528): Killing 10523:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 277us total 9.767ms
D/TimaKeyStoreProvider(11332): TimaSignature is unavailable
D/ActivityThread(11332): Added TimaKeyStore provider
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 472us total 8.376ms
D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 257us total 8.402ms
,V/GLSActivity( 4229): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4229): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AclDataUtils(10293): Circle ID not found for type: 9
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11332): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11332): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11332): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11332): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(11332): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11332): Loading: webviewchromium
,I/LibraryLoader(11332): Time to load native libraries: 2 ms (timestamps 1452-1454)
I/LibraryLoader(11332): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11332): Binding Chromium to main looper Looper (main, tid 1) {2654ac77}
,I/LibraryLoader(11332): Expected native library version number "",actual native library version number ""
,I/chromium(11332): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11332): Initializing chromium process, renderers=0
,W/art     (11332): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11332): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid(11332): Requires BLUETOOTH permission
,I/chromium(11332): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(11332): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/SA      (11276): [RC New] Execute method=[GET] start
,I/SA      (11276): [RC New] Security=[true]
,I/System.out(11276): Thread-1535(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11276): Thread-1535(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11276): Thread-1535(ApacheHTTPLog):isShipBuild true
I/System.out(11276): Thread-1535(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10045
,I/NSApplication(11332): Starting up...
,I/ActivityManager( 3528): Killing 10560:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11401): MountEmulatedStorage()
,E/Zygote  (11401): v2
I/libpersona(11401): KNOX_SDCARD checking this for 10150
I/libpersona(11401): KNOX_SDCARD not a persona
,I/SELinux (11401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=11401 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (11401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Killing 9769:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
E/SELinux (11401): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Killing 10576:com.android.calendar/u0a164 (adj 13): bgCount ##32
,D/TimaKeyStoreProvider(11401): TimaSignature is unavailable
,D/ActivityThread(11401): Added TimaKeyStore provider
,D/ResourcesManager(11401): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(11401): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11401): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11401): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(11401): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(11401): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(11401): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,I/ActivityManager( 3528): Killing 10468:com.android.vending/u0a31 (adj 13): bgCount ##31
,I/iu.SyncManager( 4478): SYNC; picasa accounts
,D/NetworkLogImpl( 4478): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4478): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4478): num queued entries: 0
,I/iu.UploadsManager( 4478): num updated entries: 0
I/iu.SyncManager( 4478): NEXT; no task
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,E/Zygote  (11421): MountEmulatedStorage()
E/Zygote  (11421): v2
I/libpersona(11421): KNOX_SDCARD checking this for 10013
I/libpersona(11421): KNOX_SDCARD not a persona
,I/SELinux (11421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=11421 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11421): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11421): TimaSignature is unavailable
,D/ActivityThread(11421): Added TimaKeyStore provider
,D/ResourcesManager(11421): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/dhcpcd  (10975): wlan0: sending IPv6 Router Solicitation
,D/WaitQueueForNetworkActivate(11421): notifyNetworkActivated
,W/ContextImpl(11421): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3528): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ResourcesManager( 4229): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GCM     ( 4229): GCM config loaded
,D/hcjo    (11421): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(11421): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(11421): exit::IDLE
D/InitializeManagerStateMachine(11421): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(11421): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(11421): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(11421): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11421): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(11421): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11421): entry::SUCCESS
D/hcjo    (11421): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/FOTA_Client(11185): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/splitIntent( 3528): Split this intent : android.intent.action.TIME_SET !!   mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=17 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 3528): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/hcjo    (11421): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,I/FOTA_Client(11185): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11445): MountEmulatedStorage()
E/Zygote  (11445): v2
I/libpersona(11445): KNOX_SDCARD checking this for 10052
I/libpersona(11445): KNOX_SDCARD not a persona
,D/WifiStateMachine( 3528): updateConfiguredNetworkExpiration - currTime: 1449751093260
I/SELinux (11445): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/WifiStateMachine( 3528): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,I/SELinux (11445): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11445): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=11445 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11201): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Dec 10 13:38:13 GMT+01:00 2015
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11445): TimaSignature is unavailable
,D/ActivityThread(11445): Added TimaKeyStore provider
E/Zygote  (11460): MountEmulatedStorage()
E/Zygote  (11460): v2
I/libpersona(11460): KNOX_SDCARD checking this for 10164
I/libpersona(11460): KNOX_SDCARD not a persona
,I/SELinux (11460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=11460 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (11460): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 3774): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 3774): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/hcjo    (11421): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (11421): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/InitializeManagerStateMachine(11421): exit::SUCCESS
D/InitializeManagerStateMachine(11421): entry::IDLE
,I/KLMS-2.4.521: (11201): KLMSAbstractReciever(): onReceive().END.
,D/ResourcesManager(11445): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11201): KLMSIntentService(): onCreate()
W/ResourcesManager(11445): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(11445): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11445): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11445): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11445): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(11445): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/daemonapp( 3774): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
I/KLMS-2.4.521: (11201): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/comsamsunglog( 3774): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3774): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
D/comsamsunglog( 3774): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3774): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 3774): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/TimaKeyStoreProvider(11460): TimaSignature is unavailable
I/KLMS-2.4.521: (11201): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/daemonapp( 3774): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/ActivityThread(11460): Added TimaKeyStore provider
I/KLMS-2.4.521: (11201): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
I/KLMS-2.4.521: (11201): KLMSIntentService(): TIME_CHANGED
I/KLMS-2.4.521: (11201): StateImplV2(): dateTimeChanged().START : Thu Dec 10 13:38:13 GMT+01:00 2015
,E/Zygote  (11476): MountEmulatedStorage()
I/libpersona(11476): KNOX_SDCARD checking this for 10036
E/Zygote  (11476): v2
I/libpersona(11476): KNOX_SDCARD not a persona
,D/daemonapp( 3774): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
I/SELinux (11476): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/daemonapp( 3774): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3774): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
I/ActivityManager( 3528): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/com.cigna.mobile.coach.CoachBroadcastReceiver: pid=11476 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.4.521: (11201): StateImplV2(): dateTimeChanged().END
,I/SELinux (11476): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/daemonapp( 3774): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
E/SELinux (11476): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11201): KLMSIntentService(): onDestroy()
,D/ResourcesManager(11460): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11460): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11460): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11460): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11460): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(11476): TimaSignature is unavailable
,D/ActivityThread(11476): Added TimaKeyStore provider
,D/comdaemonstockapp( 3774): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 3774): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/Mms/MmsApp(11445): [start]    onCreate() consume time = 0.0
,D/ResourcesManager(11476): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/Mms/ArtClassLoader(11445): init before art
,D/Mms/ArtClassLoader(11445): init [DONE] art
,D/Mms/TelephonyPermission(11445): start operation mode monitor
,D/ResourcesManager(11445): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11445): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission(11445): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(11445): isDefault true
,D/Mms/MmsApp(11445): onCreate() com.android.mms
,I/CheckinService( 4478): Checkin interval check for package: unspecified last checkin: 1449680000549 min interval config: 0 actual interval: 71092812
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/MmsApp(11445): [start]    initCountryIso consume time = 36.771833
,D/CountryDetector( 3528): The first listener is added
,D/Mms/MmsApp(11445): [end]    initCountryIso consume time = 9.644417
D/Mms/MmsConfig(11445): [start]    MmsConfig.init() consume time = 0.0575
,D/Mms/MmsConfig(11445): before partial update
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsConfig(11445): Load Resize quality : 80
,D/Mms/MmsConfig(11445):  enable multiwindow = true
,E/Zygote  (11506): MountEmulatedStorage()
I/libpersona(11506): KNOX_SDCARD checking this for 10047
E/Zygote  (11506): v2
I/libpersona(11506): KNOX_SDCARD not a persona
,I/SELinux (11506): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11506): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/Mms/MessageUtils(11445): setCountryDetector : update country detector info 
E/Mms/MessageUtils(11445): updateCountryIso : update country iso info 
,E/SELinux (11506): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=11506 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthServiceInstalled() : HealthService is Installed.
,D/Mms/PackageInfo(11445): com.sec.imsservice is not installed
D/Mms/MmsConfig(11445): [end]    init() consume time = 25.043083
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/Mms/Contact(11445): [start]    init() consume time = 0.731792
,D/Mms/Contact(11445): [end]    init consume time = 5.053333
,D/Mms/DraftCache(11445): [start]    rebuildCache consume time = 2.425667
,D/TP/MmsSmsProvider( 3980): query,matched:13, calling pid = 11445
,D/TP/MmsSmsProvider( 3980): query,matched:12, calling pid = 11445
D/TimaKeyStoreProvider(11506): TimaSignature is unavailable
,D/TP/MmsSmsProvider( 3980): match 13:Elapsed time : 0.648 ms
D/ActivityThread(11506): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 3980): match 12:Elapsed time : 1.358 ms
,D/SecurityLogAgent(10854): KnoxConfiguration : Current State = 0
,D/SecurityLogAgent(10854): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent(10854): StateMachine : Initialized
D/SecurityLogAgent(10854): StateMachine : Changed Current State = 0
D/SecurityLogAgent(10854): StateMachine : Current State = 0
,D/Mms/TelephonyUtils(11445): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(11445): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11445): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11445): auto download without roaming -> true
D/Mms/DownloadManager(11445): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,E/Mms/TelephonyUtils(11445): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(11445): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(11445): roaming -> false (slotId = 1)
D/Mms/DownloadManager(11445): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(11445): auto download without roaming -> true
D/Mms/DownloadManager(11445): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(11445): auto download during roaming secondary -> false
D/Mms/DownloadManager(11445): mAutoDownload ------> true
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/Mms/MmsApp(11445): [end]    onCreate() consume time = 12.216042
,D/Mms/DownloadManager(11445): Service state changed: Bundle[mParcelledData.dataSize=692]
D/ResourcesManager(11506): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,D/Mms/DownloadManager(11445): roaming ------> false, mSimSlot = 0
D/Mms/Conversation(11445): [start]    init() consume time = 2.785125
,D/Mms/TelephonyUtils(11445): getSubId from simSlot 0, return Value = -1
W/ResourcesManager(11506): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/Mms/DownloadManager(11445): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11445): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11445): auto download without roaming -> true
D/Mms/DownloadManager(11445): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(11445): mAutoDownload ------> true
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): checkState() : APP TYPE = Full
,E/Zygote  (11529): MountEmulatedStorage()
E/Zygote  (11529): v2
I/libpersona(11529): KNOX_SDCARD checking this for 10191
I/libpersona(11529): KNOX_SDCARD not a persona
,I/SELinux (11529): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11529): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11529): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=11529 uid=10191 gids={50191, 9997} abi=armeabi-v7a
,D/Mms/DraftCache(11445): [end]    rebuildCache consume time = 12.676041
,D/TP/MmsSmsProvider( 3980): deleteConversation threadId: 9223372036854775807
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/TP/MmsSmsProvider( 3980): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
I/CalendarProvider2(11506): CalendarProvider2.onCreate() called
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/TimaKeyStoreProvider(11529): TimaSignature is unavailable
,D/ActivityThread(11529): Added TimaKeyStore provider
,E/Zygote  (11544): MountEmulatedStorage()
E/Zygote  (11544): v2
I/libpersona(11544): KNOX_SDCARD checking this for 10069
I/libpersona(11544): KNOX_SDCARD not a persona
,I/SELinux (11544): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/SQLiteLog( 3980): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3980): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3980): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3980): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3980): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3980): (284) automatic index on im_threads(normal_thread_id)
,I/SELinux (11544): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11544): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/MmsSmsProvider( 3980): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 3980): need read changed broadcast:false
,I/ActivityManager( 3528): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=11544 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 10818:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11544): TimaSignature is unavailable
,D/ActivityThread(11544): Added TimaKeyStore provider
,E/Zygote  (11559): MountEmulatedStorage()
I/libpersona(11559): KNOX_SDCARD checking this for 10019
E/Zygote  (11559): v2
I/libpersona(11559): KNOX_SDCARD not a persona
,I/SELinux (11559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11559): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=11559 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/Mms/Conversation(11445): [end]    init consume time = 37.428292
D/Mms/MessagingNotification(11445): [start]    init() consume time = 0.055875
,D/TimaKeyStoreProvider(11559): TimaSignature is unavailable
,D/ActivityThread(11559): Added TimaKeyStore provider
,D/Mms/MessagingNotification(11445): [end]    init consume time = 11.594375
,D/Mms/Synchronizer(11445): [start]    doSync consume time = 1.397333
,D/Mms/SpamFilter(11445): [start]    SpamFilter fill() begin consume time = 0.736792
,D/ResourcesManager(11529): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,D/TP/MmsSmsProvider( 3980): query,matched:0, calling pid = 11445
V/TP/MmsSmsProvider( 3980): getSimpleConversations entered.
,W/ResourcesManager(11529): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 3980): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 3980): syncDBData start
D/ResourcesManager(11544): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,D/TP/MmsSmsProvider( 3980): match 0:Elapsed time : 1.748 ms
,I/ActivityManager( 3528): Killing 10126:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/TP/MmsSmsProvider( 3980): query,matched:400, calling pid = 11445
D/ResourcesManager(11559): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,V/TP/MmsSmsProvider( 3980): syncDBData sms end
,V/TP/MmsSmsProvider( 3980): syncDBData mms end
V/TP/MmsSmsProvider( 3980): syncDBData end
,D/Mms/SpamFilter(11445): [end]    SpamFilter fill() finished consume time = 12.314917
,D/Mms/Synchronizer(11445): [end]    doSync consume time = 0.545708
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11578): MountEmulatedStorage()
E/Zygote  (11578): v2
I/libpersona(11578): KNOX_SDCARD checking this for 10082
I/libpersona(11578): KNOX_SDCARD not a persona
,I/SELinux (11578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11578): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=11578 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 10540:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/TimaKeyStoreProvider(11578): TimaSignature is unavailable
,I/ActivityManager( 3528): Killing 10957:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31
D/ActivityThread(11578): Added TimaKeyStore provider
,D/accuweather( 5229): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/com.sec.android.service.health.keyManager.KeyManager(11476): Current encrypted state : -1
D/accuweather( 5229): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SecSQLiteOpenHelper(11476): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11476): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11476): Open platform.db in secure mode
D/SecSQLiteDatabase(11476): Android Version: 5.0.1
D/SecSQLiteDatabase(11476): Load library secsqlite.so for Android 5.0.1
,I/SA      (11276): [RC New] [v2liruge] api execute + 606
I/SA      (11276): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11276): AsyncTask #1 calls detatch()
,I/SecSQLiteDatabase(11476): openSecureDatabase...
,I/SecSQLiteDatabase(11476): private openSecureDatabase...
I/SecSQLiteConnectionPool(11476): OpenSecure
I/SecSQLiteConnectionPool(11476): OpenSecure with password
I/SecSQLiteConnectionPool(11476): openSecureConnectionLocked
,I/SecSQLiteDatabase(11476): ...private openSecureDatabase
I/SecSQLiteDatabase(11476): ...openSecureDatabase
,I/SA      (11276): [TPMU] getNetworkMcc : 
,I/SA      (11276): [SCU] saveMccToPreferece Start
,I/SA      (11276): [SCU] RegionMCC : 260
I/SA      (11276): [SSP] query invoked
,I/ Time Manager (11544): Time Difference not stored. TIME_DIFFERENCE
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11578): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,E/SQLiteLog(11476): (26) statement aborts at 0: [PRAGMA user_version;] file is encrypted or is not a database
,E/SecDefaultDatabaseErrorHandler(11476): Corruption reported by sqlite on database: /data/data/com.sec.android.app.shealth/databases/platform.db
E/SecDefaultDatabaseErrorHandler(11476): backup the database file: /data/data/com.sec.android.app.shealth/databases/platform.db
D/SecSQLiteOpenHelper(11476): ...getDatabaseLocked(b,b,pwd)
E/Zygote  (11599): MountEmulatedStorage()
I/libpersona(11599): KNOX_SDCARD checking this for 10094
E/Zygote  (11599): v2
I/libpersona(11599): KNOX_SDCARD not a persona
D/BadgeProvider(11578): onCreate
D/BadgeProvider(11578): DatabaseHelper
,I/SELinux (11599): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11599): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11599): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=11599 uid=10094 gids={50094, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PhenotypeConfigurator( 4229): Scheduling Phenotype for one-off execution 6755 seconds from now (1449751093580)
,I/ActivityManager( 3528): Killing 7605:com.android.settings/1000 (adj 13): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 434us total 10.283ms
,D/TimaKeyStoreProvider(11599): TimaSignature is unavailable
D/ActivityThread(11599): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 288us total 10.243ms
,D/ResourcesManager(11599): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 248us total 8.747ms
I/SecureStorage(11559): [INFO]: SPID(0x00000000)Processing data
,W/ResourcesManager(11599): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(11599): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11599): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11599): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11599): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11599): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Credentials: uid 10019, gid 10019, pid 11559
I/SecureStorage( 2916): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,D/GetConfigurationSnapshotOperation( 4229): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/art     ( 3528): Explicit concurrent mark sweep GC freed 26813(1597KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.443ms total 81.197ms
,I/SA      (11276): [TPMU] GetMccFromDB : null
I/SA      (11276): [SCU] getMccFromPreferece mcc = 260
I/SA      (11276): [SCU] saveMccToPreferece End
,I/SA      (11276): [RC New] executeRequest [v2liruge] end. 704
I/SA      (11276): [RC New] Execute end
,I/SA      (11276): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11276): [OR] GetMyCountryZoneTask Success
,D/Mms/MessagingNotification(11445): checkBadgeCount unreadCount=0 badgeCount=0
,I/PhenotypeFlagCommitter( 4229): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
D/TP/SmsProvider( 3980): query,matched:26, calling pid = 11445
,D/TP/SmsProvider( 3980): match 26:Elapsed time : 0.999 ms
,I/GoogleURLConnFactory( 4229): Using platform SSLCertificateSocketFactory
,D/TP/MmsSmsProvider( 3980): query,matched:6, calling pid = 11445
,D/TP/MmsSmsProvider( 3980): match 6:Elapsed time : 0.930 ms
,D/WifiService( 3528): Client connection lost with reason: 4
I/Mms/ReservationManager(11445): ReservationManager()
,I/Mms/ReservationManager(11445): resetAfterConnected()
,D/TP/MmsSmsProvider( 3980): query,matched:7, calling pid = 11445
,D/TP/MmsSmsProvider( 3980): match 7:Elapsed time : 2.307 ms
,I/Mms/ReservationManager(11445): getReservedSendMessageCount(): retMessageCount=0
,I/ActivityManager( 3528): Killing 10346:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService( 3528): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/Zygote  (11619): MountEmulatedStorage()
I/libpersona(11619): KNOX_SDCARD checking this for 10028
E/Zygote  (11619): v2
I/libpersona(11619): KNOX_SDCARD not a persona
,I/SELinux (11619): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11619): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=11619 uid=10028 gids={50028, 9997} abi=armeabi-v7a
E/SELinux (11619): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 3528): name = next_alarm_formatted
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 10094
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,D/TimaKeyStoreProvider(11619): TimaSignature is unavailable
,D/ActivityThread(11619): Added TimaKeyStore provider
,I/ActivityManager( 3528): Killing 10440:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
,D/ResourcesManager(11619): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,W/ResourcesManager(11619): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,V/GLSActivity( 4229): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4229): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/OMACP   (11619): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp(11445): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/Mms/ArtClassLoader(11445): init before art
D/Mms/ArtClassLoader(11445): init [DONE] art
,D/Mms/PerformanceUtils(11445): link cahcing start
,I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
D/Mms/PerformanceUtils(11445): link cahcing done
,I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   (11619): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11637): MountEmulatedStorage()
I/libpersona(11637): KNOX_SDCARD checking this for 10106
E/Zygote  (11637): v2
I/libpersona(11637): KNOX_SDCARD not a persona
,I/SELinux (11637): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11637): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11637): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11637 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 11037:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11637): TimaSignature is unavailable
,D/ActivityThread(11637): Added TimaKeyStore provider
,D/ResourcesManager(11637): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,I/System.out( 4229): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4229): (HTTPLog)-Static: isShipBuild true
I/System.out( 4229): (HTTPLog)-Thread-261-505681529: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4229): (HTTPLog)-Static: isSBSettingEnabled false
,D/elm:14491(11637): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
D/elm:14491(11637): ELMEngine.ELMEngine( context ).
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,D/elm:14491(11637): MDMBridge.setEnterpriseBridge()
,D/elm:14491(11637): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/elm:14491(11637): ElmAgentService : onCreate()
D/elm:14491(11637): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14491(11637): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491(11637): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491(11637): ModuleBase.ModifySetAlarm()
D/elm:14491(11637): MDMBridge.getInstance()
D/elm:14491(11637): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (11656): MountEmulatedStorage()
E/Zygote  (11656): v2
I/libpersona(11656): KNOX_SDCARD checking this for 10163
I/libpersona(11656): KNOX_SDCARD not a persona
,I/SELinux (11656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=11656 uid=10163 gids={50163, 9997} abi=armeabi-v7a
E/SELinux (11656): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/elm:14491(11637): ElmAgentService : onDestroy().
,I/ActivityManager( 3528): Killing 11069:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11656): TimaSignature is unavailable
,D/ActivityThread(11656): Added TimaKeyStore provider
,I/System.out( 4229): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4229): Tagging socket 78 with tag 1000040100000000{268436481,0} uid 10014, pid: 4229, getuid(): 10014
,D/ResourcesManager(11656): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(11656): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(11656): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/qtaguid ( 4229): Tagging socket 82 with tag 1000040100000000{268436481,0} uid 10014, pid: 4229, getuid(): 10014
,I/ActivityManager( 3528): Killing 11089:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,D/btif_config_util(10763): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/WifiStateMachine( 3528): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3528): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/System.out( 4229): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/SecureStorage( 2916): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
,I/System.out( 4229): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4229): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 4229, getuid(): 10014
,I/qtaguid ( 4229): Tagging socket 85 with tag 1000120100000000{268440065,0} uid -1, pid: 4229, getuid(): 10014
,I/SurfaceFlinger( 2850): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger( 2850): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 3528): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3528) eventTime = 142799
,D/PowerManagerService( 3528): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3528 (0x0)
,D/PowerManagerService( 3528): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3528, ws=WorkSource{10060}) (elapsedTime=3478)
,D/OpenGLRenderer( 5926): Render dirty regions requested: true
,I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3528): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3528
,I/OpenGLRenderer( 5926): Initialized EGL, version 1.4
,I/OpenGLRenderer( 5926): HWUI protection enabled for context ,  &this =0xaf322088 ,&mEglDisplay = 1 , &mEglConfig = -1355423472 
,D/OpenGLRenderer( 5926): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 5926): Enabling debug mode 0
,D/mali_winsys( 5926): new_window_surface returns 0x3000,  [616x201]-format:1
,D/LocationManagerService( 3528): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/SecureStorage(11559): [INFO]: SPID(0x00000006)Processing data has been completed
,I/SecureStorage(11559): [INFO]: SPID(0x00000006)Skip using SecureStorageExceptionJNI
,I/SecSQLiteOpenHelper(11476): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11476): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11476): Open platform.db in secure mode
I/SecSQLiteDatabase(11476): openSecureDatabase...
I/SecSQLiteDatabase(11476): private openSecureDatabase...
I/SecSQLiteConnectionPool(11476): OpenSecure
I/SecSQLiteConnectionPool(11476): OpenSecure with password
I/SecSQLiteConnectionPool(11476): openSecureConnectionLocked
I/SecSQLiteDatabase(11476): ...private openSecureDatabase
I/SecSQLiteDatabase(11476): ...openSecureDatabase
,I/System.out( 4229): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4229): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 4229, getuid(): 10014
,I/SecSQLiteOpenHelper(11476): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11476): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/LocationManagerService( 3528): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4229): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4229): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 4229, getuid(): 10014
,D/-----SIC-----(11476): ------------------skip TGH
,I/CalendarProvider2(11506): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager( 3528): Killing 11136:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,I/SecSQLiteOpenHelper(11476): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11476): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11476): Open platform.db in secure mode
I/SecSQLiteDatabase(11476): openSecureDatabase...
I/SecSQLiteDatabase(11476): private openSecureDatabase...
I/SecSQLiteConnectionPool(11476): OpenSecure
I/SecSQLiteConnectionPool(11476): OpenSecure with password
I/SecSQLiteConnectionPool(11476): openSecureConnectionLocked
I/SecSQLiteDatabase(11476): ...private openSecureDatabase
I/SecSQLiteDatabase(11476): ...openSecureDatabase
,D/LocationManagerService( 3528): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/SecSQLiteOpenHelper(11476): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11476): ...getDatabaseLocked(b,b,pwd)
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11476): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,I/System.out( 4229): (HTTPLog)-Static: isSBSettingEnabled false
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
I/qtaguid ( 4229): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 4229, getuid(): 10014
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11476): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer(11476): decode(35, 20909908, 4230)
,V/MediaPlayerService( 2858): decode(26, 20909908, 4230)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20909908, 4230)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/SO_AGENT(11222): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/SA      (11276): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
,I/AudioPlayer( 2858): First fillBuffer call!!
V/MediaPlayerService( 2858): wait for playback complete
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11476): decode(37, 20763080, 15440)
V/MediaPlayerService( 2858): decode(26, 20763080, 15440)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
,V/StagefrightPlayer( 2858): setDataSource(26, 20763080, 15440)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
,V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
,V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder',
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2858): finishAsyncPrepare_l
,V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
,V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2858): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
,E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2858): wait for playback complete
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthServiceInstalled() : HealthService is Installed.
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthServiceInstalled() : HealthService is Installed.
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11476): decode(36, 20807608, 9226)
V/MediaPlayerService( 2858): decode(26, 20807608, 9226)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20807608, 9226)
V/AwesomePlayer( 2858): reset_l()
,V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
I/ActivityManager( 3528): Killing 11158:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,D/AdaptiveEventManager( 3689): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3689): M updateContainers()
D/AdaptiveEventContainerSmall( 3689): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3689): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3689): pedoEvent == null
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,D/AdaptiveEventManager( 3689): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3689): M updateContainers()
D/AdaptiveEventContainerSmall( 3689): C updatePedoContainer()
,D/AdaptiveEventContainerSmall( 3689): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3689): pedoEvent == null
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2858): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
V/MediaPlayerService( 2858): wait for playback complete
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,I/ActivityManager( 3528): Killing 11238:com.policydm/1000 (adj 13): bgCount ##31
,W/System.err(10021): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
,W/System.err(10021): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,W/System.err(10021): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err(10021): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err(10021): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err(10021): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
W/System.err(10021): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
W/System.err(10021): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
W/System.err(10021): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10021): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10021): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10021): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10021): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10021): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10021): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/splitIntent( 3528): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
W/System.err(11476): java.lang.NumberFormatException: Invalid int: "null"
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
W/System.err(11476): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err(11476): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err(11476): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err(11476): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:498)
W/System.err(11476): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1242)
W/System.err(11476): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11476): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11476): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/MediaPlayer(11476): decode(34, 20914220, 4890)
V/MediaPlayerService( 2858): decode(26, 20914220, 4890)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20914220, 4890)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
,V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
V/MediaPlayerService( 2858): wait for playback complete
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
E/DatabaseUtils( 3528): Writing exception to parcel
E/DatabaseUtils( 3528): java.lang.NullPointerException: key == null
E/DatabaseUtils( 3528): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils( 3528): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils( 3528): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils( 3528): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:376)
E/DatabaseUtils( 3528): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils( 3528): 	at android.os.Binder.execTransact(Binder.java:446)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11476): decode(38, 20840384, 17329)
V/MediaPlayerService( 2858): decode(26, 20840384, 17329)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20840384, 17329)
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2858): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
V/MediaPlayerService( 2858): wait for playback complete
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11476): decode(39, 20740576, 6644)
,V/MediaPlayerService( 2858): decode(26, 20740576, 6644)
V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20740576, 6644)
V/AwesomePlayer( 2858): reset_l()
,V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l,
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
,V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
,V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
V/MediaPlayerService( 2858): wait for playback complete
,I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): addBatteryData
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/libpersona(11734): KNOX_SDCARD checking this for 10022
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/libpersona(11734): KNOX_SDCARD not a persona
E/Zygote  (11734): MountEmulatedStorage()
I/SecVideoCapture( 2858): reset
E/Zygote  (11734): v2
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
,V/AwesomePlayer( 2858): reset_l()
I/SELinux (11734): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/MediaPlayer(11476): decode(41, 20816916, 23389)
V/MediaPlayerService( 2858): decode(26, 20816916, 23389)
V/MediaPlayerService( 2858): player type = 3
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
I/SELinux (11734): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20816916, 23389)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,E/SELinux (11734): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=11734 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
,I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
,I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 1, 0, 0)
V/AudioCache( 2858): prepared
,V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2858): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,V/MediaPlayerService( 2858): wait for playback complete
,D/TimaKeyStoreProvider(11734): TimaSignature is unavailable
,D/ActivityThread(11734): Added TimaKeyStore provider
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,I/AudioPlayer( 2858): reset out
,V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
,V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11476): decode(43, 20706272, 8154)
V/MediaPlayerService( 2858): decode(26, 20706272, 8154)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
,V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20706272, 8154)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2858): notify(0xb040f0b0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
D/ResourcesManager(11734): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
,W/ResourcesManager(11734): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
W/ResourcesManager(11734): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/MediaPlayerService( 2858): prepare
W/ResourcesManager(11734): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
,I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 200, 973, 0)
V/AudioCache( 2858): ignored
,V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
V/MediaPlayerService( 2858): wait for playback complete
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11476): decode(42, 20679752, 4804)
V/MediaPlayerService( 2858): decode(26, 20679752, 4804)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
,V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20679752, 4804)
V/AwesomePlayer( 2858): reset_l()
,V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
,V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2858): notify(0xb0009100, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 1, 0, 0)
,V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
,V/MediaPlayerService( 2858): wait for playback complete
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
,V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 7, 0, 0)
,V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 8, 0, 0)
,V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x84, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11476): decode(44, 20649204, 9400)
V/MediaPlayerService( 2858): decode(26, 20649204, 9400)
V/MediaPlayerService( 2858): player type = 3
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20649204, 9400)
V/AwesomePlayer( 2858): reset_l()
,V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11476): decode(50, 20722624, 4112)
V/MediaPlayerService( 2858): decode(36, 20722624, 4112)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
,V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(36, 20722624, 4112)
V/AwesomePlayer( 2858): reset_l()
V/MediaPlayerService( 2858): wait for prepare
,V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
,V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
V/MediaPlayerService( 2858): wait for prepare
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/AwesomePlayer( 2858): onPrepareAsyncEvent
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
,V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 2858): notify(0xb020d1a0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
,V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/LocationWidgetApplication(11734): onCreate() : start
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 200, 973, 0)
D/LocationWidgetApplication(11734): countryCode = POLAND
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 5, 0, 0)
,V/AudioCache( 2858): ignored
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
,V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache( 2858): notify(0xb020d1a0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
V/MediaPlayerService( 2858): wait for playback complete
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1733175209, value : 485677307
,E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1733175209, value : 485677307
V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/MediaPlayerService( 2858): wait for playback complete
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
,V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 7, 0, 0)
V/AudioCache( 2858): ignored
,V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 8, 0, 0)
,V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x86, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
,V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache( 2858): notify(0xb020d1a0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
,V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 8, 0, 0),
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x85, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
,I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
,I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11476): decode(45, 20857804, 52024)
V/MediaPlayerService( 2858): decode(26, 20857804, 52024)
V/MediaPlayerService( 2858): player type = 3
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20857804, 52024)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 8, 0, 0)
,V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
D/LocationWidgetUtils(11734): getUpcommingInstances() start: 1449751094957, end: 1450306799999
D/LocationWidgetUtils(11734): getUpcommingInstances() DB begin time >= start:1449751094957, DB begin time <= end:1450306799999
V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
,I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 1, 0, 0)
,V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2858): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
,I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2858): wait for playback complete
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants(11476): RegionGroup for  is null
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11476): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/LocationManagerService( 3528): getProviders()=[]
,D/LocationManagerService( 3528): getProviders()=[passive]
D/LocationManagerService( 3528): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x87, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
D/LWLocationManager(11734): mPrivacy is null
W/ContextImpl(11734): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
,V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
,V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11476): decode(46, 20722624, 4112)
V/MediaPlayerService( 2858): decode(26, 20722624, 4112)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20722624, 4112)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,D/ContextFramework:PrivacyManager(11734): Service for PrivacyManager is connected
D/PackageManager( 3528): [MSG] WRITE_PACKAGE_RESTRICTIONS
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 2858): notify(0xb0009100, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 1, 0, 0)
,V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
,I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AudioCache( 2858): notify(0xb0009100, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
V/MediaPlayerService( 2858): wait for playback complete
,V/AwesomePlayer( 2858): onCheckAudioStatus
,V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb0009100, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x88, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/MediaPlayer(11476): decode(47, 20785700, 21825)
V/MediaPlayerService( 2858): decode(26, 20785700, 21825)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20785700, 21825)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
,V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
D/BluetoothManager(11476): getConnectedDevices
,V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,D/BluetoothManager(11476): getConnectedDevices
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2858): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
,V/AudioCache( 2858): notify(0xb00091f0, 6, 0, 0)
D/LWLocationManager(11734): Privacy service : STATUS_PLACE
D/LWLocationManager(11734): updateLocationStatus()
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
,V/MediaPlayerService( 2858): wait for playback complete
,I/LocationWidgetFuctionData(11734): readDB
D/BluetoothManager(11476): getConnectedDevices
,I/LocationWidgetFuctionData(11734): selectedAppSize: 3
I/LocationWidgetFuctionData(11734): configPlaceList aroundMeItems
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb00091f0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x89, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/libpersona(11793): KNOX_SDCARD checking this for 10003
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/libpersona(11793): KNOX_SDCARD not a persona
I/OggExtractor( 2858): ~OggExtractor --
E/Zygote  (11793): MountEmulatedStorage()
E/Zygote  (11793): v2
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SELinux (11793): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11476): decode(48, 20684636, 21552)
V/MediaPlayerService( 2858): decode(26, 20684636, 21552)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
I/SELinux (11793): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
V/AwesomePlayer( 2858): constructor
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20684636, 21552)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
E/SELinux (11793): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate,
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector,
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
,V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
,I/ActivityManager( 3528): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=11793 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2858): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
V/MediaPlayerService( 2858): wait for playback complete
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,D/TimaKeyStoreProvider(11793): TimaSignature is unavailable
,D/BluetoothManager(11476): getConnectedDevices
D/ActivityThread(11793): Added TimaKeyStore provider
,I/ActivityManager( 3528): Killing 11258:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,D/BluetoothManager(11476): getConnectedDevices
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
,D/ResourcesManager(11793): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d1a0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x8a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,I/ActivityManager( 3528): Killing 11298:com.samsung.android.scloud.backup/u0a67 (adj 13): bgCount ##31
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11476): decode(49, 20778600, 7017)
V/MediaPlayerService( 2858): decode(26, 20778600, 7017)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
D/BluetoothManager(11476): getConnectedDevices
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20778600, 7017)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2858): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
,V/MediaPlayerService( 2858): wait for playback complete
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,D/UserAnalysis.PlaceProvider(11793): PlaceProvider onCreate()
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb040f0b0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x8b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,I/AudioPlayer( 2858): reset out
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,D/UserAnalysis.SecureDbManager(11793): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(11793): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(11793): Create SecureDbHelper
,D/IntelligenceServiceApplication(11793): onCreate()
,I/LocationWidgetFuctionData(11734): selectedAppSize: 3
,I/LocationWidgetFuctionData(11734): selectedAppSize: 3
,I/LocationWidgetFuctionData(11734): selectedAppSize: 3
,I/LocationWidgetFuctionData(11734): selectedAppSize: 3
,E/LWLocationManager(11734): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(11734): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(11734): setShouldUpdateLocationId
D/LWLocationManager(11734): setShouldUpdateLocationId return false
D/LWLocationManager(11734): setShouldUpdateLocationId
D/LWLocationManager(11734): setShouldUpdateLocationId return false
D/LWLocationManager(11734): setShouldUpdateLocationId
D/LWLocationManager(11734): setShouldUpdateLocationId return false
D/LWLocationManager(11734): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,I/Mms/MmsApp(11445):  start initViewCache mms
,D/Mms/ComposeMessageFragment(11445): [start]    fillCache consume time = 1922.442125
D/Mms/ComposeMessageFragment(11445): fillCache, easy = false
,D/SSRM:n  ( 3528): SIOP:: AP = 320, PST = 291, CUR = 18
,D/AbsListView(11445): Get MotionRecognitionManager
,D/MotionRecognitionService( 3528):  ssp status : true
,D/Mms/ComposeMessageFragment(11445): [end]    fillCache consume time = 171.316125
,I/PowerManagerService( 3528): [PWL] Off : 50s ago
I/PowerManagerService( 3528): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3528): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3528): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10094, pid=11599, ws=null) (elapsedTime=2029)
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:-344, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:125
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Mms/BubbleViewCache(11445): fillCache bubble = 8
,V/AlarmManager( 3528): waitForAlarm result :4
,E/SQLiteLog(11506): (284) automatic index on view_events(_id)
,D/CalendarAlarmManager(11506): sys current time:1449751096358
,D/CalendarAlarmManager(11506): reminder amount:0
,W/ProcessCpuTracker( 3528): Skipping unknown process pid 11847
,I/dhcpcd  (10975): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/System.out( 3528): Thread-147(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3528): Thread-147(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3528): Thread-147(ApacheHTTPLog):isShipBuild true
I/System.out( 3528): Thread-147(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
,I/SurfaceFlinger( 2850): id=14 Removed Uoast (8/9)
,D/PowerManagerService( 3528): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3528) eventTime = 146313
,D/PowerManagerService( 3528): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3528 (0x0)
,D/PowerManagerService( 3528): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3528, ws=WorkSource{1000}) (elapsedTime=3480)
,I/GAV4    (11332): Thread[GAThread,5,main]: No campaign data found.
,I/System.out( 3528): AsyncTask #2 calls detatch()
,W/System.err( 3528): java.io.IOException: Not Found
,W/System.err( 3528): 	at a.d.b(Unknown Source)
,W/System.err( 3528): 	at a.d.doInBackground(Unknown Source)
,W/System.err( 3528): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 3528): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 3528): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 3528): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 3528): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 3528): 	at java.lang.Thread.run(Thread.java:818)
,I/GAV3    (11476): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  (10975): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (10975): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(11421): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(11421): exit::IDLE
,D/PreloadUpdateManagerStateMachine(11421): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (11421): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (11421): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(11421): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(11421): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(11421): entry::IDLE
,D/SSRM:n  ( 3528): SIOP:: AP = 290, PST = 286, CUR = -344
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:-73, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:100
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3528): Waited long enough for: ServiceRecord{3a2370f5 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/Watchdog( 3528): !@Sync 5
,D/SSRM:n  ( 3528): SIOP:: AP = 280, PST = 287, CUR = -73,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:77
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3528): [PWL] Off : 75s ago
,V/AlarmManager( 3528): waitForAlarm result :4
,D/SSRM:n  ( 3528): SIOP:: AP = 270, PST = 287, CUR = 24
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4229): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3528): SIOP:: AP = 270, PST = 287, CUR = 55,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:64
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 3528): waitForAlarm result :8
,E/Watchdog( 3528): !@Sync 6
,D/SSRM:n  ( 3528): SIOP:: AP = 260, PST = 285, CUR = 63
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:62, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:73
D/BatteryService( 3528): stay LED for fully charged
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged,
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,I/PowerManagerService( 3528): [PWL] Off : 105s ago
,V/AlarmManager( 3528): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3689): handleTimeUpdate
,D/KeyguardEffectViewController( 3689): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3689): *** don't update sliding image ***
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/ActivityThread( 4478): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3528): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 171332, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager( 3528): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 263324, reason: UserStart
,W/ResourceType( 4945): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4945): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3528): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3528): mCursor = null
,D/SSRM:n  ( 3528): SIOP:: AP = 260, PST = 280, CUR = 62
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/BatteryService( 3528): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3528): Skipping unknown process pid 11996
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 260, PST = 278, CUR = 60
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
,D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3528): waitForAlarm result :4
,E/Watchdog( 3528): !@Sync 7
,D/SSRM:n  ( 3528): SIOP:: AP = 260, PST = 277, CUR = 57
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3528): waitForAlarm result :4
,I/PowerManagerService( 3528): [PWL] Off : 140s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 260, PST = 277, CUR = 54
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 250, PST = 272, CUR = 51
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3528): waitForAlarm result :8
,E/Watchdog( 3528): !@Sync 8
,D/SSRM:n  ( 3528): SIOP:: AP = 250, PST = 270, CUR = 48
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 250, PST = 268, CUR = 46
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3528): [PWL] Off : 180s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 250, PST = 266, CUR = 45
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10763): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10763): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2

```
