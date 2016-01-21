#### Test 56449660311ec66_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,E/Watchdog( 3527): !@Sync 4
--------- beginning of main
D/AndroidRuntime(10759): 
D/AndroidRuntime(10759): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10759): CheckJNI is OFF
D/AndroidRuntime(10759): readGMSProperty: start
D/AndroidRuntime(10759): readGMSProperty: already setted!!
D/AndroidRuntime(10759): readGMSProperty: end
D/AndroidRuntime(10759): addProductProperty: start
E/AffinityControl(10759): AffinityControl: registerfunction enter
D/AndroidRuntime(10759): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3527): inState():  stateMachine is null !!
I/PersonaManagerService( 3527): PersonaId don't exist
I/ActivityManager( 3527): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3527): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3527): mDVFSHelper.acquire()
D/FocusedStackFrame( 3527): Set to : 0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/Zygote  (10777): MountEmulatedStorage()
E/Zygote  (10777): v2
I/libpersona(10777): KNOX_SDCARD checking this for 10592
I/libpersona(10777): KNOX_SDCARD not a persona
I/SELinux (10777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3527): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=10777 uid=10592 gids={50592, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (10777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10777): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10759): Shutting down VM
D/PointerIcon( 3527): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3527): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3527): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3527): setHoveringSpenCustomIcon IconType is same.1
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8734(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 873us total 22.753ms
D/TimaKeyStoreProvider(10777): TimaSignature is unavailable
D/ActivityThread(10777): Added TimaKeyStore provider
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3527): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 926us total 18.509ms
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 626us total 18.273ms
D/ResourcesManager(10777): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2855): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2855): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 3997): updateVisibility : ActivityRecord{ad15ca2 token=android.os.BinderProxy@243e9a4d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3997): onTrimMemory. Level: 20
I/WebViewFactory(10777): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10777): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10777): Loading: webviewchromium
I/LibraryLoader(10777): Time to load native libraries: 4 ms (timestamps 3756-3760)
I/LibraryLoader(10777): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10777): Binding Chromium to main looper Looper (main, tid 1) {255c12b}
,I/LibraryLoader(10777): Expected native library version number "",actual native library version number ""
I/chromium(10777): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10777): Initializing chromium process, renderers=0
,W/art     (10777): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10777): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10777): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10777): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10777): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothAdapter(10777): 832604552: getState() :  mService = null. Returning STATE_OFF
,W/chromium(10777): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10777): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10777): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10777): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(10777): CordovaWebView is running on device made by: samsung
,W/art     (10777): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10777): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(10777): performCreate Call secproduct feature valuefalse
D/Activity(10777): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(10777): Render dirty regions requested: true
,D/ActivityManager( 3527): post active user change for 0
D/KnoxTimeoutHandler( 3527): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3527): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2855): id=11 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3527): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3527): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3527): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3527): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(10777): Initialized EGL, version 1.4
I/OpenGLRenderer(10777): HWUI protection enabled for context ,  &this =0xaf545060 ,&mEglDisplay = 1 , &mEglConfig = -1278709488 
,D/OpenGLRenderer(10777): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10777): Enabling debug mode 0
,D/mali_winsys(10777): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(10777): updateVisibility : ActivityRecord{e4d64b8 token=android.os.BinderProxy@1498a06e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3527): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3527): mDVFSHelper.release()
,I/Timeline( 3527): Timeline: Activity_windows_visible id: ActivityRecord{39d00202 u0 com.test.thalitest/.MainActivity t25} time:134101
,W/IInputConnectionWrapper(10777): showStatusIcon on inactive InputConnection
,I/Timeline(10777): Timeline: Activity_idle id: android.os.BinderProxy@1498a06e time:134107
,D/JsMessageQueue(10777): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(10777): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10777): 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-416
D/BatteryService( 3527): stay LED for fully charged
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/jxcore_app_log(10777): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358473472
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/chromium(10777): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(10777): Initializing JXcore engine
W/jxcore-log(10777): JXcore engine is ready
,E/auditd  ( 4539): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3527): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3527): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10777): Starting JXcore engine
,W/jxcore-log(10777): Platform android
W/jxcore-log(10777): 
W/jxcore-log(10777): Process ARCH arm
W/jxcore-log(10777): 
,I/jxcore-log(10777): JXcore Cordova bridge is ready!
I/jxcore-log(10777): 
W/jxcore-log(10777): JXcore engine is started
,I/jxcore-log(10777): Toggling radios to true
I/jxcore-log(10777): 
,D/BluetoothAdapter(10777): enable()
,W/ActivityManager( 3527): Permission Denial: getCurrentUser() from pid=10777, uid=10592 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 3527): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 3527): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10777, uid=10592 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 3527): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/BluetoothManagerService( 3527): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2160)
W/BluetoothManagerService( 3527): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService( 3527): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 3527): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService( 3527): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3527): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 3527): name = bluetooth_on
,E/DevicePolicyManagerService( 3527): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3527): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/WifiManager(10777): packageName : com.test.thalitest
,D/WifiService( 3527): New client listening to asynchronous messages
D/SecContentProvider( 3527): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3527): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3527): mCursor = null
,D/WifiService( 3527): setWifiEnabled: true pid=10777, uid=10592
E/WifiService( 3527): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3527): Permission Denial: getCurrentUser() from pid=10777, uid=10592 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3527): Failed getting userId using ActivityManagerNative
W/WifiService( 3527): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10777, uid=10592 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3527): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3527): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3527): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3527): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3527): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3527): name = wifi_on
,E/WifiStateMachine( 3527): setting operational mode to 1
I/WifiService( 3527): disconnect: pid=10777, uid=10592
,E/WifiHW  ( 3527): ##################### set firmware type 0 #####################
,I/jxcore-log(10777): Radios toggled
I/jxcore-log(10777): 
I/libpersona(10848): KNOX_SDCARD checking this for 1002
E/Zygote  (10848): MountEmulatedStorage()
I/libpersona(10848): KNOX_SDCARD not a persona
E/Zygote  (10848): v2
I/jxcore-log(10777): My device name is: samsung-SM-N910C
I/jxcore-log(10777): 
I/SELinux (10848): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/WifiHW  ( 2847): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
I/SELinux (10848): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10848): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=10848 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/WifiHW  ( 2847): module is murata
E/WifiHW  ( 2847): ==========[WIFI] MURATA MODULE ===========
I/WifiHW  ( 2847): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_murata
E/WifiHW  ( 2847): TEMP_FAILURE_RETRY complete
D/SoftapController( 2847): Softap fwReload - Ok
,D/CommandListener( 2847): Setting iface cfg
D/CommandListener( 2847): Trying to bring down wlan0
,D/CommandListener( 2847): Clearing all IP addresses on wlan0
,D/TimaKeyStoreProvider(10848): TimaSignature is unavailable
,D/ActivityThread(10848): Added TimaKeyStore provider
,D/ResourcesManager(10848): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(10848): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(10848): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni(10848): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig(10848): Adding GattService
,D/BtSettings.ProfileConfig(10848): Adding HeadsetService
D/BtSettings.ProfileConfig(10848): Adding A2dpService
D/BtSettings.ProfileConfig(10848): Adding HidService
D/BtSettings.ProfileConfig(10848): Adding HealthService
,D/BtSettings.ProfileConfig(10848): Adding PanService
D/BtSettings.ProfileConfig(10848): Adding BluetoothMapService
D/BtSettings.ProfileConfig(10848): Adding SapService
D/BtSettings.ProfileConfig(10848): Adding HeadsetClientService
D/BtSettings.ProfileConfig(10848): Adding A2dpSinkService
D/BtSettings.ProfileConfig(10848): Adding SapClientService
D/BtSettings.ProfileConfig(10848): Adding HidDevService
I/BtSettings.ProfileConfig(10848): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3527): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3527): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3527): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3527): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3527): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3527): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3527): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3527): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3527): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,E/WifiHW  ( 3527): supplicant_name : p2p_supplicant
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3527): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3527): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3527): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterState(10848): make
,I/bluedroid(10848): init
I/BluetoothAdapterState(10848): Entering OffState
,I/bte_conf(10848): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf(10848): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config(10848): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf(10848): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif (10848): btif_fetch_local_ble_random_bdaddr
I/bluedroid(10848): get_profile_interface socket
I/bluedroid(10848): get_profile_interface map_client
,D/BluetoothAdapterService(10848): checkAddrForIOP: Loading from conf
,D/BluetoothAdapterService(10848): Inband Ring is supported
,I/GKI_LINUX(10848): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties(10848): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10848): populateRssiValuesNative
I/bluedroid(10848): getModelRssiValues
E/BluetoothServiceJni(10848): model_rssi_values_callback: low = -75, mid = -65, high = 127
,D/BluetoothAdapterProperties(10848): modelRssiValuesCallback, low, mid, high = -75,-65,127
,D/BluetoothAdapterProperties(10848): Name is: Note4-1
D/SettingsProvider( 3527): name = bluetooth_name
,I/bluedroid(10848): config_hci_snoop_log
,D/BluetoothManagerService( 3527): Broadcasting onBluetoothServiceUp() to 12 receivers.
,E/DevicePolicyManagerService( 3527): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3527): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 3527): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState(10848): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties(10848): Setting state to 11
I/wpa_supplicant(10864): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant(10864): Successfully initialized wpa_supplicant
I/BluetoothAdapterState(10848): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(10848): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10848): updateAdapterState state is 11
I/SecureStorage(10864): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
D/BluetoothAdapterService(10848): Autoconnection is available 
D/BluetoothAdapterService(10848): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager(10848): getInstant: null
D/BluetoothSecureManager(10848): calling getMethod for getService
D/BluetoothSecureManager(10848): calling getService
D/BluetoothSecureManager(10848): getService return binder: android.os.BinderProxy@148f2aa3
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3694): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothSecureManagerService( 3527): isSecureModeEnabled
D/BluetoothSecureManagerService( 3527): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode(10848): isSecureModeOn:false
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService(10848): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10848): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService(10848): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/STATUSBAR-QSTileView( 3694): onStateChanged: Bluetooth
I/SamsungIME( 4456): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
D/StatusBarManagerService( 3527): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
W/BluetoothAdapterService(10848): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/InputMethodManagerService( 3527): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3527): [BT Setting State] State =11
W/BluetoothAdapterService(10848): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/StatusBarManagerService( 3527): setIconVisibility slot=bluetooth visible=false
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/PhoneStatusBar( 3694): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
W/BluetoothAdapterService(10848): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10848): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
E/WifiStateMachine( 3527): setWifiState: enabling
W/BluetoothAdapterService(10848): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
I/SecureStorage(10864): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage( 2915): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10864
I/SecureStorage( 2915): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
I/SecureStorage(10864): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant(10864): ssSupport state is = 1
W/BluetoothAdapterService(10848): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
I/wpa_supplicant(10864): >>>>> GET KEY, IV <<<<<
,W/BluetoothAdapterService(10848): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10848): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
I/SecureStorage(10864): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage( 2915): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10864
I/SecureStorage( 2915): [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,V/[CarModeFW](10199): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/WifiStateMachine( 3527): Supplicant start successful
D/WifiMonitor( 3527): startMonitoring(wlan0) with mConnected = false
W/BluetoothAdapterService(10848): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine(10848): make
,W/BluetoothAdapterService(10848): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService(10848): Not skipping com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine(10848): StableState(): Entering Off State
,D/SmartBondingService( 3527): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3527): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=false enabledDesc:null
,D/SmartBondingService( 3527): getNetworkEnabled : wifi : false mobile : false
D/STATUSBAR-WifiQuickSettingButton( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3694): Wifi onReceive(2)
,D/STATUSBAR-QSTileView( 3694): onStateChanged: Wi-Fi
D/HotspotTile( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 3694): onReceive : 2, 0
,W/BluetoothAdapterService(10848): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10848): Not skipping com.android.bluetooth.hfp.HeadsetService
I/BtGatt.JNI(10848): classInitNative(L900): classInitNative: Success!
,D/BtGatt.DebugUtils(10848): handleDebugAction() action=null
D/BtGatt.GattService(10848): Received start request. Starting profile...
D/BtGatt.GattService(10848): start()
I/bluedroid(10848): get_profile_interface gatt
D/BluetoothAdapterService(10848): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@255c12b
D/BtGatt.AdvertiseManager(10848): advertise manager created
,W/BluetoothAdapterService(10848): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10848): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BluetoothAdapterService(10848): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@255c12b
W/BluetoothAdapterService(10848): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService(10848): Not skipping com.android.bluetooth.hid.HidService
,D/HeadsetService(10848): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni(10848): classInitNative: succeeds
D/HeadsetStateMachine(10848): make
,E/HeadsetStateMachine(10848): # of Max HF connection is 2
,W/BluetoothAdapterService(10848): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10848): Not skipping com.android.bluetooth.hdp.HealthService
,D/BluetoothNotiBroadcastReceiver( 7854): onReceive
,W/BluetoothAdapterService(10848): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10848): Not skipping com.android.bluetooth.pan.PanService
,I/bluedroid(10848): get_profile_interface handsfree
,W/BluetoothAdapterService(10848): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10848): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService(10848): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10848): Not skipping com.broadcom.bt.service.sap.SapService
,I/DualScoManager(10848): Instantiating Dual Sco Manager
I/DualScoManager(10848): Set HeadsetServiceHelper
,W/BluetoothAdapterService(10848): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10848): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10848): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10848): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10848): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10848): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10848): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig(10848): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
D/BluetoothAtMessage(10848): createCMTIContentObservers
W/BluetoothAdapterService(10848): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState(10848): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/SettingsProvider( 3527): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine(10848): Enter Disconnected: -2
,E/HeadsetStateMachine(10848): set to mRemoteBrsf = 0
,D/BluetoothAdapterService(10848): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@255c12b
,D/HeadsetStateMachine(10848): map size, before remove : 0
D/HeadsetStateMachine(10848): map size, after remove: 0
,D/BluetoothA2dp( 3527): Proxy object connected
D/BluetoothA2dp( 4802): Proxy object connected
D/A2dpService(10848): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni(10848): classInitNative: succeeds
V/Avrcp   (10848): make
V/Avrcp   (10848): Avrcp
I/bluedroid(10848): get_profile_interface avrcp
,V/Avrcp   (10848): start
,E/RemoteController(10848): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   (10848): ++registerMediaPlayers++
,I/Avrcp   (10848): No of Audio players :: 2
I/Avrcp   (10848): App Package name is com.google.android.music
,D/ResourcesManager(10848): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   (10848): App pkg name is Google Play Music
,I/Avrcp   (10848): Name::Google Play Music
V/Avrcp   (10848): MediaPlayerInfo: mPlayerId=1
I/Avrcp   (10848): App Package name is com.sec.android.app.music
,D/ResourcesManager(10848): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   (10848): App pkg name is Music
,I/Avrcp   (10848): Name::Music
V/Avrcp   (10848): MediaPlayerInfo: mPlayerId=2
,I/Avrcp   (10848): No of Video players :: 1
I/Avrcp   (10848): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager(10848): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   (10848): Video App pkg name is Video Player
,I/Avrcp   (10848): Name::Video Player
V/Avrcp   (10848): MediaPlayerInfo: mPlayerId=3
I/Avrcp   (10848): Add tempPlayer
V/Avrcp   (10848): MediaPlayerInfo: mPlayerId=4
I/Avrcp   (10848): Total no of players: 4
V/Avrcp   (10848): swapping the samsung player with 1st player
I/Avrcp   (10848):  Updating now playing list upon AVRCP Start
V/Avrcp   (10848): handleMessage, msg=207
D/BluetoothMediaBrowser(10848):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,V/Avrcp   (10848): CurrentAudioFocusPackageName is null
I/Avrcp   (10848): There is no currently selected player ,setting Samsung Music Player ID
I/Avrcp   (10848):  set player publishabilty with player id::1 toBePublished ::true
I/BluetoothA2dpServiceJni(10848): classInitNative: succeeds
D/A2dpStateMachine(10848): make
I/bluedroid(10848): get_profile_interface a2dp
,I/GKI_LINUX(10848): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif (10848): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService(10848): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@255c12b
D/A2dpStateMachine(10848): Enter Disconnected: -2
E/BluetoothAdapterService(39174443)(10848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,I/BluetoothHidServiceJni(10848): classInitNative: succeeds
,D/HidService(10848): Received start request. Starting profile...
I/bluedroid(10848): get_profile_interface hidhost
D/HidService(10848): setHidService(): set to: null
D/BluetoothAdapterService(10848): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@255c12b
I/BluetoothHealthServiceJni(10848): classInitNative: succeeds
,D/HealthService(10848): Received start request. Starting profile...
,I/bluedroid(10848): get_profile_interface health
D/BluetoothAdapterService(10848): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@255c12b
,D/HeadsetStateMachine(10848): Try to query the phonestate on bind
,I/Telecom ( 3948): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 3948): BluetoothPhoneService: updateHeadsetWithCallState
,D/AuthorizationBluetoothService( 4257): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothMediaBrowser(10848): no now playing list
D/BluetoothMediaBrowser(10848):  getNowPlayingId now playing id : -1
D/Avrcp   (10848):  checkNowPlayingList start
,I/Hs20UtilService( 6404): Starting #2
,I/Hs20UtilService( 6404): Message received 5011
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/Telecom ( 3948): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 3948): Proxy not attached to service
,D/HeadsetStateMachine(10848): Proxy object connected
,E/Zygote  (10883): MountEmulatedStorage()
I/libpersona(10883): KNOX_SDCARD checking this for 10127
E/Zygote  (10883): v2
I/libpersona(10883): KNOX_SDCARD not a persona
I/BluetoothPanServiceJni(10848): classInitNative(L105): succeeds
I/SELinux (10883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10883): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=10883 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BluetoothPan( 3527): BluetoothPAN Proxy object connected
,D/PanService(10848): Received start request. Starting profile...
D/BluetoothPanServiceJni(10848): initializeNative(L110): pan
I/bluedroid(10848): get_profile_interface pan
D/BluetoothAdapterService(10848): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@255c12b
D/HeadsetPhoneState(10848): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine(10848): Disconnected process message: 11
,D/BluetoothMapService(10848): Received start request. Starting profile...
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10883): TimaSignature is unavailable
,D/ActivityThread(10883): Added TimaKeyStore provider
,E/Zygote  (10898): MountEmulatedStorage()
I/libpersona(10898): KNOX_SDCARD checking this for 10178
E/Zygote  (10898): v2
I/libpersona(10898): KNOX_SDCARD not a persona
,I/SELinux (10898): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10898): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=10898 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux (10898): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10883): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/TimaKeyStoreProvider(10898): TimaSignature is unavailable
,D/ActivityThread(10898): Added TimaKeyStore provider
,D/ResourcesManager(10898): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(10898): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(10898): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10898): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10898): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10898): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/KeyguardWallpaperUpdator(10883): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(10883): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10883): stopCheckCategoryVersion
,I/SignOutReceiver(10466): WIFI_STATE_CHANGED_ACTION
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10914): MountEmulatedStorage()
E/Zygote  (10914): v2
I/libpersona(10914): KNOX_SDCARD checking this for 1000
I/libpersona(10914): KNOX_SDCARD not a persona
,I/SELinux (10914): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10914): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10914): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=10914 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 8811:com.sec.android.app.shealth/u0a36 (adj 13): bgCount ##31
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(10914): TimaSignature is unavailable
,D/ActivityThread(10914): Added TimaKeyStore provider
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,D/ResourcesManager(10914): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,D/BadgeProvider(10105): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BluetoothAdapterService(10848): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@255c12b
,D/HeadsetPhoneState(10848): sendDeviceDataStateChanged
D/HeadsetStateMachine(10848): Disconnected process message: 18
D/HeadsetPhoneState(10848): Signal level : previous=0 curr=0
,I/BluetoothSAPServiceJni(10848): classInitNative(L204): succeeds
,D/SapService(10848): Received start request. Starting profile...
D/BluetoothSAPServiceJni(10848): initializeNative(L209): sap
I/bluedroid(10848): get_profile_interface sap
D/BluetoothAdapterService(10848): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@255c12b
,E/BluetoothAdapterService(39174443)(10848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp(10848): Proxy object connected
D/BluetoothAdapterService(10848): Bluetooth A2dp source service connected
E/BluetoothAdapterService(39174443)(10848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(39174443)(10848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(39174443)(10848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/HeadsetStateMachine(10848): Disconnected process message: 10
D/HeadsetPhoneState(10848): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine(10848): Disconnected process message: 11
,I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
E/BluetoothAdapterService(39174443)(10848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10938): MountEmulatedStorage()
E/Zygote  (10938): v2
I/libpersona(10938): KNOX_SDCARD checking this for 10186
I/libpersona(10938): KNOX_SDCARD not a persona
,I/SELinux (10938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10938): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc tv.peel.smartremote for broadcast tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver: pid=10938 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10074:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,I/ActivityManager( 3527): Killing 10090:com.policydm/1000 (adj 13): bgCount ##31
,E/BluetoothAdapterService(39174443)(10848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(39174443)(10848): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/BluetoothAdapterState(10848): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid(10848): enable
,I/GKI_LINUX(10848): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid(10848): init
,I/bt_vendor(10848): init
I/bt_vnd_conf(10848): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf(10848): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial(10848): userial_init
,D/TimaKeyStoreProvider(10938): TimaSignature is unavailable
,D/ActivityThread(10938): Added TimaKeyStore provider
D/BadgeProvider(10105): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10105): sendNotify, [notify] : null
D/BadgeProvider(10105): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10105): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10105): update, [UpdateCount] : 1
,D/Launcher.Model( 3997): reloadBadges entered.
,D/ResourcesManager(10938): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,W/ResourcesManager(10938): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/ActivityManager( 3527): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/WebViewFactory(10938): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(10938): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(10938): Loading: webviewchromium
,I/LibraryLoader(10938): Time to load native libraries: 6 ms (timestamps 6112-6118)
I/LibraryLoader(10938): Expected native library version number "",actual native library version number ""
,I/bt_userial_vendor(10848): userial vendor open: opening /dev/ttySAC3
,I/bt_userial_vendor(10848): userial_vendor_open():UART is setup
I/bt_userial_vendor(10848): device fd = 65 open
E/bt_hwcfg(10848): Start CFG HW, HCI reset
D/bt_userial(10848): Entering userial_read_thread()
,E/bt_hwcfg(10848): Read Local Name after HCI reset
V/WebViewChromiumFactoryProvider(10938): Binding Chromium to main looper Looper (main, tid 1) {22745da5}
,I/LibraryLoader(10938): Expected native library version number "",actual native library version number ""
,I/chromium(10938): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10938): Initializing chromium process, renderers=0
,W/art     (10938): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10938): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10938): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10938): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
I/chromium(10938): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
,D/bt_hwcfg(10848): Chipset BCM43569A1
D/bt_hwcfg(10848): Target name = [BCM4358A1]
,I/bt_hwcfg(10848): module_type[murata].
I/bt_hwcfg(10848): module_type[murata] is invalid.
E/bt_hwcfg(10848): patchram path ORG . BCM4358A1
E/bt_hwcfg(10848): patchram path ORG .. BCM4358A1
E/bt_hwcfg(10848): patchram path ORG bcm4358A0_V0033.0000.hcd BCM4358A1
E/bt_hwcfg(10848): patchram path ORG bcm4358A1_V0044.0078.hcd BCM4358A1
I/bt_hwcfg(10848): patch(org) : bcm4358A1_V0044.0078.hcd
I/bt_hwcfg(10848): Found patchfile: /vendor/firmware/bcm4358A1_V0044.0078.hcd
E/bt_hwcfg(10848): ORG patchram base 0044
E/bt_hwcfg(10848): ORG patchram minor 0078
E/bt_hwcfg(10848): fw ver (org)44.78
E/bt_hwcfg(10848): Final Patchram is /vendor/firmware/bcm4358A1_V0044.0078.hcd
,I/bt_hwcfg(10848): Axi patch failure or not include AXI patching
,I/bt_hwcfg(10848): bt vendor lib: set UART baud 3000000
,W/chromium(10938): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10938): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10938): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10938): onDetachedFromWindow called when already detached. Ignoring
,I/SecureStorage(10864): [INFO]: SPID(0x00000005)Processing data has been completed
,D/SSRM:n  ( 3527): SIOP:: AP = 250, PST = 271, CUR = 39
,I/SecureStorage(10864): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10864): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10864
I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10864): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10864): ssSupport state is = 1
,I/wpa_supplicant(10864): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant(10864): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10864): SIM READ ERROR
I/wpa_supplicant(10864): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10864): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10864): SIM READ ERROR
I/wpa_supplicant(10864): Blacklist: Clear (all) 
I/wpa_supplicant(10864): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10864): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant(10864): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10864): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant(10864): rfkill: Cannot open RFKILL control device
,I/ActivityManager( 3527): Killing 10141:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,I/bt_hwcfg(10848): bt vendor lib: set UART baud 115200
I/bt_hwcfg(10848): FW Download delta = 482711
D/bt_hwcfg(10848): Settlement delay -- 100 ms
I/bt_hwcfg(10848): Setting fw settlement delay to 100 
,I/bt_hwcfg(10848): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg(10848): vendor lib fwcfg completed
,I/        (10848): BTE_InitTraceLevels -- TRC_HCI
I/        (10848): BTE_InitTraceLevels -- TRC_L2CAP
I/        (10848): BTE_InitTraceLevels -- TRC_RFCOMM
I/        (10848): BTE_InitTraceLevels -- TRC_AVDT
I/        (10848): BTE_InitTraceLevels -- TRC_AVRC
I/        (10848): BTE_InitTraceLevels -- TRC_A2D
I/        (10848): BTE_InitTraceLevels -- TRC_BNEP
I/        (10848): BTE_InitTraceLevels -- TRC_BTM
I/        (10848): BTE_InitTraceLevels -- TRC_GAP
I/        (10848): BTE_InitTraceLevels -- TRC_PAN
I/        (10848): BTE_InitTraceLevels -- TRC_SAP
I/        (10848): BTE_InitTraceLevels -- TRC_SDP
I/        (10848): BTE_InitTraceLevels -- TRC_GATT
I/        (10848): BTE_InitTraceLevels -- TRC_SMP
I/        (10848): BTE_InitTraceLevels -- TRC_BTAPP
I/        (10848): BTE_InitTraceLevels -- TRC_BTIF
I/        (10848): BTE_InitTraceLevels -- TRC_PROTOCOL
,W/bt-l2cap(10848): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  (10848): BTM_SecRegister:p_cb_info->p_le_callback == 0xb3a0f9e1 
E/bt-btm  (10848): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb3a0f9e1 
,E/Tethering( 3527): No numeric data
,D/Tethering( 3527): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 3527): forceRefresh() from cache miss
,D/HotspotTile( 3694): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3694): updateTetherState():false, false
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 3527): forceRefresh Fail.
,V/NetworkStats( 3527): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3527): UpdateStatsForKnox
,V/NetworkStats( 3527): performPollLocked() took 2ms
,E/Zygote  (11003): MountEmulatedStorage()
E/Zygote  (11003): v2
I/libpersona(11003): KNOX_SDCARD checking this for 10110
I/libpersona(11003): KNOX_SDCARD not a persona
,I/SELinux (11003): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11003): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11003 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (11003): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/NtpTrustedTime( 3527): forceRefresh() from cache miss
,D/NtpTrustedTime( 3527): forceRefresh Fail.
,D/TimaKeyStoreProvider(11003): TimaSignature is unavailable
,D/ActivityThread(11003): Added TimaKeyStore provider
,D/ResourcesManager(11003): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/BluetoothAdapterProperties(10848): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif (10848): Calling BTA_HhEnable
,I/wpa_supplicant(10864): wlan0: Setting scan request: 0 sec 100000 usec
E/bt-btif (10848): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties(10848): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10848): populateRssiValuesNative
I/bluedroid(10848): getModelRssiValues
E/BluetoothServiceJni(10848): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10848): modelRssiValuesCallback, low, mid, high = -75,-65,127
,D/BluetoothAdapterProperties(10848): Name is: Note4-1
D/SettingsProvider( 3527): name = bluetooth_name
,D/BluetoothAdapterProperties(10848): Scan Mode:20
D/BluetoothAdapterProperties(10848): Discoverable Timeout:120
D/BluetoothAdapterProperties(10848): LE Address is:E0:B7:20:28:C5:81
E/bt-btif (10848): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif (10848): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif (10848): btif_sock_init: !radio_req && !rfc_init
E/bt-btif (10848): btif_sock_init: !vhci_init
D/IOP_DB_BT(10848): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT(10848): db_open: db_open : handle 3026083856l, read 14063 bytes onto local cache
D/IOP_DB_BT(10848): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT(10848): db_query: result 1
I/        (10848): iop_db_open: iop_db_open status 0
,D/bte_conf(10848): Device ID record 1 : primary
D/bte_conf(10848):   vendorId            = 0075
D/bte_conf(10848):   vendorIdSource      = 0001
D/bte_conf(10848):   product             = 0100
D/bte_conf(10848):   version             = 0200
D/bte_conf(10848):   clientExecutableURL = 
D/bte_conf(10848):   serviceDescription  = 
D/bte_conf(10848):   documentationURL    = 
D/bte_conf(10848): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni(10848): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState(10848): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties(10848): ScanMode =  20
D/BluetoothAdapterProperties(10848): State =  11
,D/SecContentProvider( 3527): uri = 3 selection = isDiscoverableEnabled
D/BluetoothAdapterProperties(10848): Setting state to 12
I/BluetoothAdapterState(10848): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties(10848): Scan Mode:21
D/BluetoothAdapterProperties(10848): Discoverable Timeout:120
,D/SettingsProvider( 3527): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService(10848): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10848): updateAdapterState state is 12
,D/BluetoothAdapterService(10848): Autoconnection is available 
D/BluetoothAdapterService(10848): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService(10848): starting service from this receiver
,D/BluetoothA2dp( 4802): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 3527): onBluetoothStateChange: up=true
D/BluetoothA2dp(10848): onBluetoothStateChange: up=true
,I/BluetoothAdapterState(10848): Entering On State from state = 11
,W/InputMethodManagerService( 3527): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3527): [BT Setting State] State =12
I/InputMethodManagerService( 3527): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothTile( 3694):  onBluetoothStateChange:
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
D/BluetoothHeadset( 3948): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@7dae932, true
D/BluetoothTile( 3694): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,I/SamsungIME( 4456): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothHeadset( 3948): registerMessageListener
,D/HeadsetService(10848): registerMessageListener
,I/BluetoothPbapService(10848): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
D/HeadsetService(10848): registerMessageListener
,D/HeadsetStateMachine(10848): Disconnected process message: 70
I/Telecom ( 3948): BluetoothPhoneService: updateHeadsetWithCallState
I/Telecom ( 3948): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/HeadsetStateMachine(10848): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@11f672fb
,E/bt_h4   (10848): vendor lib postload completed
,D/StatusBarManagerService( 3527): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/HeadsetStateMachine(10848): Disconnected process message: 9
D/HeadsetStateMachine(10848): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/StatusBarManagerService( 3527): setIconVisibility slot=bluetooth visible=true
,D/PhoneStatusBar( 3694): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,V/[CarModeFW](10199): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
D/BluetoothTile( 3694):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 3694): onStateChanged: Bluetooth
,D/[CarModeFW](10199): ConnectivityManager-handleMessage INITIAL_STATE_ON
,I/AudioHardwareTinyALSA( 2860): setParameters(A2dpSuspended=false)
,E/HeadsetStateMachine(10848): terminateScoUsingVirtualVoiceCall:No present call to terminate
,I/wpa_supplicant(10864): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage(10864): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10864): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10864
I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10864): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10864): ssSupport state is = 1
,I/SecureStorage(10864): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10864): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10864
I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10864): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10864): ssSupport state is = 1
I/wpa_supplicant(10864): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10864): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10864): SIM READ ERROR
I/wpa_supplicant(10864): rfkill: Cannot open RFKILL control device
E/wpa_supplicant(10864): nl80211: Could not configure driver mode
E/wpa_supplicant(10864): p2p0: Failed to initialize driver interface
I/wpa_supplicant(10864): Blacklist: Clear (all) 
,I/SecureStorage(10864): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10864): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10864
I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10864): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10864): ssSupport state is = 1
I/SecureStorage(10864): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10864): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10864
I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10864): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10864): ssSupport state is = 1
I/wpa_supplicant(10864): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10864): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10864): SIM READ ERROR
I/wpa_supplicant(10864): rfkill: Cannot open RFKILL control device
,D/ACRA    (11003): ACRA is enabled for com.facebook.appmanager, intializing...
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 30010(1771KB) AllocSpace objects, 13(208KB) LOS objects, 24% free, 48MB/64MB, paused 1.525ms total 82.706ms
,I/BluetoothPbapService(10848): Handler(): got msg=1
,D/BluetoothManagerService( 3527): Broadcasting onBluetoothServiceUp() to 0 receivers.
D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/BluetoothPbapService(10848): PBAP Service initSocket try: 0
,D/BluetoothMapMasInstance(10848): set MAP SDP message type : 1
,W/BluetoothAdapter(10848): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10848): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket(10848): bindListen(), new LocalSocket 
D/BluetoothSocket(10848): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10848): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6bc02e2
D/BluetoothSocket(10848): channel: 19
D/BluetoothPbapService(10848): PBAP Socket is BluetoothServerSocket
,I/DexLibLoader(11003): not using cross-dex optimization: ART in use
W/BluetoothAdapter(10848): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10848): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket(10848): bindListen(), new LocalSocket 
D/BluetoothSocket(10848): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10848): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ba4673
D/BluetoothSocket(10848): channel: 5
,I/art     (11003): Thread[1,tid=11003,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,I/wpa_supplicant(10864): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant(10864): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,V/DexLibLoader(11003): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11003): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11003): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11003): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11003): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11003): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11003): loading pre-built fallback odex files
,V/MultiDexClassLoader(11003): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11003): released odex store lock
D/DexLibLoader(11003): DexLibLoader.loadAll took 13 ms
,W/ca      (11003): Verify
,I/wpa_supplicant(10864): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant(10864): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant(10864): Skip scan - bUseNetwork false
,E/WifiStateMachine( 3527): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,E/WifiStateMachine( 3527): setSuspendOptimizations: 2 true
E/WifiStateMachine( 3527): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine( 3527): Supplicant connection established
D/WifiNative-HAL( 3527): callSECApiBoolean - ID [21]
I/wpa_supplicant(10864): HOTSPOT20_ENABLE called
I/wpa_supplicant(10864): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10864): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10864): SIM READ ERROR
I/wpa_supplicant(10864): Blacklist: Clear (all) 
,I/wpa_supplicant(10864): wlan0: Setting scan request: 0 sec 0 usec
,W/LightSharedPreferencesImpl(11003): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11003): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11003): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11003): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11003): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11003): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11003): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11003): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11003): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11003): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11003): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11003): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11003): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11003): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11003): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11003): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11003): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11003): 	... 10 more
,I/wpa_supplicant(10864): Skip scan - bUseNetwork false
E/WifiStateMachine( 3527): setWifiState: enabled
D/WifiNative-HAL( 3527): callSECApiInt - ID [210]
D/SmartBondingService( 3527): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SLocation( 3527): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/WifiConfigStore( 3527): Loading config and enabling all networks 
D/SmartBondingService( 3527): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/HotspotTile( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3694): Wifi onReceive(3)
D/HotspotTile( 3694): onReceive : 3, 0
D/STATUSBAR-QSTileView( 3694): onStateChanged: Wi-Fi
W/appmanager(:<default>):b(11003): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/WifiConfigStore( 3527): Not a HS20
E/WifiConfigStore( 3527): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):b(11003): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/ContextImpl( 7854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/WifiStateMachine( 3527): update LTECoexState:0
D/WifiNative-HAL( 3527): callSECApiInt - ID [65]
D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
I/wpa_supplicant(10864): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant(10864): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant(10864): reset timer : RESET_TIMER 0
I/wpa_supplicant(10864): P2P: Current p2p state = IDLE
I/wpa_supplicant(10864): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant(10864): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant(10864): First Scan Start
I/wpa_supplicant(10864): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiNative-HAL( 3527): Setting external_sim to 1
D/WifiStateMachine( 3527): Setting OUI to DA-A1-19
I/WifiNative-HAL( 3527): startHal
E/wifi    ( 3527): getStaticLongField sWifiHalHandle 0x8fd1a85c
D/wifi    ( 3527): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x50219a
I/WifiNative-HAL( 3527): Could not start hal
E/WifiStateMachine( 3527): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,D/LocalBluetoothProfileManager( 7854): Adding local A2DP profile
E/WifiStateMachine( 3527): Attempting to reconnect to wifi network ..
E/native  ( 3527): do suspend true
D/LocalBluetoothProfileManager( 7854): Adding local HEADSET profile
E/BluetoothHeadset( 7854): BTStateChangeCB is registed
D/WifiP2pService( 3527): P2pDisabledState{ what=131203 }
E/BluetoothHeadset( 7854): BluetoothHeadset service is binded
E/WifiStateMachine( 3527): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiStateMachine( 3527): updateConfiguredNetworkExpiration - currTime: 1453367954173
D/WifiStateMachine( 3527): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/WifiScanningService( 3527): SCAN_AVAILABLE : 3
D/WifiScanningService( 3527): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 3527): startHal
E/wifi    ( 3527): getStaticLongField sWifiHalHandle 0x8ead298c
D/wifi    ( 3527): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x701f82
I/WifiNative-HAL( 3527): Could not start hal
E/WifiScanningService( 3527): could not start HAL
D/CommandListener( 2847): Setting iface cfg
D/CommandListener( 2847): Trying to bring up p2p0
E/WifiStateMachine( 3527): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3527): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/RttService( 3527): SCAN_AVAILABLE : 3
E/WifiStateMachine( 3527): set country code pl
D/RttService( 3527): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 3527): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 3527): P2pEnablingState
D/WifiP2pService( 3527): P2pEnablingState{ what=147457 }
D/WifiP2pService( 3527): P2p socket connection successful
D/WifiP2pService( 3527): P2pEnabledState
D/WifiP2pService( 3527): sending p2p connection changed broadcast: IDLE
E/WifiStateMachine( 3527): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 3527): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiP2pService( 3527): create mNetworkAgent
W/ContextImpl( 7854): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 7854): bindService called to Bluetooth SAP Service
D/WifiDisplayController( 3527): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3527): disconnect
D/WifiDisplayController( 3527): updateConnection
D/WifiDisplayController( 3527): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3527): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3694): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3694): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/LocalBluetoothProfileManager( 7854): PANU : true
D/LocalBluetoothProfileManager( 7854): Adding local MAP profile
D/BluetoothMap( 7854): Create BluetoothMap proxy object
W/LocalBluetoothProfileManager( 7854): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 7854): LocalBluetoothProfileManager construction complete
W/appmanager(:<default>):QuickExperimentControllerImpl(11003): Exposure of experiment com.facebook.common.network.l@3e001e43 occurred when no user was logged in
I/wpa_supplicant(10864): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
D/DockEventReceiver( 7854): finishStartingService: stopping service
E/WifiStateMachine( 3527): set frequency band 0
D/BluetoothNotiBroadcastReceiver( 7854): onReceive
D/BluetoothA2dp( 7854): Proxy object connected
D/A2dpProfile( 7854): Bluetooth service connected
D/ConnectivityService( 3527): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 3527): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 3527): updateNetworkInfo()
D/ConnectivityService( 3527): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/CSLegacyTypeTracker( 3527): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
D/BluetoothAdapterService(10848): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@255c12b
D/BtConfig.SecureMode(10848): isSecureModeOn:false
D/HeadsetProfile( 7854): Bluetooth service connected
D/AuthorizationBluetoothService( 4257): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/Bluetoothsap( 7854): BluetoothSAP Proxy object connected
D/SapProfile( 7854): Bluetooth service connected
D/Bluetoothsap( 7854): getConnectedDevices()
D/BluetoothInputDevice( 7854): Proxy object connected
D/HidProfile( 7854): Bluetooth service connected
I/Hs20UtilService( 6404): Starting #3
I/Hs20UtilService( 6404): Message received 5011
I/WifiStateMachine( 3527): callSECApi what=207
D/BluetoothPan( 7854): BluetoothPAN Proxy object connected
D/PanProfile( 7854): Bluetooth service connected
I/wpa_supplicant(10864): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/KeyguardWallpaperUpdator(10883): cancelUpdateWallpaper
E/WifiStateMachine( 3527): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3527): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine( 3527): setDetailed state send new extra info
D/KeyguardWallpaperUpdator(10883): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10883): stopCheckCategoryVersion
D/BluetoothMap( 7854): Proxy object connected
D/MapProfile( 7854): Bluetooth service connected
D/BluetoothPbap( 7854): Proxy object connected
D/PbapServerProfile( 7854): Bluetooth service connected
D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
D/WifiNative-HAL( 3527): p2pGetDeviceAddress
D/WifiNative-HAL( 3527): p2pGetDeviceAddress returning 92:b6:86:43:73:1c
I/SignOutReceiver(10466): WIFI_STATE_CHANGED_ACTION
D/WifiP2pService( 3527): DeviceAddress: 92:73:1c
D/WifiDisplayController( 3527): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note4-1
D/WifiDisplayController( 3527):  deviceAddress: 92:b6:86:43:73:1c
D/WifiDisplayController( 3527):  primary type: 10-0050F204-5
D/WifiDisplayController( 3527):  secondary type: null
D/WifiDisplayController( 3527):  wps: 0
D/WifiDisplayController( 3527):  grpcapab: 0
D/WifiDisplayController( 3527):  devcapab: 0
D/WifiDisplayController( 3527):  status: 3
D/WifiDisplayController( 3527):  wfdInfo: null
D/WifiDisplayController( 3527):  groupownerAddress: null
D/WifiDisplayController( 3527):  GOdeviceName: null
D/WifiDisplayController( 3527):  interfaceAddress: 
D/WifiDisplayController( 3527):  SConnectInfo : null
W/BluetoothAdapter(10848): getBluetoothService() called with no BluetoothManagerCallback
E/WifiStateMachine( 3527): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL( 3527): callSECStringApiVoid - ID [215]
E/WifiNative-HAL( 3527): invaild command id : 215
D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
,D/WifiP2pService( 3527): sending p2p persistent groups changed broadcast
,D/BluetoothSocket(10848): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
D/BluetoothSocket(10848): bindListen(), new LocalSocket 
D/BluetoothSocket(10848): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10848): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@412b765
D/BluetoothSocket(10848): channel: 12
I/BtOppRfcommListener(10848): Accept thread started.
,D/WifiP2pService( 3527): InactiveState
D/WifiP2pService( 3527): InactiveState{ what=143376 }
D/WifiP2pService( 3527): P2pEnabledState{ what=143376 }
,I/wpa_supplicant(10864): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService( 3527): updateNetworkInfo()
D/WifiP2pService( 3527): InactiveState{ what=143376 }
D/WifiP2pService( 3527): P2pEnabledState{ what=143376 }
,I/ActivityManager( 3527): Killing 10125:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/NearbySettings( 7854): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 7854): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 7854): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 7854): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 7854): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 7854): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3527): New client listening to asynchronous messages
,I/NearbySettings( 7854): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7854): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7854): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7854): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11069): MountEmulatedStorage()
E/Zygote  (11069): v2
I/libpersona(11069): KNOX_SDCARD checking this for 10079
I/libpersona(11069): KNOX_SDCARD not a persona
,I/SELinux (11069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11069): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=11069 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager( 3527): waitForAlarm result :8
,V/AlarmManager( 3527): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 3527): <AppSync3 Whitelist>
V/AlarmManager( 3527): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/TimaKeyStoreProvider(11069): TimaSignature is unavailable
,D/ActivityThread(11069): Added TimaKeyStore provider
,D/ResourcesManager(11069): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(11069): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/NtpTrustedTime( 3527): forceRefresh() from cache miss
,D/NtpTrustedTime( 3527): forceRefresh Fail.
I/ActivityManager( 3527): Killing 10157:com.wsomacp/u0a28 (adj 13): bgCount ##31
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11003): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11003): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(11003): Exposure of experiment com.facebook.imagepipeline.a.g@10482979 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11003): Exposure of experiment com.facebook.imagepipeline.a.d@229f80ca occurred when no user was logged in
,I/art     (11003): Explicit concurrent mark sweep GC freed 45394(2MB) AllocSpace objects, 3(48KB) LOS objects, 22% free, 27MB/35MB, paused 516us total 20.755ms
,W/appmanager(:<default>):m(11003): No feature status reporters found; is this dead code?
,I/wpa_supplicant(10864): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant(10864): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant(10864): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant(10864): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant(10864): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
I/WifiNative-HAL( 3527): startHal
E/wifi    ( 3527): getStaticLongField sWifiHalHandle 0x8fd1a87c
D/wifi    ( 3527): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x30225e
I/WifiNative-HAL( 3527): Could not start hal
E/WifiStateMachine( 3527): [1,453,367,954,727 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3527): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@e37742e sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3527): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3527): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
,I/wpa_supplicant(10864): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant(10864): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3527): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3527): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant(10864): Associated with C0.AA.48
E/WifiStateMachine( 3527): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
,I/wpa_supplicant(10864): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant(10864): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine( 3527): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3527): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
,I/jxcore-log(10777): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(10777): 
,I/wpa_supplicant(10864): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant(10864): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant(10864): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3527): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3527): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant(10864): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(10864): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant(10864): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant(10864): Blacklist: Clear (temp) 
I/wpa_supplicant(10864): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3527): Network connection established
,D/WifiNative-HAL( 3527): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3527): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3527): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3527): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3527): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine( 3527): L2ConnectedState "NG700" nid=0
D/ConnectivityService( 3527): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 3527): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3527): updateNetworkInfo()
E/WifiConfigStore( 3527): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 6404): Starting #4
,I/Hs20UtilService( 6404): Message received 5007
,D/NearbySettings( 7854): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 7854): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 7854): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 7854): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7854): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7854): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7854): MountReceiver.mPrefHandler - 7002
,E/WifiStateMachine( 3527): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine( 3527): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3527): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3527): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SignOutReceiver(10466): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2847): Setting iface cfg
,E/WifiStateMachine( 3527): Start Dhcp Watchdog 1
,D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
,E/WifiStateMachine( 3527): Force RSSI Broadcast 1/3
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3527): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3527): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3527): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3527): do suspend false
,D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3527): InactiveState{ what=143375 }
D/SecContentProvider2( 3527): mCursor = null
D/WifiP2pService( 3527): P2pEnabledState{ what=143375 }
,I/jxcore-log(10777): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(10777): 
,I/jxcore-log(10777): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(10777): 
,I/jxcore-log(10777): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(10777): 
,I/jxcore-log(10777): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(10777): 
,I/jxcore-log(10777): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(10777): 
,I/jxcore-log(10777): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(10777): 
,E/dhcpcd  (11091): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11091): version 5.5.6 starting
,E/dhcpcd  (11091): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11091): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11091): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11091): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (11091): bssid match
,I/dhcpcd  (11091): wlan0: rebinding lease of 192.168.1.124
,E/WifiStateMachine( 3527): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3527): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/dhcpcd  (11091): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (11091): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3527): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3527): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3527): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3527): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3527): do suspend true
,D/WifiP2pService( 3527): InactiveState{ what=143375 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3527): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3527): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3527): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3527): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3527): Not connected state, yet.
E/WifiStateMachine( 3527): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3527): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3527): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3527): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3527): callSECApiInt - ID [210]
,E/WifiStateMachine( 3527): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3527): updateNetworkInfo()
,D/ConnectivityService( 3527): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3527): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 3527): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3527): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3527): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3527): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3527): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3527): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3527): Now, connected state.
E/WifiStateMachine( 3527): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3527): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/Hs20UtilService( 6404): Starting #5
,I/Hs20UtilService( 6404): Message received 5007
I/WifiTrafficPoller( 3527): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3527): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3527): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3527): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3527): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3527): REQUEST_POWER_SAVE_ON
D/ConnectivityService( 3527): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService( 3527): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/ConnectivityService( 3527): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,D/NearbySettings( 7854): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,E/ConnectivityService( 3527): Unexpected mtu value: 0, wlan0
,I/NearbySettings( 7854): MountReceiver.onReceive - Keep current state
V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,W/NetworkManagementService( 3527): route cmd failed: 
W/NetworkManagementService( 3527): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '51 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 51 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3527): '
W/NetworkManagementService( 3527): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3527): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3527): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3527): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3527): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3527): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3527): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3527): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6313)
W/NetworkManagementService( 3527): 	at com.android.server.ConnectivityService.access$2700(ConnectivityService.java:231)
W/NetworkManagementService( 3527): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2449)
W/NetworkManagementService( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/        ( 2847): QcRouteController
,I/SignOutReceiver(10466): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2847): QcRouteController
,I/Hs20UtilService( 6404): Starting #6
I/Hs20UtilService( 6404): Message received 5007
,V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
D/NearbySettings( 7854): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 7854): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 7854): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 7854): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7854): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7854): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 7854): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(10466): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2847): QcRouteController
,I/Hs20UtilService( 6404): Starting #7
I/Hs20UtilService( 6404): Message received 5007
,D/NearbySettings( 7854): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 7854): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3527): callSECApi what=220
D/WifiStateMachine( 3527): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,I/SignOutReceiver(10466): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2847): QcRouteController
,D/ConnectivityService( 3527): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService( 3527): LTETest block dns file not exists
,D/ConnectivityService( 3527): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
E/ConnectivityService( 3527): updateNetworkInfo()
D/ConnectivityService( 3527): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3527): updateNetworkInfo()
D/ConnectivityService( 3527): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3527): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3527):    accepting network in place of null
,I/System.out( 3527): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService( 3527): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
I/System.out( 3527): (HTTPLog)-Static: isShipBuild true
I/System.out( 3527): (HTTPLog)-Thread-189-122171527: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3527): (HTTPLog)-Static: isSBSettingEnabled false
,D/TelephonyNetworkFactory( 3975): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SurfaceFlinger( 2855): id=12 createSurf (1x1),1 flag=4, Uoast
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 1000
,E/CSLegacyTypeTracker( 3527): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3527): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService( 3527): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/PowerManagerService( 3527): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3527
,D/ConnectivityService( 3527): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3527): MasterInitialState.processMessage what=3
D/SmartBondingService( 3527): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3527): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats( 3527): updateIfacesLocked()
V/NetworkStats( 3527): performPollLocked(flags=0x1)
D/SmartBondingService( 3527): getSBEnabled() enabled =false
D/NtpTrustedTime( 3527): forceRefresh() from cache miss
D/SmartBondingService( 3527): getSBEnabled() enabled =false
D/NetworkStatsFactory( 3527): UpdateStatsForKnox
,D/EntConnectivity( 3527): Not allowed due to - mEnabled false
D/ConnectivityService( 3527): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/SmartBondingService( 3527): getSBEnabled() enabled =false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
V/NetworkStats( 3527): performPollLocked() took 1ms
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 1000
,D/SmartBondingService( 3527): getNetworkEnabled : wifi : true mobile : false
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 4473): CM callback handler got msg 524290
,D/mali_winsys( 3694): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,D/NtpTrustedTime( 3527): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1453367958488 mCachedNtpElapsedRealtime : 140246 mCachedNtpCertainty : 17
,D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
V/NetworkStats( 3527): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
,I/System.out( 3527): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 09:19:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453367957316], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453367957277]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): Validated
,D/ConnectivityService( 3527): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3527): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3527): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 3527): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3527): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 4473): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3527): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3527): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3527): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3527): SmartBondingReceiver: wifi ap is changed, init speed ratio
D/SmartBondingService( 3527): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3527): getSBEnabled() enabled =false
D/SmartBondingService( 3527): getSBEnabled() enabled =false
D/SmartBondingService( 3527): getSBEnabled() enabled =false
,D/SmartBondingService( 3527): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
,D/AlarmManagerService( 3527): Setting time of day to sec=1453367958
D/AlarmManagerService( 3527): Trying to open a file
,D/AlarmManagerService( 3527): File Open Success
D/AlarmManagerService( 3527): File Close Success
I/AlarmManagerService( 3527): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 3527): waitForAlarm result :65536
,D/WifiStateMachine( 3527): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_SET
D/SettingsProvider( 3527): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10060
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,I/DBG_DM  ( 5892): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 5892): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 5892): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,I/DBG_DM  ( 5892): [IlIIlIIlIllllIlllIII(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/KeyguardEffectViewUtil( 3694): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3694): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3694): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,I/DBG_DM  ( 5892): [IlIlllIlllllIlIllllI(403/llllllIllIlIlllIIlIl)] Check completed.
,D/VisualEffectParticleEffect( 3694): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3694): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{2a984b6e G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3694): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{ee7d20f V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3694): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{2a984b6e G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3694): clearEffect
D/WallpaperWidget( 3694): setLockScreenWallpaper()
,I/DBG_DM  ( 5892): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
D/KeyguardEffectViewUtil( 3694): getCurrentWallpaper() mWallpaperPath :null
I/DBG_DM  ( 5892): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,E/Zygote  (11154): MountEmulatedStorage()
I/libpersona(11154): KNOX_SDCARD checking this for 1000
E/Zygote  (11154): v2
I/libpersona(11154): KNOX_SDCARD not a persona
,I/SELinux (11154): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11154): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11154): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11154 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/DBG_DM  ( 5892): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5892): [IIlIIIlllllIIlIIIlII(72/llllIIIllIlIIIIllllI)] 
,W/Settings( 3527): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TimaKeyStoreProvider(11154): TimaSignature is unavailable
,D/ActivityThread(11154): Added TimaKeyStore provider
,W/SEC_DRM_PLUGIN_Playready( 2859): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1453367957 after conversion: 1453367957
W/SEC_DRM_PLUGIN_Playready( 2859): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1453367958 after conversion: 1453367958
,I/DBG_DM  ( 5892): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 5892): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 5892): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 5892): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 5892): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 5892): [IlIIlIIlIllllIlllIII(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,D/ResourcesManager(11154): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/DBG_DM  ( 5892): [IlIIlIIlIllllIlllIII(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 5892): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 5892): [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 5892): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(502/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,W/appmanager(:<default>):QuickExperimentControllerImpl(11003): Exposure of experiment com.facebook.http.g.an@20edf407 occurred when no user was logged in
,I/DBG_DM  ( 5892): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,I/PCWCLIENTTRACE_LOG(11154): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11154): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11154): new DMDBOpenHelper instance
,I/GoogleURLConnFactory( 4257): Using platform SSLCertificateSocketFactory
,I/DBG_DM  ( 5892): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5892): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,I/PCWCLIENTTRACE_PushUtil(11154): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11154): sales region : global
I/PCWCLIENTTRACE_PushUtil(11154): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11154): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 5892): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 5892): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 5892): [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
W/appmanager(:<default>):QuickExperimentControllerImpl(11003): Exposure of experiment com.facebook.http.g.aw@34af635d occurred when no user was logged in
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
W/appmanager(:<default>):QuickExperimentControllerImpl(11003): Exposure of experiment com.facebook.http.g.aj@15e1d4d2 occurred when no user was logged in
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
W/appmanager(:<default>):QuickExperimentControllerImpl(11003): Exposure of experiment com.facebook.http.g.a@c6bc9a3 occurred when no user was logged in
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 6378): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/DBG_DM  ( 5892): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
E/DBG_DM  ( 5892): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@2c9c3fad
,W/ResourcesManager( 6378): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6378): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  (11176): MountEmulatedStorage()
E/Zygote  (11176): v2
I/libpersona(11176): KNOX_SDCARD checking this for 10135
I/libpersona(11176): KNOX_SDCARD not a persona
,I/SELinux (11176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11176): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11176 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 5892): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,D/TimaKeyStoreProvider(11176): TimaSignature is unavailable
W/appmanager(:<default>):QuickExperimentControllerImpl(11003): Exposure of experiment com.facebook.http.g.k@be46c1e occurred when no user was logged in
D/ActivityThread(11176): Added TimaKeyStore provider
,E/Zygote  (11193): MountEmulatedStorage()
E/Zygote  (11193): v2
I/libpersona(11193): KNOX_SDCARD checking this for 10090
I/libpersona(11193): KNOX_SDCARD not a persona
,I/SELinux (11193): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11193): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11193): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=11193 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/KeyguardEffectViewUtil( 3694): set current wallpaper info
,D/SettingsProvider( 3527): name = keyguard_current_wallpaper_type
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10060
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11193): TimaSignature is unavailable
,D/ActivityThread(11193): Added TimaKeyStore provider
,E/Zygote  (11210): MountEmulatedStorage()
I/libpersona(11210): KNOX_SDCARD checking this for 10050
E/Zygote  (11210): v2
I/libpersona(11210): KNOX_SDCARD not a persona
,I/SELinux (11210): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11210): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11210): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=11210 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3527): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10060
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8761(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 312us total 11.414ms
,I/DBG_DM  ( 5892): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/TimaKeyStoreProvider(11210): TimaSignature is unavailable
,D/ActivityThread(11210): Added TimaKeyStore provider
D/GpsLocationProvider( 3527): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,I/System.out(11003): Thread-1496(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11003): Thread-1496(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11003): Thread-1496(ApacheHTTPLog):isShipBuild true
I/System.out(11003): Thread-1496(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/appmanager(:<default>):QuickExperimentControllerImpl(11003): Exposure of experiment com.facebook.http.g.c@2a5eca1b occurred when no user was logged in
,D/SettingsProvider( 3527): name = keyguard_current_wallpaper_res_id
D/ResourcesManager(11176): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 564us total 9.262ms
D/SettingsProvider( 3527): selectionArgs: 10060
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10110
,D/ResourcesManager(11193): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/StatusBar-DoNotDistrub( 3694): Received intent with android.intent.action.TIME_SET action
I/DBG_DM  ( 5892): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/StatusBar-DoNotDistrub( 3694): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 637us total 14.375ms
,D/StatusBar-DoNotDistrub( 3694): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager( 2860): getOutputsForDevice device 0002 -> 0002
,I/AudioService( 3527): getStreamVolume 5 index 110
,D/StatusBar-DoNotDistrub( 3694): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,I/PhenotypeConfigurator( 4257): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/ResourcesManager(11210): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(11210): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11210): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11210): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11210): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(11210): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(11210): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(11210): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(11210): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityThread( 4473): Failed to find provider info for com.android.contacts.metadata
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SyncManager( 3527): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 15800, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 3527): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 171406, reason: UserStart
,D/KeyguardEffectViewUtil( 3694): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3694): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3694): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3694): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3694): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{2a984b6e G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3694): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{ee7d20f V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3694): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{2a984b6e G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3694): clearEffect
,D/SecContentProvider2( 3527): uri = 14 selection = getSealedState
D/SecContentProvider2( 3527): mCursor = null
,D/ApplicationPolicy( 3527): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 3527): showStatusBarByNotification() mOpenByNotification=false
,D/ResourcesManager( 3694): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,I/MusicStore(11176): Database version: 104
,W/ResourceType( 4963): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4963): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/System.out( 6378): Thread-596(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6378): Thread-596(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6378): Thread-596(ApacheHTTPLog):isShipBuild true
I/System.out( 6378): Thread-596(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/KnoxNotification( 3694): ----- inflateViews : modified publicViewLocal -----
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10202
,I/DBG_DM  ( 5892): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,D/KnoxNotification( 3694): ----- inflateViews : modified KnoxViewLocal -----
,I/dex2oat (11233): ----------------------------------------------------
I/dex2oat (11233): <SS>: S T A R T I N G . . .
I/dex2oat (11233): <SS>: Zip is absent. Canceled.
I/dex2oat (11233): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1494042565.jar --oat-fd=54 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1494042565.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/PersonaManager( 3694): PersonaID is invalid or persona doesn't exists. : 0
I/DBG_DM  ( 5892): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/PhoneStatusBar( 3694): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2d5e1bca
,D/PersonaManager( 3694): isKioskContainerExistOnDevice
D/PersonaManager( 3694): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3694): Icon Only
,D/SecContentProvider2( 3527): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3527): mCursor = null
,I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
,D/PanelView( 3694): There is/are notification(s) 
D/PersonaManager( 3694): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
,D/ResourcesManager(11176): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/DBG_DM  ( 5892): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 5892): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 5892): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,W/ResourcesManager(11176): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11176): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11176): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 6378): Tagging socket 53 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6378, getuid(): 10202
,I/dex2oat (11233): dex2oat took 65.693ms (threads: 8)
,D/PackageManager( 3527): findPreferredActivity: No PreferredActivities set
,E/Auth.Api.Credentials( 4473): [CredentialSyncAdapter] Unknown sync event.
,D/PanelView( 3694): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,W/ActivityThread(11176): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11176): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f68d6cf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11176): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11176): GMSCore installation verified
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 67645(3MB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 49MB/65MB, paused 3.439ms total 95.498ms
,D/NearbySource(11210): Nearby Source Create!
D/NearbyContext(11210): Nearby Context Create!
,D/DelayedSyncController(11193): Delaying sync.
,I/ConfigStore(11176): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11210): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(11210): Samsung link source created
,I/System.out( 4257): (HTTPLog)-Static: isSBSettingEnabled false
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,D/ContactProvider(11210): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11176): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
D/ContactProvider(11210): getAllContactInfoList End
,I/syncContacts(11210): thread: 1493, sync time = 39
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 3527): Killing 9955:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11176): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11176): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ActivityThread(11003): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/System.out( 4257): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4257): Tagging socket 55 with tag 1000120300000000{268440067,0} uid -1, pid: 4257, getuid(): 10014
I/AudioService( 3527): getStreamVolume 3 index 0
,I/MediaRouter(11176): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10202
,I/NetworkMonitor(11176): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/PicasaService(11210): start picasa sync
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/PicasaService(11210): end picasa sync
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11275): MountEmulatedStorage()
E/Zygote  (11275): v2
I/libpersona(11275): KNOX_SDCARD checking this for 10002
I/libpersona(11275): KNOX_SDCARD not a persona
,I/SELinux (11275): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11275): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11275): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11275 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider(11275): TimaSignature is unavailable
D/ActivityThread(11275): Added TimaKeyStore provider
I/ActivityManager( 3527): Killing 10180:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,I/qtaguid ( 6378): Tagging socket 54 with tag 0{0,0} uid -1, pid: 6378, getuid(): 10202
,I/qtaguid ( 6378): Untagging socket 53
,I/System.out( 6378): Thread-596 calls detatch()
,I/NetworkMonitor(11176): type=WIFI subType= reason=null isConnected=true
,D/ResourcesManager(11275): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3527): Killing 10214:com.samsung.android.sdk.samsunglink/u0a42 (adj 13): bgCount ##31
,D/DelayedSyncController(11193): Delaying sync.
,I/ActivityManager( 3527): Killing 10239:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11299): MountEmulatedStorage()
E/Zygote  (11299): v2
I/libpersona(11299): KNOX_SDCARD checking this for 1000
I/libpersona(11299): KNOX_SDCARD not a persona
,I/SELinux (11299): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11299): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11299): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11299 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11299): TimaSignature is unavailable
,D/ActivityThread(11299): Added TimaKeyStore provider
,D/ResourcesManager(11299): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/System.out(11003): P[5]_NetworkDispatch1 calls detatch()
,I/GoogleURLConnFactory( 4473): Using platform SSLCertificateSocketFactory
,I/qtaguid ( 4257): Tagging socket 71 with tag 1000120300000000{268440067,0} uid -1, pid: 4257, getuid(): 10014
,I/DIAGMON_AGENT(11299): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleSync( 4473): onPerformSync() [5005f081]
,I/System.out( 4473): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4473): (HTTPLog)-Static: isShipBuild true
I/System.out( 4473): (HTTPLog)-Thread-307-126627775: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4473): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/DIAGMON_AGENT(11299): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11299): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11299): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11299): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/PeopleSync( 4473): Setting subscription: result=true [5005f081]
,I/PeopleSync( 4473): Starting sync, feed=null [5005f081]
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11323): MountEmulatedStorage()
I/libpersona(11323): KNOX_SDCARD checking this for 10012
E/Zygote  (11323): v2
I/libpersona(11323): KNOX_SDCARD not a persona
,I/SELinux (11323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11323): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11323 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11323): TimaSignature is unavailable
,D/ActivityThread(11323): Added TimaKeyStore provider
,W/BaseAppContext( 4473): Using Auth Proxy for data requests.
,W/BaseAppContext( 4473): Using Auth Proxy for data requests.
,D/ResourcesManager(11323): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,W/DefaultRequestDirector( 6378): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/System.out( 4473): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6378): Untagging socket 54
I/System.out( 6378): Thread-601 calls detatch()
E/Volley  ( 6378): [601] xe.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
I/qtaguid ( 4473): Tagging socket 107 with tag 1000210100000000{268443905,0} uid -1, pid: 4473, getuid(): 10014
,I/qtaguid ( 6378): Tagging socket 54 with tag 0{0,0} uid -1, pid: 6378, getuid(): 10202
,I/qtaguid ( 6378): Tagging socket 61 with tag 0{0,0} uid -1, pid: 6378, getuid(): 10202
W/BaseAppContext( 4473): Using Auth Proxy for data requests.
,I/PeopleSync( 4473): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/ActivityManager( 3527): Killing 10273:com.osp.app.signin/u0a45 (adj 13): bgCount ##31
,I/FOTA_Client(11323): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/System.out( 4257): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4257): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4257): Tagging socket 72 with tag 1000040100000000{268436481,0} uid 10014, pid: 4257, getuid(): 10014
,I/qtaguid ( 4473): Tagging socket 112 with tag 1000210100000000{268443905,0} uid -1, pid: 4473, getuid(): 10014
,I/FOTA_Client(11323): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11323): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,W/DefaultRequestDirector( 6378): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 6378): Untagging socket 54
I/System.out( 6378): Thread-601 calls detatch()
E/Zygote  (11340): MountEmulatedStorage()
E/Zygote  (11340): v2
I/libpersona(11340): KNOX_SDCARD checking this for 10021
E/Volley  ( 6378): [601] xe.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
I/libpersona(11340): KNOX_SDCARD not a persona
,I/SELinux (11340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/YouTube ( 6378): apps.youtube.app.task.YouTubeNetworkTaskService.a:119 Failed to fetch settings
E/YouTube ( 6378): fdv: java.util.concurrent.ExecutionException: wb
E/YouTube ( 6378): 	at fco.a(SourceFile:103)
E/YouTube ( 6378): 	at fcp.c(SourceFile:160)
E/YouTube ( 6378): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:111)
E/YouTube ( 6378): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:49)
E/YouTube ( 6378): 	at emi.run(Unknown Source)
E/YouTube ( 6378): Caused by: java.util.concurrent.ExecutionException: wb
E/YouTube ( 6378): 	at xz.a(SourceFile:117)
E/YouTube ( 6378): 	at xz.get(SourceFile:88)
E/YouTube ( 6378): 	at gky.get(SourceFile:69)
E/YouTube ( 6378): 	at fco.a(SourceFile:99)
E/YouTube ( 6378): 	... 4 more
E/YouTube ( 6378): Caused by: wb
E/YouTube ( 6378): 	at xe.a(SourceFile:141)
E/YouTube ( 6378): 	at gkq.a(SourceFile:49)
E/YouTube ( 6378): 	at wk.run(SourceFile:105)
,I/SELinux (11340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11340): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11340 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10330:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/qtaguid ( 4257): Tagging socket 75 with tag 1000040100000000{268436481,0} uid 10014, pid: 4257, getuid(): 10014
,D/TimaKeyStoreProvider(11340): TimaSignature is unavailable
,D/ActivityThread(11340): Added TimaKeyStore provider
,D/ResourcesManager(11340): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11340): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 21 10:19:19 GMT+01:00 2016
,I/KLMS-2.4.521: (11340): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11340): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11340): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11340): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ChimeraCfgMgr( 4473): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4473): Module APK com.google.android.play.games already loaded
,I/KLMS-2.4.521: (11340): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11340): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11340): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
I/KLMS-2.4.521: (11340): StateImplV2(): networkChangeListener().START
I/KLMS-2.4.521: (11340): NetworkChangeOperations(): uploadRequestLog().START 
,E/Zygote  (11357): MountEmulatedStorage()
E/Zygote  (11357): v2
I/libpersona(11357): KNOX_SDCARD checking this for 10038
I/libpersona(11357): KNOX_SDCARD not a persona
I/SELinux (11357): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11357): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11357): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.4.521: (11340): NetworkChangeOperations(): uploadRequestLog().END 
,I/ActivityManager( 3527): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11357 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11340): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11340): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3527): Killing 10300:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,I/GamesSyncServiceMain( 4473): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 4473): Failed to execute periodic sync, missing client context - aborting
,D/TimaKeyStoreProvider(11357): TimaSignature is unavailable
,D/ActivityThread(11357): Added TimaKeyStore provider
,D/ResourcesManager(11357): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11357): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11378): MountEmulatedStorage()
I/libpersona(11378): KNOX_SDCARD checking this for 1000
E/Zygote  (11378): v2
I/libpersona(11378): KNOX_SDCARD not a persona
,I/SELinux (11378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11378): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11378 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10349:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11378): TimaSignature is unavailable
,D/ActivityThread(11378): Added TimaKeyStore provider
,D/ResourcesManager(11378): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11400): MountEmulatedStorage()
I/libpersona(11400): KNOX_SDCARD checking this for 10039
E/Zygote  (11400): v2
I/libpersona(11400): KNOX_SDCARD not a persona
,I/SELinux (11400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11400): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11400 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10366:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11400): TimaSignature is unavailable
,D/ActivityThread(11400): Added TimaKeyStore provider
,D/ResourcesManager(11400): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(11400): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11400): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService(11400): PushLog.txt file is not deleted.
D/SPPClientService(11400): PushLog.txt file is not deleted.
D/SPPClientService(11400): ============PushLog. stop!
,E/SPPClientService(11400): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11418): MountEmulatedStorage()
I/libpersona(11418): KNOX_SDCARD checking this for 10045
E/Zygote  (11418): v2
I/libpersona(11418): KNOX_SDCARD not a persona
,I/SELinux (11418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11418): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=11418 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10383:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11418): TimaSignature is unavailable
,D/ActivityThread(11418): Added TimaKeyStore provider
,W/PhenotypeConfigurator( 4257): Server returned 404
,D/ResourcesManager(11418): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (11418): [SSP] onCreated
,I/SA      (11418): [TPM] There is no property file
,I/SA      (11418): [SCU] isHaveSA() - false
,I/SA      (11418): [TPM] getModelProperty : null
I/SA      (11418): [TPM] getCSCProperty : null
,I/SA      (11418): [DM] init START
,I/SA      (11418): [DM] This device is not a Vodafone
,I/SA      (11418): checkReactivationActive for LOLLIPOP
,I/SA      (11418): checkReactivationActive for reactiveActive
I/SA      (11418): setSupportRL : true
,I/SA      (11418): [SCU] isHaveSA() - false
I/SA      (11418): support phone number id : false
,I/SA      (11418): [DM] init END
I/SA      (11418): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11418): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11418): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11418): [SLFUCHKMGR] constructor called
,I/SA      (11418): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11418): [OR] == isSIMCardReady false ==
,I/SA      (11418): [SCU] == networkStateCheck == true
I/SA      (11418): [DM] getCountryCodeFromCSC : PL
I/SA      (11418): isChinaCountryCode : false
I/SA      (11418): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11418): [OR] == networkStateCheck true ==
,I/SA      (11418): [OR] GetMyCountryZoneTask
,I/SA      (11418): [OR] onReceive END
,I/ActivityManager( 3527): Killing 10414:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,V/DownloadManager( 3718): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11418): [SRS] prepareGetMyCountryZone
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/SA      (11418): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11418): [SSP] query invoked
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 45471(2MB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 48MB/64MB, paused 2.076ms total 97.826ms
,I/art     ( 3527): WaitForGcToComplete blocked for 41.691ms for cause HeapTrim
,I/SA      (11418): [TPMU] GetMccFromDB : null
,I/SA      (11418): [SCU] getMccFromPreferece mcc = 260
I/SA      (11418): [TPM] isNoProxy(default) : true
,E/Zygote  (11442): MountEmulatedStorage()
E/Zygote  (11442): v2
I/libpersona(11442): KNOX_SDCARD checking this for 10067
I/libpersona(11442): KNOX_SDCARD not a persona
,I/SELinux (11442): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11442): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11442): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11442 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11442): TimaSignature is unavailable
,D/ActivityThread(11442): Added TimaKeyStore provider
,D/ResourcesManager(11442): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/VacuumService( 4257): Vacuum at: now=1453367960429 tag=VacuumService
,I/System.out( 4473): (HTTPLog)-Static: isSBSettingEnabled false
,I/sCloudBackupApp(11442): sCloudBackupApp Version Info : 4.00.4.KK_APP
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4473): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/SCloudBackupReceiver(11442): Other Intent
,I/qtaguid ( 4473): Tagging socket 113 with tag 1000150000000000{268440832,0} uid 10014, pid: 4473, getuid(): 10014
,I/ActivityManager( 3527): Killing 10489:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/accuweather( 5154): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 18
,D/accuweather( 5154): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5154): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5154): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5154): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5154): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5154): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/jxcore-log(10777): Test app app.js loaded
I/jxcore-log(10777): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10777): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(10777): BLE advertisement is supported
I/jxcore-log(10777): 
,E/Zygote  (11464): MountEmulatedStorage()
I/libpersona(11464): KNOX_SDCARD checking this for 1000
E/Zygote  (11464): v2
I/libpersona(11464): KNOX_SDCARD not a persona
,I/SELinux (11464): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11464): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11464): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11464 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/chromium(10777): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TimaKeyStoreProvider(11464): TimaSignature is unavailable
,D/ActivityThread(11464): Added TimaKeyStore provider
,D/ResourcesManager(11464): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11464): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(11464): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(11464): premStatus:2
,I/KnoxUsageLogPro(11464): isEulaShown : false
I/KnoxUsageLogPro(11464): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(10883): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(10883): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10883): stopCheckCategoryVersion
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11479): MountEmulatedStorage()
E/Zygote  (11479): v2
I/libpersona(11479): KNOX_SDCARD checking this for 10136
I/libpersona(11479): KNOX_SDCARD not a persona
,I/SELinux (11479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11479): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11479 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10506:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8745(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 276us total 10.191ms
,D/TimaKeyStoreProvider(11479): TimaSignature is unavailable
,D/ActivityThread(11479): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 254us total 8.351ms
,D/ResourcesManager(11479): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 259us total 8.032ms
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11479): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11479): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/qtaguid ( 4473): Tagging socket 116 with tag 1000150000000000{268440832,0} uid 10014, pid: 4473, getuid(): 10014
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11479): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11479): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(11479): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11479): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/SA      (11418): [RC New] Execute method=[GET] start
,I/LibraryLoader(11479): Loading: webviewchromium
,I/LibraryLoader(11479): Time to load native libraries: 3 ms (timestamps 2501-2504)
I/LibraryLoader(11479): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11479): Binding Chromium to main looper Looper (main, tid 1) {16fc64e1}
,I/LibraryLoader(11479): Expected native library version number "",actual native library version number ""
,I/chromium(11479): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/SA      (11418): [RC New] Security=[true]
,I/System.out(11418): Thread-1535(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11418): Thread-1535(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11418): Thread-1535(ApacheHTTPLog):isShipBuild true
I/System.out(11418): Thread-1535(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10045
,I/BrowserStartupController(11479): Initializing chromium process, renderers=0
,W/art     (11479): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11479): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/AudioManagerAndroid(11479): Requires BLUETOOTH permission
,I/chromium(11479): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium(11479): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(11479): Starting up...
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11547): MountEmulatedStorage()
E/Zygote  (11547): v2
I/libpersona(11547): KNOX_SDCARD checking this for 10147
I/libpersona(11547): KNOX_SDCARD not a persona
,I/SELinux (11547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=11547 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11547): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 10524:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11547): TimaSignature is unavailable
,D/ActivityThread(11547): Added TimaKeyStore provider
,D/ResourcesManager(11547): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(11547): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/WifiStateMachine( 3527): updateConfiguredNetworkExpiration - currTime: 1453367960901
D/WifiStateMachine( 3527): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11575): MountEmulatedStorage()
E/Zygote  (11575): v2
I/libpersona(11575): KNOX_SDCARD checking this for 10150
I/libpersona(11575): KNOX_SDCARD not a persona
,I/SELinux (11575): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/qtaguid ( 4473): Untagging socket 113
,I/SELinux (11575): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11575): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=11575 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11575): TimaSignature is unavailable
,D/ActivityThread(11575): Added TimaKeyStore provider
,D/ResourcesManager(11575): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(11575): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11575): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11575): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/dhcpcd  (11091): wlan0: sending IPv6 Router Solicitation
,I/System.out( 4473): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4473): Tagging socket 113 with tag 1000190000000000{268441856,0} uid 10014, pid: 4473, getuid(): 10014
,D/QuickConnect(11575): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(11575): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(11575): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,I/ActivityManager( 3527): Killing 10561:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/qtaguid ( 4473): Untagging socket 113
,I/qtaguid ( 4473): Untagging socket 107
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10186
,I/PhenotypeConfigurator( 4257): Scheduling Phenotype for one-off execution 7049 seconds from now (1453367961122)
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/GetConfigurationSnapshotOperation( 4257): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/Zygote  (11601): MountEmulatedStorage()
E/Zygote  (11601): v2
I/libpersona(11601): KNOX_SDCARD checking this for 10123
I/libpersona(11601): KNOX_SDCARD not a persona
,I/SELinux (11601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=11601 uid=10123 gids={50123, 9997, 3003} abi=armeabi-v7a
,I/SELinux (11601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11601): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/iu.SyncManager( 4473): SYNC; picasa accounts
D/TimaKeyStoreProvider(11601): TimaSignature is unavailable
,D/ActivityThread(11601): Added TimaKeyStore provider
,I/PhenotypeFlagCommitter( 4257): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4257): Using platform SSLCertificateSocketFactory
,D/NetworkLogImpl( 4473): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4473): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/ResourcesManager(11601): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/iu.UploadsManager( 4473): num queued entries: 0
,I/iu.UploadsManager( 4473): num updated entries: 0
,I/iu.SyncManager( 4473): NEXT; no task
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11618): MountEmulatedStorage()
E/Zygote  (11618): v2
I/libpersona(11618): KNOX_SDCARD checking this for 10013
I/libpersona(11618): KNOX_SDCARD not a persona
,I/SELinux (11618): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11618): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=11618 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11618): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 10578:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,D/TimaKeyStoreProvider(11618): TimaSignature is unavailable
,D/ActivityThread(11618): Added TimaKeyStore provider
,W/IdleConnectionHandler(11003): Removing a connection that never existed!
,W/AbstractGoogleClient(11601): Application name is not set. Call Builder#setApplicationName.
,D/btif_config_util(10848): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/ResourcesManager(11618): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11637): MountEmulatedStorage()
E/Zygote  (11637): v2
I/libpersona(11637): KNOX_SDCARD checking this for 10047
I/libpersona(11637): KNOX_SDCARD not a persona
,I/SELinux (11637): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11637): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11637): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=11637 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/System.out( 4473): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4473): Tagging socket 113 with tag 1000150000000000{268440832,0} uid 10014, pid: 4473, getuid(): 10014
,D/LocationManagerService( 3527): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/TimaKeyStoreProvider(11637): TimaSignature is unavailable
,D/ActivityThread(11637): Added TimaKeyStore provider
,D/ResourcesManager(11637): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager(11637): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/WaitQueueForNetworkActivate(11618): notifyNetworkActivated
,I/CalendarProvider2(11637): CalendarProvider2.onCreate() called
,I/System.out( 4257): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,W/ContextImpl(11618): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3527): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (11618): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(11618): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(11618): exit::IDLE
D/InitializeManagerStateMachine(11618): entry::NETWORK_CHECK
,I/FOTA_Client(11323): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/InitializeManagerStateMachine(11618): execute::NETWORK_CHECK:NETWORK_STATE_OK
I/splitIntent( 3527): Split this intent : android.intent.action.TIME_SET !!   mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=17 divideNum= 5 r.nextReceiver= 1 receivers.size=23
D/InitializeManagerStateMachine(11618): exit::NETWORK_CHECK
I/splitIntent( 3527): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
D/InitializeManagerStateMachine(11618): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11618): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(11618): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11618): entry::SUCCESS
D/hcjo    (11618): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (11618): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client(11323): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,E/Zygote  (11660): MountEmulatedStorage()
I/libpersona(11660): KNOX_SDCARD checking this for 10052
E/Zygote  (11660): v2
I/libpersona(11660): KNOX_SDCARD not a persona
,I/SELinux (11660): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11660): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11660): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=11660 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/hcjo    (11618): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (11618): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/KLMS-2.4.521: (11340): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Jan 21 10:19:21 GMT+01:00 2016
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/InitializeManagerStateMachine(11618): exit::SUCCESS
D/InitializeManagerStateMachine(11618): entry::IDLE
,D/TimaKeyStoreProvider(11660): TimaSignature is unavailable
,D/ActivityThread(11660): Added TimaKeyStore provider
,E/Zygote  (11675): MountEmulatedStorage()
E/Zygote  (11675): v2
I/libpersona(11675): KNOX_SDCARD checking this for 10164
I/libpersona(11675): KNOX_SDCARD not a persona
,I/SELinux (11675): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11675): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=11675 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (11675): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11340): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11340): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11340): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/daemonapp( 3775): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 3775): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11660): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11675): TimaSignature is unavailable
D/ActivityThread(11675): Added TimaKeyStore provider
,W/ResourcesManager(11660): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(11660): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11660): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11660): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11660): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/KLMS-2.4.521: (11340): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
W/ResourcesManager(11660): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (11340): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/KLMS-2.4.521: (11340): KLMSIntentService(): TIME_CHANGED
I/KLMS-2.4.521: (11340): StateImplV2(): dateTimeChanged().START : Thu Jan 21 10:19:21 GMT+01:00 2016
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 3775): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 3775): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3775): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
D/comsamsunglog( 3775): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3775): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 3775): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/Zygote  (11691): MountEmulatedStorage()
,E/Zygote  (11691): v2
I/libpersona(11691): KNOX_SDCARD checking this for 10036
I/libpersona(11691): KNOX_SDCARD not a persona
I/KLMS-2.4.521: (11340): StateImplV2(): dateTimeChanged().END
,I/SELinux (11691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/qtaguid ( 4473): Untagging socket 113
D/daemonapp( 3775): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/SELinux (11691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/com.cigna.mobile.coach.CoachBroadcastReceiver: pid=11691 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/SELinux (11691): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/daemonapp( 3775): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3775): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3775): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.4.521: (11340): KLMSIntentService(): onDestroy()
,E/daemonapp( 3775): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/TimaKeyStoreProvider(11691): TimaSignature is unavailable
,D/ActivityThread(11691): Added TimaKeyStore provider
,I/ActivityManager( 3527): Killing 9867:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/ResourcesManager(11675): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11675): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11675): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11675): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11675): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11691): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/comdaemonstockapp( 3775): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 3775): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/Mms/MmsApp(11660): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(11660): init before art
,D/Mms/ArtClassLoader(11660): init [DONE] art
,D/Mms/TelephonyPermission(11660): start operation mode monitor
,D/ResourcesManager(11660): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11660): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission(11660): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(11660): isDefault true
D/Mms/MmsApp(11660): onCreate() com.android.mms
,I/System.out( 4257): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4257): Tagging socket 84 with tag 1000120100000000{268440065,0} uid -1, pid: 4257, getuid(): 10014
,I/CheckinService( 4473): Checkin interval check for package: unspecified last checkin: 1453082886478 min interval config: 0 actual interval: 285074991
,I/PeopleSync( 4473): Sync finished, successful=true, took 1585ms
,D/Mms/MmsApp(11660): [start]    initCountryIso consume time = 35.588084
,D/CountryDetector( 3527): The first listener is added
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/MmsApp(11660): [end]    initCountryIso consume time = 10.0315
D/Mms/MmsConfig(11660): [start]    MmsConfig.init() consume time = 0.064791
,D/Mms/MmsConfig(11660): before partial update
,D/Mms/MmsConfig(11660): Load Resize quality : 80
,D/Mms/MmsConfig(11660):  enable multiwindow = true
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/Mms/MessageUtils(11660): setCountryDetector : update country detector info 
E/Mms/MessageUtils(11660): updateCountryIso : update country iso info 
,I/PeopleContactsSync( 4473): CP2 sync start [5005f081]
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SecurityLogAgent(10914): KnoxConfiguration : Current State = 0
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
I/PeopleContactsSync( 4473): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/Mms/PackageInfo(11660): com.sec.imsservice is not installed
D/Mms/MmsConfig(11660): [end]    init() consume time = 33.772292
D/Mms/Contact(11660): [start]    init() consume time = 0.400625
,I/PeopleContactsSync( 4473): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,D/SecurityLogAgent(10914): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent(10914): StateMachine : Initialized
,D/SecurityLogAgent(10914): StateMachine : Changed Current State = 0
D/SecurityLogAgent(10914): StateMachine : Current State = 0
,I/System.out( 4257): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4257): Tagging socket 72 with tag 1000040100000000{268436481,0} uid 10014, pid: 4257, getuid(): 10014
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 3975): query,matched:13, calling pid = 11660
,D/Mms/Contact(11660): [end]    init consume time = 12.909125
,D/Mms/DraftCache(11660): [start]    rebuildCache consume time = 0.888875
,D/TP/MmsSmsProvider( 3975): match 13:Elapsed time : 2.891 ms
,D/TP/MmsSmsProvider( 3975): query,matched:12, calling pid = 11660
,D/TP/MmsSmsProvider( 3975): match 12:Elapsed time : 1.280 ms
,E/Zygote  (11731): MountEmulatedStorage()
E/Zygote  (11731): v2
I/libpersona(11731): KNOX_SDCARD checking this for 10019
I/libpersona(11731): KNOX_SDCARD not a persona
,I/SELinux (11731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=11731 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (11731): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11731): TimaSignature is unavailable
,D/ActivityThread(11731): Added TimaKeyStore provider
E/Zygote  (11746): MountEmulatedStorage()
I/libpersona(11746): KNOX_SDCARD checking this for 10191
E/Zygote  (11746): v2
I/libpersona(11746): KNOX_SDCARD not a persona
,I/SELinux (11746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=11746 uid=10191 gids={50191, 9997} abi=armeabi-v7a
E/SELinux (11746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/TelephonyUtils(11660): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(11660): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11660): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11660): auto download without roaming -> true
D/Mms/DownloadManager(11660): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,E/Mms/TelephonyUtils(11660): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(11660): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(11660): roaming -> false (slotId = 1)
D/Mms/DownloadManager(11660): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(11660): auto download without roaming -> true
D/Mms/DownloadManager(11660): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(11660): auto download during roaming secondary -> false
D/Mms/DownloadManager(11660): mAutoDownload ------> true
,D/ResourcesManager(11731): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/Mms/DraftCache(11660): [end]    rebuildCache consume time = 36.939375
D/TimaKeyStoreProvider(11746): TimaSignature is unavailable
,D/ActivityThread(11746): Added TimaKeyStore provider
,D/Mms/Conversation(11660): [start]    init() consume time = 2.873958
,D/Mms/MmsApp(11660): [end]    onCreate() consume time = 2.0215
,D/TP/MmsSmsProvider( 3975): deleteConversation threadId: 9223372036854775807
,D/Mms/DownloadManager(11660): Service state changed: Bundle[mParcelledData.dataSize=692]
D/Mms/DownloadManager(11660): roaming ------> false, mSimSlot = 0
,D/TP/MmsSmsProvider( 3975): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,D/Mms/TelephonyUtils(11660): getSubId from simSlot 0, return Value = -1
D/Mms/DownloadManager(11660): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11660): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11660): auto download without roaming -> true
D/Mms/DownloadManager(11660): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(11660): mAutoDownload ------> true
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 3975): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3975): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3975): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3975): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3975): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3975): (284) automatic index on im_threads(normal_thread_id)
,D/ResourcesManager(11746): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,W/ResourcesManager(11746): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 3975): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 3975): need read changed broadcast:false
,I/qtaguid ( 4257): Tagging socket 89 with tag 1000120100000000{268440065,0} uid -1, pid: 4257, getuid(): 10014
,E/Zygote  (11762): MountEmulatedStorage()
E/Zygote  (11762): v2
I/libpersona(11762): KNOX_SDCARD checking this for 10069
I/libpersona(11762): KNOX_SDCARD not a persona
,I/SELinux (11762): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11762): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11762): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=11762 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10688:com.android.vending/u0a31 (adj 13): bgCount ##31
,I/ActivityManager( 3527): Killing 10105:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/Mms/Conversation(11660): [end]    init consume time = 23.84875
,D/Mms/MessagingNotification(11660): [start]    init() consume time = 1.902417
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 434us total 11.568ms
,D/TimaKeyStoreProvider(11762): TimaSignature is unavailable
,D/ActivityThread(11762): Added TimaKeyStore provider
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 391us total 8.463ms
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 261us total 7.985ms
,D/com.sec.android.service.health.keyManager.KeyManager(11691): Current encrypted state : -1
,I/SecSQLiteOpenHelper(11691): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11691): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11691): Open platform.db in secure mode
D/SecSQLiteDatabase(11691): Android Version: 5.0.1
D/SecSQLiteDatabase(11691): Load library secsqlite.so for Android 5.0.1
,I/SecSQLiteDatabase(11691): openSecureDatabase...
,I/SecSQLiteDatabase(11691): private openSecureDatabase...
I/SecSQLiteConnectionPool(11691): OpenSecure
I/SecSQLiteConnectionPool(11691): OpenSecure with password
I/SecSQLiteConnectionPool(11691): openSecureConnectionLocked
,I/SecSQLiteDatabase(11691): ...private openSecureDatabase
I/SecSQLiteDatabase(11691): ...openSecureDatabase
,D/ResourcesManager( 4257): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/SQLiteLog(11691): (26) statement aborts at 0: [PRAGMA user_version;] file is encrypted or is not a database
,E/SecDefaultDatabaseErrorHandler(11691): Corruption reported by sqlite on database: /data/data/com.sec.android.app.shealth/databases/platform.db
E/SecDefaultDatabaseErrorHandler(11691): backup the database file: /data/data/com.sec.android.app.shealth/databases/platform.db
D/SecSQLiteOpenHelper(11691): ...getDatabaseLocked(b,b,pwd)
,I/GCM     ( 4257): GCM config loaded
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 26477(1564KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.161ms total 77.978ms
,I/ActivityManager( 3527): Killing 10199:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/Mms/MessagingNotification(11660): [end]    init consume time = 89.938792
,D/Mms/SpamFilter(11660): [start]    SpamFilter fill() begin consume time = 1.270208
,D/Mms/Synchronizer(11660): [start]    doSync consume time = 0.655834
,D/TP/MmsSmsProvider( 3975): query,matched:400, calling pid = 11660
,D/TP/MmsSmsProvider( 3975): query,matched:0, calling pid = 11660
V/TP/MmsSmsProvider( 3975): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3975): match 0:Elapsed time : 0.599 ms
,D/ResourcesManager(11762): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
I/PeopleContactsSync( 4473): CP2 cleanup done, kept= duration=179 ms
,I/PeopleContactsSync( 4473): ===CP2 sync finished, success=true, time=185,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/SA      (11418): [RC New] [v2liruge] api execute + 944
I/SA      (11418): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11418): AsyncTask #1 calls detatch()
,D/Mms/SpamFilter(11660): [end]    SpamFilter fill() finished consume time = 11.684166
I/SecureStorage(11731): [INFO]: SPID(0x00000000)Processing data
,D/TP/MmsSmsProvider( 3975): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 3975): syncDBData start
,V/TP/MmsSmsProvider( 3975): syncDBData sms end
,V/TP/MmsSmsProvider( 3975): syncDBData mms end
I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Credentials: uid 10019, gid 10019, pid 11731
I/SecureStorage( 2915): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,V/TP/MmsSmsProvider( 3975): syncDBData end
D/Mms/Synchronizer(11660): [end]    doSync consume time = 5.042209
,I/SA      (11418): [TPMU] getNetworkMcc : 
,I/SA      (11418): [SCU] saveMccToPreferece Start
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11786): MountEmulatedStorage()
E/Zygote  (11786): v2
I/libpersona(11786): KNOX_SDCARD checking this for 10082
I/libpersona(11786): KNOX_SDCARD not a persona
,I/SELinux (11786): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11786): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11786): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/SA      (11418): [SCU] RegionMCC : 260
I/SA      (11418): [SSP] query invoked
I/ActivityManager( 3527): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=11786 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,I/SA      (11418): [TPMU] GetMccFromDB : null
I/SA      (11418): [SCU] getMccFromPreferece mcc = 260
I/SA      (11418): [SCU] saveMccToPreferece End
,I/SA      (11418): [RC New] executeRequest [v2liruge] end. 990
I/SA      (11418): [RC New] Execute end
I/SA      (11418): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11418): [OR] GetMyCountryZoneTask Success
,D/LocationManagerService( 3527): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ActivityManager( 3527): Killing 10542:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,I/PeopleSync( 4473): ***Sync finished***, duration: 2004 [5005f081]
,D/TimaKeyStoreProvider(11786): TimaSignature is unavailable
,D/ActivityThread(11786): Added TimaKeyStore provider
,I/ActivityManager( 3527): Killing 11069:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31
,I/System.out( 4257): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4257): Tagging socket 84 with tag 1000120100000000{268440065,0} uid -1, pid: 4257, getuid(): 10014
,I/ Time Manager (11762): Time Difference not stored. TIME_DIFFERENCE
,D/ResourcesManager(11786): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/accuweather( 5154): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 5154): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider(11786): onCreate
D/BadgeProvider(11786): DatabaseHelper
,I/WifiStateMachine( 3527): REQUEST_POWER_SAVE_ON
,E/Zygote  (11805): MountEmulatedStorage()
E/Zygote  (11805): v2
I/libpersona(11805): KNOX_SDCARD checking this for 10094
I/libpersona(11805): KNOX_SDCARD not a persona
,I/SELinux (11805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=11805 uid=10094 gids={50094, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11805): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PackageManager( 3527): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/TimaKeyStoreProvider(11805): TimaSignature is unavailable
,D/ActivityThread(11805): Added TimaKeyStore provider
,I/System.out(11601): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(11601): (HTTPLog)-Static: isShipBuild true
I/System.out(11601): (HTTPLog)-Thread-1561-70008573: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(11601): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10123
,D/LocationManagerService( 3527): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/Mms/MessagingNotification(11660): checkBadgeCount unreadCount=0 badgeCount=0
I/System.out(11601): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (11601): Tagging socket 28 with tag 1100000000000000{285212672,0} uid -1, pid: 11601, getuid(): 10123
,D/TP/SmsProvider( 3975): query,matched:26, calling pid = 11660
,D/ResourcesManager(11805): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,W/ResourcesManager(11805): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(11805): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11805): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11805): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11805): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11805): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,E/WifiStateMachine( 3527): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/System.out( 4257): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4257): Tagging socket 84 with tag 1000120100000000{268440065,0} uid -1, pid: 4257, getuid(): 10014
,I/SurfaceFlinger( 2855): id=12 Removed Uoast (8/9)
,I/SurfaceFlinger( 2855): id=12 Removed Uoast (-2/9)
,D/OpenGLRenderer( 5892): Render dirty regions requested: true
,D/PowerManagerService( 3527): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3527) eventTime = 143610
,D/PowerManagerService( 3527): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3527 (0x0)
D/PowerManagerService( 3527): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3527, ws=WorkSource{10060}) (elapsedTime=3483)
,I/art     ( 3975): Explicit concurrent mark sweep GC freed 63385(3MB) AllocSpace objects, 15(240KB) LOS objects, 36% free, 27MB/43MB, paused 653us total 34.287ms
,D/TP/SmsProvider( 3975): match 26:Elapsed time : 39.058 ms
,I/SurfaceFlinger( 2855): id=13 createSurf (1x1),1 flag=4, Uoast
,D/TP/MmsSmsProvider( 3975): query,matched:6, calling pid = 11660
,D/PowerManagerService( 3527): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3527
,D/TP/MmsSmsProvider( 3975): match 6:Elapsed time : 3.701 ms
,I/Mms/ReservationManager(11660): ReservationManager()
,I/Mms/ReservationManager(11660): resetAfterConnected()
,D/TP/MmsSmsProvider( 3975): query,matched:7, calling pid = 11660
,I/OpenGLRenderer( 5892): Initialized EGL, version 1.4
,D/TP/MmsSmsProvider( 3975): match 7:Elapsed time : 1.771 ms
,I/OpenGLRenderer( 5892): HWUI protection enabled for context ,  &this =0xaf822088 ,&mEglDisplay = 1 , &mEglConfig = -1350180592 
,D/OpenGLRenderer( 5892): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 5892): Enabling debug mode 0
,D/mali_winsys( 5892): new_window_surface returns 0x3000,  [616x201]-format:1
,I/Mms/ReservationManager(11660): getReservedSendMessageCount(): retMessageCount=0
,D/SettingsProvider( 3527): name = next_alarm_formatted
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10094
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11839): MountEmulatedStorage()
I/libpersona(11839): KNOX_SDCARD checking this for 10028
E/Zygote  (11839): v2
I/libpersona(11839): KNOX_SDCARD not a persona
,I/SELinux (11839): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11839): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11839): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=11839 uid=10028 gids={50028, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11839): TimaSignature is unavailable
,D/ActivityThread(11839): Added TimaKeyStore provider
,D/LocationManagerService( 3527): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ActivityManager( 3527): Killing 7854:com.android.settings/1000 (adj 13): bgCount ##31
,D/ResourcesManager(11839): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,W/ResourcesManager(11839): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/BaseAppContext( 4257): Using Auth Proxy for data requests.
,E/BaseAppContext( 4257): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/qtaguid (11601): Untagging socket 28
,E/Zygote  (11861): MountEmulatedStorage()
E/Zygote  (11861): v2
I/libpersona(11861): KNOX_SDCARD checking this for 10106
I/libpersona(11861): KNOX_SDCARD not a persona
,I/SELinux (11861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11861): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11861 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10466:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
,I/OMACP   (11839): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,I/System.out( 4257): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4257): Tagging socket 84 with tag 1000120100000000{268440065,0} uid -1, pid: 4257, getuid(): 10014
,D/TimaKeyStoreProvider(11861): TimaSignature is unavailable
,D/Mms/Omacp(11660): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/ActivityThread(11861): Added TimaKeyStore provider
,I/System.out( 4257): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4257): Tagging socket 72 with tag 1000040100000000{268436481,0} uid 10014, pid: 4257, getuid(): 10014
,I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,D/Mms/ArtClassLoader(11660): init before art
D/Mms/ArtClassLoader(11660): init [DONE] art
I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,D/Mms/PerformanceUtils(11660): link cahcing start
I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,D/ResourcesManager(11861): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   (11839): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/WifiService( 3527): Client connection lost with reason: 4
,D/elm:14491(11861): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491(11861): ELMEngine.ELMEngine( context ).
,D/Mms/PerformanceUtils(11660): link cahcing done
D/elm:14491(11861): MDMBridge.setEnterpriseBridge()
,D/elm:14491(11861): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14491(11861): ElmAgentService : onCreate()
,D/elm:14491(11861): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/elm:14491(11861): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14491(11861): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491(11861): ModuleBase.ModifySetAlarm()
D/elm:14491(11861): MDMBridge.getInstance()
D/elm:14491(11861): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (11882): MountEmulatedStorage()
I/libpersona(11882): KNOX_SDCARD checking this for 10163
E/Zygote  (11882): v2
I/libpersona(11882): KNOX_SDCARD not a persona
,I/SELinux (11882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=11882 uid=10163 gids={50163, 9997} abi=armeabi-v7a
,E/SELinux (11882): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/elm:14491(11861): ElmAgentService : onDestroy().
,D/LocationManagerService( 3527): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ActivityManager( 3527): Killing 11003:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
,I/System.out( 4257): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4257): Tagging socket 84 with tag 1000120100000000{268440065,0} uid -1, pid: 4257, getuid(): 10014
,D/TimaKeyStoreProvider(11882): TimaSignature is unavailable
,D/ActivityThread(11882): Added TimaKeyStore provider
,D/CalendarSyncAdapter(11601): Found 0 events marked dirty & lastSynced
,D/ResourcesManager(11882): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(11882): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11882): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/ActivityManager( 3527): Killing 11154:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3527): Killing 11176:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11902): MountEmulatedStorage()
E/Zygote  (11902): v2
I/libpersona(11902): KNOX_SDCARD checking this for 10122
I/libpersona(11902): KNOX_SDCARD not a persona
,I/SELinux (11902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=11902 uid=10122 gids={50122, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11902): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11902): TimaSignature is unavailable
,D/ActivityThread(11902): Added TimaKeyStore provider
,D/ResourcesManager(11902): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/System.out( 4257): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4257): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4257): Tagging socket 80 with tag 1000060200000000{268436994,0} uid 10014, pid: 4257, getuid(): 10014
,W/ActivityManager( 3527): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread(11902): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 3527): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/qtaguid ( 4257): Tagging socket 92 with tag 1000060200000000{268436994,0} uid 10014, pid: 4257, getuid(): 10014
,I/Gmail   (11902): getAccountsCursor
,W/ActivityManager( 3527): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 3527): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 3527): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   (11902): Observing account changes for notifications
,W/GAV2    (11902): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 3527): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 3527): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/Gmail   (11902): Sync started for account: account:61035162
,E/Gmail   (11902): Error finding the version of the Email provider.....
E/Gmail   (11902): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   (11902): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   (11902): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   (11902): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   (11902): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   (11902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   (11902): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   (11902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration(11902): We do not support migrating this version of the Email provider.
,I/Gmail   (11902): getAccountsCursor
,E/SQLiteLog(11902): (283) recovered 59 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (11902): notifyAccountChanged
,I/Gmail   (11902): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   (11902): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     ( 4473): Explicit concurrent mark sweep GC freed 42134(2MB) AllocSpace objects, 42(983KB) LOS objects, 33% free, 31MB/47MB, paused 702us total 27.089ms
,I/Gmail   (11902): notifyAccountChanged
,I/Gmail   (11902): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/CalendarProvider2(11637): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/Gmail   (11902): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/SecureStorage( 2915): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
,D/ResourcesManager( 4473): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/ActivityManager( 3527): Killing 11210:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,I/Gmail   (11902): getAccountsCursor
,I/Gmail   (11902): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15403, normalSync: true
,D/ResourcesManager(11902): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11902): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11902): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 4257): Explicit concurrent mark sweep GC freed 130285(7MB) AllocSpace objects, 80(3MB) LOS objects, 34% free, 30MB/46MB, paused 889us total 57.446ms
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (11902): getAccountsCursor
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp (11902): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11902): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11902): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@135cb34a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11902): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(11902): Thread-1650(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11902): Thread-1650(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11902): Thread-1650(ApacheHTTPLog):isShipBuild true
I/System.out(11902): Thread-1650(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10122
,I/qtaguid (11902): Tagging socket 59 with tag 1010000000000000{269484032,0} uid -1, pid: 11902, getuid(): 10122
,I/qtaguid (11902): Tagging socket 63 with tag 1010000000000000{269484032,0} uid -1, pid: 11902, getuid(): 10122
,I/qtaguid ( 4257): Untagging socket 80
,I/GCoreUlr( 4257): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 4257): DispatchingService.onCreate()
,I/GCoreUlr( 4257): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 4257): Unbound from all location providers
I/GCoreUlr( 4257): Place inference reporting - stopped
,I/GCoreUlr( 4257): DispatchingService.onDestroy()
I/GCoreUlr( 4257): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 4257): Unbound from all location providers
I/GCoreUlr( 4257): Place inference reporting - stopped
,I/SecureStorage(11731): [INFO]: SPID(0x00000006)Processing data has been completed
,I/SecureStorage(11731): [INFO]: SPID(0x00000006)Skip using SecureStorageExceptionJNI
,I/SecSQLiteOpenHelper(11691): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11691): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11691): Open platform.db in secure mode
I/SecSQLiteDatabase(11691): openSecureDatabase...
I/SecSQLiteDatabase(11691): private openSecureDatabase...
I/SecSQLiteConnectionPool(11691): OpenSecure
I/SecSQLiteConnectionPool(11691): OpenSecure with password
I/SecSQLiteConnectionPool(11691): openSecureConnectionLocked
,I/SecSQLiteDatabase(11691): ...private openSecureDatabase
I/SecSQLiteDatabase(11691): ...openSecureDatabase
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4216, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:-516, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1358
D/BatteryService( 3527): stay LED for fully charged
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,I/SecSQLiteOpenHelper(11691): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11691): ...getDatabaseLocked(b,b,pwd)
,I/System.out( 4257): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4257): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4257): Tagging socket 55 with tag 1000040100000000{268436481,0} uid 10014, pid: 4257, getuid(): 10014
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/-----SIC-----(11691): ------------------skip TGH
,I/SecSQLiteOpenHelper(11691): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11691): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11691): Open platform.db in secure mode
I/SecSQLiteDatabase(11691): openSecureDatabase...
I/SecSQLiteDatabase(11691): private openSecureDatabase...
I/SecSQLiteConnectionPool(11691): OpenSecure
I/SecSQLiteConnectionPool(11691): OpenSecure with password
I/SecSQLiteConnectionPool(11691): openSecureConnectionLocked
I/SecSQLiteDatabase(11691): ...private openSecureDatabase
I/SecSQLiteDatabase(11691): ...openSecureDatabase
,I/SecSQLiteOpenHelper(11691): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11691): ...getDatabaseLocked(b,b,pwd)
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11691): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11691): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer(11691): decode(33, 20909908, 4230)
,V/MediaPlayerService( 2860): decode(28, 20909908, 4230)
,V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
,V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20909908, 4230)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
,V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
,I/qtaguid ( 4257): Tagging socket 71 with tag 1000040100000000{268436481,0} uid 10014, pid: 4257, getuid(): 10014
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2860): wait for playback complete
V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/SO_AGENT(11357): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/MediaPlayer(11691): decode(35, 20763080, 15440)
V/MediaPlayerService( 2860): decode(28, 20763080, 15440)
,V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
I/SA      (11418): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
,V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20763080, 15440)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
V/MediaPlayerService( 2860): wait for playback complete
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/AdaptiveEventManager( 3694): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3694): M updateContainers()
D/AdaptiveEventContainerSmall( 3694): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3694): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3694): pedoEvent == null
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
I/ActivityManager( 3527): Killing 11275:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache( 2860): notify(0xaf426100, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
D/AdaptiveEventManager( 3694): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3694): M updateContainers()
D/AdaptiveEventContainerSmall( 3694): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3694): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3694): pedoEvent == null
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/AudioPlayer( 2860): reset out
,V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/ActivityManager( 3527): Killing 11299:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/MediaPlayer(11691): decode(36, 20807608, 9226)
V/MediaPlayerService( 2860): decode(28, 20807608, 9226)
,V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20807608, 9226)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
W/System.err(10315): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
,W/System.err(10315): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err(10315): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err(10315): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err(10315): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err(10315): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
W/System.err(10315): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
W/System.err(10315): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
W/System.err(10315): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10315): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10315): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10315): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10315): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10315): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10315): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/splitIntent( 3527): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
W/System.err(11691): java.lang.NumberFormatException: Invalid int: "null"
W/System.err(11691): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err(11691): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err(11691): 	at java.lang.Integer.parseInt(Integer.java:334)
V/MediaPlayerService( 2860): wait for playback complete
W/System.err(11691): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:498)
W/System.err(11691): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1242)
W/System.err(11691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11691): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11691): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/MediaPlayer(11691): decode(37, 20914220, 4890)
V/MediaPlayerService( 2860): decode(28, 20914220, 4890)
,V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20914220, 4890)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
,V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2860): notify(0xb246c5b0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
,V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache( 2860): notify(0xb246c5b0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2860): wait for playback complete
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 2, 0, 0)
,V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
,V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
,V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/MediaPlayer(11691): decode(38, 20840384, 17329)
V/MediaPlayerService( 2860): decode(28, 20840384, 17329)
V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
,V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20840384, 17329)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
,V/MediaPlayerService( 2860): wait for playback complete
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/MediaPlayer(11691): decode(40, 20740576, 6644)
,V/MediaPlayerService( 2860): decode(28, 20740576, 6644)
,V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20740576, 6644)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
,I/AudioPlayer( 2860): First fillBuffer call!!
V/MediaPlayerService( 2860): wait for playback complete
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/MediaPlayer(11691): decode(41, 20816916, 23389)
V/MediaPlayerService( 2860): decode(28, 20816916, 23389)
V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
,V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20816916, 23389)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
,I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,V/MediaPlayerService( 2860): wait for playback complete
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
I/art     ( 3527): Explicit concurrent mark sweep GC freed 36565(1965KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 48MB/64MB, paused 1.456ms total 79.989ms
,E/DatabaseUtils( 3527): Writing exception to parcel
E/DatabaseUtils( 3527): java.lang.NullPointerException: key == null
E/DatabaseUtils( 3527): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils( 3527): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils( 3527): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils( 3527): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:376)
E/DatabaseUtils( 3527): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils( 3527): 	at android.os.Binder.execTransact(Binder.java:446)
,I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/MediaPlayer(11691): decode(42, 20706272, 8154)
V/MediaPlayerService( 2860): decode(28, 20706272, 8154)
,V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
,V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20706272, 8154)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
,V/MediaPlayerService( 2860): wait for playback complete
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer( 2860): reset_l()
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
V/AudioCache( 2860): notify(0xaf3ebc40, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/MediaPlayer(11691): decode(43, 20679752, 4804)
V/MediaPlayerService( 2860): decode(28, 20679752, 4804)
,V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20679752, 4804)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
,V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 200, 973, 0)
,V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2860): wait for playback complete
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
E/Zygote  (12012): MountEmulatedStorage()
I/libpersona(12012): KNOX_SDCARD checking this for 10022
V/AwesomePlayer( 2860): onStreamDone
I/libpersona(12012): KNOX_SDCARD not a persona
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
E/Zygote  (12012): v2
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache( 2860): notify(0xb246c5b0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 8, 0, 0)
,V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x84, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/SELinux (12012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
I/ActivityManager( 3527): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12012 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/MediaPlayer(11691): decode(44, 20649204, 9400)
,V/MediaPlayerService( 2860): decode(28, 20649204, 9400)
V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/MediaPlayer(11691): decode(50, 20722624, 4112)
V/MediaPlayerService( 2860): decode(37, 20722624, 4112)
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20649204, 9400)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 8, 0, 0)
V/AudioCache( 2860): ignored
,V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
I/SELinux (12012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
,V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
E/SELinux (12012): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(37, 20722624, 4112)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): onPrepareAsyncEvent
,I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
,V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 200, 973, 0)
,V/AudioCache( 2860): notify(0xaea166a0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 1, 0, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): notify(0xb246c380, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/AudioCache( 2860): wait - success
,V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
I/AudioPlayer( 2860): First fillBuffer call!!
V/MediaPlayerService( 2860): wait for playback complete
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1733175209, value : 485677307
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1733175209, value : 485677307
V/MediaPlayerService( 2860): wait for playback complete
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
,V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
,V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x86, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
,I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear,
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache( 2860): notify(0xb246c380, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
,V/AwesomePlayer( 2860): reset_l()
,V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x85, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
D/TimaKeyStoreProvider(12012): TimaSignature is unavailable
,D/ActivityThread(12012): Added TimaKeyStore provider
I/AudioPlayer( 2860): reset out
,V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
,V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/MediaPlayer(11691): decode(45, 20857804, 52024)
V/MediaPlayerService( 2860): decode(28, 20857804, 52024)
V/MediaPlayerService( 2860): player type = 3
,V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
,V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20857804, 52024)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
,V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 1, 0, 0)
V/AudioCache( 2860): prepared
,V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(48000, 2, 0x0, 1, 0)
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,V/MediaPlayerService( 2860): wait for playback complete
,W/ResourcesManager(12012): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12012): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12012): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
,V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf426100, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x87, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/LocationWidgetApplication(12012): onCreate() : start
D/LocationWidgetApplication(12012): countryCode = POLAND
I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/MediaPlayer(11691): decode(46, 20722624, 4112)
V/MediaPlayerService( 2860): decode(28, 20722624, 4112)
V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
,V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
,V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20722624, 4112)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/MediaPlayerService( 2860): wait for playback complete
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
,D/LocationWidgetUtils(12012): getUpcommingInstances() start: 1453367962911, end: 1453935599999
D/LocationWidgetUtils(12012): getUpcommingInstances() DB begin time >= start:1453367962911, DB begin time <= end:1453935599999
,V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaf3ebc40, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x88, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
,V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/MediaPlayer(11691): decode(47, 20785700, 21825)
V/MediaPlayerService( 2860): decode(28, 20785700, 21825)
,V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20785700, 21825)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2860): wait for playback complete
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
D/com.sec.android.service.health.cp.common.HttpConnectionConstants(11691): RegionGroup for  is null
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c5b0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x89, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthServiceInstalled() : HealthService is Installed.
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11691): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/OggExtractor( 2860): ~OggExtractor --
,I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/MediaPlayer(11691): decode(48, 20684636, 21552)
,V/MediaPlayerService( 2860): decode(28, 20684636, 21552)
V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20684636, 21552)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,D/LocationManagerService( 3527): getProviders()=[]
D/LocationManagerService( 3527): getProviders()=[passive]
D/LocationManagerService( 3527): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
V/MediaPlayerService( 2860): wait for playback complete
,D/LWLocationManager(12012): mPrivacy is null
,W/ContextImpl(12012): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaea166a0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x8a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
,V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/MediaPlayer(11691): decode(49, 20778600, 7017)
D/BluetoothManager(11691): getConnectedDevices
,V/MediaPlayerService( 2860): decode(28, 20778600, 7017)
V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
D/ContextFramework:PrivacyManager(12012): Service for PrivacyManager is connected
,V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
D/BluetoothManager(11691): getConnectedDevices
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(28, 20778600, 7017)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,D/BluetoothManager(11691): getConnectedDevices
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
V/MediaPlayerService( 2860): wait for playback complete
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
D/LWLocationManager(12012): Privacy service : STATUS_PLACE
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
D/LWLocationManager(12012): updateLocationStatus()
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb246c380, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x8b, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/AudioPlayer( 2860): reset out
,V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
,I/LocationWidgetFuctionData(12012): readDB
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,I/LocationWidgetFuctionData(12012): selectedAppSize: 3
I/LocationWidgetFuctionData(12012): configPlaceList aroundMeItems
,D/BluetoothManager(11691): getConnectedDevices
,D/BluetoothManager(11691): getConnectedDevices
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12071): MountEmulatedStorage()
E/Zygote  (12071): v2
I/libpersona(12071): KNOX_SDCARD checking this for 10003
I/libpersona(12071): KNOX_SDCARD not a persona
,I/SELinux (12071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=12071 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
E/SELinux (12071): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothManager(11691): getConnectedDevices
,D/TimaKeyStoreProvider(12071): TimaSignature is unavailable
,D/ActivityThread(12071): Added TimaKeyStore provider
,I/ActivityManager( 3527): Killing 11378:com.policydm/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3527): Killing 11400:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,D/ResourcesManager(12071): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/UserAnalysis.PlaceProvider(12071): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager(12071): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(12071): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(12071): Create SecureDbHelper
,D/IntelligenceServiceApplication(12071): onCreate()
,W/art     (11547): Attempt to remove local handle scope entry from IRT, ignoring
,I/LocationWidgetFuctionData(12012): selectedAppSize: 3
,I/LocationWidgetFuctionData(12012): selectedAppSize: 3
,I/LocationWidgetFuctionData(12012): selectedAppSize: 3
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10147
,I/LocationWidgetFuctionData(12012): selectedAppSize: 3
,E/LWLocationManager(12012): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(12012): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(12012): setShouldUpdateLocationId
D/LWLocationManager(12012): setShouldUpdateLocationId return false
D/LWLocationManager(12012): setShouldUpdateLocationId
D/LWLocationManager(12012): setShouldUpdateLocationId return false
D/LWLocationManager(12012): setShouldUpdateLocationId
D/LWLocationManager(12012): setShouldUpdateLocationId return false
D/LWLocationManager(12012): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,I/qtaguid (11902): Untagging socket 59
I/System.out(11902): SyncAdapterThread-1 calls detatch()
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Mms/MmsApp(11660):  start initViewCache mms
,D/Mms/ComposeMessageFragment(11660): [start]    fillCache consume time = 1869.125458
D/Mms/ComposeMessageFragment(11660): fillCache, easy = false
,D/AbsListView(11660): Get MotionRecognitionManager
,D/MotionRecognitionService( 3527):  ssp status : true
,D/Mms/ComposeMessageFragment(11660): [end]    fillCache consume time = 86.048542
,D/Mms/BubbleViewCache(11660): fillCache bubble = 8
,V/AlarmManager( 3527): waitForAlarm result :4
,I/art     (11902): Explicit concurrent mark sweep GC freed 159511(5MB) AllocSpace objects, 12(215KB) LOS objects, 21% free, 29MB/37MB, paused 1.510ms total 101.091ms
,E/SQLiteLog(11637): (284) automatic index on view_events(_id)
,I/Gmail   (11902): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15502, normalSync: true
,I/Gmail   (11902): lowestBackward conversation id 0
,D/CalendarAlarmManager(11637): sys current time:1453367963967
,D/CalendarAlarmManager(11637): reminder amount:0
,I/Gmail   (11902): notifyAccountChanged
,I/Gmail   (11902): getAccountsCursor
,I/Gmail   (11902): notifyAccountChanged
,W/Gmail   (11902): Sync complete for account: account:61035162
V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (11902): getAccountsCursor
,I/ActivityManager( 3527): Killing 11442:com.samsung.android.scloud.backup/u0a67 (adj 13): bgCount ##31
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (10441): Explicit concurrent mark sweep GC freed 3895(154KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 919us total 26.099ms
,I/GoogleHttpClient(10441): GMS http client unavailable, use old client
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(10441): Thread-1399(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(10441): Thread-1399(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10441): Thread-1399(ApacheHTTPLog):isShipBuild true
I/System.out(10441): Thread-1399(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/qtaguid (10441): Tagging socket 37 with tag 1244000400000000{306446340,0} uid -1, pid: 10441, getuid(): 10014
,I/System.out( 3527): Thread-146(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3527): Thread-146(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3527): Thread-146(ApacheHTTPLog):isShipBuild true
I/System.out( 3527): Thread-146(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 1000
,I/qtaguid (10441): Tagging socket 41 with tag 1244000400000000{306446340,0} uid -1, pid: 10441, getuid(): 10014
,E/AclDataUtils(11547): Circle ID not found for type: 9
,D/SSRM:n  ( 3527): SIOP:: AP = 310, PST = 270, CUR = -516
,I/qtaguid (10441): Untagging socket 37
,I/System.out(10441): GDataFeedFetcher calls detatch()
,D/Mms/Contact(11660): performUpdate:widgetCount=0
D/Mms/Contact(11660): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/ContactsCache(11660): [start]    invalidate() consume time = 925.689583
D/Mms/ContactsCache(11660): [end]    invalidate() consume time = 0.242334
,I/qtaguid (10441): Tagging socket 37 with tag 1144000400000000{289669124,0} uid -1, pid: 10441, getuid(): 10014
,I/System.out( 3527): AsyncTask #1 calls detatch()
,W/System.err( 3527): java.io.IOException: Not Found
W/System.err( 3527): 	at a.d.b(Unknown Source)
W/System.err( 3527): 	at a.d.doInBackground(Unknown Source)
W/System.err( 3527): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 3527): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 3527): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3527): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 3527): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 3527): 	at java.lang.Thread.run(Thread.java:818)
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/qtaguid (10441): Untagging socket 37
,I/System.out(10441): GDataFeedFetcher calls detatch()
,D/Mms/Contact(11660): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/ContactsCache(11660): [start]    invalidate() consume time = 194.082833
,D/Mms/ContactsCache(11660): [end]    invalidate() consume time = 0.875167
,E/SQLiteLog( 4274): (284) automatic index on sqlite_sq_A074FE20(STAT_DATA_ID)
,E/SQLiteLog( 4274): (284) automatic index on sqlite_sq_A074FFB0(STAT_DATA_ID)
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12139): MountEmulatedStorage()
,E/Zygote  (12139): v2
I/libpersona(12139): KNOX_SDCARD checking this for 10101
I/libpersona(12139): KNOX_SDCARD not a persona
,I/SELinux (12139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=12139 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12139): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12139): TimaSignature is unavailable
,D/ActivityThread(12139): Added TimaKeyStore provider
,E/SQLiteLog( 4274): (284) automatic index on sqlite_sq_A075A560(STAT_DATA_ID)
,D/ResourcesManager(12139): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/SQLiteLog( 4274): (284) automatic index on sqlite_sq_A074FD30(STAT_DATA_ID)
,D/DocsApplication(12139): Installing DEX configuration.
,D/DexInstaller(12139): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12139): Provided clientMode=RELEASE, packageInfo=PackageInfo{d599c70 com.google.android.apps.docs}
,D/TAG     (12139): onCreate()
,D/CrossAppStateProvider(12139): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,I/dhcpcd  (11091): wlan0: sending IPv6 Router Solicitation
,I/SyncAdapterService(11479): Ignoring sync request for non-current account
,W/BaseAppContext( 4473): Using Auth Proxy for data requests.
W/BaseAppContext( 4473): Using Auth Proxy for data requests.
,W/BaseAppContext( 4473): Using Auth Proxy for data requests.
W/BaseAppContext( 4473): Using Auth Proxy for data requests.
,W/BaseAppContext( 4473): Using Auth Proxy for data requests.
,W/BaseAppContext( 4473): Using Auth Proxy for data requests.
,W/BaseAppContext( 4473): Using Auth Proxy for data requests.
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12164): MountEmulatedStorage()
I/libpersona(12164): KNOX_SDCARD checking this for 10135
E/Zygote  (12164): v2
I/libpersona(12164): KNOX_SDCARD not a persona
,I/SELinux (12164): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=12164 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12164): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12164): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12164): TimaSignature is unavailable
,D/ActivityThread(12164): Added TimaKeyStore provider
,D/ResourcesManager(12164): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(12164): Database version: 104
,I/SurfaceFlinger( 2855): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger( 2855): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 3527): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3527) eventTime = 147114
,D/PowerManagerService( 3527): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3527 (0x0)
D/PowerManagerService( 3527): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3527, ws=WorkSource{1000}) (elapsedTime=3474)
,D/ResourcesManager(12164): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12164): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12164): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12164): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/GAV2    (12139): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityThread(12164): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (12164): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f68d6cf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12164): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12164): GMSCore installation verified
,I/ConfigStore(12164): Config Database version: 1
,D/WifiService( 3527): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@65d72da}
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12164): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/System.out(12139): Thread-1661(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12139): Thread-1661(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12139): Thread-1661(ApacheHTTPLog):isShipBuild true
I/System.out(12139): Thread-1661(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10101
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12164): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12164): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3527): getStreamVolume 3 index 0
,I/MediaRouter(12164): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/GHttpClientFactory(12164): Using the GMSCore's GoogleHttpClient
,I/NetworkMonitor(12164): type=WIFI subType= reason=null isConnected=true
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(12164): type=WIFI subType= reason=null isConnected=true
,I/System.out(12139): SyncManager calls detatch()
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 50643(2MB) AllocSpace objects, 16(3MB) LOS objects, 24% free, 48MB/64MB, paused 2.357ms total 146.549ms
,I/GAV4    (11479): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12164): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12164): (HTTPLog)-Static: isShipBuild true
I/System.out(12164): (HTTPLog)-Thread-1661-964242441: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(12164): (HTTPLog)-Static: isSBSettingEnabled false
I/GAV2    (11547): Thread[GAThread,5,main]: No campaign data found.
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10135
,I/System.out( 4257): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4257): Tagging socket 55 with tag 1000040100000000{268436481,0} uid 10014, pid: 4257, getuid(): 10014
,I/ActivityManager( 3527): Killing 11464:com.sec.knox.bridge/1000 (adj 13): bgCount ##31
,I/System.out(12164): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/bdH     (12139): Application name is not set. Call Builder#setApplicationName.
,I/System.out(12139): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12139): (HTTPLog)-Static: isShipBuild true
I/System.out(12139): (HTTPLog)-Thread-1661-406967442: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12139): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10101
,I/System.out(12139): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12164): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12164): (HTTPLog)-Static: isSBSettingEnabled false
,W/MusicApiClient(12164): No content in 'data' field in GET sync response for Track
,I/MusicSyncAdapter(12164): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter(12164): Periodic update
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12237): MountEmulatedStorage()
E/Zygote  (12237): v2
I/libpersona(12237): KNOX_SDCARD checking this for 10031
I/libpersona(12237): KNOX_SDCARD not a persona
,I/SELinux (12237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=12237 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12237): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8717(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 927us total 23.869ms
,D/TimaKeyStoreProvider(12237): TimaSignature is unavailable
,D/ActivityThread(12237): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 837us total 18.876ms
,D/ResourcesManager(12237): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 452us total 18.058ms
,I/ActivityManager( 3527): Killing 11193:com.android.chrome/u0a90 (adj 13): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/Mms/Contact(11660): performUpdate:widgetCount=0
,E/Zygote  (12252): MountEmulatedStorage()
E/Zygote  (12252): v2
I/libpersona(12252): KNOX_SDCARD checking this for 10195
I/libpersona(12252): KNOX_SDCARD not a persona
,I/SELinux (12252): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12252): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=12252 uid=10195 gids={50195, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/SELinux (12252): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12252): TimaSignature is unavailable
,D/ActivityThread(12252): Added TimaKeyStore provider
,D/ResourcesManager(12252): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/ResourcesManager(12252): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,D/Finsky  (12237): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  (12237): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(12237): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(12237): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     (12237): Skipping gmscore version check
,D/Finsky  (12237): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (12237): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  (12237): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  (12237): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12164): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12164): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ArtDownloadService(12164): Setting cache size 0
,W/System  (12164): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/GHttpClientFactory(12164): Using the GMSCore's GoogleHttpClient
,W/PsynchoHelperImpl(12139): Error fetching or saving configuration
W/PsynchoHelperImpl(12139): bdz: 404 Not Found
W/PsynchoHelperImpl(12139): {
W/PsynchoHelperImpl(12139):   "errors": [
W/PsynchoHelperImpl(12139):     {
W/PsynchoHelperImpl(12139):       "domain": "global",
W/PsynchoHelperImpl(12139):       "reason": "notFound",
W/PsynchoHelperImpl(12139):       "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found",
W/PsynchoHelperImpl(12139):       "locationType": "other",
W/PsynchoHelperImpl(12139):       "location": "setting"
W/PsynchoHelperImpl(12139):     }
W/PsynchoHelperImpl(12139):   ],
W/PsynchoHelperImpl(12139):   "code": 404,
W/PsynchoHelperImpl(12139):   "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found"
W/PsynchoHelperImpl(12139): }
W/PsynchoHelperImpl(12139): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:113)
W/PsynchoHelperImpl(12139): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:40)
W/PsynchoHelperImpl(12139): 	at bdK.a(AbstractGoogleClientRequest.java:321)
W/PsynchoHelperImpl(12139): 	at bei.a(HttpRequest.java:1049)
W/PsynchoHelperImpl(12139): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:419)
W/PsynchoHelperImpl(12139): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:352)
W/PsynchoHelperImpl(12139): 	at bdJ.execute(AbstractGoogleClientRequest.java:469)
W/PsynchoHelperImpl(12139): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:142)
W/PsynchoHelperImpl(12139): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl(12139): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl(12139): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl(12139): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl(12139): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl(12139): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl(12139): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl(12139): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl(12139): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl(12139): 	at agP.run(LegacySyncManager.java:416)
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicLeanback(12164): Conditions not met for autocaching.
I/MusicLeanback(12164): Stop autocaching.
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10101
,D/WearableService( 4257): callingUid 10014, callindPid: 4257
,D/WearableClient(12164): WearableClientImpl.onPostInitHandler: done
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12164): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,D/WearableClient(12164): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12164): WearableClientImpl.onPostInitHandler: done
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12164): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
D/WearableClient(12164): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12164): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12164): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12164): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@ee7d20f that was originally bound here
E/ActivityThread(12164): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@ee7d20f that was originally bound here
E/ActivityThread(12164): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12164): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12164): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12164): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12164): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12164): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12164): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12164): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12164): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12164): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12164): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12164): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12164): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12164): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12164): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12164): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12164): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12164): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12164): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12164): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12164): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12164): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12164): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12164): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12164): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/PlayMovies(12252): SyncService$SyncAdapter.onPerformSync:252 Skipping sync for 515013DC511638B0584069811EF28701C0771BF5
,D/PlayMovies(12252): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/PlayMovies(12252): TransferService.onCreate:52 creating transfer service
,W/AudioCapabilities(12252): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities(12252): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities(12252): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities(12252): Unsupported mime audio/x-ima
,W/VideoCapabilities(12252): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities(12252): Unsupported mime video/wvc1
,W/VideoCapabilities(12252): Unsupported mime video/x-ms-wmv
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.videos/files/Movies/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12252): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.videos/files/Movies
,D/ResourcesManager( 4473): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/VideoCapabilities(12252): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities(12252): Unsupported mime video/wvc1
,W/VideoCapabilities(12252): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities(12252): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities(12252): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities(12252): Unsupported mime video/sorenson
,D/WVCdm   ( 2860): Instantiating CDM.
,I/WVCdm   ( 2860): CdmEngine::QueryStatus
,I/WVCdm   ( 2860): Level3 Library Sep 25 2014 17:10:03
,W/VideoCapabilities(12252): Unsupported mime video/mp43
,W/ResourcesManager( 4473): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,W/AudioCapabilities(12252): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities(12252): Unsupported mime audio/mpeg-L2
,W/WVCdm   ( 2860): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/VideoCapabilities(12252): Unrecognized profile/level 32768/2 for video/mp4v-es
,E/wv_dash ( 2860): No saved usage table. Creating new table.
,I/GAV2    (11902): Thread[GAThread,5,main]: No campaign data found.
,I/VideoCapabilities(12252): Unsupported profile 4 for video/mp4v-es
,D/WVCdm   ( 2860): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   ( 2860): L3 Terminate.
,I/ActivityManager( 3527): Killing 10883:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 13): bgCount ##31
,I/GAV3    (11691): Thread[GAThread,5,main]: No campaign data found.
,E/Auth.Api.Credentials( 4473): [CredentialSyncAdapter] Unknown sync event.
,I/System.out(11601): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid (11601): Tagging socket 28 with tag 1000000400000000{268435460,0} uid -1, pid: 11601, getuid(): 10123
I/qtaguid (11601): Tagging socket 32 with tag 1000000400000000{268435460,0} uid -1, pid: 11601, getuid(): 10123
,V/CalendarSyncAdapter(11601): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-01-24T00:00:00.000Z, updatedMin=2015-11-18T16:31:02.459Z}
,I/qtaguid (11601): Untagging socket 28
,D/CalendarSyncAdapter(11601): Found 0 events marked dirty & lastSynced
,I/dhcpcd  (11091): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  (11091): wlan0: no IPv6 Routers available
,I/System.out(12139): SyncManager calls detatch()
,W/GAV2    (12139): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/WifiService( 3527): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@65d72da}
,I/ActivityManager( 3527): Killing 11575:com.samsung.android.sconnect/u0a150 (adj 13): bgCount ##31
,I/PowerManagerService( 3527): [PWL] Off : 105s ago
,I/GAV2    (12139): Thread[GAThread,5,main]: No campaign data found.
,D/WearableClient(12164): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12164): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12164): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12164): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient(12164): WearableClientImpl.onPostInitHandler: done
,I/MusicLeanback(12164): Conditions not met for autocaching.
I/MusicLeanback(12164): Stop autocaching.
,E/GmsUtils(12164): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PreloadUpdateManagerStateMachine(11618): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(11618): exit::IDLE
D/PreloadUpdateManagerStateMachine(11618): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (11618): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  (11618): RestApi Request Add : 2307
,I/System.out(11618): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(11618): (HTTPLog)-Static: isShipBuild true
I/System.out(11618): (HTTPLog)-Thread-1570-360180096: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(11618): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10013
,I/System.out(11618): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (11618): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 11618, getuid(): 10013
,I/qtaguid (11618): Untagging socket 26,
,D/hcjo    (11618): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    (11618): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine(11618): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine(11618): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(11618): entry::REQ_UPDATE_CHECK
,I/Volley  (11618): RestApi Request Add : 2315
,I/System.out(11618): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out(11618): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid (11618): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 11618, getuid(): 10013
,I/qtaguid (11618): Untagging socket -1
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:-187, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:105
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,I/qtaguid (11618): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid (11618): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger(11618): untagSocket(-1) failed with errno -9
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PreloadUpdateManagerStateMachine(11618): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine(11618): exit::REQ_UPDATE_CHECK
,D/PreloadUpdateManagerStateMachine(11618): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine(11618): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine(11618): entry::FINISH
,D/PreloadUpdateManagerStateMachine(11618): exit::FINISH
,D/PreloadUpdateManagerStateMachine(11618): entry::IDLE
,W/ProcessCpuTracker( 3527): Skipping unknown process pid 12440
,D/SSRM:n  ( 3527): SIOP:: AP = 280, PST = 266, CUR = -187
,D/PackageManager( 3527): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 3997): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/InputReader( 3527): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/PageBuddyNotiSvc( 4647): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ResourcesManager( 3975): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3975): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 3975): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/LocationWidgetApplication(12012): Intent.ACTION_PACKAGE_CHANGED has been called for com.google.android.videos
,D/LWLocationManager(12012): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12012): getLastUiLocationId() : mLastUiLocationId = -100
,D/RegisteredServicesCache( 3956): empty dynamic service
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/ResourceType( 4963): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4963): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,E/Zygote  (12466): MountEmulatedStorage()
E/Zygote  (12466): v2
I/libpersona(12466): KNOX_SDCARD checking this for 10035
I/libpersona(12466): KNOX_SDCARD not a persona
,I/SELinux (12466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12466 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux (12466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12466): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Books/Books.apk
,D/SecContentProvider2( 3527): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3527): mCursor = null
,D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/TimaKeyStoreProvider(12466): TimaSignature is unavailable
,D/ActivityThread(12466): Added TimaKeyStore provider
,I/Launcher.Workspace( 3997): isBadgeUpdate : false
,D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(12466): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/FeatureConfig(12466): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/ActivityManager( 3527): Killing 10898:com.android.email/u0a178 (adj 13): bgCount ##31
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(12012): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/Zygote  (12489): MountEmulatedStorage()
E/Zygote  (12489): v2
I/libpersona(12489): KNOX_SDCARD checking this for 10050
I/libpersona(12489): KNOX_SDCARD not a persona
,I/SELinux (12489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12489 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (12489): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/TimaKeyStoreProvider(12489): TimaSignature is unavailable
,D/ActivityThread(12489): Added TimaKeyStore provider
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12012): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12012): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12012): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12012): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/ResourcesManager(12489): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager(12489): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12489): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12489): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12489): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12489): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12489): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12489): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12489): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/ResourceType( 3527): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3527): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/BackupManagerService( 3527): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(12012): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager(12466): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12466): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(12466): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12466): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12466): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(12466): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/PackageManager( 3527): findPreferredActivity: No PreferredActivities set
,W/ResourcesManager(12466): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(12466): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/NearbySource(12489): Nearby Source Create!
D/ResourcesManager(12466): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/NearbyContext(12489): Nearby Context Create!
W/ResourcesManager(12466): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager(12466): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12466): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12466): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/ResourcesManager(12466): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ResourcesManager(12466): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ContextImpl(12489): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/SLinkSource(12489): Samsung link source created
W/ResourcesManager(12466): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12466): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12466): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(12466): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager(12466): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager(12466): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider(12489): getAllContactInfoList Start
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(12466): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourcesManager(12466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(12466): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12466): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(12466): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/UpdateIcingCorporaServi( 4050): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager(12466): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(12466): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/ActivityManager( 3527): Killing 10938:tv.peel.smartremote/u0a186 (adj 13): bgCount ##31
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12466): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(12466): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager(12466): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/ResourcesManager(12466): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(12466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Maps/Maps.apk
,E/Zygote  (12509): MountEmulatedStorage()
I/libpersona(12509): KNOX_SDCARD checking this for 10079
E/Zygote  (12509): v2
I/libpersona(12509): KNOX_SDCARD not a persona
I/SELinux (12509): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12509): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/GalaxyFinderApplication(12466): system/finder_cp/cpdata.xml file not found
E/SELinux (12509): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=12509 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/TimaKeyStoreProvider(12509): TimaSignature is unavailable
,D/ActivityThread(12509): Added TimaKeyStore provider
,D/ResourcesManager( 4050): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(12509): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/FileShare-Server(12509): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.videos
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/UpdateIcingCorporaServi( 4050): UpdateCorporaTask done [took 127 ms] updated apps [took 127 ms] 
,E/Zygote  (12526): MountEmulatedStorage()
,E/Zygote  (12526): v2
I/libpersona(12526): KNOX_SDCARD checking this for 1000
I/libpersona(12526): KNOX_SDCARD not a persona
,I/SELinux (12526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=12526 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
I/SELinux (12526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12526): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 11323:com.sec.android.fotaclient/u0a12 (adj 13): bgCount ##31
,D/ResourcesManager(12012): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(12012): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 42692(2MB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 48MB/64MB, paused 2.122ms total 153.265ms
,D/TimaKeyStoreProvider(12526): TimaSignature is unavailable
,D/ActivityThread(12526): Added TimaKeyStore provider
,D/ContactProvider(12489): getAllContactInfoList End
,I/syncContacts(12489): thread: 1673, sync time = 241
,D/ResourcesManager(12526): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12526): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12543): MountEmulatedStorage()
E/Zygote  (12543): v2
I/libpersona(12543): KNOX_SDCARD checking this for 1000
I/libpersona(12543): KNOX_SDCARD not a persona
,I/SELinux (12543): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12543): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=12543 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12543): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 11340:com.samsung.klmsagent/u0a21 (adj 13): bgCount ##31
,D/ResourcesManager(12012): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/TimaKeyStoreProvider(12543): TimaSignature is unavailable
,D/ActivityThread(12543): Added TimaKeyStore provider
,D/ResourcesManager(12012): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/ResourcesManager(12543): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,D/ShortcutReceiver(12543):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/PackageBroadcastService( 4473): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12561): MountEmulatedStorage()
I/libpersona(12561): KNOX_SDCARD checking this for 10110
E/Zygote  (12561): v2
I/libpersona(12561): KNOX_SDCARD not a persona
,I/SELinux (12561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12561): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.packages.PackageReceiver: pid=12561 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 11660:com.android.mms/u0a52 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12561): TimaSignature is unavailable
,D/ActivityThread(12561): Added TimaKeyStore provider
,D/ResourcesManager(12561): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/CountryDetector( 3527): No listener is left
,D/ACRA    (12561): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(12561): not using cross-dex optimization: ART in use
,I/art     (12561): Thread[1,tid=12561,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(12561): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(12561): locking /data/data/com.facebook.appmanager/mdex_lock took 1 ms
,V/DexLibLoader(12561): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(12561): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(12561): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (12561): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(12561): loading pre-built fallback odex files
V/MultiDexClassLoader(12561): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(12561): released odex store lock
D/DexLibLoader(12561): DexLibLoader.loadAll took 34 ms
,W/ca      (12561): Verify
,W/LightSharedPreferencesImpl(12561): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(12561): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12561): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(12561): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(12561): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(12561): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(12561): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(12561): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(12561): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(12561): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(12561): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(12561): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(12561): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(12561): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12561): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(12561): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(12561): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(12561): 	... 10 more
,W/appmanager(:<default>):b(12561): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/ActivityThread(12561): Failed to find provider info for com.facebook.appmanager.installrecord
,W/appmanager(:<default>):b(12561): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):QuickExperimentControllerImpl(12561): Exposure of experiment com.facebook.common.network.l@1a09c13e occurred when no user was logged in
,I/ActivityManager( 3527): Killing 10914:com.samsung.android.securitylogagent/1000 (adj 13): bgCount ##31
,W/BroadcastQueue( 3527): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3024d02e u0 ReceiverList{3b5602a9 12561 com.facebook.appmanager/10110/u0 remote:23f8d630}}
,W/BroadcastQueue( 3527): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3024d02e u0 ReceiverList{3b5602a9 12561 com.facebook.appmanager/10110/u0 remote:23f8d630}}
,W/BroadcastQueue( 3527): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{30eb3d92 u0 ReceiverList{354df71d 12561 com.facebook.appmanager/10110/u0 remote:2006c3f4}}
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12561): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12561): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(12561): Exposure of experiment com.facebook.imagepipeline.a.g@2893566c occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12561): Exposure of experiment com.facebook.imagepipeline.a.d@27008eb1 occurred when no user was logged in
,I/art     (12561): Explicit concurrent mark sweep GC freed 47202(2MB) AllocSpace objects, 3(48KB) LOS objects, 22% free, 27MB/35MB, paused 1.521ms total 47.212ms
,W/appmanager(:<default>):m(12561): No feature status reporters found; is this dead code?
,I/Icing   ( 4473): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,W/appmanager(:<default>):b(12561): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12561): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12561): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):QuickExperimentControllerImpl(12561): Exposure of experiment com.facebook.http.g.bb@34af635d occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12561): Exposure of experiment com.facebook.http.g.an@15e1d4d2 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12561): Exposure of experiment com.facebook.http.g.aw@3866b4a0 occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(12561): Exposure of experiment com.facebook.http.g.aj@2283d859 occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(12561): Exposure of experiment com.facebook.http.g.a@be46c1e occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12561): Exposure of experiment com.facebook.http.g.k@1990a115 occurred when no user was logged in
,D/ResourcesManager( 4473): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/System.out(12561): Thread-1723(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12561): Thread-1723(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12561): Thread-1723(ApacheHTTPLog):isShipBuild true
I/System.out(12561): Thread-1723(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/appmanager(:<default>):QuickExperimentControllerImpl(12561): Exposure of experiment com.facebook.http.g.c@27a3e0f6 occurred when no user was logged in
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10110
,I/Icing   ( 4473): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,W/ActivityThread(12561): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out(12561): P[5]_NetworkDispatch1 calls detatch()
,W/appmanager(:<default>):b(12561): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12561): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/Watchdog( 3527): !@Sync 5
,W/IdleConnectionHandler(12561): Removing a connection that never existed!
,I/ActivityManager( 3527): Waited long enough for: ServiceRecord{70f45d5 u0 com.google.android.music/.download.artwork.ArtDownloadService}
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:-28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:95
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 270, PST = 271, CUR = -28,
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3527): waitForAlarm result :4
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:76
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 250, PST = 271, CUR = 37,
,W/IcingInternalCorpora( 4473): getNumBytesRead when not calculated.
,I/ClearcutLoggerApiImpl( 4257): disconnect managed GoogleApiClient
,V/AlarmManager( 3527): waitForAlarm result :8
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:79
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3527): [PWL] Off : 140s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 250, PST = 267, CUR = 57
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3527): !@Sync 6
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 250, PST = 266, CUR = 60
,V/AlarmManager( 3527): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/ActivityThread( 4473): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3527): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 171406, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 3527): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 261960, reason: UserStart
,W/ResourceType( 4963): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4963): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3527): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3527): mCursor = null
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 240, PST = 264, CUR = 56
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 240, PST = 263, CUR = 52
,V/AlarmManager( 3527): waitForAlarm result :4
,E/Watchdog( 3527): !@Sync 7
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3527): [PWL] Off : 180s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 240, PST = 260, CUR = 50
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3527): waitForAlarm result :4
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 240, PST = 260, CUR = 47
,V/AlarmManager( 3527): waitForAlarm result :8
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 240, PST = 257, CUR = 43
,E/Watchdog( 3527): !@Sync 8
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 240, PST = 255, CUR = 42
,I/ClearcutLoggerApiImpl( 4473): disconnect managed GoogleApiClient
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 240, PST = 252, CUR = 40
,I/PowerManagerService( 3527): [PWL] Off : 225s ago
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 250, CUR = 38
,E/Watchdog( 3527): !@Sync 9
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 248, CUR = 37
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 246, CUR = 38
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 243, CUR = 36
,D/TimaService( 3527): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3527): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3527): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3527): initializing...
,I/TLC_TIMA_PKM_initialize( 3527): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 3527): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3527): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3527): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 3527): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3527): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3527): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3527): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 3527): device_id = 0x0
I/TZ: mc_tlc_communication( 3527): tlc_open() was called
I/TZ: mc_tlc_communication( 3527): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3527): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3527): Opening the session
,I/TZ: mc_tlc_communication( 3527): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3527): Trustlet response is completed
,E/Watchdog( 3527): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 3527): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3527): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3527): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3527): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 241, CUR = 35
,I/PowerManagerService( 3527): [PWL] Off : 275s ago
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10202
,I/System.out( 6378): Thread-613 calls detatch(),
,I/System.out( 6378): Thread-613 calls detatch()
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/System.out( 6378): Thread-613 calls detatch()
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 239, CUR = 33
,I/ActivityManager( 3527): Killing 11746:com.sec.android.app.taskmanager/u0a191 (adj 13): bgCount ##31,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 238, CUR = 32
,E/Watchdog( 3527): !@Sync 11
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 237, CUR = 32
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 236, CUR = 32
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 236, CUR = 30
,E/Watchdog( 3527): !@Sync 12
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3527): [PWL] Off : 330s ago
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 235, CUR = 30
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 234, CUR = 31
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 233, CUR = 30
,E/Watchdog( 3527): !@Sync 13
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 233, CUR = 31
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 233, CUR = 31
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3527): waitForAlarm result :8
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 232, CUR = 28
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 14
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3527): [PWL] Off : 390s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 232, CUR = 27
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 232, CUR = 27
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12237): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12237): (HTTPLog)-Static: isShipBuild true
I/System.out(12237): (HTTPLog)-Thread-1673-535822995: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12237): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10031
,W/PlayEventLogger(12252): No account for auth token provided
,I/System.out(12252): Thread-1665(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12252): Thread-1665(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12252): Thread-1665(ApacheHTTPLog):isShipBuild true
I/System.out(12252): Thread-1665(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10195
,I/System.out(12237): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/System.out(12252): PlayEventLogger calls detatch()
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 231, CUR = 26
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 15
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 231, CUR = 28
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 231, CUR = 25
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 25,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 16
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 25
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3527): [PWL] Off : 455s ago
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 26
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 25,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3527): !@Sync 17
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 25
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 25
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 24
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 18,
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 24
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 24
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3527): [PWL] Off : 525s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 24
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 19
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 24
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 24
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 25,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,D/BatteryService( 3527): stay LED for fully charged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3527): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3527): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3527): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3527): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3527): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3527): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3527): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3527): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 24
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/BatteryService( 3527): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 23
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 21
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 21
,I/PowerManagerService( 3527): [PWL] Off : 600s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 21
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 20
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 22
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 21
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 21
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 21
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 23
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 19,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3527): [PWL] Off : 680s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 20
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 24
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 19,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 25
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 17,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 26
,V/AlarmManager( 3527): waitForAlarm result :4
,D/Finsky  (12237): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/LightsService( 3527): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3527): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3527): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 4473): Aggregate from 1453366807115 (log), 1453366807115 (data)
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/System.out(12237): Thread-1662(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12237): Thread-1662(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12237): Thread-1662(ApacheHTTPLog):isShipBuild true
I/System.out(12237): Thread-1662(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10031
,I/qtaguid (12237): Tagging socket 47 with tag e8d195d100000000{3906049489,0} uid -1, pid: 12237, getuid(): 10031
,I/Sensors ( 3527): #>LightSensor r=360 g=350 b=287 c=758 atime=238 again=64 lux=127.000000
,D/LightsService( 3527): [SvcLED]  onSensorChanged::light value = 127
I/Sensors ( 3527): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3527): unregisterListener ::   
D/LightsService( 3527): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/qtaguid (12237): Tagging socket 51 with tag e8d195d100000000{3906049489,0} uid -1, pid: 12237, getuid(): 10031
,I/qtaguid (12237): Untagging socket 47
,I/System.out(12237): Thread-1662 calls detatch()
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid (12237): Untagging socket 47
I/qtaguid (12237): Failed write_ctrl(u 47) res=-1 errno=22
I/qtaguid (12237): Untagging socket 47 failed errno=-22
W/NetworkManagementSocketTagger(12237): untagSocket(47) failed with errno -22
I/System.out(12237): Thread-1663 calls detatch()
,D/Finsky  (12237): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (13260): MountEmulatedStorage()
E/Zygote  (13260): v2
I/libpersona(13260): KNOX_SDCARD checking this for 10014
I/libpersona(13260): KNOX_SDCARD not a persona
,I/SELinux (13260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=13260 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/SELinux (13260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13260): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider(13260): TimaSignature is unavailable
,D/ActivityThread(13260): Added TimaKeyStore provider
,D/ResourcesManager(13260): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(13260): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(13260): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/qtaguid (12237): Untagging socket 47
,I/qtaguid (12237): Failed write_ctrl(u 47) res=-1 errno=22
I/qtaguid (12237): Untagging socket 47 failed errno=-22
W/NetworkManagementSocketTagger(12237): untagSocket(47) failed with errno -22
I/System.out(12237): Thread-1662 calls detatch()
,I/MultiDex(13260): VM with version 2.1.0 has multidex support
I/MultiDex(13260): install
I/MultiDex(13260): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp (13260): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(13260): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (13260): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e9594c4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(13260): Installed default security provider GmsCore_OpenSSL
,I/splitIntent( 3527): Split this intent : com.google.android.gms.INITIALIZE !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
I/splitIntent( 3527): finish to split intent : com.google.android.gms.INITIALIZE !! Enqueue -> schedule it!!
,D/AuthorizationBluetoothService( 4257): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/WearableService( 4257): callingUid 10014, callindPid: 4257
,E/MDM     ( 4257): [290] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ChimeraCfgMgr(13260): Reading stored module config
,D/LocationInitializer( 4473): Restart initialization of location
,D/ChimeraCfgMgr(13260): Loading module com.google.android.gms.car from APK com.google.android.gms
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/splitIntent( 3527): Queue : backgroundsplit_1 intent com.google.android.gms.INITIALIZE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/GCoreFlp( 4257): No location to return for getLastLocation()
,W/FusedLocationProvider( 4257): location=null
,D/CAR.SERVICE(13260): Connecting to CarCallService...
,I/art     (13260): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     (13260): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE(13260): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service(13260): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter(13260): Creating a new PhoneAdapter instance
,W/ActivityManager( 3527): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter(13260): setListener: com.google.android.gms.car.dn@841b263
W/ActivityManager( 3527): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter(13260): Returning an existing PhoneAdapter instance.
D/NativeLibraryUtils(13260): Install completed successfully. count=14 extracted=0
D/CAR.TEL.Service(13260): Starting CarCallService with initial phone null
,D/CAR.SERVICE(13260): Package validated; name: com.android.vending
,V/Finsky  (12237): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 71934(6MB) AllocSpace objects, 191(2MB) LOS objects, 24% free, 49MB/65MB, paused 3.315ms total 213.249ms
,I/qtaguid (12237): Untagging socket 47
,I/qtaguid (12237): Failed write_ctrl(u 47) res=-1 errno=22
,I/qtaguid (12237): Untagging socket 47 failed errno=-22
W/NetworkManagementSocketTagger(12237): untagSocket(47) failed with errno -22
I/System.out(12237): Thread-1663 calls detatch()
,D/ResourcesManager(12237): creating new AssetManager and set to /system/framework/framework-res.apk
,D/ResourcesManager(12237): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(12237): creating new AssetManager and set to /system/app/ANTRadioService/ANTRadioService.apk
,D/ResourcesManager(12237): creating new AssetManager and set to /system/app/AntHalService/AntHalService.apk
,W/ResourcesManager(12237): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(12237): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12237): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12237): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ResourcesManager(12237): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(12237): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(12237): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  (12237): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 3527): waitForAlarm result :4
,D/DeviceConnectionService( 4257): client connected with version: 8296000
,D/Finsky  (12237): [1687] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 4257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  (12237): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  (12237): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/System.out(12237): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10031
,I/System.out(12237): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 18
,I/ActivityManager( 3527): Killing 11762:com.samsung.android.scloud.sync/u0a69 (adj 13): bgCount ##31
,D/CAR.SERVICE(13260): mConnectedToCar = false, abort
,E/ActivityThread(13260): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@16fc64e1 that was originally bound here
E/ActivityThread(13260): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@16fc64e1 that was originally bound here
E/ActivityThread(13260): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(13260): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(13260): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(13260): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(13260): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(13260): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(13260): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(13260): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread(13260): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread(13260): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread(13260): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread(13260): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread(13260): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread(13260): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(13260): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(13260): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(13260): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(13260): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(13260): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(13260): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(13260): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(13260): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(13260): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread(13260): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@aee892 that was originally bound here
E/ActivityThread(13260): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@aee892 that was originally bound here
E/ActivityThread(13260): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(13260): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(13260): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(13260): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(13260): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(13260): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread(13260): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread(13260): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread(13260): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread(13260): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread(13260): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread(13260): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread(13260): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3181)
E/ActivityThread(13260): 	at android.app.ActivityThread.access$2000(ActivityThread.java:178)
E/ActivityThread(13260): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1537)
E/ActivityThread(13260): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(13260): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(13260): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(13260): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(13260): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(13260): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(13260): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 3527): Unbind failed: could not find connection for android.os.BinderProxy@35f2930e
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/SQLiteConnectionPool( 4473): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 18
,V/AlarmManager( 3527): waitForAlarm result :4
,D/Finsky  (12237): [1675] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (12237): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3527): [PWL] Off : 765s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 27
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3527): waitForAlarm result :8
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 28
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 29
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 229, CUR = 16
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3527): stay LED for fully charged
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 229, CUR = 17
,V/AlarmManager( 3527): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 3527): [PWL] Off : 855s ago
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3527): waitForAlarm result :8
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 229, CUR = 16
,D/TimaService( 3527): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3527): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3527): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3527): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3527): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3527): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3527): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 228, CUR = 16
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 228, CUR = 15
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 228, CUR = 16
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3527): !@Sync 31
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 227, CUR = 16
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 227, CUR = 15
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 227, CUR = 14
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 32
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 226, CUR = 15
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 226, CUR = 14
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3527): [PWL] Off : 950s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 226, CUR = 14
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 33
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 225, CUR = 16
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 225, CUR = 14
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 225, CUR = 13
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 34
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 224, CUR = 14
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 224, CUR = 13
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 224, CUR = 14
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 35
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 223, CUR = 14
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 223, CUR = 15
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 223, CUR = 13
,E/Watchdog( 3527): !@Sync 36
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3527): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 222, CUR = 13,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 222, CUR = 15,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 222, CUR = 14
,E/Watchdog( 3527): !@Sync 37
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 221, CUR = 14
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 221, CUR = 15
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 221, CUR = 15
,E/Watchdog( 3527): !@Sync 38
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 14
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 12
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 13
,E/Watchdog( 3527): !@Sync 39
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 12,
,I/PowerManagerService( 3527): [PWL] Off : 1155s ago
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 13
,D/TimaService( 3527): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3527): TIMA: checkEvent, operation: 50000 subject: 10000,
D/TimaService( 3527): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService( 3527): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3527): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3527): Updating Usage Statistics in DB @ 1453369029704
,I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
,W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$Cu,rsorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3527): ::getAppControlDB: Exception to create DB
W/System.err( 3527): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3527): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3527): Done Updating Usage Statistics in DB @ 1453369029768
,E/Watchdog( 3527): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3527): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3527): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3527): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3527): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 12
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 12
,E/Watchdog( 3527): !@Sync 41
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 12
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 12
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 10
,E/Watchdog( 3527): !@Sync 42
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 11
,E/Watchdog( 3527): !@Sync 43
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3527): stay LED for fully charged
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 10
,I/PowerManagerService( 3527): [PWL] Off : 1265s ago
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10848): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 12
,E/Watchdog( 3527): !@Sync 44
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 12
,TIME-OUT KILL (timeout was 1200000ms),D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
D/BatteryService( 3527): stay LED for fully charged
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService(10848): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10848): Disconnected process message: 10
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(13726): 
D/AndroidRuntime(13726): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13726): CheckJNI is OFF
D/AndroidRuntime(13726): readGMSProperty: start
D/AndroidRuntime(13726): readGMSProperty: already setted!!
D/AndroidRuntime(13726): readGMSProperty: end
D/AndroidRuntime(13726): addProductProperty: start
E/AffinityControl(13726): AffinityControl: registerfunction enter
D/AndroidRuntime(13726): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 3527): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3527): START PACKAGE DELETE: observer{933335371}
D/PackageManager( 3527): pkg{<packageName>}
D/PackageManager( 3527): user{0}
D/PackageManager( 3527): caller{2000}
D/PackageManager( 3527): flags{3}
D/PersonaManagerService( 3527): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3527): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3527): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3527): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3527): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3527): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3527): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3527): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3527): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3527): !@killApplicatoin: 10592, uninstall pkg
I/ActivityManager( 3527): Force stopping com.test.thalitest appid=10592 user=-1: uninstall pkg
I/ActivityManager( 3527): Killing 10777:com.test.thalitest/u0a592 (adj 0): stop com.test.thalitest
I/ActivityManager( 3527):   Force finishing activity ActivityRecord{39d00202 u0 com.test.thalitest/.MainActivity t25}
I/SurfaceFlinger( 2855): id=11 Removed NainActivit (6/8)
I/SurfaceFlinger( 2855): id=11 Removed NainActivit (-2/8)
D/PointerIcon( 3527): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3527): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3527): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3527): setHoveringSpenCustomIcon IconType is same.1
W/PackageSettings( 3527): Skipping PackageSetting{3977e6d2 com.example.hello/10563} due to missing metadata
I/ActivityManager( 3527): Force stopping com.test.thalitest appid=10592 user=0: pkg removed
D/WifiService( 3527): Client connection lost with reason: 4
I/art     (12012): Explicit concurrent mark sweep GC freed 56(14KB) AllocSpace objects, 0(0B) LOS objects, 19% free, 33MB/41MB, paused 938us total 40.397ms
I/art     ( 7947): Explicit concurrent mark sweep GC freed 25365(1476KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.155ms total 37.288ms
I/art     ( 4473): Explicit concurrent mark sweep GC freed 3216(142KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 31MB/39MB, paused 2.232ms total 74.238ms
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader( 3527): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 4257): Ignoring removeGeofence because network location is disabled.
I/art     ( 4050): Explicit concurrent mark sweep GC freed 12483(735KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 918us total 69.923ms
E/SamsungIME( 4456): mOCRHelper is null
D/LocationWidgetApplication(12012): getLastUiLocationId() : mLastUiLocationId = -100
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/Zygote  (13744): MountEmulatedStorage()
E/Zygote  (13744): v2
I/libpersona(13744): KNOX_SDCARD checking this for 10063
I/libpersona(13744): KNOX_SDCARD not a persona
I/SELinux (13744): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3527): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13744 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (13744): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13744): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourceType( 4963): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4963): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
D/TimaKeyStoreProvider(13744): TimaSignature is unavailable
D/ActivityThread(13744): Added TimaKeyStore provider
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ResourcesManager(13744): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
I/art     ( 3527): Explicit concurrent mark sweep GC freed 58514(5MB) AllocSpace objects, 173(2MB) LOS objects, 24% free, 49MB/65MB, paused 2.223ms total 190.828ms
D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     ( 3527): WaitForGcToComplete blocked for 99.638ms for cause Explicit
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/SecContentProvider2( 3527): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3527): mCursor = null
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/VRSetupWizardStub/PackageIntentReceiver(13744): onReceive()
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/VRSetupWizardStub/PackageIntentReceiver(13744): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13744): packagename:com.test.thalitest
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
E/Zygote  (13761): MountEmulatedStorage()
E/Zygote  (13761): v2
I/libpersona(13761): KNOX_SDCARD checking this for 10021
I/libpersona(13761): KNOX_SDCARD not a persona
I/SELinux (13761): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13761): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/SELinux (13761): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=13761 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3527): Killing 11786:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/RegisteredServicesCache( 3956): empty dynamic service
D/TimaKeyStoreProvider(13761): TimaSignature is unavailable
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
D/ActivityThread(13761): Added TimaKeyStore provider
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(13761): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
W/ResourcesManager(12012): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/KLMS-2.4.521: (13761): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 21 10:39:25 GMT+01:00 2016
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Books/Books.apk
I/KLMS-2.4.521: (13761): KLMSAbstractReciever(): onReceive().END.
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/splitIntent( 3527): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3527): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/KLMS-2.4.521: (13761): KLMSIntentService(): onCreate()
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/elm:14491(11861): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/KLMS-2.4.521: (13761): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (13761): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/KLMS-2.4.521: (13761): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
I/KLMS-2.4.521: (13761): KLMSIntentService(): PACKAGE_REMOVED
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/ResourcesManager(12012): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12012): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12012): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12012): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
I/KLMS-2.4.521: (13761): KLMSIntentService(): listeningToPackageRemoved().START
I/art     ( 3527): Explicit concurrent mark sweep GC freed 10804(539KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.660ms total 145.907ms
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/KLMS-2.4.521: (13761): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/elm:14491(11861): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
D/elm:14491(11861): ElmAgentService : onCreate()
D/elm:14491(11861): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(11861): MainReceiver.listeningToPackageRemoved()
D/elm:14491(11861): MDMBridge.getInstance()
D/elm:14491(11861): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491(11861): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/Zygote  (13779): MountEmulatedStorage()
I/libpersona(13779): KNOX_SDCARD checking this for 10160
E/Zygote  (13779): v2
I/libpersona(13779): KNOX_SDCARD not a persona
I/SELinux (13779): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux (13779): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/RCPManager(12526):  in createShortcut() for packageName: com.test.thalitest userId0
E/SELinux (13779): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=13779 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/RCPManagerService( 3527):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3527): queryAllProviders():  providerCallBack is not register for 0
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/PackageManager( 3527): delete codoeFile: 
I/AASAUninstall( 3527):  com.test.thalitest not target!
D/PackageManager( 3527): result of delete: 1{933335371}
D/elm:14491(11861): ElmAgentService : onDestroy().
D/RCPManagerService( 3527): PackageReceiver onReceive()
I/HarmonyEASService( 3527): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 3527): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3527): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3527): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3527): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3527): uID is 10592
V/EnterpriseBillingPolicy( 3527): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3527): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3527): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3527): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3527): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3527): getBillingProfileForVpnEngine - start - com.test.thalitest
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
V/EnterpriseBillingPolicyStorage( 3527): getBillingProfileForVpnEngine - end - null
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8749(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 836us total 23.570ms
D/com.sec.android.service.health.upgrade.UninstallReceiver(11731): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(11731): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(11731): onReceive() : package name is not s health. Return !!!
D/ResourcesManager(12012): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/AndroidRuntime(13726): Shutting down VM
D/TaskPersister( 3527): removeObsoleteFile: deleting file=25_task.xml
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 794us total 18.189ms
D/TimaKeyStoreProvider(13779): TimaSignature is unavailable
D/ActivityThread(13779): Added TimaKeyStore provider
D/ResourcesManager(12012): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 240us total 7.807ms
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
D/LocationWidgetApplication(12012): getLastUiLocationId() : mLastUiLocationId = -100
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (13761): KLMSIntentService(): listeningToPackageRemoved().END
D/ResourcesManager(13779): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/ResourcesManager(13779): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13779): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13779): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
E/Zygote  (13795): MountEmulatedStorage()
E/Zygote  (13795): v2
I/libpersona(13795): KNOX_SDCARD checking this for 10052
I/libpersona(13795): KNOX_SDCARD not a persona
I/SELinux (13795): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13795): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=13795 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux (13795): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
E/Zygote  (13808): MountEmulatedStorage()
I/libpersona(13808): KNOX_SDCARD checking this for 1000
E/Zygote  (13808): v2
I/libpersona(13808): KNOX_SDCARD not a persona
I/SELinux (13808): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13808): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=13808 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (13808): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(13795): TimaSignature is unavailable
D/ActivityThread(13795): Added TimaKeyStore provider
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (13761): KLMSIntentService(): onDestroy()
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
E/Zygote  (13823): MountEmulatedStorage()
E/Zygote  (13823): v2
I/libpersona(13823): KNOX_SDCARD checking this for 1000
I/libpersona(13823): KNOX_SDCARD not a persona
I/SELinux (13823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(13808): TimaSignature is unavailable
I/ActivityManager( 3527): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=13823 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ActivityThread(13808): Added TimaKeyStore provider
D/TimaKeyStoreProvider(13823): TimaSignature is unavailable
D/ActivityThread(13823): Added TimaKeyStore provider
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(13795): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/ActivityManager( 3527): Killing 11805:com.sec.android.app.clockpackage/u0a94 (adj 13): bgCount ##31
V/Common  (13779): getScreenSize 1440 2560
D/ResourcesManager(13823): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/ResourcesManager(13808): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
W/ResourcesManager(13795): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13795): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13795): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13795): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13795): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(13795): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/JAM     (13779): Load The ApaService JNI
I/PCWCLIENTTRACE_LOG(13823): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(13823): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(13823): new DMDBOpenHelper instance
I/JAM     (13779): version: ProfessionalAudio_v1.0.b5
I/JAM     (13779): Try v1.0.b3 ...
D/Spen    (13779): SpenSdk version level = 55
D/Spen    (13779): SpenSdk jar version = 3.0.243
D/Spen    (13779): SpenSdk apk version = 3.0.235
D/Spen    (13779): Server UPDATE Check
W/linker  (13779): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/SPenError(13779): JNI_OnLoad
D/JNI_Bitmap(13779): Init .. Done
D/SPenSpiDecoder(13779): JNI_OnLoad .. Done
D/SPenError(13779): JNI_OnLoad Success
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/PluginManager(13779): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(13779): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
D/Init_SPenSdk_Jni(13779): JNI_OnLoad
D/Init_SPenSdk_Jni(13779): AndroidSDK: 21
D/Init_SPenSdk_Jni(13779): JNI_OnLoad .. Done
E/Zygote  (13844): MountEmulatedStorage()
E/Zygote  (13844): v2
D/Model_ObjectBase_Jni(13779): JNI_OnLoad .. Done
D/Model_ObjectStroke_Jni(13779): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(13779): JNI_OnLoad .. Done
W/ContextImpl(13808): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
I/libpersona(13844): KNOX_SDCARD checking this for 10160
I/libpersona(13844): KNOX_SDCARD not a persona
D/Model_ObjectText_Jni(13779): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(13779): JNI_OnLoad .. Done
I/ActivityManager( 3527): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=13844 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
I/SELinux (13844): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/Model_PageDoc_Jni(13779): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni(13779): check build type eng[0]
D/Model_NoteDoc_Jni(13779): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(13779): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(13779): JNI_OnLoad .. Done
D/Model   (13779): OnLoad class Done
I/SELinux (13844): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13844): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/PCWCLIENTTRACE_PushUtil(13823): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(13823): sales region : global
I/PCWCLIENTTRACE_PushUtil(13823): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(13823): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/spe_log (13779): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
D/SPen_Library(13779): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(13779): Canvas JNI_OnLoad enter!!
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
D/SPen_Library(13779): Canvas JNI_OnLoad Success
D/SPen_Library(13779): TextView JNI_OnLoad enter!!
D/SPen_Library(13779): TextView JNI_OnLoad Success
D/SPen_Library(13779): Text JNI_OnLoad enter!!
D/SPen_Library(13779): Text JNI_OnLoad Success
D/SPen_Library(13779): FontManager JNI_OnLoad enter!!
D/SPen_Library(13779): FontManager JNI_OnLoad Success
D/SPen_Library(13779): CapturePage JNI_OnLoad enter!!
D/SPen_Library(13779): CapturePage JNI_OnLoad Success
D/SPen_Library(13779): Multi JNI_OnLoad enter!!
D/SPen_Library(13779): Multi JNI_OnLoad Success
D/SPen_Library(13779): Draw Engine JNI_OnLoad Success
D/SPen_Library(13779): Brush JNI_OnLoad enter!!
D/SPen_Library(13779): Brush JNI_OnLoad Success
D/SPen_Library(13779): ChineseBrush JNI_OnLoad enter!!
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/SPen_Library(13779): ChineseBrush JNI_OnLoad Success
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/SPen_Library(13779): InkPen JNI_OnLoad enter!!
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
D/SPen_Library(13779): InkPen JNI_OnLoad Success
D/ResourcesManager(12466): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/SPen_Library(13779): Marker JNI_OnLoad enter!!
D/SPen_Library(13779): Marker JNI_OnLoad Success
D/SPen_Library(13779): Pencil JNI_OnLoad enter!!
D/SPen_Library(13779): Pencil JNI_OnLoad Success
D/SPen_Library(13779): NativePen JNI_OnLoad enter!!
D/SPen_Library(13779): NativePen JNI_OnLoad Success
D/SPen_Library(13779): MontblancFountainPen JNI_OnLoad enter!!
D/SPen_Library(13779): MontblancFountainPen JNI_OnLoad Success
D/ResourcesManager(12012): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
D/SPen_Library(13779): MontblancCalligraphyPen JNI_OnLoad enter!!
D/SPen_Library(13779): MontblancCalligraphyPen JNI_OnLoad Success
W/ResourcesManager(12466): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/SPen_Library(13779): MagicPen JNI_OnLoad enter!!
D/SPen_Library(13779): MagicPen JNI_OnLoad Success
W/ResourcesManager(12466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/SPen_Library(13779): ObliquePen JNI_OnLoad enter!!
D/SPen_Library(13779): ObliquePen JNI_OnLoad Success
W/ResourcesManager(12466): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/SPen_Library(13779): FountainPen JNI_OnLoad enter!!
D/SPen_Library(13779): FountainPen JNI_OnLoad Success
D/Spen    (13779): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(13779): SPenSdk_init2
D/Init_SPenSdk(13779): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(13779): Total S Pen SDK Directory Size = 0
D/Spen    (13779): initialize complete

```
