#### Test 54970261c23922d_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 217, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
D/BatteryService( 3517): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(10881): 
D/AndroidRuntime(10881): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10881): CheckJNI is OFF
D/AndroidRuntime(10881): readGMSProperty: start
D/AndroidRuntime(10881): readGMSProperty: already setted!!
D/AndroidRuntime(10881): readGMSProperty: end
D/AndroidRuntime(10881): addProductProperty: start
D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 201, CUR = 28
E/AffinityControl(10881): AffinityControl: registerfunction enter
D/AndroidRuntime(10881): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3517): inState():  stateMachine is null !!
I/PersonaManagerService( 3517): PersonaId don't exist
I/ActivityManager( 3517): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3517): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3517): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3517): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3517): mDVFSHelper.acquire()
D/FocusedStackFrame( 3517): Set to : 0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/Zygote  (10899): MountEmulatedStorage()
E/Zygote  (10899): v2
I/libpersona(10899): KNOX_SDCARD checking this for 10530
I/libpersona(10899): KNOX_SDCARD not a persona
I/SELinux (10899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3517): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=10899 uid=10530 gids={50530, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (10899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10899): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10881): Shutting down VM
D/PointerIcon( 3517): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3517): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3517): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3517): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(10899): TimaSignature is unavailable
D/ActivityThread(10899): Added TimaKeyStore provider
V/WindowOrientationListener( 3517): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3517): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3517): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3517): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3517): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(10899): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2854): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2854): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 3997): updateVisibility : ActivityRecord{1c635da0 token=android.os.BinderProxy@37f3aa32 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3997): onTrimMemory. Level: 20
I/WebViewFactory(10899): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10899): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10899): Loading: webviewchromium
I/LibraryLoader(10899): Time to load native libraries: 3 ms (timestamps 6763-6766)
I/LibraryLoader(10899): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(10899): Binding Chromium to main looper Looper (main, tid 1) {32f2e4aa}
I/LibraryLoader(10899): Expected native library version number "",actual native library version number ""
I/chromium(10899): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10899): Initializing chromium process, renderers=0
,W/art     (10899): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10899): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10899): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10899): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10899): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothAdapter(10899): 949180571: getState() :  mService = null. Returning STATE_OFF
,W/chromium(10899): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10899): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10899): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10899): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(10899): CordovaWebView is running on device made by: samsung
,W/art     (10899): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10899): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(10899): performCreate Call secproduct feature valuefalse
D/Activity(10899): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(10899): Render dirty regions requested: true
,D/ActivityManager( 3517): post active user change for 0
D/KnoxTimeoutHandler( 3517): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3517): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2854): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3517): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3517): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3517): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3517): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3517): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3517): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(10899): Initialized EGL, version 1.4
,I/OpenGLRenderer(10899): HWUI protection enabled for context ,  &this =0xaf945060 ,&mEglDisplay = 1 , &mEglConfig = -1279758064 
,D/OpenGLRenderer(10899): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10899): Enabling debug mode 0
,D/mali_winsys(10899): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(10899): updateVisibility : ActivityRecord{b79e8b token=android.os.BinderProxy@3f097ad9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3517): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3517): mDVFSHelper.release()
I/Timeline( 3517): Timeline: Activity_windows_visible id: ActivityRecord{2d6ea1c8 u0 com.test.thalitest/.MainActivity t25} time:297208
,W/IInputConnectionWrapper(10899): showStatusIcon on inactive InputConnection
,I/Timeline(10899): Timeline: Activity_idle id: android.os.BinderProxy@3f097ad9 time:297215
,I/chromium(10899): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10899): 
,D/JsMessageQueue(10899): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(10899): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1362670976
D/JX-Cordova(10899): jxcore cordova android initializing
,I/art     (10899): Background sticky concurrent mark sweep GC freed 74788(7MB) AllocSpace objects, 15(3MB) LOS objects, 18% free, 34MB/42MB, paused 1.657ms total 102.463ms
,W/jxcore-log(10899): Initializing JXcore engine
W/jxcore-log(10899): JXcore engine is ready
,W/jxcore-log(10899): Starting JXcore engine
,I/art     (10899): Background partial concurrent mark sweep GC freed 63107(5MB) AllocSpace objects, 2(3MB) LOS objects, 28% free, 39MB/55MB, paused 7.509ms total 88.819ms
,E/auditd  ( 4541): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService( 3517): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService( 3517): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10899): Platform android
W/jxcore-log(10899): 
W/jxcore-log(10899): Process ARCH arm
W/jxcore-log(10899): 
,I/jxcore-log(10899): JXcore Cordova bridge is ready!
I/jxcore-log(10899): 
W/jxcore-log(10899): JXcore engine is started
,I/Choreographer(10899): Skipped 84 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log(10899): Toggling radios to true
I/jxcore-log(10899): 
,D/BluetoothAdapter(10899): enable()
,W/ActivityManager( 3517): Permission Denial: getCurrentUser() from pid=10899, uid=10530 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 3517): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 3517): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10899, uid=10530 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 3517): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/BluetoothManagerService( 3517): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2160)
W/BluetoothManagerService( 3517): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService( 3517): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 3517): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DevicePolicyManagerService( 3517): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3517): getAllowBluetoothMode - value retunrs : 2
D/SettingsProvider( 3517): name = bluetooth_on
,E/DevicePolicyManagerService( 3517): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3517): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/WifiManager(10899): packageName : com.test.thalitest
,D/SecContentProvider( 3517): uri = 18 selection = isWifiEnabled
D/WifiService( 3517): New client listening to asynchronous messages
D/SecContentProvider2( 3517): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3517): mCursor = null
,D/WifiService( 3517): setWifiEnabled: true pid=10899, uid=10530
E/WifiService( 3517): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3517): Permission Denial: getCurrentUser() from pid=10899, uid=10530 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3517): Failed getting userId using ActivityManagerNative
W/WifiService( 3517): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10899, uid=10530 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3517): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3517): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3517): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3517): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3517): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3517): name = wifi_on
,I/WifiService( 3517): disconnect: pid=10899, uid=10530
,E/WifiStateMachine( 3517): setting operational mode to 1
I/jxcore-log(10899): Radios toggled
I/jxcore-log(10899): 
,E/WifiHW  ( 3517): ##################### set firmware type 0 #####################
,E/Zygote  (10982): MountEmulatedStorage()
I/libpersona(10982): KNOX_SDCARD checking this for 1002
E/Zygote  (10982): v2
I/libpersona(10982): KNOX_SDCARD not a persona
I/WifiHW  ( 2847): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,I/SELinux (10982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/WifiHW  ( 2847): module is murata
E/WifiHW  ( 2847): ==========[WIFI] MURATA MODULE ===========
I/WifiHW  ( 2847): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_murata
,E/WifiHW  ( 2847): TEMP_FAILURE_RETRY complete
D/SoftapController( 2847): Softap fwReload - Ok
I/SELinux (10982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10982): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=10982 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/CommandListener( 2847): Setting iface cfg
,D/CommandListener( 2847): Trying to bring down wlan0
,D/CommandListener( 2847): Clearing all IP addresses on wlan0
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 449us total 12.449ms
,D/TimaKeyStoreProvider(10982): TimaSignature is unavailable
,D/ActivityThread(10982): Added TimaKeyStore provider
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 694us total 9.581ms
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 255us total 8.192ms
,D/ResourcesManager(10982): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(10982): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(10982): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni(10982): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig(10982): Adding GattService
,D/BtSettings.ProfileConfig(10982): Adding HeadsetService
D/BtSettings.ProfileConfig(10982): Adding A2dpService
D/BtSettings.ProfileConfig(10982): Adding HidService
,D/BtSettings.ProfileConfig(10982): Adding HealthService
D/BtSettings.ProfileConfig(10982): Adding PanService
D/BtSettings.ProfileConfig(10982): Adding BluetoothMapService
D/BtSettings.ProfileConfig(10982): Adding SapService
D/BtSettings.ProfileConfig(10982): Adding HeadsetClientService
D/BtSettings.ProfileConfig(10982): Adding A2dpSinkService
D/BtSettings.ProfileConfig(10982): Adding SapClientService
D/BtSettings.ProfileConfig(10982): Adding HidDevService
I/BtSettings.ProfileConfig(10982): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3517): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3517): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3517): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3517): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3517): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider( 3517): ret = -1
,D/SettingsProvider( 3517): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
,D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3517): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3517): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3517): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,E/WifiHW  ( 3517): supplicant_name : p2p_supplicant
D/SettingsProvider( 3517): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3517): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3517): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterState(10982): make
,I/bluedroid(10982): init
I/BluetoothAdapterState(10982): Entering OffState
,I/bte_conf(10982): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf(10982): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config(10982): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf(10982): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif (10982): btif_fetch_local_ble_random_bdaddr
,I/bluedroid(10982): get_profile_interface socket
I/bluedroid(10982): get_profile_interface map_client
D/BluetoothAdapterService(10982): checkAddrForIOP: Loading from conf
,D/BluetoothAdapterService(10982): Inband Ring is supported
,I/GKI_LINUX(10982): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties(10982): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10982): populateRssiValuesNative
I/bluedroid(10982): getModelRssiValues
E/BluetoothServiceJni(10982): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10982): modelRssiValuesCallback, low, mid, high = -75,-65,127
,D/BluetoothAdapterProperties(10982): Name is: Note4-1
,D/SettingsProvider( 3517): name = bluetooth_name
,I/wpa_supplicant(10997): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant(10997): Successfully initialized wpa_supplicant
,I/SecureStorage(10997): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/bluedroid(10982): config_hci_snoop_log
,D/BluetoothManagerService( 3517): Broadcasting onBluetoothServiceUp() to 11 receivers.
,I/SecureStorage(10997): [INFO]: SPID(0x00000000)This device supports Secure Storage
E/DevicePolicyManagerService( 3517): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3517): getAllowBluetoothMode - value retunrs : 2
,I/SecureStorage( 2918): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10997
I/SecureStorage( 2918): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,I/SecureStorage(10997): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant(10997): ssSupport state is = 1
I/wpa_supplicant(10997): >>>>> GET KEY, IV <<<<<
,D/SecContentProvider( 3517): uri = 3 selection = isBluetoothEnabled
,I/SecureStorage(10997): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 2918): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10997
I/SecureStorage( 2918): [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,D/BluetoothAdapterState(10982): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties(10982): Setting state to 11
I/BluetoothAdapterState(10982): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(10982): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10982): updateAdapterState state is 11
,D/BluetoothAdapterService(10982): Autoconnection is available 
D/BluetoothAdapterService(10982): updateAdapterState prevState = 10newState = 11
W/InputMethodManagerService( 3517): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3517): [BT Setting State] State =11
,D/BluetoothSecureManager(10982): getInstant: null
D/BluetoothSecureManager(10982): calling getMethod for getService
D/BluetoothSecureManager(10982): calling getService
,D/BluetoothSecureManager(10982): getService return binder: android.os.BinderProxy@105f5f02
D/BluetoothSecureManagerService( 3517): isSecureModeEnabled
,D/BluetoothTile( 3691):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3691): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/STATUSBAR-QSTileView( 3691): onStateChanged: Bluetooth
,D/BluetoothSecureManagerService( 3517): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode(10982): isSecureModeOn:false
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,I/SamsungIME( 4426): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService(10982): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService(10982): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/StatusBarManagerService( 3517): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
W/BluetoothAdapterService(10982): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/StatusBarManagerService( 3517): setIconVisibility slot=bluetooth visible=false
W/BluetoothAdapterService(10982): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10982): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10982): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10982): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/PhoneStatusBar( 3691): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
W/BluetoothAdapterService(10982): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService(10982): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10982): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService(10982): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService(10982): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
E/WifiStateMachine( 3517): setWifiState: enabling
D/BluetoothBondStateMachine(10982): make
,E/WifiStateMachine( 3517): Supplicant start successful
D/WifiMonitor( 3517): startMonitoring(wlan0) with mConnected = false
W/BluetoothAdapterService(10982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine(10982): StableState(): Entering Off State
W/BluetoothAdapterService(10982): Not skipping com.android.bluetooth.gatt.GattService
,I/BtGatt.JNI(10982): classInitNative(L900): classInitNative: Success!
,D/BtGatt.DebugUtils(10982): handleDebugAction() action=null
D/BtGatt.GattService(10982): Received start request. Starting profile...
D/BtGatt.GattService(10982): start()
I/bluedroid(10982): get_profile_interface gatt
,W/BluetoothAdapterService(10982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10982): Not skipping com.android.bluetooth.hfp.HeadsetService
V/[CarModeFW](10111): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
D/BluetoothAdapterService(10982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32f2e4aa
D/BtGatt.AdvertiseManager(10982): advertise manager created
D/SmartBondingService( 3517): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3517): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService( 3517): getNetworkEnabled : wifi : false mobile : false
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 3691): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3691): Wifi onReceive(2)
D/HotspotTile( 3691): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 3691): onStateChanged: Wi-Fi
D/HotspotTile( 3691): onReceive : 2, 0
,W/BluetoothAdapterService(10982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10982): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService(10982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(10982): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService(10982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10982): Not skipping com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService(10982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32f2e4aa
,W/BluetoothAdapterService(10982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10982): Not skipping com.android.bluetooth.pan.PanService
,D/BluetoothNotiBroadcastReceiver(10039): onReceive
,W/BluetoothAdapterService(10982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10982): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/HeadsetService(10982): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni(10982): classInitNative: succeeds
D/HeadsetStateMachine(10982): make
,E/HeadsetStateMachine(10982): # of Max HF connection is 2
,W/BluetoothAdapterService(10982): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10982): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService(10982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10982): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10982): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10982): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig(10982): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService(10982): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,I/BluetoothAdapterState(10982): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid(10982): get_profile_interface handsfree
,I/DualScoManager(10982): Instantiating Dual Sco Manager
I/DualScoManager(10982): Set HeadsetServiceHelper
,D/BluetoothAtMessage(10982): createCMTIContentObservers
,D/SettingsProvider( 3517): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine(10982): Enter Disconnected: -2
,E/HeadsetStateMachine(10982): set to mRemoteBrsf = 0
D/BluetoothAdapterService(10982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32f2e4aa
,D/HeadsetStateMachine(10982): map size, before remove : 0
D/HeadsetStateMachine(10982): map size, after remove: 0
,D/BluetoothA2dp( 4807): Proxy object connected
D/A2dpService(10982): Received start request. Starting profile...
D/BluetoothA2dp( 3517): Proxy object connected
,I/BluetoothAvrcpServiceJni(10982): classInitNative: succeeds
V/Avrcp   (10982): make
V/Avrcp   (10982): Avrcp
I/bluedroid(10982): get_profile_interface avrcp
,V/Avrcp   (10982): start
,E/RemoteController(10982): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   (10982): ++registerMediaPlayers++
,I/Avrcp   (10982): No of Audio players :: 2
I/Avrcp   (10982): App Package name is com.google.android.music
,D/ResourcesManager(10982): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   (10982): App pkg name is Google Play Music
,I/Avrcp   (10982): Name::Google Play Music
V/Avrcp   (10982): MediaPlayerInfo: mPlayerId=1
I/Avrcp   (10982): App Package name is com.sec.android.app.music
,D/ResourcesManager(10982): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   (10982): App pkg name is Music
I/Avrcp   (10982): Name::Music
V/Avrcp   (10982): MediaPlayerInfo: mPlayerId=2
,I/Avrcp   (10982): No of Video players :: 1
I/Avrcp   (10982): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager(10982): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   (10982): Video App pkg name is Video Player
I/Avrcp   (10982): Name::Video Player
V/Avrcp   (10982): MediaPlayerInfo: mPlayerId=3
I/Avrcp   (10982): Add tempPlayer
V/Avrcp   (10982): MediaPlayerInfo: mPlayerId=4
I/Avrcp   (10982): Total no of players: 4
V/Avrcp   (10982): swapping the samsung player with 1st player
I/Avrcp   (10982):  Updating now playing list upon AVRCP Start
,V/Avrcp   (10982): handleMessage, msg=207
D/BluetoothMediaBrowser(10982):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
V/Avrcp   (10982): CurrentAudioFocusPackageName is null
I/Avrcp   (10982): There is no currently selected player ,setting Samsung Music Player ID
I/Avrcp   (10982):  set player publishabilty with player id::1 toBePublished ::true
,I/BluetoothA2dpServiceJni(10982): classInitNative: succeeds
D/A2dpStateMachine(10982): make
I/bluedroid(10982): get_profile_interface a2dp
I/GKI_LINUX(10982): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif (10982): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService(10982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32f2e4aa
D/A2dpStateMachine(10982): Enter Disconnected: -2
,I/BluetoothHidServiceJni(10982): classInitNative: succeeds
,D/HidService(10982): Received start request. Starting profile...
I/bluedroid(10982): get_profile_interface hidhost
D/HidService(10982): setHidService(): set to: null
D/BluetoothAdapterService(10982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32f2e4aa
E/BluetoothAdapterService(854779050)(10982): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
I/BluetoothHealthServiceJni(10982): classInitNative: succeeds
,D/HealthService(10982): Received start request. Starting profile...
,I/bluedroid(10982): get_profile_interface health
D/BluetoothAdapterService(10982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32f2e4aa
,I/BluetoothPanServiceJni(10982): classInitNative(L105): succeeds
,D/BluetoothPan( 3517): BluetoothPAN Proxy object connected
,D/PanService(10982): Received start request. Starting profile...
D/BluetoothPanServiceJni(10982): initializeNative(L110): pan
I/bluedroid(10982): get_profile_interface pan
D/BluetoothAdapterService(10982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32f2e4aa
,D/BluetoothMapService(10982): Received start request. Starting profile...
,D/BluetoothMediaBrowser(10982): no now playing list
D/BluetoothMediaBrowser(10982):  getNowPlayingId now playing id : -1
D/Avrcp   (10982):  checkNowPlayingList start
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11015): MountEmulatedStorage()
E/Zygote  (11015): v2
I/libpersona(11015): KNOX_SDCARD checking this for 10178
I/libpersona(11015): KNOX_SDCARD not a persona
,I/SELinux (11015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3517): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=11015 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux (11015): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11015): TimaSignature is unavailable
,D/ActivityThread(11015): Added TimaKeyStore provider
,D/ResourcesManager(11015): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(11015): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(11015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11015): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11015): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(11015): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3517): exchangeData() failure , invalid userId
,D/RCPManagerService( 3517): exchangeData() failure , invalid userId
,D/RCPManagerService( 3517): exchangeData() failure , invalid userId
,I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,D/BadgeProvider(10019): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BluetoothAdapterService(10982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32f2e4aa
,I/BluetoothSAPServiceJni(10982): classInitNative(L204): succeeds
,D/AuthorizationBluetoothService( 4247): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/SapService(10982): Received start request. Starting profile...
D/BluetoothSAPServiceJni(10982): initializeNative(L209): sap
I/bluedroid(10982): get_profile_interface sap
D/BluetoothAdapterService(10982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32f2e4aa
D/HeadsetStateMachine(10982): Try to query the phonestate on bind
,D/RCPManagerService( 3517): exchangeData() failure , invalid userId
I/Telecom ( 3949): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 3949): BluetoothPhoneService: updateHeadsetWithCallState
,I/Hs20UtilService( 6329): Starting #2
,I/Hs20UtilService( 6329): Message received 5011
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/Telecom ( 3949): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 3949): Proxy not attached to service
,D/HeadsetStateMachine(10982): Proxy object connected
D/HeadsetPhoneState(10982): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState(10982): sendDeviceDataStateChanged
D/HeadsetStateMachine(10982): Disconnected process message: 11
D/HeadsetStateMachine(10982): Disconnected process message: 18
D/HeadsetPhoneState(10982): Signal level : previous=0 curr=0
E/BluetoothAdapterService(854779050)(10982): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
D/BluetoothA2dp(10982): Proxy object connected
D/BluetoothAdapterService(10982): Bluetooth A2dp source service connected
E/BluetoothAdapterService(854779050)(10982): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(854779050)(10982): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/HeadsetPhoneState(10982): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
E/BluetoothAdapterService(854779050)(10982): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/HeadsetStateMachine(10982): Disconnected process message: 11
E/BluetoothAdapterService(854779050)(10982): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,E/Zygote  (11038): MountEmulatedStorage()
E/Zygote  (11038): v2
I/libpersona(11038): KNOX_SDCARD checking this for 10127
I/libpersona(11038): KNOX_SDCARD not a persona
,I/SELinux (11038): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11038): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11038): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=11038 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3517): Killing 9987:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,E/BluetoothAdapterService(854779050)(10982): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BadgeProvider(10019): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10019): sendNotify, [notify] : null
E/BluetoothAdapterService(854779050)(10982): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BadgeProvider(10019): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10019): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10019): update, [UpdateCount] : 1
,D/BluetoothAdapterState(10982): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid(10982): enable
D/Launcher.Model( 3997): reloadBadges entered.
,I/bt_hci_bdroid(10982): init
I/GKI_LINUX(10982): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor(10982): init
I/bt_vnd_conf(10982): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf(10982): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial(10982): userial_init
,D/TimaKeyStoreProvider(11038): TimaSignature is unavailable
,D/ActivityThread(11038): Added TimaKeyStore provider
,I/art     ( 3517): Explicit concurrent mark sweep GC freed 50112(3MB) AllocSpace objects, 61(976KB) LOS objects, 24% free, 48MB/64MB, paused 1.200ms total 81.455ms
,D/ResourcesManager(11038): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,W/ActivityManager( 3517): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/bt_userial_vendor(10982): userial vendor open: opening /dev/ttySAC3
,I/bt_userial_vendor(10982): userial_vendor_open():UART is setup
I/bt_userial_vendor(10982): device fd = 65 open
E/bt_hwcfg(10982): Start CFG HW, HCI reset
D/bt_userial(10982): Entering userial_read_thread()
,E/bt_hwcfg(10982): Read Local Name after HCI reset
,D/KeyguardWallpaperUpdator(11038): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11038): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11038): stopCheckCategoryVersion
,I/SignOutReceiver(10393): WIFI_STATE_CHANGED_ACTION
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11063): MountEmulatedStorage()
E/Zygote  (11063): v2
I/libpersona(11063): KNOX_SDCARD checking this for 1000
I/libpersona(11063): KNOX_SDCARD not a persona
,I/SELinux (11063): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11063): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11063): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=11063 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/bt_hwcfg(10982): Chipset BCM43569A1
D/bt_hwcfg(10982): Target name = [BCM4358A1]
,I/bt_hwcfg(10982): module_type[murata].
I/bt_hwcfg(10982): module_type[murata] is invalid.
E/bt_hwcfg(10982): patchram path ORG . BCM4358A1
E/bt_hwcfg(10982): patchram path ORG .. BCM4358A1
E/bt_hwcfg(10982): patchram path ORG bcm4358A0_V0033.0000.hcd BCM4358A1
E/bt_hwcfg(10982): patchram path ORG bcm4358A1_V0044.0078.hcd BCM4358A1
I/bt_hwcfg(10982): patch(org) : bcm4358A1_V0044.0078.hcd
I/bt_hwcfg(10982): Found patchfile: /vendor/firmware/bcm4358A1_V0044.0078.hcd
E/bt_hwcfg(10982): ORG patchram base 0044
E/bt_hwcfg(10982): ORG patchram minor 0078
E/bt_hwcfg(10982): fw ver (org)44.78
E/bt_hwcfg(10982): Final Patchram is /vendor/firmware/bcm4358A1_V0044.0078.hcd
,I/ActivityManager( 3517): Killing 10001:com.policydm/1000 (adj 13): bgCount ##31
,I/bt_hwcfg(10982): Axi patch failure or not include AXI patching
,I/bt_hwcfg(10982): bt vendor lib: set UART baud 3000000
,D/TimaKeyStoreProvider(11063): TimaSignature is unavailable
D/ActivityThread(11063): Added TimaKeyStore provider
,D/ResourcesManager(11063): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11079): MountEmulatedStorage()
I/libpersona(11079): KNOX_SDCARD checking this for 10186
E/Zygote  (11079): v2
I/libpersona(11079): KNOX_SDCARD not a persona
,I/SELinux (11079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11079): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3517): Start proc tv.peel.smartremote for broadcast tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver: pid=11079 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 3517): Killing 10056:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,I/SecureStorage(10997): [INFO]: SPID(0x00000005)Processing data has been completed
,D/TimaKeyStoreProvider(11079): TimaSignature is unavailable
,D/ActivityThread(11079): Added TimaKeyStore provider
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,W/ResourcesManager(11079): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/SecureStorage(10997): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10997): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10997
I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,I/SecureStorage(10997): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10997): ssSupport state is = 1
,I/wpa_supplicant(10997): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant(10997): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10997): SIM READ ERROR
I/wpa_supplicant(10997): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10997): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10997): SIM READ ERROR
I/wpa_supplicant(10997): Blacklist: Clear (all) 
I/wpa_supplicant(10997): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10997): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant(10997): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10997): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant(10997): rfkill: Cannot open RFKILL control device
,I/WebViewFactory(11079): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11079): Loading: webviewchromium
,I/LibraryLoader(11079): Time to load native libraries: 3 ms (timestamps 9843-9846)
I/LibraryLoader(11079): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11079): Binding Chromium to main looper Looper (main, tid 1) {2ae45f4c}
,I/LibraryLoader(11079): Expected native library version number "",actual native library version number ""
,I/chromium(11079): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11079): Initializing chromium process, renderers=0
,W/art     (11079): Attempt to remove local handle scope entry from IRT, ignoring
,I/bt_hwcfg(10982): bt vendor lib: set UART baud 115200
I/bt_hwcfg(10982): FW Download delta = 507051
D/bt_hwcfg(10982): Settlement delay -- 100 ms
I/bt_hwcfg(10982): Setting fw settlement delay to 100 
,I/bt_hwcfg(10982): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg(10982): vendor lib fwcfg completed
,I/        (10982): BTE_InitTraceLevels -- TRC_HCI
I/        (10982): BTE_InitTraceLevels -- TRC_L2CAP
I/        (10982): BTE_InitTraceLevels -- TRC_RFCOMM
I/        (10982): BTE_InitTraceLevels -- TRC_AVDT
I/        (10982): BTE_InitTraceLevels -- TRC_AVRC
I/        (10982): BTE_InitTraceLevels -- TRC_A2D
I/        (10982): BTE_InitTraceLevels -- TRC_BNEP
I/        (10982): BTE_InitTraceLevels -- TRC_BTM
I/        (10982): BTE_InitTraceLevels -- TRC_GAP
I/        (10982): BTE_InitTraceLevels -- TRC_PAN
I/        (10982): BTE_InitTraceLevels -- TRC_SAP
I/        (10982): BTE_InitTraceLevels -- TRC_SDP
I/        (10982): BTE_InitTraceLevels -- TRC_GATT
I/        (10982): BTE_InitTraceLevels -- TRC_SMP
I/        (10982): BTE_InitTraceLevels -- TRC_BTAPP
I/        (10982): BTE_InitTraceLevels -- TRC_BTIF
I/        (10982): BTE_InitTraceLevels -- TRC_PROTOCOL
,W/bt-l2cap(10982): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  (10982): BTM_SecRegister:p_cb_info->p_le_callback == 0xb390f9e1 
E/bt-btm  (10982): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb390f9e1 
,E/Tethering( 3517): No numeric data
W/chromium(11079): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,D/Tethering( 3517): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 3517): forceRefresh() from cache miss
,W/chromium(11079): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
D/HotspotTile( 3691): onReceive : android.net.conn.TETHER_STATE_CHANGED
I/chromium(11079): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
D/HotspotTile( 3691): updateTetherState():false, false
I/chromium(11079): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 3517): forceRefresh Fail.
,V/NetworkStats( 3517): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3517): UpdateStatsForKnox
,V/NetworkStats( 3517): performPollLocked() took 3ms
,D/NtpTrustedTime( 3517): forceRefresh() from cache miss
,D/NtpTrustedTime( 3517): forceRefresh Fail.
,I/wpa_supplicant(10997): wlan0: Setting scan request: 0 sec 100000 usec
,W/chromium(11079): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11079): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/wpa_supplicant(10997): wlan0: State: DISCONNECTED -> DISCONNECTED
I/SecureStorage(10997): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10997): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10997
I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10997): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10997): ssSupport state is = 1
,I/SecureStorage(10997): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,W/art     (11079): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11079): onDetachedFromWindow called when already detached. Ignoring
,I/SecureStorage(10997): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10997
I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10997): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10997): ssSupport state is = 1
I/wpa_supplicant(10997): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10997): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10997): SIM READ ERROR
I/wpa_supplicant(10997): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant(10997): nl80211: Could not configure driver mode
E/wpa_supplicant(10997): p2p0: Failed to initialize driver interface
I/wpa_supplicant(10997): Blacklist: Clear (all) 
,I/SecureStorage(10997): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10997): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10997
I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10997): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10997): ssSupport state is = 1
I/SecureStorage(10997): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10997): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10997
I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10997): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10997): ssSupport state is = 1
I/wpa_supplicant(10997): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10997): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10997): SIM READ ERROR
I/wpa_supplicant(10997): rfkill: Cannot open RFKILL control device
,D/BluetoothAdapterProperties(10982): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif (10982): Calling BTA_HhEnable
,E/bt-btif (10982): BTM_SEC_REG[8get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties(10982): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10982): populateRssiValuesNative
I/bluedroid(10982): getModelRssiValues
E/BluetoothServiceJni(10982): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10982): modelRssiValuesCallback, low, mid, high = -75,-65,127
,D/BluetoothAdapterProperties(10982): Name is: Note4-1
D/SettingsProvider( 3517): name = bluetooth_name
D/BluetoothAdapterProperties(10982): Scan Mode:20
D/BluetoothAdapterProperties(10982): Discoverable Timeout:120
,D/BluetoothAdapterProperties(10982): LE Address is:E0:B7:20:28:C5:81
E/bt-btif (10982): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif (10982): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif (10982): btif_sock_init: !radio_req && !rfc_init
E/bt-btif (10982): btif_sock_init: !vhci_init
,D/IOP_DB_BT(10982): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT(10982): db_open: db_open : handle 3025047568l, read 14063 bytes onto local cache
D/IOP_DB_BT(10982): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT(10982): db_query: result 1
I/        (10982): iop_db_open: iop_db_open status 0
,D/bte_conf(10982): Device ID record 1 : primary
D/bte_conf(10982):   vendorId            = 0075
D/bte_conf(10982):   vendorIdSource      = 0001
D/bte_conf(10982):   product             = 0100
D/bte_conf(10982):   version             = 0200
D/bte_conf(10982):   clientExecutableURL = 
D/bte_conf(10982):   serviceDescription  = 
D/bte_conf(10982):   documentationURL    = 
D/bte_conf(10982): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni(10982): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState(10982): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties(10982): ScanMode =  20
D/BluetoothAdapterProperties(10982): State =  11
D/SecContentProvider( 3517): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties(10982): Setting state to 12
I/BluetoothAdapterState(10982): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties(10982): Scan Mode:21
D/BluetoothAdapterProperties(10982): Discoverable Timeout:120
,D/SettingsProvider( 3517): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 1002
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService(10982): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10982): updateAdapterState state is 12
,D/BluetoothAdapterService(10982): Autoconnection is available 
D/BluetoothAdapterService(10982): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService(10982): starting service from this receiver
,D/BluetoothA2dp(10982): onBluetoothStateChange: up=true
,I/BluetoothAdapterState(10982): Entering On State from state = 11
,D/BluetoothA2dp( 3517): onBluetoothStateChange: up=true
,E/bt_h4   (10982): vendor lib postload completed
D/BluetoothA2dp( 4807): onBluetoothStateChange: up=true
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/BluetoothPbapService(10982): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,I/wpa_supplicant(10997): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant(10997): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,E/Zygote  (11142): MountEmulatedStorage()
E/Zygote  (11142): v2
I/libpersona(11142): KNOX_SDCARD checking this for 10110
I/libpersona(11142): KNOX_SDCARD not a persona
,I/SELinux (11142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3517): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11142 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11142): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Killing 10072:com.wsomacp/u0a28 (adj 13): bgCount ##31
,W/InputMethodManagerService( 3517): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3517): [BT Setting State] State =12
I/InputMethodManagerService( 3517): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothTile( 3691):  onBluetoothStateChange:
,D/BluetoothTile( 3691):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3691): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
I/SamsungIME( 4426): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothHeadset( 3949): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2fe48c44, true
,D/BluetoothHeadset( 3949): registerMessageListener
,D/StatusBarManagerService( 3517): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3517): setIconVisibility slot=bluetooth visible=true
,D/BluetoothTile( 3691):  handleUpdatestate:false name:null
D/PhoneStatusBar( 3691): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
D/STATUSBAR-QSTileView( 3691): onStateChanged: Bluetooth
D/TimaKeyStoreProvider(11142): TimaSignature is unavailable
D/ActivityThread(11142): Added TimaKeyStore provider
,D/HeadsetService(10982): registerMessageListener
,D/HeadsetService(10982): registerMessageListener
D/HeadsetStateMachine(10982): Disconnected process message: 70
D/HeadsetStateMachine(10982): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@16e15647
I/Telecom ( 3949): BluetoothPhoneService: updateHeadsetWithCallState
I/Telecom ( 3949): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,I/wpa_supplicant(10997): p2p0: State: INACTIVE -> DISCONNECTED
,I/wpa_supplicant(10997): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant(10997): Skip scan - bUseNetwork false
,D/HeadsetStateMachine(10982): Disconnected process message: 9
E/WifiStateMachine( 3517): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,E/WifiStateMachine( 3517): setSuspendOptimizations: 2 true
E/WifiStateMachine( 3517): mSuspendOptNeedsDisabled 0
D/HeadsetStateMachine(10982): mNumActive: 0 mNumHeld: 0 mCallState: 6
E/WifiStateMachine( 3517): Supplicant connection established
,D/WifiNative-HAL( 3517): callSECApiBoolean - ID [21]
,I/wpa_supplicant(10997): HOTSPOT20_ENABLE called
I/wpa_supplicant(10997): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10997): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10997): SIM READ ERROR
I/wpa_supplicant(10997): Blacklist: Clear (all) 
I/BluetoothPbapService(10982): Handler(): got msg=1
,D/SecContentProvider( 3517): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
V/[CarModeFW](10111): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
D/[CarModeFW](10111): ConnectivityManager-handleMessage INITIAL_STATE_ON
,D/ResourcesManager(11142): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,I/wpa_supplicant(10997): wlan0: Setting scan request: 0 sec 0 usec
,I/AudioHardwareTinyALSA( 2859): setParameters(A2dpSuspended=false)
E/HeadsetStateMachine(10982): terminateScoUsingVirtualVoiceCall:No present call to terminate
,V/BluetoothPbapService(10982): PBAP Service initSocket try: 0
,I/wpa_supplicant(10997): Skip scan - bUseNetwork false
,E/WifiStateMachine( 3517): setWifiState: enabled
D/BluetoothManagerService( 3517): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/WifiNative-HAL( 3517): callSECApiInt - ID [210]
,W/BluetoothAdapter(10982): getBluetoothService() called with no BluetoothManagerCallback
D/SmartBondingService( 3517): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/WifiConfigStore( 3517): Loading config and enabling all networks 
D/SmartBondingService( 3517): getNetworkEnabled : wifi : true mobile : false
,D/BluetoothMapMasInstance(10982): set MAP SDP message type : 1
D/SLocation( 3517): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/HotspotTile( 3691): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3691): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3691): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 3691): onStateChanged: Wi-Fi
D/BluetoothSocket(10982): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket(10982): bindListen(), new LocalSocket 
D/BluetoothSocket(10982): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10982): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cd30fe3
D/BluetoothSocket(10982): channel: 19
D/HotspotTile( 3691): onReceive : 3, 0
D/BluetoothPbapService(10982): PBAP Socket is BluetoothServerSocket
,W/BluetoothAdapter(10982): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10982): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket(10982): bindListen(), new LocalSocket 
D/BluetoothSocket(10982): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10982): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11471de0
D/BluetoothSocket(10982): channel: 5
,E/WifiConfigStore( 3517): Not a HS20
,E/WifiConfigStore( 3517): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/WifiStateMachine( 3517): update LTECoexState:0
D/WifiNative-HAL( 3517): callSECApiInt - ID [65]
,D/WifiNative-HAL( 3517): callSECApiBoolean - ID [13]
,I/wpa_supplicant(10997): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant(10997): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant(10997): reset timer : RESET_TIMER 0
I/wpa_supplicant(10997): P2P: Current p2p state = IDLE
I/wpa_supplicant(10997): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant(10997): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant(10997): First Scan Start
,I/wpa_supplicant(10997): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL( 3517): Setting external_sim to 1
D/WifiStateMachine( 3517): Setting OUI to DA-A1-19
I/WifiNative-HAL( 3517): startHal
E/wifi    ( 3517): getStaticLongField sWifiHalHandle 0x8f80c85c
D/wifi    ( 3517): halHandle = 0x0, mVM = 0xb4d5c280, mCls = 0xb01ea6
I/WifiNative-HAL( 3517): Could not start hal
,E/WifiStateMachine( 3517): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,E/WifiStateMachine( 3517): Attempting to reconnect to wifi network ..
,E/native  ( 3517): do suspend true
,E/WifiStateMachine( 3517): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiP2pService( 3517): P2pDisabledState{ what=131203 }
D/WifiStateMachine( 3517): updateConfiguredNetworkExpiration - currTime: 1451923680583
D/WifiStateMachine( 3517): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/WifiScanningService( 3517): SCAN_AVAILABLE : 3
D/RttService( 3517): SCAN_AVAILABLE : 3
D/RttService( 3517): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 3517): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 3517): startHal
E/wifi    ( 3517): getStaticLongField sWifiHalHandle 0x8e5c498c
E/WifiStateMachine( 3517): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/wifi    ( 3517): halHandle = 0x0, mVM = 0xb4d5c280, mCls = 0xa01e9a
E/WifiStateMachine( 3517): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
I/WifiNative-HAL( 3517): Could not start hal
E/WifiScanningService( 3517): could not start HAL
D/CommandListener( 2847): Setting iface cfg
D/CommandListener( 2847): Trying to bring up p2p0
,E/WifiStateMachine( 3517): set country code pl
D/WifiMonitor( 3517): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 3517): P2pEnablingState
,D/WifiP2pService( 3517): P2pEnablingState{ what=147457 }
D/WifiP2pService( 3517): P2p socket connection successful
D/WifiP2pService( 3517): P2pEnabledState
,D/WifiP2pService( 3517): sending p2p connection changed broadcast: IDLE
,E/WifiStateMachine( 3517): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 3517): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiP2pService( 3517): create mNetworkAgent
,D/WifiDisplayController( 3517): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3517): disconnect
D/WifiDisplayController( 3517): updateConnection
D/WifiDisplayController( 3517): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3517): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3517): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 3691): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 3517): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3691): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,I/wpa_supplicant(10997): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/WifiStateMachine( 3517): set frequency band 0
,D/ConnectivityService( 3517): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 3517): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3517): updateNetworkInfo()
D/ConnectivityService( 3517): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/CSLegacyTypeTracker( 3517): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,I/wpa_supplicant(10997): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/WifiStateMachine( 3517): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3517): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine( 3517): setDetailed state send new extra info
,D/SecContentProvider2( 3517): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3517): mCursor = null
,D/WifiNative-HAL( 3517): p2pGetDeviceAddress
,D/WifiNative-HAL( 3517): p2pGetDeviceAddress returning 92:b6:86:43:73:1c
D/SecContentProvider2( 3517): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3517): mCursor = null
,D/WifiP2pService( 3517): DeviceAddress: 92:73:1c
D/WifiDisplayController( 3517): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note4-1
D/WifiDisplayController( 3517):  deviceAddress: 92:b6:86:43:73:1c
D/WifiDisplayController( 3517):  primary type: 10-0050F204-5
D/WifiDisplayController( 3517):  secondary type: null
D/WifiDisplayController( 3517):  wps: 0
D/WifiDisplayController( 3517):  grpcapab: 0
D/WifiDisplayController( 3517):  devcapab: 0
D/WifiDisplayController( 3517):  status: 3
D/WifiDisplayController( 3517):  wfdInfo: null
D/WifiDisplayController( 3517):  groupownerAddress: null
D/WifiDisplayController( 3517):  GOdeviceName: null
D/WifiDisplayController( 3517):  interfaceAddress: 
D/WifiDisplayController( 3517):  SConnectInfo : null
,D/WifiP2pService( 3517): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 3517): InactiveState
D/WifiP2pService( 3517): InactiveState{ what=143376 }
D/WifiP2pService( 3517): P2pEnabledState{ what=143376 }
,I/wpa_supplicant(10997): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService( 3517): updateNetworkInfo()
D/WifiP2pService( 3517): InactiveState{ what=143376 }
,D/WifiP2pService( 3517): P2pEnabledState{ what=143376 }
,D/ACRA    (11142): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11142): not using cross-dex optimization: ART in use
,I/art     (11142): Thread[1,tid=11142,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11142): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11142): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11142): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11142): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11142): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11142): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11142): loading pre-built fallback odex files
,V/MultiDexClassLoader(11142): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11142): released odex store lock
D/DexLibLoader(11142): DexLibLoader.loadAll took 13 ms
,W/ca      (11142): Verify
,W/LightSharedPreferencesImpl(11142): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11142): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11142): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11142): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11142): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11142): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11142): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11142): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11142): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11142): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11142): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11142): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11142): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11142): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11142): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11142): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11142): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11142): 	... 10 more
,W/ContextImpl(10039): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
W/appmanager(:<default>):b(11142): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/appmanager(:<default>):b(11142): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/LocalBluetoothProfileManager(10039): Adding local A2DP profile
D/LocalBluetoothProfileManager(10039): Adding local HEADSET profile
E/BluetoothHeadset(10039): BTStateChangeCB is registed
E/BluetoothHeadset(10039): BluetoothHeadset service is binded
,W/ContextImpl(10039): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap(10039): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager(10039): PANU : true
D/LocalBluetoothProfileManager(10039): Adding local MAP profile
,D/BluetoothMap(10039): Create BluetoothMap proxy object
,W/appmanager(:<default>):QuickExperimentControllerImpl(11142): Exposure of experiment com.facebook.common.network.l@e566522 occurred when no user was logged in
,W/LocalBluetoothProfileManager(10039): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager(10039): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver(10039): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver(10039): onReceive
D/BluetoothA2dp(10039): Proxy object connected
D/A2dpProfile(10039): Bluetooth service connected
,D/BluetoothAdapterService(10982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32f2e4aa
D/BtConfig.SecureMode(10982): isSecureModeOn:false
,D/HeadsetProfile(10039): Bluetooth service connected
,D/AuthorizationBluetoothService( 4247): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/Hs20UtilService( 6329): Starting #3
,I/Hs20UtilService( 6329): Message received 5011
D/Bluetoothsap(10039): BluetoothSAP Proxy object connected
I/WifiStateMachine( 3517): callSECApi what=207
,D/SapProfile(10039): Bluetooth service connected
D/Bluetoothsap(10039): getConnectedDevices()
E/WifiStateMachine( 3517): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL( 3517): callSECStringApiVoid - ID [215]
E/WifiNative-HAL( 3517): invaild command id : 215
,D/SecContentProvider( 3517): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/BluetoothInputDevice(10039): Proxy object connected
D/HidProfile(10039): Bluetooth service connected
,D/KeyguardWallpaperUpdator(11038): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11038): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11038): stopCheckCategoryVersion
,D/BluetoothPan(10039): BluetoothPAN Proxy object connected
D/PanProfile(10039): Bluetooth service connected
,I/SignOutReceiver(10393): WIFI_STATE_CHANGED_ACTION
,D/BluetoothMap(10039): Proxy object connected
D/MapProfile(10039): Bluetooth service connected
D/BluetoothPbap(10039): Proxy object connected
D/PbapServerProfile(10039): Bluetooth service connected
,W/BluetoothAdapter(10982): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10982): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
D/BluetoothSocket(10982): bindListen(), new LocalSocket 
D/BluetoothSocket(10982): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10982): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7f24b6a
,D/BluetoothSocket(10982): channel: 12
I/BtOppRfcommListener(10982): Accept thread started.
,D/NearbySettings(10039): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings(10039): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings(10039): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings(10039): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings(10039): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(10039): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3517): New client listening to asynchronous messages
I/NearbySettings(10039): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(10039): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(10039): MountReceiver.onReceive - Set preference state off
V/NearbySettings(10039): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11201): MountEmulatedStorage()
E/Zygote  (11201): v2
I/libpersona(11201): KNOX_SDCARD checking this for 10079
I/libpersona(11201): KNOX_SDCARD not a persona
,I/SELinux (11201): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=11201 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11201): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11201): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Killing 9869:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11201): TimaSignature is unavailable
,D/ActivityThread(11201): Added TimaKeyStore provider
,D/ResourcesManager(11201): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(11201): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 3517): Killing 10127:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11142): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11142): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(11142): Exposure of experiment com.facebook.imagepipeline.a.g@3c78b33 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11142): Exposure of experiment com.facebook.imagepipeline.a.d@2f701a1c occurred when no user was logged in
,I/art     (11142): Explicit concurrent mark sweep GC freed 44588(2MB) AllocSpace objects, 3(48KB) LOS objects, 22% free, 27MB/35MB, paused 491us total 20.637ms
,W/appmanager(:<default>):m(11142): No feature status reporters found; is this dead code?
,I/wpa_supplicant(10997): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant(10997): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant(10997): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant(10997): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant(10997): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
I/WifiNative-HAL( 3517): startHal
E/wifi    ( 3517): getStaticLongField sWifiHalHandle 0x8f80c87c
D/wifi    ( 3517): halHandle = 0x0, mVM = 0xb4d5c280, mCls = 0x50214e
I/WifiNative-HAL( 3517): Could not start hal
E/WifiStateMachine( 3517): [1,451,923,681,133 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3517): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@384bdc3f sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3517): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3517): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,D/SecContentProvider2( 3517): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3517): mCursor = null
,I/wpa_supplicant(10997): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant(10997): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3517): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3517): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3517): setDetailed state send new extra info"NG700"
I/wpa_supplicant(10997): Associated with C0.AA.48
,D/SecContentProvider2( 3517): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3517): mCursor = null
,I/wpa_supplicant(10997): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant(10997): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3517): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3517): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/SecContentProvider2( 3517): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3517): mCursor = null
,I/wpa_supplicant(10997): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant(10997): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant(10997): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3517): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3517): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant(10997): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(10997): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant(10997): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant(10997): Blacklist: Clear (temp) 
I/wpa_supplicant(10997): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3517): Network connection established
,D/WifiNative-HAL( 3517): callSECApiVoid - ID [50]
E/WifiStateMachine( 3517): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3517): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3517): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3517): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine( 3517): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3517): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3517): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 3517): updateNetworkInfo()
D/ConnectivityService( 3517): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 6329): Starting #4
,I/Hs20UtilService( 6329): Message received 5007
E/WifiStateMachine( 3517): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine( 3517): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3517): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3517): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/NearbySettings(10039): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(10039): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings(10039): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings(10039): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(10039): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(10039): MountReceiver.onReceive - Set preference state off
V/NearbySettings(10039): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(10393): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2847): Setting iface cfg
,E/WifiStateMachine( 3517): Start Dhcp Watchdog 1
,D/SecContentProvider2( 3517): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3517): mCursor = null
,E/WifiStateMachine( 3517): Force RSSI Broadcast 1/3
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3517): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3517): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3517): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3517): do suspend false
,D/SecContentProvider2( 3517): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3517): InactiveState{ what=143375 }
D/SecContentProvider2( 3517): mCursor = null
D/WifiP2pService( 3517): P2pEnabledState{ what=143375 }
,E/dhcpcd  (11222): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11222): version 5.5.6 starting
,E/dhcpcd  (11222): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11222): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11222): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11222): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (11222): bssid match
,I/dhcpcd  (11222): wlan0: rebinding lease of 192.168.1.124
,I/dhcpcd  (11222): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (11222): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3517): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3517): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3517): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3517): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3517): do suspend true
,D/WifiP2pService( 3517): InactiveState{ what=143375 }
D/WifiP2pService( 3517): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3517): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3517): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3517): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3517): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3517): Not connected state, yet.
E/WifiStateMachine( 3517): VerifyingLinkState enter
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3517): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3517): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3517): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3517): callSECApiInt - ID [210]
,E/WifiStateMachine( 3517): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3517): updateNetworkInfo()
,D/ConnectivityService( 3517): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3517): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 3517): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3517): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3517): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3517): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3517): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3517): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3517): Now, connected state.
E/WifiStateMachine( 3517): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
E/WifiStateMachine( 3517): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3517): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3517): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3517): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3517): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,I/Hs20UtilService( 6329): Starting #5
,D/StatusBar.NetworkController( 3691): applyOpen
I/Hs20UtilService( 6329): Message received 5007
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,D/NearbySettings(10039): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 3517): Adding Route [fe80::/64 -> :: wlan0] to network 502
E/WifiStateMachine( 3517): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/NearbySettings(10039): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3517): REQUEST_POWER_SAVE_ON
D/ConnectivityService( 3517): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService( 3517): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,E/ConnectivityService( 3517): Unexpected mtu value: 0, wlan0
,V/        ( 2847): QcRouteController
,I/SignOutReceiver(10393): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2847): QcRouteController
,I/Hs20UtilService( 6329): Starting #6
,I/Hs20UtilService( 6329): Message received 5007
,D/NearbySettings(10039): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/        ( 2847): QcRouteController
V/NearbySettings(10039): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(10039): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
V/        ( 2847): QcRouteController
,I/NearbySettings(10039): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(10039): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(10039): MountReceiver.onReceive - Set preference state off
,V/NearbySettings(10039): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(10393): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2847): QcRouteController
,I/Hs20UtilService( 6329): Starting #7
,I/Hs20UtilService( 6329): Message received 5007
,D/NearbySettings(10039): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings(10039): MountReceiver.onReceive - Keep current state
,V/        ( 2847): QcRouteController
,I/WifiStateMachine( 3517): callSECApi what=220
D/WifiStateMachine( 3517): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,I/SignOutReceiver(10393): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2847): QcRouteController
,D/ConnectivityService( 3517): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 3517): LTETest block dns file not exists
,D/ConnectivityService( 3517): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
E/ConnectivityService( 3517): updateNetworkInfo()
E/ConnectivityService( 3517): updateNetworkInfo()
D/ConnectivityService( 3517): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3517): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3517): rematching NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3517): DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3517): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3517): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3517):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3517): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 3517): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/TelephonyNetworkFactory( 3981): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/System.out( 3517): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3517): (HTTPLog)-Static: isShipBuild true
I/System.out( 3517): (HTTPLog)-Thread-190-469504254: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3517): (HTTPLog)-Static: isSBSettingEnabled false
,I/SurfaceFlinger( 2854): id=12 createSurf (1x1),1 flag=4, Uoast
,E/CSLegacyTypeTracker( 3517): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3517): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService( 3517): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3517): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering( 3517): MasterInitialState.processMessage what=3
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 1000
D/SmartBondingService( 3517): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity( 3517): Not allowed due to - mEnabled false
D/SmartBondingService( 3517): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityService( 3517): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/SmartBondingService( 3517): getSBEnabled() enabled =false
D/SmartBondingService( 3517): getSBEnabled() enabled =false
D/SmartBondingService( 3517): getSBEnabled() enabled =false
V/NetworkStats( 3517): updateIfacesLocked()
V/NetworkStats( 3517): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 3517): forceRefresh() from cache miss
D/NetworkStatsFactory( 3517): UpdateStatsForKnox
D/SmartBondingService( 3517): getNetworkEnabled : wifi : true mobile : false
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 1000
,V/NetworkStats( 3517): performPollLocked() took 6ms
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 4466): CM callback handler got msg 524290
,D/PowerManagerService( 3517): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3517
,D/mali_winsys( 3691): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,I/System.out( 3517): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NtpTrustedTime( 3517): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1451923692643 mCachedNtpElapsedRealtime : 302180 mCachedNtpCertainty : 8
,D/NtpTrustedTime( 3517): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3517): currentTimeMillis() cache hit
D/NtpTrustedTime( 3517): currentTimeMillis() cache hit
D/NtpTrustedTime( 3517): currentTimeMillis() cache hit
D/NtpTrustedTime( 3517): currentTimeMillis() cache hit
D/NtpTrustedTime( 3517): currentTimeMillis() cache hit
V/NetworkStats( 3517): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3517): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 04 Jan 2016 16:08:12 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451923682191], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451923682177]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3517): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3517): Validated
,D/ConnectivityService( 3517): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3517): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3517): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 3517): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
D/ConnectivityService( 3517): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 4466): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3517): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3517): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3517): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3517): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/SmartBondingService( 3517): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3517): getSBEnabled() enabled =false
D/SmartBondingService( 3517): getSBEnabled() enabled =false
D/SmartBondingService( 3517): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3517): currentTimeMillis() cache hit
D/AlarmManagerService( 3517): Setting time of day to sec=1451923693
D/AlarmManagerService( 3517): Trying to open a file
,D/AlarmManagerService( 3517): File Open Success
D/AlarmManagerService( 3517): File Close Success
I/AlarmManagerService( 3517): DRM_TIME_PATH CHMOD 666 for resetState done 
,D/SmartBondingService( 3517): getNetworkEnabled : wifi : true mobile : false
,V/AlarmManager( 3517): waitForAlarm result :65536
,I/DBG_DM  ( 5897): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 5897): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 5897): [IlIIlIIlIllllIlllIII(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 5897): [IlIlllIlllllIlIllllI(403/llllllIllIlIlllIIlIl)] Check completed.
,I/DBG_DM  ( 5897): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5897): [IIlIIIlllllIIlIIIlII(72/llllIIIllIlIIIIllllI)] 
,D/WifiStateMachine( 3517): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_SET
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
D/SettingsProvider( 3517): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 10060
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/KeyguardEffectViewUtil( 3691): isPowerSavingMode() :false
,I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 3
,D/KeyguardEffectViewUtil( 3691): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3691): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 5897): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,D/VisualEffectParticleEffect( 3691): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3691): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{2c02b1d9 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3691): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{362c079e V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3691): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{2c02b1d9 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3691): clearEffect
D/WallpaperWidget( 3691): setLockScreenWallpaper()
,D/KeyguardEffectViewUtil( 3691): getCurrentWallpaper() mWallpaperPath :null
,I/DBG_DM  ( 5897): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [3]
,I/DBG_DM  ( 5897): [IlIIlIIlIllllIlllIII(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 5897): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1280/handleMessage)] 
,W/appmanager(:<default>):QuickExperimentControllerImpl(11142): Exposure of experiment com.facebook.http.g.an@38d36c76 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11142): Exposure of experiment com.facebook.http.g.aw@207e8ee4 occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(11142): Exposure of experiment com.facebook.http.g.aj@dc47f4d occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(11142): Exposure of experiment com.facebook.http.g.a@3e01da02 occurred when no user was logged in
,E/Zygote  (11280): MountEmulatedStorage()
E/Zygote  (11280): v2
I/libpersona(11280): KNOX_SDCARD checking this for 1000
I/libpersona(11280): KNOX_SDCARD not a persona
,I/SELinux (11280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11280): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5897): [IlIIlIIlIllllIlllIII(1907/lllIlIlIIIllIIlIllIl)] 
,I/ActivityManager( 3517): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11280 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/DBG_DM  ( 5897): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(849/llIIllllIIlllIIIIlll)] 
,W/appmanager(:<default>):QuickExperimentControllerImpl(11142): Exposure of experiment com.facebook.http.g.k@d66c349 occurred when no user was logged in
,I/DBG_DM  ( 5897): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(502/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 5897): [com.wssyncmldm.ui.XUIFotaPostponeActivity(493/llIIIIlllllIIllIIllI)] 
,D/TimaKeyStoreProvider(11280): TimaSignature is unavailable
,D/ActivityThread(11280): Added TimaKeyStore provider
W/Settings( 3517): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DBG_DM  ( 5897): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,W/SEC_DRM_PLUGIN_Playready( 2858): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1451923682 after conversion: 1451923682
W/SEC_DRM_PLUGIN_Playready( 2858): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1451923693 after conversion: 1451923693
,V/AlarmManager( 3517): waitForAlarm result :4
,D/ResourcesManager(11280): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/System.out(11142): Thread-1491(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11142): Thread-1491(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11142): Thread-1491(ApacheHTTPLog):isShipBuild true
I/System.out(11142): Thread-1491(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
W/appmanager(:<default>):QuickExperimentControllerImpl(11142): Exposure of experiment com.facebook.http.g.c@39fca75a occurred when no user was logged in
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10110
,V/AlarmManager( 3517):  next == MAX_VALUE
,I/PCWCLIENTTRACE_LOG(11280): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11280): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11280): new DMDBOpenHelper instance
,I/GoogleURLConnFactory( 4247): Using platform SSLCertificateSocketFactory
,I/DBG_DM  ( 5897): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,I/PCWCLIENTTRACE_PushUtil(11280): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11280): sales region : global
I/PCWCLIENTTRACE_PushUtil(11280): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11280): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3517): uri = 14 selection = getSealedState
,D/SecContentProvider2( 3517): mCursor = null
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/ApplicationPolicy( 3517): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3517): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 3517): showStatusBarByNotification() mOpenByNotification=false
,D/ResourcesManager( 6500): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6500): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6500): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  (11304): MountEmulatedStorage()
I/libpersona(11304): KNOX_SDCARD checking this for 10135
E/Zygote  (11304): v2
I/libpersona(11304): KNOX_SDCARD not a persona
,I/SELinux (11304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11304): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11304 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager( 3691): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11319): MountEmulatedStorage()
I/libpersona(11319): KNOX_SDCARD checking this for 10090
E/Zygote  (11319): v2
I/libpersona(11319): KNOX_SDCARD not a persona
,I/SELinux (11319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=11319 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11319): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11304): TimaSignature is unavailable
D/ActivityThread(11304): Added TimaKeyStore provider
,I/KeyguardEffectViewUtil( 3691): set current wallpaper info
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 3517): name = keyguard_current_wallpaper_type
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 10060
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,D/ResourcesManager(11304): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3517): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 10060
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,E/Zygote  (11336): MountEmulatedStorage()
E/Zygote  (11336): v2
I/libpersona(11336): KNOX_SDCARD checking this for 10050
I/libpersona(11336): KNOX_SDCARD not a persona
,I/SELinux (11336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/TimaKeyStoreProvider(11319): TimaSignature is unavailable
,D/ActivityThread(11319): Added TimaKeyStore provider
,D/SettingsProvider( 3517): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 10060
,I/SELinux (11336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
E/SELinux (11336): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,I/ActivityManager( 3517): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=11336 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/StatusBar-DoNotDistrub( 3691): Received intent with android.intent.action.TIME_SET action
,D/GpsLocationProvider( 3517): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/StatusBar-DoNotDistrub( 3691): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/TimaKeyStoreProvider(11336): TimaSignature is unavailable
,D/ActivityThread(11336): Added TimaKeyStore provider
,D/StatusBar-DoNotDistrub( 3691): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager( 2859): getOutputsForDevice device 0002 -> 0002
,I/AudioService( 3517): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 3691): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService( 3517): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,D/ResourcesManager(11319): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11336): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(11336): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11336): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11336): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11336): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11336): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(11336): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(11336): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11336): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,I/PhenotypeConfigurator( 4247): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,E/ActivityThread( 4466): Failed to find provider info for com.android.contacts.metadata
,D/KnoxNotification( 3691): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 3691): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 3691): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 3691): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2b61bd25
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
D/PersonaManager( 3691): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3691): Icon Only
,I/StatusBar( 3691): Icon Only
,D/PanelView( 3691): There is/are notification(s) 
D/PanelView( 3691): There is/are notification(s) 
D/PersonaManager( 3691): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3691): Icon Only
I/StatusBar( 3691): Icon Only
D/PanelView( 3691): There is/are notification(s) 
,D/KeyguardEffectViewUtil( 3691): isPowerSavingMode() :false
,I/MusicStore(11304): Database version: 104
I/dex2oat (11355): ----------------------------------------------------
I/dex2oat (11355): <SS>: S T A R T I N G . . .
I/dex2oat (11355): <SS>: Zip is absent. Canceled.
I/dex2oat (11355): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-2078628846.jar --oat-fd=28 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-2078628846.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/SyncManager( 3517): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 15915, reason: UserStart, SyncResult: databaseError: true stats []
,W/ActivityThread(11142): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/SyncManager( 3517): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 334022, reason: UserStart
,D/KeyguardEffectViewUtil( 3691): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3691): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3691): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3691): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{2c02b1d9 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3691): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{362c079e V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3691): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{2c02b1d9 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3691): clearEffect
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,W/ResourceType( 4948): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4948): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/PanelView( 3691): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/art     ( 3517): Explicit concurrent mark sweep GC freed 64535(3MB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 48MB/64MB, paused 1.818ms total 147.008ms
,D/ResourcesManager(11304): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecContentProvider2( 3517): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3517): mCursor = null
,I/System.out( 6500): Thread-625(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6500): Thread-625(ApacheHTTPLog):isSBSettingEnabled false
V/JNIHelp (11304): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/System.out( 6500): Thread-625(ApacheHTTPLog):isShipBuild true
I/System.out( 6500): Thread-625(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10202
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10202
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10202
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10202
,I/dex2oat (11355): dex2oat took 102.552ms (threads: 8)
,D/PackageManager( 3517): findPreferredActivity: No PreferredActivities set
,W/ActivityThread(11304): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11304): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19c0175e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11304): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11304): GMSCore installation verified
I/qtaguid ( 6500): Tagging socket 27 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6500, getuid(): 10202
I/qtaguid ( 6500): Tagging socket 58 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6500, getuid(): 10202
,I/qtaguid ( 6500): Tagging socket 55 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6500, getuid(): 10202
,I/qtaguid ( 6500): Tagging socket 57 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6500, getuid(): 10202
,I/ConfigStore(11304): Config Database version: 1
,E/Auth.Api.Credentials( 4466): [CredentialSyncAdapter] Unknown sync event.
,D/NearbySource(11336): Nearby Source Create!
D/NearbyContext(11336): Nearby Context Create!
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11336): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(11336): Samsung link source created
,D/DelayedSyncController(11319): Delaying sync.
,D/WifiDisplayAdapter( 3517): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3517): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider(11336): getAllContactInfoList Start
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11304): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/System.out(11142): P[5]_NetworkDispatch1 calls detatch()
,D/ContactProvider(11336): getAllContactInfoList End
I/syncContacts(11336): thread: 1488, sync time = 60
,I/System.out( 4247): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4247): Tagging socket 69 with tag 1000120300000000{268440067,0} uid -1, pid: 4247, getuid(): 10014
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11304): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/ActivityManager( 3517): Killing 10151:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11304): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3517): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiDisplayAdapter( 3517): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3517): getStreamVolume 3 index 0
,I/MediaRouter(11304): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager( 3517): Killing 10092:com.samsung.android.sdk.samsunglink/u0a42 (adj 13): bgCount ##31
,I/NetworkMonitor(11304): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11401): MountEmulatedStorage()
I/libpersona(11401): KNOX_SDCARD checking this for 10002
E/Zygote  (11401): v2
I/libpersona(11401): KNOX_SDCARD not a persona
,I/SELinux (11401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10202
,I/SELinux (11401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11401): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11401 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 365us total 10.303ms
,D/WifiDisplayAdapter( 3517): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider(11401): TimaSignature is unavailable
,D/ActivityThread(11401): Added TimaKeyStore provider
,I/ActivityManager( 3517): Killing 10170:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,I/NetworkMonitor(11304): type=WIFI subType= reason=null isConnected=true
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 461us total 8.579ms
,I/ActivityManager( 3517): Killing 10192:com.osp.app.signin/u0a45 (adj 13): bgCount ##31
D/ResourcesManager(11401): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
I/qtaguid ( 6500): Untagging socket 58
I/qtaguid ( 6500): Untagging socket 55
I/System.out( 6500): Thread-626 calls detatch()
I/System.out( 6500): Thread-628 calls detatch()
,I/qtaguid ( 6500): Untagging socket 27
I/System.out( 6500): Thread-625 calls detatch()
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 261us total 8.604ms
,I/qtaguid ( 6500): Tagging socket 27 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6500, getuid(): 10202
I/qtaguid ( 6500): Tagging socket 55 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6500, getuid(): 10202
I/qtaguid ( 6500): Tagging socket 70 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6500, getuid(): 10202
I/qtaguid ( 6500): Tagging socket 69 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6500, getuid(): 10202
,I/qtaguid ( 6500): Tagging socket 58 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6500, getuid(): 10202
,I/qtaguid ( 6500): Tagging socket 71 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6500, getuid(): 10202
,I/qtaguid ( 6500): Untagging socket 57
I/System.out( 6500): Thread-627 calls detatch()
,I/qtaguid ( 6500): Tagging socket 56 with tag 0{0,0} uid -1, pid: 6500, getuid(): 10202
,I/qtaguid ( 6500): Untagging socket 55
I/System.out( 6500): Thread-625 calls detatch()
,I/qtaguid ( 6500): Untagging socket 58
,I/System.out( 6500): Thread-628 calls detatch()
I/qtaguid ( 6500): Untagging socket 27
,I/System.out( 6500): Thread-626 calls detatch()
,I/qtaguid ( 4247): Tagging socket 76 with tag 1000120300000000{268440067,0} uid -1, pid: 4247, getuid(): 10014
,I/ActivityManager( 3517): Killing 10262:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11421): MountEmulatedStorage()
E/Zygote  (11421): v2
I/libpersona(11421): KNOX_SDCARD checking this for 1000
I/libpersona(11421): KNOX_SDCARD not a persona
,I/SELinux (11421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11421 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (11421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11421): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11421): TimaSignature is unavailable
,D/ActivityThread(11421): Added TimaKeyStore provider
,D/ResourcesManager(11421): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11421): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
D/PicasaService(11336): start picasa sync
,D/PicasaService(11336): end picasa sync
,W/DefaultRequestDirector( 6500): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 6500): Untagging socket 56
I/System.out( 6500): Thread-630 calls detatch()
,E/Volley  ( 6500): [630] xe.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,I/qtaguid ( 6500): Tagging socket 56 with tag 0{0,0} uid -1, pid: 6500, getuid(): 10202
,I/qtaguid ( 6500): Tagging socket 74 with tag 0{0,0} uid -1, pid: 6500, getuid(): 10202
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11442): MountEmulatedStorage()
I/libpersona(11442): KNOX_SDCARD checking this for 10122
E/Zygote  (11442): v2
I/libpersona(11442): KNOX_SDCARD not a persona
,I/SELinux (11442): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11442): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3517): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=11442 uid=10122 gids={50122, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11442): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/DefaultRequestDirector( 6500): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 6500): Untagging socket 56
I/System.out( 6500): Thread-630 calls detatch()
E/Volley  ( 6500): [630] xe.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,E/YouTube ( 6500): apps.youtube.app.task.YouTubeNetworkTaskService.a:119 Failed to fetch settings
E/YouTube ( 6500): fdv: java.util.concurrent.ExecutionException: wb
E/YouTube ( 6500): 	at fco.a(SourceFile:103)
E/YouTube ( 6500): 	at fcp.c(SourceFile:160)
E/YouTube ( 6500): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:111)
E/YouTube ( 6500): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:49)
E/YouTube ( 6500): 	at emi.run(Unknown Source)
E/YouTube ( 6500): Caused by: java.util.concurrent.ExecutionException: wb
E/YouTube ( 6500): 	at xz.a(SourceFile:117)
E/YouTube ( 6500): 	at xz.get(SourceFile:88)
E/YouTube ( 6500): 	at gky.get(SourceFile:69)
E/YouTube ( 6500): 	at fco.a(SourceFile:99)
E/YouTube ( 6500): 	... 4 more
E/YouTube ( 6500): Caused by: wb
E/YouTube ( 6500): 	at xe.a(SourceFile:141)
E/YouTube ( 6500): 	at gkq.a(SourceFile:49)
E/YouTube ( 6500): 	at wk.run(SourceFile:105)
,D/TimaKeyStoreProvider(11442): TimaSignature is unavailable
,D/ActivityThread(11442): Added TimaKeyStore provider
,D/ResourcesManager(11442): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/DIAGMON_AGENT(11421): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,V/AlarmManager( 3517):  next == MAX_VALUE
,I/DIAGMON_AGENT(11421): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11421): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11421): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/ActivityManager( 3517): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread(11442): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 3517): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11467): MountEmulatedStorage()
I/libpersona(11467): KNOX_SDCARD checking this for 10012
E/Zygote  (11467): v2
I/libpersona(11467): KNOX_SDCARD not a persona
,I/SELinux (11467): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11467): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11467): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11467 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ChimeraCfgMgr( 4466): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4466): Module APK com.google.android.play.games already loaded
,W/ActivityManager( 3517): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 3517): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 3517): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   (11442): getAccountsCursor
,V/AlarmManager( 3517):  next == MAX_VALUE
,W/GAV2    (11442): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11467): TimaSignature is unavailable
,D/ActivityThread(11467): Added TimaKeyStore provider
,I/Gmail   (11442): Observing account changes for notifications
,E/Zygote  (11491): MountEmulatedStorage()
E/Zygote  (11491): v2
I/libpersona(11491): KNOX_SDCARD checking this for 10195
I/libpersona(11491): KNOX_SDCARD not a persona
,I/SELinux (11491): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11491): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11491): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=11491 uid=10195 gids={50195, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager( 3517): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/TimaKeyStoreProvider(11491): TimaSignature is unavailable
,D/ActivityThread(11491): Added TimaKeyStore provider
,I/GamesSyncServiceMain( 4466): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 4466): Failed to execute periodic sync, missing client context - aborting
,I/art     ( 4247): Explicit concurrent mark sweep GC freed 48079(2MB) AllocSpace objects, 10(183KB) LOS objects, 34% free, 29MB/45MB, paused 732us total 46.692ms
,D/ResourcesManager(11467): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,W/ActivityManager( 3517): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ResourcesManager(11491): creating new AssetManager and set to /system/app/Videos/Videos.apk
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager(11491): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,W/Gmail   (11442): Sync started for account: account:61035162
,E/Gmail   (11442): Error finding the version of the Email provider.....
E/Gmail   (11442): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   (11442): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   (11442): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   (11442): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   (11442): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   (11442): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   (11442): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   (11442): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration(11442): We do not support migrating this version of the Email provider.
,I/Gmail   (11442): getAccountsCursor
,E/SQLiteLog(11442): (283) recovered 69 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/AlarmManager( 3517):  next == MAX_VALUE
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 3517):  next == MAX_VALUE
,I/ActivityManager( 3517): Killing 10247:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,I/FOTA_Client(11467): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11467): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11467): [IIIllIIllIlIllIlllII(200/lllIlIlIIIllIIlIllIl)] Polling time is not vaild
I/FOTA_Client(11467): [com.sec.android.fotaclient.FotaUpdaterReceiver(112/onReceive)] Polling time is already passed. Start device init Immediately
,I/FOTA_Client(11467): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(104/handleMessage)] Update State: Check condition to decide next state: 1
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Zygote  (11517): MountEmulatedStorage()
I/libpersona(11517): KNOX_SDCARD checking this for 10021
E/Zygote  (11517): v2
I/libpersona(11517): KNOX_SDCARD not a persona
,I/SELinux (11517): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11517): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11517): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11517 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/FOTA_Client(11467): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(121/handleMessage)] Update State: Initialize polling update: 1
,I/FOTA_Client(11467): [lIllIllllIIIlllIlllI(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,D/TimaKeyStoreProvider(11517): TimaSignature is unavailable
,D/ActivityThread(11517): Added TimaKeyStore provider
,I/Gmail   (11442): notifyAccountChanged
V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (11442): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/ResourcesManager(11517): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/Gmail   (11442): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/PhenotypeConfigurator( 4247): Server returned 404
,I/Gmail   (11442): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/KLMS-2.4.521: (11517): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 04 17:08:14 GMT+01:00 2016
I/Gmail   (11442): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   (11442): notifyAccountChanged
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/KLMS-2.4.521: (11517): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11517): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11517): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11517): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11517): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11517): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11517): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11517): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11517): NetworkChangeOperations(): uploadRequestLog().START 
,E/Zygote  (11542): MountEmulatedStorage()
E/Zygote  (11542): v2
I/libpersona(11542): KNOX_SDCARD checking this for 10038
I/libpersona(11542): KNOX_SDCARD not a persona
,I/SELinux (11542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11542 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/SELinux (11542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11542): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 3517): Explicit concurrent mark sweep GC freed 49483(2MB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 48MB/64MB, paused 1.691ms total 85.037ms
,I/KLMS-2.4.521: (11517): NetworkChangeOperations(): uploadRequestLog().END 
,D/TimaKeyStoreProvider(11542): TimaSignature is unavailable
D/ActivityThread(11542): Added TimaKeyStore provider
,I/KLMS-2.4.521: (11517): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11517): KLMSIntentService(): onDestroy()
,I/FOTA_Client(11467): [llIlllIIIIlIllIIlIIl(31/llIIIIlllllIIllIIllI)] Request Network Connection
,D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/FOTA_Client(11467): [lIllIllllIIIlllIlllI(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/FOTA_Client(11467): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(82/llIIIIlllllIIllIIllI)] Server time is zero
,I/FOTA_Client(11467): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(111/llllIIIllIlIIIIllllI)] Request ServerTime
,V/AlarmManager( 3517):  next == MAX_VALUE
,I/FOTA_Client(11467): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
I/Gmail   (11442): getAccountsCursor
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/FOTA_Client(11467): [com.sec.android.fotaclient.FotaInitUpdateService(352/llllIIIllIlIIIIllllI)] Request NetActionGetPolling
,I/SO_AGENT(11542): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ResourcesManager( 4466): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/Gmail   (11442): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 13759, normalSync: true
,I/Gmail   (11442): getAccountsCursor
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/FOTA_Client(11467): [com.sec.android.fota.osp.http.RestClient(277/llIIIIlllllIIllIIllI)] =====================================================================
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/System.out(11467): Thread-1508(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11467): Thread-1508(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11467): Thread-1508(ApacheHTTPLog):isShipBuild true
I/System.out(11467): Thread-1508(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 4247): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4247): Tagging socket 72 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10012
,E/Zygote  (11572): MountEmulatedStorage()
I/libpersona(11572): KNOX_SDCARD checking this for 1000
E/Zygote  (11572): v2
I/libpersona(11572): KNOX_SDCARD not a persona
,I/SELinux (11572): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11572): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11572): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3517): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11572 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3517): Killing 10279:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,I/qtaguid ( 4247): Tagging socket 79 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,D/TimaKeyStoreProvider(11572): TimaSignature is unavailable
,D/ActivityThread(11572): Added TimaKeyStore provider
,D/ResourcesManager(11572): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/PlayMovies(11491): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,I/PlayMovies(11491): SyncService$SyncAdapter.onPerformSync:252 Skipping sync for 515013DC511638B0584069811EF28701C0771BF5
,I/ActivityManager( 3517): Killing 10296:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,W/AudioCapabilities(11491): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities(11491): Unsupported mime audio/mpeg-L2
,D/ResourcesManager(11442): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/PlayMovies(11491): TransferService.onCreate:52 creating transfer service
W/AudioCapabilities(11491): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities(11491): Unsupported mime audio/x-ima
,W/VideoCapabilities(11491): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/ResourcesManager(11442): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11442): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
W/VideoCapabilities(11491): Unsupported mime video/wvc1
W/VideoCapabilities(11491): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities(11491): Unrecognized profile/level 32768/2 for video/mp4v-es
,E/Zygote  (11608): MountEmulatedStorage()
E/Zygote  (11608): v2
I/libpersona(11608): KNOX_SDCARD checking this for 10039
I/libpersona(11608): KNOX_SDCARD not a persona
W/VideoCapabilities(11491): Unsupported mime video/wvc1
,W/VideoCapabilities(11491): Unsupported mime video/x-ms-wmv
,I/SELinux (11608): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/VideoCapabilities(11491): Unsupported mime video/x-ms-wmv7
,I/ActivityManager( 3517): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11608 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11608): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,W/VideoCapabilities(11491): Unsupported mime video/x-ms-wmv8
,E/SELinux (11608): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3517): Killing 10311:com.samsung.helphub/1000 (adj 13): bgCount ##31
,W/VideoCapabilities(11491): Unsupported mime video/sorenson
,W/VideoCapabilities(11491): Unsupported mime video/mp43
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.videos/files/Movies/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11491): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.videos/files/Movies
,D/ResourcesManager( 4466): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/TimaKeyStoreProvider(11608): TimaSignature is unavailable
,D/ActivityThread(11608): Added TimaKeyStore provider
,W/AudioCapabilities(11491): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities(11491): Unsupported mime audio/mpeg-L2
,D/ResourcesManager(11608): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,I/System.out(11467): AsyncTask #1 calls detatch()
,W/VideoCapabilities(11491): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/ResourcesManager( 4466): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/FOTA_Client(11467): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(139/llllIIIllIlIIIIllllI)] Receive result: success in ServerTime
,D/WVCdm   ( 2859): Instantiating CDM.
,I/WVCdm   ( 2859): CdmEngine::QueryStatus
I/WVCdm   ( 2859): Level3 Library Sep 25 2014 17:10:03
V/JNIHelp (11442): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/FOTA_Client(11467): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,I/VideoCapabilities(11491): Unsupported profile 4 for video/mp4v-es
,W/WVCdm   ( 2859): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,E/wv_dash ( 2859): No saved usage table. Creating new table.
,E/SPPClientService(11608): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11608): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService(11608): PushLog.txt file is not deleted.
D/SPPClientService(11608): PushLog.txt file is not deleted.
D/SPPClientService(11608): ============PushLog. stop!
I/FOTA_Client(11467): [com.sec.android.fota.osp.http.RestClient(277/llIIIIlllllIIllIIllI)] =====================================================================
,E/SPPClientService(11608): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10012
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,W/ActivityThread(11442): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11442): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f3162a5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11442): Installed default security provider GmsCore_OpenSSL
,E/Zygote  (11627): MountEmulatedStorage()
E/Zygote  (11627): v2
I/libpersona(11627): KNOX_SDCARD checking this for 10045
I/libpersona(11627): KNOX_SDCARD not a persona
,I/SELinux (11627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=11627 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3517): Killing 10416:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/WVCdm   ( 2859): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   ( 2859): L3 Terminate.
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SELinux (11627): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,W/ActivityThread(11572): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/SELinux (11627): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/System.out(11572): Thread-1532(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11572): Thread-1532(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11572): Thread-1532(ApacheHTTPLog):isShipBuild true
I/System.out(11572): Thread-1532(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 1000
,D/TimaKeyStoreProvider(11627): TimaSignature is unavailable
,D/ActivityThread(11627): Added TimaKeyStore provider
,D/ResourcesManager(11627): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/chromium(10899): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium(10899): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SA      (11627): [SSP] onCreated
,I/SA      (11627): [TPM] There is no property file
,I/SA      (11627): [SCU] isHaveSA() - false
,I/SA      (11627): [TPM] getModelProperty : null
I/SA      (11627): [TPM] getCSCProperty : null
,I/System.out(11467): AsyncTask #1 calls detatch()
,I/FOTA_Client(11467): [lIllIlIlIIIIIIlIlIII(97/llIIIIlllllIIllIIllI)] result is success
I/FOTA_Client(11467): [IIllIIIIlIlIlIlIllII(78/llIIIIlllllIIllIIllI)] Response Network Connection
,I/FOTA_Client(11467): [com.sec.android.fotaclient.llIIIIlllllIIllIIllI(304/llIIIIlllllIIllIIllI)] Receive result: success in NetActionGetPolling
,I/SA      (11627): [DM] init START
,I/SA      (11627): [DM] This device is not a Vodafone
,I/SA      (11627): checkReactivationActive for LOLLIPOP
I/SA      (11627): checkReactivationActive for reactiveActive
I/SA      (11627): setSupportRL : true
,I/System.out(11442): Thread-1521(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11442): Thread-1521(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11442): Thread-1521(ApacheHTTPLog):isShipBuild true
I/System.out(11442): Thread-1521(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/SettingsProvider( 3517): name = FOTA_CLIENT_HEARTBEAT_PERIOD
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 10012
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,D/SettingsProvider( 3517): name = FOTA_CLIENT_HEARTBEAT_ADD
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 10012
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,I/SA      (11627): [SCU] isHaveSA() - false
I/SA      (11627): support phone number id : false
I/SA      (11627): [DM] init END
I/SA      (11627): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11627): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11627): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10122
,I/qtaguid (11442): Tagging socket 59 with tag 1010000000000000{269484032,0} uid -1, pid: 11442, getuid(): 10122
,I/System.out(11572): Thread-1532 calls detatch()
,I/SA      (11627): [SLFUCHKMGR] constructor called
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=10012
,I/FOTA_Client(11467): [IIIllIIllIlIllIlllII(157/llllIIIllIlIIIIllllI)] Calculate next polling time
,I/qtaguid (11442): Tagging socket 63 with tag 1010000000000000{269484032,0} uid -1, pid: 11442, getuid(): 10122
,I/SA      (11627): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11627): [OR] == isSIMCardReady false ==
,I/SA      (11627): [SCU] == networkStateCheck == true
I/SA      (11627): [DM] getCountryCodeFromCSC : PL
I/SA      (11627): isChinaCountryCode : false
I/SA      (11627): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11627): [OR] == networkStateCheck true ==
,D/SettingsProvider( 3517): name = FOTA_CLIENT_POLLING_TIME
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 10012
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,W/BackupManagerService( 3517): dataChanged but no participant pkg='com.android.providers.settings' uid=10012
,I/FOTA_Client(11467): [lIllIlIlIIIIIIlIlIII(194/llIIllllIIlllIIIIlll)] Find Firmware version in Version List
,I/FOTA_Client(11467): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(131/handleMessage)] Update State: Need to polling update: 1
,I/FOTA_Client(11467): [com.sec.android.fotaclient.FotaInitUpdateService(359/lllIlIlIIIllIIlIllIl)] request Polling
,I/FOTA_Client(11467): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(137/handleMessage)] Update State: Finish update init: 1
,I/SA      (11627): [OR] GetMyCountryZoneTask
,I/SA      (11627): [OR] onReceive END
I/ActivityManager( 3517): Killing 10434:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,I/ActivityManager( 3517): Killing 10343:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,I/SA      (11627): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3714): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/dex2oat (11652): ----------------------------------------------------
I/dex2oat (11652): <SS>: S T A R T I N G . . .
I/dex2oat (11652): <SS>: Zip is absent. Canceled.
,I/dex2oat (11652): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads1543834488.jar --oat-fd=110 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/cache/ads1543834488.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/SA      (11627): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11627): [SSP] query invoked
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
I/SA      (11627): [TPMU] GetMccFromDB : null
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
I/SA      (11627): [SCU] getMccFromPreferece mcc = 260
I/SA      (11627): [TPM] isNoProxy(default) : true
,E/Zygote  (11666): MountEmulatedStorage()
E/Zygote  (11666): v2
I/libpersona(11666): KNOX_SDCARD checking this for 10067
I/libpersona(11666): KNOX_SDCARD not a persona
,I/SELinux (11666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11666): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11666 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11666): TimaSignature is unavailable
,D/ActivityThread(11666): Added TimaKeyStore provider
,I/dex2oat (11652): dex2oat took 50.959ms (threads: 8)
,D/ResourcesManager(11666): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/PhenotypeConfigurator( 4247): Scheduling Phenotype for one-off execution 7080 seconds from now (1451923694889)
,I/sCloudBackupApp(11666): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11666): Other Intent
,I/ActivityManager( 3517): Killing 10454:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/accuweather( 5242): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/GetConfigurationSnapshotOperation( 4247): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/ActivityManager( 3517): Killing 10489:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 131
,D/accuweather( 5242): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5242): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5242): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5242): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5242): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5242): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11688): MountEmulatedStorage()
E/Zygote  (11688): v2
I/libpersona(11688): KNOX_SDCARD checking this for 1000
I/libpersona(11688): KNOX_SDCARD not a persona
,I/SELinux (11688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11688 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 8745(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 316us total 10.540ms
,D/TimaKeyStoreProvider(11688): TimaSignature is unavailable
,D/ActivityThread(11688): Added TimaKeyStore provider
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 281us total 8.171ms
,D/ResourcesManager(11688): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 494us total 8.145ms
W/ResourcesManager(11688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(11688): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(11688): premStatus:2
,I/KnoxUsageLogPro(11688): isEulaShown : false
I/KnoxUsageLogPro(11688): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(11038): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11038): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11038): stopCheckCategoryVersion
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/WifiStateMachine( 3517): updateConfiguredNetworkExpiration - currTime: 1451923695122
D/WifiStateMachine( 3517): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/Zygote  (11703): MountEmulatedStorage()
I/libpersona(11703): KNOX_SDCARD checking this for 10136
E/Zygote  (11703): v2
I/libpersona(11703): KNOX_SDCARD not a persona
,I/SELinux (11703): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11703): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3517): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11703 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11703): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3517): Killing 10506:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11703): TimaSignature is unavailable
,D/ActivityThread(11703): Added TimaKeyStore provider
,D/ResourcesManager(11703): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/IdleConnectionHandler(11142): Removing a connection that never existed!
,I/PhenotypeFlagCommitter( 4247): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4247): Using platform SSLCertificateSocketFactory
,I/qtaguid (11442): Untagging socket 59
,I/System.out(11442): SyncAdapterThread-1 calls detatch()
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11718): MountEmulatedStorage()
I/libpersona(11718): KNOX_SDCARD checking this for 10101
E/Zygote  (11718): v2
I/libpersona(11718): KNOX_SDCARD not a persona
,I/SELinux (11718): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11718): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3517): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=11718 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11718): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11718): TimaSignature is unavailable
,D/ActivityThread(11718): Added TimaKeyStore provider
,D/ResourcesManager(11718): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/DocsApplication(11718): Installing DEX configuration.
,D/DexInstaller(11718): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(11718): Provided clientMode=RELEASE, packageInfo=PackageInfo{f470823 com.google.android.apps.docs}
,D/TAG     (11718): onCreate()
,D/CrossAppStateProvider(11718): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationManagerService( 3517): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11703): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
I/System.out( 4466): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4466): (HTTPLog)-Static: isShipBuild true
I/System.out( 4466): (HTTPLog)-Thread-312-246747296: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4466): (HTTPLog)-Static: isSBSettingEnabled false
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,W/ContextImpl(11703): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/System.out( 4466): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4466): Tagging socket 110 with tag 1000010400000000{268435716,0} uid -1, pid: 4466, getuid(): 10014
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11703): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11703): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4247): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4247): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4247, getuid(): 10014
,I/WebViewFactory(11703): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11703): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11703): Loading: webviewchromium
,I/LibraryLoader(11703): Time to load native libraries: 3 ms (timestamps 4997-5000)
I/LibraryLoader(11703): Expected native library version number "",actual native library version number ""
,I/qtaguid ( 4247): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 4247, getuid(): 10014
,V/WebViewChromiumFactoryProvider(11703): Binding Chromium to main looper Looper (main, tid 1) {24aec8f8}
,I/LibraryLoader(11703): Expected native library version number "",actual native library version number ""
,I/chromium(11703): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11703): Initializing chromium process, renderers=0
,W/art     (11703): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11703): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11703): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(11703): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(11703): Requires BLUETOOTH permission
,I/qtaguid ( 4466): Untagging socket 110
,I/NSApplication(11703): Starting up...
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11789): MountEmulatedStorage()
E/Zygote  (11789): v2
I/libpersona(11789): KNOX_SDCARD checking this for 10147
I/libpersona(11789): KNOX_SDCARD not a persona
,I/SELinux (11789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=11789 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11789): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Killing 9780:com.android.defcontainer/u0a5 (adj 15): bgCount ##31
,I/art     (11442): Explicit concurrent mark sweep GC freed 155969(5MB) AllocSpace objects, 12(215KB) LOS objects, 21% free, 29MB/37MB, paused 541us total 35.017ms
,D/TimaKeyStoreProvider(11789): TimaSignature is unavailable
,D/ActivityThread(11789): Added TimaKeyStore provider
,I/Gmail   (11442): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 13931, normalSync: true
,I/Gmail   (11442): lowestBackward conversation id 0
,D/ResourcesManager(11789): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/LocationManagerService( 3517): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,W/ResourcesManager(11789): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4247): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4247, getuid(): 10014
,I/SA      (11627): [RC New] Execute method=[GET] start
,I/Gmail   (11442): notifyAccountChanged
,I/Gmail   (11442): getAccountsCursor
,I/Gmail   (11442): notifyAccountChanged
,W/Gmail   (11442): Sync complete for account: account:61035162
,I/SA      (11627): [RC New] Security=[true]
,I/System.out(11627): Thread-1540(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11627): Thread-1540(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11627): Thread-1540(ApacheHTTPLog):isShipBuild true
I/System.out(11627): Thread-1540(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10045
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (11442): getAccountsCursor
,I/ActivityManager( 3517): Killing 10659:com.google.android.gms:car/u0a14 (adj 13): bgCount ##31
,D/LocationManagerService( 3517): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 3517): Explicit concurrent mark sweep GC freed 34018(1832KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 48MB/64MB, paused 1.177ms total 83.461ms
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    (11718): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SyncAdapterService(11703): Ignoring sync request for non-current account
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4247): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4247, getuid(): 10014
,D/WifiService( 3517): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@1fa75e4f}
,I/WifiStateMachine( 3517): REQUEST_POWER_SAVE_ON
,I/PeopleSync( 4466): onPerformSync() [5005f081]
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(11718): Thread-1571(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11718): Thread-1571(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11718): Thread-1571(ApacheHTTPLog):isShipBuild true
I/System.out(11718): Thread-1571(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10101
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3517): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/Zygote  (11845): MountEmulatedStorage()
I/libpersona(11845): KNOX_SDCARD checking this for 10150
E/Zygote  (11845): v2
I/libpersona(11845): KNOX_SDCARD not a persona
,I/SELinux (11845): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11845): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3517): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=11845 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11845): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LocationManagerService( 3517): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/TimaKeyStoreProvider(11845): TimaSignature is unavailable
,D/ActivityThread(11845): Added TimaKeyStore provider
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4247): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4247, getuid(): 10014
,D/ResourcesManager(11845): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(11845): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11845): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11845): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(11845): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(11845): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(11845): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3517): exchangeData() failure , invalid userId
,D/RCPManagerService( 3517): exchangeData() failure , invalid userId
,I/ActivityManager( 3517): Killing 10592:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/LocationManagerService( 3517): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/PeopleSync( 4466): Setting subscription: result=true [5005f081]
I/PeopleSync( 4466): Starting sync, feed=null [5005f081]
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4247): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4247, getuid(): 10014
,I/System.out(11718): SyncManager calls detatch()
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10186
,I/CheckinService( 4466): Checkin interval check for package: unspecified last checkin: 1450839322352 min interval config: 0 actual interval: 1084373623
,I/CheckinService( 4466): Checking schedule, now: 1451923695981 next: 1451418701176
I/CheckinService( 4466): active receiver: enabled
,I/CheckinService( 4466): Preparing to send checkin request
,I/EventLogService( 4466): Accumulating logs since 1451922633007
,I/iu.SyncManager( 4466): SYNC; picasa accounts
,W/BaseAppContext( 4466): Using Auth Proxy for data requests.
,W/BaseAppContext( 4466): Using Auth Proxy for data requests.
,D/NetworkLogImpl( 4466): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4466): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4466): num queued entries: 0
,I/iu.UploadsManager( 4466): num updated entries: 0
,I/iu.SyncManager( 4466): NEXT; no task
,W/BaseAppContext( 4466): Using Auth Proxy for data requests.
,I/PeopleSync( 4466): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,V/AlarmManager( 3517):  next == MAX_VALUE
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,E/Zygote  (11876): MountEmulatedStorage()
E/Zygote  (11876): v2
I/libpersona(11876): KNOX_SDCARD checking this for 10013
I/libpersona(11876): KNOX_SDCARD not a persona
,I/SurfaceFlinger( 2854): id=12 Removed Uoast (8/9)
I/SELinux (11876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SurfaceFlinger( 2854): id=12 Removed Uoast (-2/9)
,I/SELinux (11876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11876): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=11876 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/PowerManagerService( 3517): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3517) eventTime = 305623
D/PowerManagerService( 3517): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3517 (0x0)
D/PowerManagerService( 3517): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3517, ws=WorkSource{10060}) (elapsedTime=3490)
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4247): Tagging socket 72 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,I/CheckinRequestBuilder( 4466): Checkin reason type: 12 attempt count: 1
,D/TimaKeyStoreProvider(11876): TimaSignature is unavailable
,D/ActivityThread(11876): Added TimaKeyStore provider
,D/WifiService( 3517): New client listening to asynchronous messages
,E/ActivityThread( 4466): Failed to find provider info for com.google.android.wearable.settings
,D/ResourcesManager(11876): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 4247): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4247): Tagging socket 87 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,I/qtaguid ( 4247): Tagging socket 89 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,D/ResourcesManager( 4466): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/WaitQueueForNetworkActivate(11876): notifyNetworkActivated
,W/ContextImpl(11876): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3517): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 4247): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4247): Tagging socket 92 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,D/hcjo    (11876): AutoUpdateManager:IDLE:execute
,I/qtaguid ( 4247): Tagging socket 95 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
I/FOTA_Client(11467): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/splitIntent( 3517): Split this intent : android.intent.action.TIME_SET !!   mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=17 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 3517): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/InitializeManagerStateMachine(11876): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(11876): exit::IDLE
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
D/InitializeManagerStateMachine(11876): entry::NETWORK_CHECK
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/InitializeManagerStateMachine(11876): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(11876): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(11876): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11876): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(11876): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11876): entry::SUCCESS
D/hcjo    (11876): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    (11876): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  (11876): RestApi Request Add : 2307
,E/Zygote  (11897): MountEmulatedStorage()
I/libpersona(11897): KNOX_SDCARD checking this for 10052
E/Zygote  (11897): v2
I/libpersona(11897): KNOX_SDCARD not a persona
,I/SELinux (11897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11897): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=11897 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/dhcpcd  (11222): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11222): wlan0: sendmsg: Cannot assign requested address
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11910): MountEmulatedStorage()
E/Zygote  (11910): v2
I/libpersona(11910): KNOX_SDCARD checking this for 10164
I/libpersona(11910): KNOX_SDCARD not a persona
I/SELinux (11910): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11910): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11910): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=11910 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/ResourcesManager( 4247): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GCM     ( 4247): GCM config loaded
,D/TimaKeyStoreProvider(11897): TimaSignature is unavailable
D/ActivityThread(11897): Added TimaKeyStore provider
,I/KLMS-2.4.521: (11517): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Mon Jan 04 17:08:16 GMT+01:00 2016
,I/SA      (11627): [RC New] [v2liruge] api execute + 621
I/SA      (11627): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11627): AsyncTask #1 calls detatch()
,I/KLMS-2.4.521: (11517): KLMSAbstractReciever(): onReceive().END.
,D/daemonapp( 3775): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/TimaKeyStoreProvider(11910): TimaSignature is unavailable
D/daemonapp( 3775): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/ActivityThread(11910): Added TimaKeyStore provider
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11517): KLMSIntentService(): onCreate()
D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.4.521: (11517): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SA      (11627): [TPMU] getNetworkMcc : 
D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/SA      (11627): [SCU] saveMccToPreferece Start
I/SA      (11627): [SCU] RegionMCC : 260
I/SA      (11627): [SSP] query invoked
,I/KLMS-2.4.521: (11517): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/daemonapp( 3775): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 3775): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3775): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
D/comsamsunglog( 3775): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3775): [MSC_Daemon]>>> ====================================================================================================================
I/SA      (11627): [TPMU] GetMccFromDB : null
I/SA      (11627): [SCU] getMccFromPreferece mcc = 260
D/daemonapp( 3775): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
I/SA      (11627): [SCU] saveMccToPreferece End
D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/SA      (11627): [RC New] executeRequest [v2liruge] end. 658
I/SA      (11627): [RC New] Execute end
I/SA      (11627): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11627): [OR] GetMyCountryZoneTask Success
,E/Zygote  (11932): MountEmulatedStorage()
E/Zygote  (11932): v2
I/libpersona(11932): KNOX_SDCARD checking this for 10036
I/libpersona(11932): KNOX_SDCARD not a persona
,I/SELinux (11932): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(11897): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/daemonapp( 3775): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
I/KLMS-2.4.521: (11517): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/SELinux (11932): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,W/ResourcesManager(11897): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(11897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/KLMS-2.4.521: (11517): KLMSIntentService(): TIME_CHANGED
W/ResourcesManager(11897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/SELinux (11932): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ResourcesManager(11897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 3775): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
W/ResourcesManager(11897): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/daemonapp( 3775): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
W/ResourcesManager(11897): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/daemonapp( 3775): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/KLMS-2.4.521: (11517): StateImplV2(): dateTimeChanged().START : Mon Jan 04 17:08:16 GMT+01:00 2016
,I/ActivityManager( 3517): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/com.cigna.mobile.coach.CoachBroadcastReceiver: pid=11932 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.4.521: (11517): StateImplV2(): dateTimeChanged().END
,E/daemonapp( 3775): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/TimaKeyStoreProvider(11932): TimaSignature is unavailable
,D/ActivityThread(11932): Added TimaKeyStore provider
,I/KLMS-2.4.521: (11517): KLMSIntentService(): onDestroy()
,D/comdaemonstockapp( 3775): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 3775): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/ResourcesManager(11910): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11910): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11910): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11910): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11910): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11932): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/Mms/MmsApp(11897): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(11897): init before art
,D/Mms/ArtClassLoader(11897): init [DONE] art
,I/CheckinService( 4466): Checkin interval check for package: unspecified last checkin: 1450839322352 min interval config: 0 actual interval: 1084374001
,D/Mms/TelephonyPermission(11897): start operation mode monitor
,D/ResourcesManager(11897): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11897): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/TelephonyPermission(11897): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(11897): isDefault true
,D/Mms/MmsApp(11897): onCreate() com.android.mms
,D/Mms/MmsApp(11897): [start]    initCountryIso consume time = 50.230958
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/CountryDetector( 3517): The first listener is added
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SecurityLogAgent(11063): KnoxConfiguration : Current State = 0
D/SecurityLogAgent(11063): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent(11063): StateMachine : Initialized
D/SecurityLogAgent(11063): StateMachine : Changed Current State = 0
D/SecurityLogAgent(11063): StateMachine : Current State = 0
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/Mms/MmsApp(11897): [end]    initCountryIso consume time = 20.676667
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
D/Mms/MmsConfig(11897): [start]    MmsConfig.init() consume time = 0.062166
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/Mms/MmsConfig(11897): before partial update
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/art     ( 4466): Explicit concurrent mark sweep GC freed 37675(2MB) AllocSpace objects, 49(976KB) LOS objects, 33% free, 31MB/47MB, paused 1.143ms total 52.734ms
,E/Zygote  (11964): MountEmulatedStorage()
,E/Zygote  (11964): v2
,I/libpersona(11964): KNOX_SDCARD checking this for 10047
I/libpersona(11964): KNOX_SDCARD not a persona
,I/SELinux (11964): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3517): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=11964 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/SELinux (11964): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/Mms/MmsConfig(11897): Load Resize quality : 80
,E/SELinux (11964): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/Mms/MmsConfig(11897):  enable multiwindow = true
,E/Zygote  (11977): MountEmulatedStorage()
E/Zygote  (11977): v2
I/libpersona(11977): KNOX_SDCARD checking this for 10191
I/libpersona(11977): KNOX_SDCARD not a persona
,I/SELinux (11977): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/Mms/MessageUtils(11897): setCountryDetector : update country detector info 
E/Mms/MessageUtils(11897): updateCountryIso : update country iso info 
,I/SELinux (11977): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3517): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=11977 uid=10191 gids={50191, 9997} abi=armeabi-v7a
,E/SELinux (11977): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11964): TimaSignature is unavailable
,D/ActivityThread(11964): Added TimaKeyStore provider
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11977): TimaSignature is unavailable
,D/ActivityThread(11977): Added TimaKeyStore provider
,D/Mms/PackageInfo(11897): com.sec.imsservice is not installed
D/Mms/MmsConfig(11897): [end]    init() consume time = 47.324334
W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/Mms/Contact(11897): [start]    init() consume time = 0.931708
,E/Zygote  (11996): MountEmulatedStorage()
E/Zygote  (11996): v2
I/libpersona(11996): KNOX_SDCARD checking this for 10019
I/libpersona(11996): KNOX_SDCARD not a persona
,I/SELinux (11996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11996): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3517): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=11996 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/Mms/Contact(11897): [end]    init consume time = 9.9965
,D/Mms/DraftCache(11897): [start]    rebuildCache consume time = 1.396875
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 8740(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 982us total 11.030ms
,W/bdH     (11718): Application name is not set. Call Builder#setApplicationName.
,D/Mms/TelephonyUtils(11897): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(11897): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11897): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11897): auto download without roaming -> true
D/Mms/DownloadManager(11897): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 276us total 8.120ms
E/Mms/TelephonyUtils(11897): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(11897): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(11897): roaming -> false (slotId = 1)
D/Mms/DownloadManager(11897): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(11897): auto download without roaming -> true
D/Mms/DownloadManager(11897): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(11897): auto download during roaming secondary -> false
D/Mms/DownloadManager(11897): mAutoDownload ------> true
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 246us total 7.904ms
,D/TP/MmsSmsProvider( 3981): query,matched:13, calling pid = 11897
,D/TimaKeyStoreProvider(11996): TimaSignature is unavailable
D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4160, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/ActivityThread(11996): Added TimaKeyStore provider
D/BatteryService( 3517): online:4, current avg:-465, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1766
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/TP/MmsSmsProvider( 3981): query,matched:12, calling pid = 11897
,D/Mms/MmsApp(11897): [end]    onCreate() consume time = 28.538042
D/Mms/Conversation(11897): [start]    init() consume time = 0.072875
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/Mms/DownloadManager(11897): Service state changed: Bundle[mParcelledData.dataSize=692]
D/Mms/DownloadManager(11897): roaming ------> false, mSimSlot = 0
,D/Mms/TelephonyUtils(11897): getSubId from simSlot 0, return Value = -1
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Mms/DownloadManager(11897): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11897): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11897): auto download without roaming -> true
D/Mms/DownloadManager(11897): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(11897): mAutoDownload ------> true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/TP/MmsSmsProvider( 3981): deleteConversation threadId: 9223372036854775807
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/TP/MmsSmsProvider( 3981): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3981): (284) automatic index on im_threads(normal_thread_id)
I/System.out(11718): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(11718): (HTTPLog)-Static: isShipBuild true
I/System.out(11718): (HTTPLog)-Thread-1571-306206221: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(11718): (HTTPLog)-Static: isSBSettingEnabled false
,D/TP/MmsSmsProvider( 3981): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 3981): need read changed broadcast:false
,D/Mms/Conversation(11897): [end]    init consume time = 16.099583
D/Mms/MessagingNotification(11897): [start]    init() consume time = 0.053042
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10101
,I/System.out(11718): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/InitializeManagerStateMachine(11876): exit::SUCCESS
D/InitializeManagerStateMachine(11876): entry::IDLE
,I/System.out(11876): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(11876): (HTTPLog)-Static: isShipBuild true
I/System.out(11876): (HTTPLog)-Thread-1575-153003181: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(11876): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10013
,I/art     ( 3517): Explicit concurrent mark sweep GC freed 26784(1537KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 48MB/64MB, paused 1.777ms total 92.604ms
,D/TP/MmsSmsProvider( 3981): match 13:Elapsed time : 74.316 ms
D/TP/MmsSmsProvider( 3981): match 12:Elapsed time : 74.400 ms
,D/ResourcesManager(11964): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,D/ResourcesManager(11977): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,W/ResourcesManager(11964): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(11977): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager(11996): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/Zygote  (12024): MountEmulatedStorage()
I/libpersona(12024): KNOX_SDCARD checking this for 10069
E/Zygote  (12024): v2
I/libpersona(12024): KNOX_SDCARD not a persona
,I/SELinux (12024): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12024): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12024): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=12024 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3517): Killing 10019:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,I/CalendarProvider2(11964): CalendarProvider2.onCreate() called
,D/Mms/MessagingNotification(11897): [end]    init consume time = 91.486
,D/Mms/SpamFilter(11897): [start]    SpamFilter fill() begin consume time = 2.203583
,D/Mms/Synchronizer(11897): [start]    doSync consume time = 3.304
,D/TimaKeyStoreProvider(12024): TimaSignature is unavailable
,D/Mms/DraftCache(11897): [end]    rebuildCache consume time = 1.162
D/ActivityThread(12024): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 3981): query,matched:0, calling pid = 11897
V/TP/MmsSmsProvider( 3981): getSimpleConversations entered.
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/TP/MmsSmsProvider( 3981): query,matched:400, calling pid = 11897
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthServiceInstalled() : HealthService is Installed.
D/TP/MmsSmsProvider( 3981): match 0:Elapsed time : 0.275 ms
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthServiceInstalled() : HealthService is Installed.
I/System.out( 4466): (HTTPLog)-Static: isSBSettingEnabled false
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/System.out( 4466): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4466): Tagging socket 104 with tag 1000150000000000{268440832,0} uid 10014, pid: 4466, getuid(): 10014
,D/com.sec.android.service.health.keyManager.KeyManager(11932): Current encrypted state : -1
,I/SecSQLiteOpenHelper(11932): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11932): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11932): Open platform.db in secure mode
D/SecSQLiteDatabase(11932): Android Version: 5.0.1
D/SecSQLiteDatabase(11932): Load library secsqlite.so for Android 5.0.1
,D/TP/MmsSmsProvider( 3981): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 3981): syncDBData start
,D/Mms/SpamFilter(11897): [end]    SpamFilter fill() finished consume time = 7.987125
,V/TP/MmsSmsProvider( 3981): syncDBData sms end
,I/SecSQLiteDatabase(11932): openSecureDatabase...
V/TP/MmsSmsProvider( 3981): syncDBData mms end
I/SecSQLiteDatabase(11932): private openSecureDatabase...
,V/TP/MmsSmsProvider( 3981): syncDBData end
I/SecSQLiteConnectionPool(11932): OpenSecure
I/SecSQLiteConnectionPool(11932): OpenSecure with password
I/SecSQLiteConnectionPool(11932): openSecureConnectionLocked
I/SecSQLiteDatabase(11932): ...private openSecureDatabase
I/SecSQLiteDatabase(11932): ...openSecureDatabase
,I/ActivityManager( 3517): Killing 10111:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
D/ResourcesManager(12024): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12042): MountEmulatedStorage()
I/libpersona(12042): KNOX_SDCARD checking this for 10082
E/Zygote  (12042): v2
I/libpersona(12042): KNOX_SDCARD not a persona
,E/SQLiteLog(11932): (26) statement aborts at 0: [PRAGMA user_version;] file is encrypted or is not a database
I/SELinux (12042): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
E/SecDefaultDatabaseErrorHandler(11932): Corruption reported by sqlite on database: /data/data/com.sec.android.app.shealth/databases/platform.db
E/SecDefaultDatabaseErrorHandler(11932): backup the database file: /data/data/com.sec.android.app.shealth/databases/platform.db
D/SecSQLiteOpenHelper(11932): ...getDatabaseLocked(b,b,pwd)
,I/SELinux (12042): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12042): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12042 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/Mms/Synchronizer(11897): [end]    doSync consume time = 26.311625
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
I/qtaguid ( 4466): Tagging socket 122 with tag 1000150000000000{268440832,0} uid 10014, pid: 4466, getuid(): 10014
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12042): TimaSignature is unavailable
,D/ActivityThread(12042): Added TimaKeyStore provider
,E/Zygote  (12059): MountEmulatedStorage()
I/libpersona(12059): KNOX_SDCARD checking this for 10014
E/Zygote  (12059): v2
I/libpersona(12059): KNOX_SDCARD not a persona
,I/SELinux (12059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3517): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=12059 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/SELinux (12059): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Killing 10472:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/ResourcesManager(12042): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,I/System.out(11876): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (11876): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 11876, getuid(): 10013
,I/SecureStorage(11996): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Credentials: uid 10019, gid 10019, pid 11996
I/SecureStorage( 2918): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,I/ActivityManager( 3517): Killing 11201:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31
,D/accuweather( 5242): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/TimaKeyStoreProvider(12059): TimaSignature is unavailable
,D/ActivityThread(12059): Added TimaKeyStore provider
,D/accuweather( 5242): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/BadgeProvider(12042): onCreate
D/BadgeProvider(12042): DatabaseHelper
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/ Time Manager (12024): Time Difference not stored. TIME_DIFFERENCE
,D/ResourcesManager(12059): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12059): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12059): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  (12080): MountEmulatedStorage()
I/libpersona(12080): KNOX_SDCARD checking this for 10094
E/Zygote  (12080): v2
I/libpersona(12080): KNOX_SDCARD not a persona
,I/SELinux (12080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=12080 uid=10094 gids={50094, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12080): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12080): TimaSignature is unavailable
,D/ActivityThread(12080): Added TimaKeyStore provider
,D/Mms/MessagingNotification(11897): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 3981): query,matched:26, calling pid = 11897
,D/TP/SmsProvider( 3981): match 26:Elapsed time : 1.762 ms
,D/ResourcesManager(12080): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/TP/MmsSmsProvider( 3981): query,matched:6, calling pid = 11897
,W/ResourcesManager(12080): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12080): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12080): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12080): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12080): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12080): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 3981): match 6:Elapsed time : 2.268 ms
,I/Mms/ReservationManager(11897): ReservationManager()
,I/Mms/ReservationManager(11897): resetAfterConnected()
,D/TP/MmsSmsProvider( 3981): query,matched:7, calling pid = 11897
,I/ActivityManager( 3517): Killing 10039:com.android.settings/1000 (adj 13): bgCount ##31
,D/TP/MmsSmsProvider( 3981): match 7:Elapsed time : 5.869 ms
,I/Mms/ReservationManager(11897): getReservedSendMessageCount(): retMessageCount=0
,I/qtaguid (11876): Untagging socket 26
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/hcjo    (11876): AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
,E/Zygote  (12097): MountEmulatedStorage()
E/Zygote  (12097): v2
I/libpersona(12097): KNOX_SDCARD checking this for 10028
I/libpersona(12097): KNOX_SDCARD not a persona
,I/SELinux (12097): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=12097 uid=10028 gids={50028, 9997} abi=armeabi-v7a
,I/SELinux (12097): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12097): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/hcjo    (11876): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
W/PsynchoHelperImpl(11718): Error fetching or saving configuration
W/PsynchoHelperImpl(11718): bdz: 404 Not Found
W/PsynchoHelperImpl(11718): {
W/PsynchoHelperImpl(11718):   "errors": [
W/PsynchoHelperImpl(11718):     {
W/PsynchoHelperImpl(11718):       "domain": "global",
W/PsynchoHelperImpl(11718):       "reason": "notFound",
W/PsynchoHelperImpl(11718):       "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found",
W/PsynchoHelperImpl(11718):       "locationType": "other",
W/PsynchoHelperImpl(11718):       "location": "setting"
W/PsynchoHelperImpl(11718):     }
W/PsynchoHelperImpl(11718):   ],
W/PsynchoHelperImpl(11718):   "code": 404,
W/PsynchoHelperImpl(11718):   "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found"
W/PsynchoHelperImpl(11718): }
W/PsynchoHelperImpl(11718): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:113)
W/PsynchoHelperImpl(11718): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:40)
W/PsynchoHelperImpl(11718): 	at bdK.a(AbstractGoogleClientRequest.java:321)
W/PsynchoHelperImpl(11718): 	at bei.a(HttpRequest.java:1049)
W/PsynchoHelperImpl(11718): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:419)
W/PsynchoHelperImpl(11718): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:352)
W/PsynchoHelperImpl(11718): 	at bdJ.execute(AbstractGoogleClientRequest.java:469)
W/PsynchoHelperImpl(11718): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:142)
W/PsynchoHelperImpl(11718): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl(11718): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl(11718): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl(11718): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl(11718): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl(11718): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl(11718): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl(11718): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl(11718): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl(11718): 	at agP.run(LegacySyncManager.java:416)
D/hcjo    (11876): AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
D/hcjo    (11876): SelfUpdateManager:IDLE:execute
,I/MultiDex(12059): VM with version 2.1.0 has multidex support
I/MultiDex(12059): install
I/MultiDex(12059): VM has multidex support, MultiDex support library is disabled.
D/WifiService( 3517): Client connection lost with reason: 4
D/TimaKeyStoreProvider(12097): TimaSignature is unavailable
D/ActivityThread(12097): Added TimaKeyStore provider
D/hcjo    (11876): SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 4466): Untagging socket 104
I/Volley  (11876): RestApi Request Add : 2346
I/System.out(11876): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(11876): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid (11876): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 11876, getuid(): 10013
D/SettingsProvider( 3517): name = next_alarm_formatted
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 10094
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
D/ResourcesManager(12097): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
W/ResourcesManager(12097): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
V/JNIHelp (12059): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/SSRM:n  ( 3517): SIOP:: AP = 260, PST = 204, CUR = -465
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10101
,I/OMACP   (12097): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/ActivityThread(12059): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12059): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16e15647: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12059): Installed default security provider GmsCore_OpenSSL
,I/art     (12059): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     (12059): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/Mms/Omacp(11897): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/Mms/ArtClassLoader(11897): init before art
D/Mms/ArtClassLoader(11897): init [DONE] art
,D/Mms/PerformanceUtils(11897): link cahcing start
,I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   (12097): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,I/ActivityManager( 3517): Killing 10393:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
,D/Mms/PerformanceUtils(11897): link cahcing done
,D/WVCdm   ( 2859): Instantiating CDM.
,I/WVCdm   ( 2859): CdmEngine::OpenSession
I/WVCdm   ( 2859): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   ( 2859): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/System.out( 4466): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4466): Tagging socket 104 with tag 1000190000000000{268441856,0} uid 10014, pid: 4466, getuid(): 10014
,E/wv_dash ( 2859): No saved usage table. Creating new table.
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/NativeLibraryUtils(12059): Install completed successfully. count=14 extracted=0
,D/btif_config_util(10982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/Zygote  (12120): MountEmulatedStorage()
I/libpersona(12120): KNOX_SDCARD checking this for 10106
E/Zygote  (12120): v2
I/libpersona(12120): KNOX_SDCARD not a persona
,I/SELinux (12120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12120 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
I/SELinux (12120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12120): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3517): Killing 11142:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12120): TimaSignature is unavailable
,D/ActivityThread(12120): Added TimaKeyStore provider
,I/GoogleURLConnFactory(12059): Using platform SSLCertificateSocketFactory
,D/ResourcesManager(12120): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/elm:14491(12120): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491(12120): ELMEngine.ELMEngine( context ).
D/elm:14491(12120): MDMBridge.setEnterpriseBridge()
,D/elm:14491(12120): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12120): ElmAgentService : onCreate()
D/elm:14491(12120): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14491(12120): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491(12120): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491(12120): ModuleBase.ModifySetAlarm()
D/elm:14491(12120): MDMBridge.getInstance()
D/elm:14491(12120): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (12137): MountEmulatedStorage()
I/libpersona(12137): KNOX_SDCARD checking this for 10163
E/Zygote  (12137): v2
I/libpersona(12137): KNOX_SDCARD not a persona
,I/SELinux (12137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12137): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3517): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=12137 uid=10163 gids={50163, 9997} abi=armeabi-v7a
,D/elm:14491(12120): ElmAgentService : onDestroy().
I/qtaguid ( 4466): Untagging socket 104
,I/System.out(12059): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12059): (HTTPLog)-Static: isShipBuild true
I/System.out(12059): (HTTPLog)-Thread-1614-782026559: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12059): (HTTPLog)-Static: isSBSettingEnabled false
,I/ActivityManager( 3517): Killing 11280:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/System.out(12059): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid (12059): Tagging socket 30 with tag 1000180300000000{268441603,0} uid 10014, pid: 12059, getuid(): 10014
,D/TimaKeyStoreProvider(12137): TimaSignature is unavailable
,D/ActivityThread(12137): Added TimaKeyStore provider
,I/qtaguid (12059): Tagging socket 34 with tag 1000180300000000{268441603,0} uid 10014, pid: 12059, getuid(): 10014
,D/PackageManager( 3517): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/ResourcesManager(12137): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(12137): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12137): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/qtaguid (11876): Untagging socket -1
,I/qtaguid (11876): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid (11876): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger(11876): untagSocket(-1) failed with errno -9
,D/hcjo    (11876): SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
D/hcjo    (11876): AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
D/hcjo    (11876): SellerAppAutoUpdate:clearFlag
,D/SellerAppAutoUpdateManagerStateMachine(11876): execute::IDLE:EXECUTE
D/SellerAppAutoUpdateManagerStateMachine(11876): exit::IDLE
D/SellerAppAutoUpdateManagerStateMachine(11876): entry::TOKENCHECK
,D/SellerAppAutoUpdateManagerStateMachine(11876): execute::TOKENCHECK:TOKEN_RECEIVED
D/SellerAppAutoUpdateManagerStateMachine(11876): exit::TOKENCHECK
D/SellerAppAutoUpdateManagerStateMachine(11876): entry::FAILED
D/hcjo    (11876): AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
D/SellerAppAutoUpdateManagerStateMachine(11876): exit::FAILED
D/SellerAppAutoUpdateManagerStateMachine(11876): entry::IDLE
,I/ActivityManager( 3517): Killing 11304:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,I/qtaguid (12059): Untagging socket 30
,I/ActivityManager( 3517): Killing 11401:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,I/System.out( 4466): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4466): Tagging socket 104 with tag 1000150000000000{268440832,0} uid 10014, pid: 4466, getuid(): 10014
,I/System.out( 3517): Thread-145(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3517): Thread-145(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3517): Thread-145(ApacheHTTPLog):isShipBuild true
I/System.out( 3517): Thread-145(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 1000
,I/SecureStorage( 2918): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
,D/WVCdm   ( 2859): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   ( 2859): CdmEngine::QueryKeyControlInfo
,W/WVCdm   ( 2859): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   ( 2859): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   ( 2859): CdmEngine::GenerateKeyRequest
,W/WVCdm   ( 2859): CdmLicense::PrepareKeyRequest: unexpected HDCP max capability version 255
,D/WVCdm   ( 2859): PrepareKeyRequest: nonce=2099602524
,I/qtaguid ( 4466): Untagging socket 104
,I/PeopleSync( 4466): Sync finished, successful=true, took 1372ms
,I/PeopleContactsSync( 4466): CP2 sync start [5005f081]
,I/PeopleContactsSync( 4466): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 4466): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/art     (10368): Explicit concurrent mark sweep GC freed 4118(164KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 27MB/43MB, paused 462us total 11.324ms
,I/PeopleContactsSync( 4466): CP2 cleanup done, kept= duration=30 ms
,I/PeopleContactsSync( 4466): ===CP2 sync finished, success=true, time=45,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/PeopleSync( 4466): ***Sync finished***, duration: 1676 [5005f081]
,I/GoogleHttpClient(10368): GMS http client unavailable, use old client
,I/System.out( 3517): AsyncTask #1 calls detatch()
W/System.err( 3517): java.io.IOException: Not Found
W/System.err( 3517): 	at a.d.b(Unknown Source)
W/System.err( 3517): 	at a.d.doInBackground(Unknown Source)
W/System.err( 3517): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 3517): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 3517): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3517): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 3517): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 3517): 	at java.lang.Thread.run(Thread.java:818)
,I/dex2oat (12164): ----------------------------------------------------
I/dex2oat (12164): <SS>: S T A R T I N G . . .
I/dex2oat (12164): <SS>: Zip is absent. Canceled.
,I/dex2oat (12164): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(10368): Thread-1389(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(10368): Thread-1389(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10368): Thread-1389(ApacheHTTPLog):isShipBuild true
I/System.out(10368): Thread-1389(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/qtaguid (10368): Tagging socket 37 with tag 1244000400000000{306446340,0} uid -1, pid: 10368, getuid(): 10014
,I/dex2oat (12164): dex2oat took 28.776ms (threads: 8)
,I/qtaguid (10368): Tagging socket 41 with tag 1244000400000000{306446340,0} uid -1, pid: 10368, getuid(): 10014
,E/WifiStateMachine( 3517): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3517): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3517): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/SmartBondingService( 3517): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3517): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3517): getSBEnabled() enabled =false
D/SmartBondingService( 3517): getSBEnabled() enabled =false
D/SmartBondingService( 3517): getSBEnabled() enabled =false
V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,W/NetworkManagementService( 3517): route cmd failed: 
W/NetworkManagementService( 3517): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '56 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 56 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3517): '
W/NetworkManagementService( 3517): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3517): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3517): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3517): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3517): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3517): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3517): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3517): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3517): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3517): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 3517): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 4466): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 4466): CM callback handler got msg 524295
,I/WVCdm   ( 2859): CdmEngine::CloseSession
,I/WVCdm   ( 2859): L3 Terminate.
,I/SecureStorage(11996): [INFO]: SPID(0x00000006)Processing data has been completed
,I/SecureStorage(11996): [INFO]: SPID(0x00000006)Skip using SecureStorageExceptionJNI
,D/WVMDrmPlugIn( 2858): WVMDrmPlugin::onInitialize : 3317
D/WVMDrmPlugIn( 2858): WVMDrmPlugin::onSetOnInfoListener : add 3317
,D/WVMDrmPlugIn( 2858): WVMDrmPlugin::onGetSupportInfo : 0
,I/SecSQLiteOpenHelper(11932): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11932): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11932): Open platform.db in secure mode
I/SecSQLiteDatabase(11932): openSecureDatabase...
I/SecSQLiteDatabase(11932): private openSecureDatabase...
I/SecSQLiteConnectionPool(11932): OpenSecure
I/SecSQLiteConnectionPool(11932): OpenSecure with password
I/SecSQLiteConnectionPool(11932): openSecureConnectionLocked
I/SecSQLiteDatabase(11932): ...private openSecureDatabase
I/SecSQLiteDatabase(11932): ...openSecureDatabase
,I/WVCdm   ( 2859): CdmEngine::OpenSession
,I/WVCdm   ( 2859): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   ( 2859): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,E/wv_dash ( 2859): No saved usage table. Creating new table.
,I/SecSQLiteOpenHelper(11932): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11932): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/WVCdm   ( 2859): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/-----SIC-----(11932): ------------------skip TGH
,I/SecSQLiteOpenHelper(11932): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11932): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11932): Open platform.db in secure mode
I/SecSQLiteDatabase(11932): openSecureDatabase...
I/SecSQLiteDatabase(11932): private openSecureDatabase...
I/SecSQLiteConnectionPool(11932): OpenSecure
I/SecSQLiteConnectionPool(11932): OpenSecure with password
I/SecSQLiteConnectionPool(11932): openSecureConnectionLocked
,I/SecSQLiteDatabase(11932): ...private openSecureDatabase
I/SecSQLiteDatabase(11932): ...openSecureDatabase
,I/WVCdm   ( 2859): CdmEngine::QueryKeyControlInfo
,W/WVCdm   ( 2859): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   ( 2859): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   ( 2859): CdmEngine::GenerateKeyRequest
,W/WVCdm   ( 2859): CdmLicense::PrepareKeyRequest: unexpected HDCP max capability version 255
,D/WVCdm   ( 2859): PrepareKeyRequest: nonce=2350265163
,I/SecSQLiteOpenHelper(11932): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11932): ...getDatabaseLocked(b,b,pwd)
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11932): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11932): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer(11932): decode(34, 20909908, 4230)
,V/MediaPlayerService( 2859): decode(38, 20909908, 4230)
,V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
,V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20909908, 4230)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
,V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2859): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
,I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2859): wait for playback complete
V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
,V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
,I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/MediaPlayer(11932): decode(36, 20763080, 15440)
V/MediaPlayerService( 2859): decode(38, 20763080, 15440)
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
,V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20763080, 15440)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
,V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/SO_AGENT(11542): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/SA      (11627): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2859): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2859): wait for playback complete
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
,I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/MediaPlayer(11932): decode(37, 20807608, 9226)
V/MediaPlayerService( 2859): decode(38, 20807608, 9226)
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthServiceInstalled() : HealthService is Installed.
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
,V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20807608, 9226)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthServiceInstalled() : HealthService is Installed.
,I/qtaguid (10368): Untagging socket 37
,I/System.out(10368): GDataFeedFetcher calls detatch()
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/CalendarProvider2(11964): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/AdaptiveEventManager( 3691): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3691): M updateContainers()
D/AdaptiveEventContainerSmall( 3691): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3691): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3691): pedoEvent == null
,V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
,D/AdaptiveEventManager( 3691): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3691): M updateContainers()
D/AdaptiveEventContainerSmall( 3691): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3691): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3691): pedoEvent == null
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2859): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1733175209, value : 485677307
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1733175209, value : 485677307
,V/MediaPlayerService( 2859): wait for playback complete
,I/ActivityManager( 3517): Killing 11421:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3517): Killing 11336:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2859): addBatteryData
W/System.err(11932): java.lang.NumberFormatException: Invalid int: "null"
W/System.err(11932): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err(11932): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err(11932): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err(11932): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:498)
W/System.err(11932): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1242)
W/System.err(11932): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11932): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11932): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/AudioCache( 2859): wait - success
,V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
,I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/MediaPlayer(11932): decode(35, 20914220, 4890)
,V/MediaPlayerService( 2859): decode(38, 20914220, 4890)
E/DatabaseUtils( 3517): Writing exception to parcel
E/DatabaseUtils( 3517): java.lang.NullPointerException: key == null
E/DatabaseUtils( 3517): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils( 3517): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils( 3517): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils( 3517): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:376)
E/DatabaseUtils( 3517): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils( 3517): 	at android.os.Binder.execTransact(Binder.java:446)
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
,V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20914220, 4890)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
D/Mms/Contact(11897): performUpdate:widgetCount=0
,V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
,I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/qtaguid (10368): Tagging socket 37 with tag 1144000400000000{289669124,0} uid -1, pid: 10368, getuid(): 10014
,I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
D/Mms/Contact(11897): sContactsObserver.onChange(),selfUpdate=false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 2859): notify(0xb236c380, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2859): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
,V/MediaPlayerService( 2859): wait for playback complete
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
W/System.err(10229): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
,V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
W/System.err(10229): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err(10229): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err(10229): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err(10229): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err(10229): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
W/System.err(10229): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
W/System.err(10229): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
W/System.err(10229): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10229): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10229): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10229): 	at java.lang.reflect.Method.invoke(Native Method)
I/splitIntent( 3517): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
W/System.err(10229): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10229): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10229): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
I/DBG_DM  ( 5897): [com.wssyncmldm.lllIlIlIIIllIIlIllIl(350/onReceive)] FotaPostpone callback received
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/MediaPlayer(11932): decode(39, 20840384, 17329)
V/MediaPlayerService( 2859): decode(38, 20840384, 17329)
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20840384, 17329)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2859): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 3
V/MediaPlayerService( 2859): wait for playback complete
D/Mms/ContactsCache(11897): [start]    invalidate() consume time = 1135.449958
D/Mms/ContactsCache(11897): [end]    invalidate() consume time = 0.106334
D/LightsService( 3517): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3517) 
D/LightsService( 3517): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/Sensors ( 3517): Light old sensor_state 0, new sensor_state : 512 en : 1
D/SensorManager( 3517): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/PersonaManager( 3691): isKioskContainerExistOnDevice
D/PersonaManager( 3691): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3691): Icon Only
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/StatusBar( 3691): Icon Only
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
D/PanelView( 3691): There is/are notification(s) 
I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
D/PanelView( 3691): There is/are notification(s) 
I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
D/PersonaManager( 3691): isKioskContainerExistOnDevice
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/PhoneStatusBar( 3691): Icon Only
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
I/StatusBar( 3691): Icon Only
D/PanelView( 3691): There is/are notification(s) 
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/MediaPlayer(11932): decode(40, 20740576, 6644)
V/MediaPlayerService( 2859): decode(38, 20740576, 6644)
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20740576, 6644)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
I/DBG_DM  ( 5897): [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/DBG_DM  ( 5897): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2859): open(44100, 1, 0x0, 1, 0)
I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
V/MediaPlayerService( 2859): wait for playback complete
I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 5897): [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
E/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
E/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@14316a09
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/MediaPlayer(11932): decode(41, 20816916, 23389)
V/MediaPlayerService( 2859): decode(38, 20816916, 23389)
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20816916, 23389)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2859): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2859): wait for playback complete
I/DBG_DM  ( 5897): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
V/AlarmManager( 3517):  next == MAX_VALUE
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
D/SecContentProvider2( 3517): uri = 14 selection = getSealedState
D/SecContentProvider2( 3517): mCursor = null
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
D/ApplicationPolicy( 3517): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/ApplicationPolicy( 3517): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
D/WindowManager( 3517): showStatusBarByNotification() mOpenByNotification=false
V/MediaPlayer(11932): decode(42, 20706272, 8154)
V/MediaPlayerService( 2859): decode(38, 20706272, 8154)
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20706272, 8154)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/DBG_DM  ( 5897): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2859): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2859): wait for playback complete
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/MediaPlayer(11932): decode(43, 20679752, 4804)
V/MediaPlayerService( 2859): decode(38, 20679752, 4804)
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20679752, 4804)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/DBG_DM  ( 5897): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2673/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/DBG_DM  ( 5897): [llIIIllllIIIlIIIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2859): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 6, 0, 0)
I/AudioPlayer( 2859): First fillBuffer call!!
V/AudioCache( 2859): ignored
I/qtaguid (10368): Untagging socket 37
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
I/System.out(10368): GDataFeedFetcher calls detatch()
V/AwesomePlayer( 2859): addBatteryData
V/MediaPlayerService( 2859): wait for playback complete
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x84, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
D/KnoxNotification( 3691): ----- inflateViews : modified publicViewLocal -----
I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/MediaPlayer(11932): decode(44, 20649204, 9400)
I/DBG_DM  ( 5897): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
V/MediaPlayerService( 2859): decode(38, 20649204, 9400)
I/DBG_DM  ( 5897): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20649204, 9400)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
D/Mms/Contact(11897): sContactsObserver.onChange(),selfUpdate=false
V/MediaPlayer(11932): decode(50, 20722624, 4112)
V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/MediaPlayerService( 2859): decode(41, 20722624, 4112)
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
V/AwesomePlayer( 2859): onPrepareAsyncEvent
D/Mms/ContactsCache(11897): [start]    invalidate() consume time = 92.984916
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(41, 20722624, 4112)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
D/Mms/ContactsCache(11897): [end]    invalidate() consume time = 0.266125
V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2859): open(44100, 1, 0x0, 1, 0)
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
V/AwesomePlayer( 2859): finishAsyncPrepare_l
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/AudioCache( 2859): notify(0xae922510, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
V/MediaPlayerService( 2859): wait for playback complete
D/KnoxNotification( 3691): ----- inflateViews : modified KnoxViewLocal -----
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
E/SQLiteLog( 4233): (284) automatic index on sqlite_sq_B3918970(STAT_DATA_ID)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:1, 1, 0
E/SQLiteLog( 4233): (284) automatic index on sqlite_sq_B3918B00(STAT_DATA_ID)
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2859): open(44100, 1, 0x0, 1, 0)
D/PersonaManager( 3691): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 3691): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2b61bd25
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
D/PersonaManager( 3691): isKioskContainerExistOnDevice
V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
D/PersonaManager( 3691): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3691): Icon Only
V/AwesomePlayer( 2859): onCheckAudioStatus
V/MediaPlayerService( 2859): wait for playback complete
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x86, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
I/StatusBar( 3691): Icon Only
I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
D/PanelView( 3691): There is/are notification(s) 
D/PanelView( 3691): There is/are notification(s) 
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
D/PersonaManager( 3691): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3691): Icon Only
I/StatusBar( 3691): Icon Only
D/PanelView( 3691): There is/are notification(s) 
I/DBG_DM  ( 5897): [com.wssyncmldm.DMSecBroadcastReceiver(194/onReceive)] sec.fota.polling.intent.RECEIVE
D/PanelView( 3691): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
I/System.out(11718): SyncManager calls detatch()
I/DBG_DM  ( 5897): [com.wssyncmldm.DMSecBroadcastReceiver(556/llllIIIllIlIIIIllllI)] nMode : 0
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x85, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
V/MediaPlayer(11932): decode(45, 20857804, 52024)
V/MediaPlayerService( 2859): decode(38, 20857804, 52024)
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20857804, 52024)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_DM  ( 5897): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(211/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(3786/IllIIlllIllIIIIIllII)] Wifi_Only_flag : true
I/DBG_DM  ( 5897): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/DBG_DM  ( 5897): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(236/llIIIIlllllIIllIIllI)] bWifiOnly flag : true
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2859): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
V/MediaPlayerService( 2859): wait for playback complete
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_DM  ( 5897): [llIIIllllIIIlIIIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
I/DBG_DM  ( 5897): [IIllIIIIlIlIlIlIllII(1845/lIlIIlIlIIlIlIIIIlll)] bUpdateProcessing : false
I/DBG_DM  ( 5897): [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
,V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x87, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
,I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
,V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
,V/MediaPlayer(11932): decode(46, 20722624, 4112)
V/MediaPlayerService( 2859): decode(38, 20722624, 4112)
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
,V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
,V/StagefrightPlayer( 2859): setDataSource(38, 20722624, 4112)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
,V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
,V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
,V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 5, 0, 0)
,V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2859): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
,E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/MediaPlayerService( 2859): wait for playback complete
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xafffdb50, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x88, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
,I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
,V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/MediaPlayer(11932): decode(47, 20785700, 21825)
V/MediaPlayerService( 2859): decode(38, 20785700, 21825)
,V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
,V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20785700, 21825)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
,I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
,V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
,V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2859): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 6, 0, 0)
V/AudioCache( 2859): ignored
I/AudioPlayer( 2859): First fillBuffer call!!
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
V/MediaPlayerService( 2859): wait for playback complete
,D/PanelView( 3691): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae922510, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x89, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
,I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
,V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/MediaPlayer(11932): decode(48, 20684636, 21552)
,V/MediaPlayerService( 2859): decode(38, 20684636, 21552)
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20684636, 21552)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
,V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 5, 0, 0)
V/AudioCache( 2859): ignored
,V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2859): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 6, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
,I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
V/MediaPlayerService( 2859): wait for playback complete
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xae822330, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x8a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
,I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/MediaPlayer(11932): decode(49, 20778600, 7017)
V/MediaPlayerService( 2859): decode(38, 20778600, 7017)
V/MediaPlayerService( 2859): player type = 3
V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): constructor
,V/AwesomePlayer( 2859): setDefault
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): StagefrightPlayer
V/AwesomePlayer( 2859): setListener
V/StagefrightPlayer( 2859): initCheck
V/AwesomePlayer( 2859): setAudioSink
V/StagefrightPlayer( 2859): setDataSource(38, 20778600, 7017)
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
,V/AwesomePlayer( 2859): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2859): mBitrate = -1 bits/sec
I/OggExtractor( 2859): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2859): current audio track index (0) is added to vector
V/AwesomePlayer( 2859): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2859): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2859): prepare
V/AwesomePlayer( 2859): prepareAsync
V/MediaPlayerService( 2859): wait for prepare
V/AwesomePlayer( 2859): onPrepareAsyncEvent
I/SecMediaClock( 2859): SecMediaClock constructor
I/SecMediaClock( 2859): reset
I/SecVideoCapture( 2859): SecVideoCapture constructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): initAudioDecoder
V/AwesomePlayer( 2859): checkOffloadExceptions is true
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2859): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2859): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2859): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2859): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2859): finishAsyncPrepare_l
V/AwesomePlayer( 2859): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 200, 973, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 5, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 1, 0, 0)
V/AudioCache( 2859): prepared
V/AudioCache( 2859): wait - success
V/MediaPlayerService( 2859): start
V/StagefrightPlayer( 2859): start
V/AwesomePlayer( 2859): play
V/AwesomePlayer( 2859): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2859): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2859): >>>UHQA initOutputFormat 16
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2859): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2859): open(44100, 2, 0x0, 1, 0)
,I/Sensors ( 3517): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
V/AwesomePlayer( 2859): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 6, 0, 0)
D/LightsService( 3517): [SvcLED]  onSensorChanged::light value = 0
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): addBatteryData
I/AudioPlayer( 2859): First fillBuffer call!!
I/AudioPlayer( 2859): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2859): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2859): wait for playback complete
I/Sensors ( 3517): Light old sensor_state 512, new sensor_state : 0 en : 0
,I/art     ( 3517): Explicit concurrent mark sweep GC freed 32560(1819KB) AllocSpace objects, 5(103KB) LOS objects, 24% free, 48MB/64MB, paused 1.275ms total 78.941ms
,D/SensorManager( 3517): unregisterListener ::   
D/LightsService( 3517): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2859): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2859): onCheckAudioStatus
V/AwesomePlayer( 2859): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2859): onStreamDone
V/AwesomePlayer( 2859): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2859): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 2, 0, 0)
V/AudioCache( 2859): playback complete - thread will wake up later
V/AwesomePlayer( 2859): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 7, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2859): addBatteryData
V/AudioCache( 2859): wait - success
V/StagefrightPlayer( 2859): reset
,V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2859): notify(0xb236c380, 8, 0, 0)
V/AudioCache( 2859): ignored
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stop() sendCommand(0x8b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2859): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2859): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2859): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2859): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2859): ~OggSource --
I/OggExtractor( 2859): ~OggExtractor ++
I/OggExtractor( 2859): ~MyVorbisExtractor ++ 
I/OggExtractor( 2859): ~MyVorbisExtractor --
I/OggExtractor( 2859): ~OggExtractor --
,D/OpenGLRenderer( 5897): Render dirty regions requested: true
,W/GAV2    (11718): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/WifiService( 3517): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@1fa75e4f}
,I/AudioPlayer( 2859): reset out
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2859): SecVideoCapture destructor
I/SecVideoCapture( 2859): reset
V/AwesomePlayer( 2859): mSecCapture clear
I/SecMediaClock( 2859): SecMediaClock destructor
V/AwesomePlayer( 2859): mSecMediaClock clear
V/StagefrightPlayer( 2859): ~StagefrightPlayer
V/StagefrightPlayer( 2859): reset
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
V/AwesomePlayer( 2859): destructor
V/AwesomePlayer( 2859): reset_l()
V/AwesomePlayer( 2859): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2859): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2859): mAudioTrackVector clear
V/AwesomePlayer( 2859): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2859): mSecCapture clear
V/AwesomePlayer( 2859): mSecMediaClock clear
,E/SQLiteLog( 4233): (284) automatic index on sqlite_sq_AF8E7060(STAT_DATA_ID)
,I/DBG_DM  ( 5897): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,E/SQLiteLog( 4233): (284) automatic index on sqlite_sq_AF82E420(STAT_DATA_ID)
,I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 5897): [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger( 2854): id=13 createSurf (1x1),1 flag=4, Uoast
,E/Zygote  (12295): MountEmulatedStorage()
E/Zygote  (12295): v2
I/libpersona(12295): KNOX_SDCARD checking this for 10123
I/libpersona(12295): KNOX_SDCARD not a persona
,I/SELinux (12295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=12295 uid=10123 gids={50123, 9997, 3003} abi=armeabi-v7a
,I/SELinux (12295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12295): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,D/PowerManagerService( 3517): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3517
I/ActivityManager( 3517): Killing 11572:com.policydm/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3517): Killing 11666:com.samsung.android.scloud.backup/u0a67 (adj 13): bgCount ##31
,I/OpenGLRenderer( 5897): Initialized EGL, version 1.4
,D/TimaKeyStoreProvider(12295): TimaSignature is unavailable
,D/ActivityThread(12295): Added TimaKeyStore provider
,I/OpenGLRenderer( 5897): HWUI protection enabled for context ,  &this =0xaf222088 ,&mEglDisplay = 1 , &mEglConfig = -1356472048 
,D/ResourcesManager(12295): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/DBG_DM  ( 5897): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
D/OpenGLRenderer( 5897): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 5897): Enabling debug mode 0
,D/mali_winsys( 5897): new_window_surface returns 0x3000,  [616x201]-format:1
,I/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,V/AlarmManager( 3517):  next == MAX_VALUE
E/DBG_DM  ( 5897): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@14316a09
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/WVCdm   ( 2859): CdmEngine::CloseSession
,I/WVCdm   ( 2859): L3 Terminate.
D/SecContentProvider2( 3517): uri = 14 selection = getSealedState
D/SecContentProvider2( 3517): mCursor = null
D/ApplicationPolicy( 3517): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3517): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
E/Zygote  (12324): MountEmulatedStorage()
E/Zygote  (12324): v2
I/libpersona(12324): KNOX_SDCARD checking this for 10125
I/DBG_DM  ( 5897): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/libpersona(12324): KNOX_SDCARD not a persona
I/SELinux (12324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12324): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=12324 uid=10125 gids={50125, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/StatusBar( 3691): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
D/PersonaManager( 3691): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3691): Icon Only
I/StatusBar( 3691): Icon Only
D/PanelView( 3691): There is/are notification(s) 
D/PanelView( 3691): There is/are notification(s) 
D/PersonaManager( 3691): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3691): Icon Only
I/StatusBar( 3691): Icon Only
D/PanelView( 3691): There is/are notification(s) 
,D/TimaKeyStoreProvider(12324): TimaSignature is unavailable
,V/AlarmManager( 3517):  next == MAX_VALUE
D/ActivityThread(12324): Added TimaKeyStore provider
,I/DBG_DM  ( 5897): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 5897): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 5897): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,D/ResourcesManager(12324): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(12324): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/BaseAppContext( 4466): Using Auth Proxy for data requests.
W/BaseAppContext( 4466): Using Auth Proxy for data requests.
,W/BaseAppContext( 4466): Using Auth Proxy for data requests.
W/BaseAppContext( 4466): Using Auth Proxy for data requests.
,W/AbstractGoogleClient(12295): Application name is not set. Call Builder#setApplicationName.
,W/BaseAppContext( 4466): Using Auth Proxy for data requests.
,W/BaseAppContext( 4466): Using Auth Proxy for data requests.
,W/BaseAppContext( 4466): Using Auth Proxy for data requests.
,D/PanelView( 3691): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,V/AlarmManager( 3517): waitForAlarm result :4
,I/Babel   (12324): MmsConfig: mnc/mcc: 0/0
I/Babel   (12324): MmsConfig.loadMmsSettings
I/Babel   (12324): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
I/Babel   (12324): MmsConfig.loadFromDatabase
,D/ResourcesManager(12324): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/Babel   (12324): canonicalizeMccMnc: invalid mccmnc 
I/Babel   (12324): MmsConfig.loadFromResources
,E/Babel   (12324): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   (12324): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
,W/AudioCapabilities(12324): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities(12324): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities(12324): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities(12324): Unsupported mime audio/x-ima
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities(12324): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities(12324): Unsupported mime video/wvc1
,W/VideoCapabilities(12324): Unsupported mime video/x-ms-wmv
,E/Zygote  (12357): MountEmulatedStorage()
I/libpersona(12357): KNOX_SDCARD checking this for 10135
E/Zygote  (12357): v2
I/libpersona(12357): KNOX_SDCARD not a persona
,I/SELinux (12357): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=12357 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Settings(12324): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SELinux (12357): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12357): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/VideoCapabilities(12324): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities(12324): Unsupported mime video/wvc1
,W/VideoCapabilities(12324): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities(12324): Unsupported mime video/x-ms-wmv7
,D/TimaKeyStoreProvider(12357): TimaSignature is unavailable
,D/ActivityThread(12357): Added TimaKeyStore provider
,W/VideoCapabilities(12324): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities(12324): Unsupported mime video/sorenson
,W/VideoCapabilities(12324): Unsupported mime video/mp43
,D/ResourcesManager(12357): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/AudioCapabilities(12324): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities(12324): Unsupported mime audio/mpeg-L2
,W/VideoCapabilities(12324): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4247): Tagging socket 72 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,I/GCM     ( 4466): Message from null null
E/GCM     ( 4466): Dropping message from null
,D/ResourcesManager(12324): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/splitIntent( 3517): Split this intent : com.google.android.gms.INITIALIZE !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
I/splitIntent( 3517): finish to split intent : com.google.android.gms.INITIALIZE !! Enqueue -> schedule it!!
,W/ResourcesManager(12324): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12324): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/VideoCapabilities(12324): Unsupported profile 4 for video/mp4v-es
,D/AuthorizationBluetoothService( 4247): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4466): Restart initialization of location
,D/WearableService( 4247): callingUid 10014, callindPid: 4247
,E/MDM     ( 4247): [286] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/MusicStore(12357): Database version: 104
,V/JNIHelp (12324): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 4247): No location to return for getLastLocation()
,W/FusedLocationProvider( 4247): location=null
,I/splitIntent( 3517): Queue : backgroundsplit_1 intent com.google.android.gms.INITIALIZE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/ChimeraCfgMgr( 4466): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4466): Module APK com.google.android.play.games already loaded
,I/CheckinRequestBuilder( 4466): Classify the device as Phone.
,W/PlaySystemBroadcastReceiver( 4466): Processed handlePeopleChanged at 307898
,D/ResourcesManager(12357): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ChimeraCfgMgr( 4466): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4466): Module APK com.google.android.play.games already loaded
,W/ResourcesManager(12357): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12357): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/DataBroker( 4466): No player ID found and calling context is not the dest app
,W/ActivityThread(12324): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12324): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17e4c7c9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12324): Installed default security provider GmsCore_OpenSSL
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants(11932): RegionGroup for  is null
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11932): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,V/JNIHelp (12357): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
E/Zygote  (12392): MountEmulatedStorage()
E/Zygote  (12392): v2
I/libpersona(12392): KNOX_SDCARD checking this for 10022
I/libpersona(12392): KNOX_SDCARD not a persona
,I/SELinux (12392): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12392): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12392): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12392 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 340us total 10.513ms
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 342us total 8.758ms
,D/TimaKeyStoreProvider(12392): TimaSignature is unavailable
,D/ActivityThread(12392): Added TimaKeyStore provider
,W/ActivityThread(12357): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12357): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19c0175e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12357): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12357): GMSCore installation verified
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 681us total 9.150ms
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(12392): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12392): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/ConfigStore(12357): Config Database version: 1
,I/LocationWidgetApplication(12392): onCreate() : start
,D/LocationWidgetApplication(12392): countryCode = POLAND
,D/LocationWidgetUtils(12392): getUpcommingInstances() start: 1451923698474, end: 1452466799999
E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
D/LocationWidgetUtils(12392): getUpcommingInstances() DB begin time >= start:1451923698474, DB begin time <= end:1452466799999
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/Mms/MmsApp(11897):  start initViewCache mms
,D/Mms/ComposeMessageFragment(11897): [start]    fillCache consume time = 624.235334
D/Mms/ComposeMessageFragment(11897): fillCache, easy = false
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4247): Tagging socket 87 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,E/SQLiteLog(11964): (284) automatic index on view_events(_id)
,D/WifiDisplayAdapter( 3517): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/BluetoothManager(11932): getConnectedDevices
D/BluetoothManager(11932): getConnectedDevices
,D/BluetoothManager(11932): getConnectedDevices
,D/WifiDisplayAdapter( 3517): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3517): getStreamVolume 3 index 0
,I/MediaRouter(12357): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/CalendarAlarmManager(11964): sys current time:1451923698513
,D/CalendarAlarmManager(11964): reminder amount:0
,I/System.out(12295): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12295): (HTTPLog)-Static: isShipBuild true
I/System.out(12295): (HTTPLog)-Thread-1641-513940740: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12295): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10123
,E/SQLiteLog( 4466): (284) automatic index on invitations(external_inviter_id)
,D/AbsListView(11897): Get MotionRecognitionManager
,I/System.out(12295): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (12295): Tagging socket 28 with tag 1100000000000000{285212672,0} uid -1, pid: 12295, getuid(): 10123
,D/MotionRecognitionService( 3517):  ssp status : true
,D/Mms/ComposeMessageFragment(11897): [end]    fillCache consume time = 53.378791
,D/BluetoothManager(11932): getConnectedDevices
,I/GHttpClientFactory(12357): Using the GMSCore's GoogleHttpClient
,D/BluetoothManager(11932): getConnectedDevices
,D/BluetoothManager(11932): getConnectedDevices
,I/NetworkMonitor(12357): type=WIFI subType= reason=null isConnected=true
,D/LocationManagerService( 3517): getProviders()=[]
D/LocationManagerService( 3517): getProviders()=[passive]
D/LocationManagerService( 3517): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/WifiDisplayAdapter( 3517): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/NetworkMonitor(12357): type=WIFI subType= reason=null isConnected=true
D/LWLocationManager(12392): mPrivacy is null
W/ContextImpl(12392): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
I/System.out( 4466): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4466): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4466): Tagging socket 123 with tag 1000040800000000{268436488,0} uid -1, pid: 4466, getuid(): 10014
D/ContextFramework:PrivacyManager(12392): Service for PrivacyManager is connected
,D/LWLocationManager(12392): Privacy service : STATUS_PLACE
D/LWLocationManager(12392): updateLocationStatus()
,I/qtaguid ( 4466): Tagging socket 126 with tag 1000040800000000{268436488,0} uid -1, pid: 4466, getuid(): 10014
,I/LocationWidgetFuctionData(12392): readDB
,I/LocationWidgetFuctionData(12392): selectedAppSize: 3
I/LocationWidgetFuctionData(12392): configPlaceList aroundMeItems
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12436): MountEmulatedStorage()
I/libpersona(12436): KNOX_SDCARD checking this for 10003
E/Zygote  (12436): v2
I/libpersona(12436): KNOX_SDCARD not a persona
,I/SELinux (12436): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12436): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12436): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=12436 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
I/CheckinTask( 4466): Sending checkin request (10951 bytes)
,D/TimaKeyStoreProvider(12436): TimaSignature is unavailable
,D/ActivityThread(12436): Added TimaKeyStore provider
,I/ActivityManager( 3517): Killing 11491:com.google.android.videos/u0a195 (adj 13): bgCount ##31
,D/ResourcesManager(12436): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/UserAnalysis.PlaceProvider(12436): PlaceProvider onCreate()
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12357): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12357): (HTTPLog)-Static: isShipBuild true
I/System.out(12357): (HTTPLog)-Thread-1661-338273728: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12357): (HTTPLog)-Static: isSBSettingEnabled false
D/UserAnalysis.SecureDbManager(12436): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(12436): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(12436): Create SecureDbHelper
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10135
,D/IntelligenceServiceApplication(12436): onCreate()
,D/Mms/BubbleViewCache(11897): fillCache bubble = 8
,I/LocationWidgetFuctionData(12392): selectedAppSize: 3
,I/LocationWidgetFuctionData(12392): selectedAppSize: 3
,I/LocationWidgetFuctionData(12392): selectedAppSize: 3
,I/LocationWidgetFuctionData(12392): selectedAppSize: 3
,I/System.out(12324): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12324): (HTTPLog)-Static: isShipBuild true
I/System.out(12324): (HTTPLog)-Thread-1658-678280343: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12324): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10125
,I/System.out(12324): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/System.out(12357): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/LWLocationManager(12392): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(12392): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(12392): setShouldUpdateLocationId
D/LWLocationManager(12392): setShouldUpdateLocationId return false
D/LWLocationManager(12392): setShouldUpdateLocationId
D/LWLocationManager(12392): setShouldUpdateLocationId return false
D/LWLocationManager(12392): setShouldUpdateLocationId
D/LWLocationManager(12392): setShouldUpdateLocationId return false
D/LWLocationManager(12392): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,I/qtaguid (12295): Untagging socket 28
,D/CalendarSyncAdapter(12295): Found 0 events marked dirty & lastSynced
,I/ActivityManager( 3517): Killing 11688:com.sec.knox.bridge/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3517): Killing 11319:com.android.chrome/u0a90 (adj 13): bgCount ##31
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4247): Tagging socket 92 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12357): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4466): Untagging socket 123
,W/MusicApiClient(12357): No content in 'data' field in GET sync response for Track
,D/ResourcesManager( 4466): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/CheckinRequestBuilder( 4466): Checkin reason type: 12 attempt count: 1
,I/art     ( 3517): Explicit concurrent mark sweep GC freed 36126(1962KB) AllocSpace objects, 13(2MB) LOS objects, 24% free, 48MB/64MB, paused 1.902ms total 141.312ms
,I/GAV2    (11442): Thread[GAThread,5,main]: No campaign data found.
,E/ActivityThread( 4466): Failed to find provider info for com.google.android.wearable.settings
,I/MusicSyncAdapter(12357): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter(12357): Periodic update
,I/art     (12324): Note: end time exceeds epoch: 
,I/Babel   (12324): Account registration complete:Redacted-21
,I/art     (10368): Explicit concurrent mark sweep GC freed 21642(1050KB) AllocSpace objects, 3(71KB) LOS objects, 36% free, 27MB/43MB, paused 1.632ms total 37.790ms
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12472): MountEmulatedStorage()
,E/Zygote  (12472): v2
I/libpersona(12472): KNOX_SDCARD checking this for 10031
,I/libpersona(12472): KNOX_SDCARD not a persona
,I/SELinux (12472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=12472 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12472): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/art     (11789): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider(12472): TimaSignature is unavailable
,D/ActivityThread(12472): Added TimaKeyStore provider
,D/ResourcesManager(12472): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10147
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12496): MountEmulatedStorage()
E/Zygote  (12496): v2
I/libpersona(12496): KNOX_SDCARD checking this for 10090
I/libpersona(12496): KNOX_SDCARD not a persona
,I/SELinux (12496): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=12496 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12496): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12496): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Killing 11038:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12496): TimaSignature is unavailable
,D/ActivityThread(12496): Added TimaKeyStore provider
,D/ResourcesManager(12496): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/Finsky  (12472): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/DelayedSyncController(12496): Delaying sync.
,I/CheckinRequestBuilder( 4466): Classify the device as Phone.
,I/CheckinTask( 4466): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4466): Checking schedule, now: 1451923699553 next: 1452503078546
I/CheckinService( 4466): active receiver: disabled
,D/Finsky  (12472): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/CheckinService( 4466): Recording last checkin time for package unspecified as 1451923699574
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Settings(12472): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(12472): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Auth.Api.Credentials( 4466): [CredentialSyncAdapter] Unknown sync event.
,D/Ads     (12472): Skipping gmscore version check
,I/System.out(12472): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12472): (HTTPLog)-Static: isShipBuild true
I/System.out(12472): (HTTPLog)-Thread-1683-12033675: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12472): (HTTPLog)-Static: isSBSettingEnabled false
I/ActivityManager( 3517): Killing 11703:com.google.android.apps.magazines/u0a136 (adj 13): bgCount ##31
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10031
,D/Finsky  (12472): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (12472): [1] Libraries$2.run: Finished loading 1 libraries.
,I/System.out(12472): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/Finsky  (12472): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,D/Finsky  (12472): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ContextImpl(12357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ArtDownloadService(12357): Setting cache size 0
,W/System  (12357): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/GHttpClientFactory(12357): Using the GMSCore's GoogleHttpClient
,D/GCM     ( 4247): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/Mms/Contact(11897): performUpdate:widgetCount=0
,I/MusicLeanback(12357): Conditions not met for autocaching.
I/MusicLeanback(12357): Stop autocaching.
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,D/WearableClient(12357): WearableClientImpl.onPostInitHandler: done
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,D/WearableClient(12357): WearableClientImpl.onPostInitHandler: done
W/ContextImpl(12357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,D/WearableClient(12357): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12357): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12357): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12357): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12357): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2c02b1d9 that was originally bound here
E/ActivityThread(12357): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2c02b1d9 that was originally bound here
E/ActivityThread(12357): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12357): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12357): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12357): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12357): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12357): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12357): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12357): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12357): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12357): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12357): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12357): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12357): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12357): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12357): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12357): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12357): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12357): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12357): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12357): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12357): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/art     ( 4466): Explicit concurrent mark sweep GC freed 34662(2MB) AllocSpace objects, 25(686KB) LOS objects, 33% free, 31MB/47MB, paused 1.982ms total 59.970ms
,W/SQLiteConnectionPool( 4466): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/GoogleURLConnFactory( 4466): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4466): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 4466): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4466): Tagging socket 118 with tag 1000210100000000{268443905,0} uid -1, pid: 4466, getuid(): 10014
,I/qtaguid ( 4466): Tagging socket 129 with tag 1000210100000000{268443905,0} uid -1, pid: 4466, getuid(): 10014
,I/dhcpcd  (11222): wlan0: sending IPv6 Router Solicitation
,E/AclDataUtils(11789): Circle ID not found for type: 9
,I/RemindersSync( 4466): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=347:priority=5:group=main]
,V/AlarmManager( 3517): waitForAlarm result :4
,D/Finsky  (12472): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/GCoreUlr( 4247): Uploading GCM registration ID for account#2#
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4247): Using Auth Proxy for data requests.
,E/BaseAppContext( 4247): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/System.out(12472): Thread-1672(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12472): Thread-1672(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12472): Thread-1672(ApacheHTTPLog):isShipBuild true
I/System.out(12472): Thread-1672(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10031
,I/qtaguid (12472): Tagging socket 47 with tag e8d195d100000000{3906049489,0} uid -1, pid: 12472, getuid(): 10031
,I/GAV2    (11718): Thread[GAThread,5,main]: No campaign data found.
,I/qtaguid (12472): Tagging socket 51 with tag e8d195d100000000{3906049489,0} uid -1, pid: 12472, getuid(): 10031
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4247): Tagging socket 72 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,I/GAV2    (11789): Thread[GAThread,5,main]: No campaign data found.
,I/qtaguid (12472): Untagging socket 47
,I/System.out(12472): Thread-1672 calls detatch()
,I/art     ( 4247): Explicit concurrent mark sweep GC freed 122619(6MB) AllocSpace objects, 90(4MB) LOS objects, 34% free, 30MB/46MB, paused 2.238ms total 77.858ms
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 4466): Untagging socket 118
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4247): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4247): Tagging socket 55 with tag 1000060200000000{268436994,0} uid 10014, pid: 4247, getuid(): 10014
,I/qtaguid ( 4247): Tagging socket 66 with tag 1000060200000000{268436994,0} uid 10014, pid: 4247, getuid(): 10014
,I/qtaguid (12472): Untagging socket 47
,I/qtaguid (12472): Failed write_ctrl(u 47) res=-1 errno=22
I/qtaguid (12472): Untagging socket 47 failed errno=-22
W/NetworkManagementSocketTagger(12472): untagSocket(47) failed with errno -22
I/System.out(12472): Thread-1673 calls detatch()
,D/Finsky  (12472): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/art     ( 3517): Explicit concurrent mark sweep GC freed 35167(1717KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 48MB/64MB, paused 5.138ms total 179.706ms
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/qtaguid ( 4247): Untagging socket 55
,E/Zygote  (12599): MountEmulatedStorage()
,E/Zygote  (12599): v2
I/libpersona(12599): KNOX_SDCARD checking this for 10014
,I/libpersona(12599): KNOX_SDCARD not a persona
,I/ActivityManager( 3517): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=12599 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux (12599): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12599): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12599): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/GCoreUlr( 4247): GCM ID uploaded for account#2#
,D/TimaKeyStoreProvider(12599): TimaSignature is unavailable
,D/ActivityThread(12599): Added TimaKeyStore provider
,D/TimaService( 3517): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3517): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3517): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3517): initializing...
I/TLC_TIMA_PKM_initialize( 3517): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3517): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3517): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3517): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3517): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3517): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3517): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3517): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3517): device_id = 0x0
I/TZ: mc_tlc_communication( 3517): tlc_open() was called
I/TZ: mc_tlc_communication( 3517): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3517): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3517): Opening the session
,D/ResourcesManager(12599): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/TZ: mc_tlc_communication( 3517): tlc_open() succeeded
W/ResourcesManager(12599): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12599): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/TLC_TIMA_PKM_initialize( 3517): Trustlet response is completed
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4247): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4247): Tagging socket 69 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,I/GCoreUlr( 4247): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 4247): DispatchingService.onCreate()
,I/qtaguid ( 4247): Tagging socket 67 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,I/qtaguid (12472): Untagging socket 47
,I/qtaguid (12472): Failed write_ctrl(u 47) res=-1 errno=22
,I/qtaguid (12472): Untagging socket 47 failed errno=-22
W/NetworkManagementSocketTagger(12472): untagSocket(47) failed with errno -22
I/System.out(12472): Thread-1672 calls detatch()
,I/GCoreUlr( 4247): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 4247): Unbound from all location providers
I/GCoreUlr( 4247): Place inference reporting - stopped
,I/GCoreUlr( 4247): DispatchingService.onDestroy()
I/GCoreUlr( 4247): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 4247): Unbound from all location providers
I/GCoreUlr( 4247): Place inference reporting - stopped
,I/MultiDex(12599): VM with version 2.1.0 has multidex support
I/MultiDex(12599): install
I/MultiDex(12599): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp (12599): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/SurfaceFlinger( 2854): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger( 2854): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 3517): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3517) eventTime = 311195
,D/PowerManagerService( 3517): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3517 (0x0)
D/PowerManagerService( 3517): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3517, ws=WorkSource{1000}) (elapsedTime=3608)
,W/ActivityThread(12599): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12599): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16e15647: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12599): Installed default security provider GmsCore_OpenSSL
,I/splitIntent( 3517): Split this intent : com.google.android.gms.INITIALIZE !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
I/splitIntent( 3517): finish to split intent : com.google.android.gms.INITIALIZE !! Enqueue -> schedule it!!
,D/AuthorizationBluetoothService( 4247): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/System.out(12295): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid (12295): Tagging socket 28 with tag 1000000400000000{268435460,0} uid -1, pid: 12295, getuid(): 10123
,I/qtaguid (12295): Tagging socket 32 with tag 1000000400000000{268435460,0} uid -1, pid: 12295, getuid(): 10123
,D/ChimeraCfgMgr(12599): Reading stored module config
,D/ChimeraCfgMgr(12599): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/LocationInitializer( 4466): Restart initialization of location
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 4247): [186] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 4247): No location to return for getLastLocation()
W/FusedLocationProvider( 4247): location=null
,I/splitIntent( 3517): Queue : backgroundsplit_1 intent com.google.android.gms.INITIALIZE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/NativeLibraryUtils(12599): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE(12599): Connecting to CarCallService...
,V/CalendarSyncAdapter(12295): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-01-24T00:00:00.000Z, updatedMin=2015-11-18T16:31:02.459Z}
,I/qtaguid (12295): Untagging socket 28
,I/art     (12599): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     (12599): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE(12599): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service(12599): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter(12599): Creating a new PhoneAdapter instance
,W/ActivityManager( 3517): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter(12599): setListener: com.google.android.gms.car.dn@338cddc2
,W/ActivityManager( 3517): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter(12599): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service(12599): Starting CarCallService with initial phone null
,D/CalendarSyncAdapter(12295): Found 0 events marked dirty & lastSynced
,I/art     (10368): Explicit concurrent mark sweep GC freed 4831(195KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 1.058ms total 27.185ms
,D/CAR.SERVICE(12599): Package validated; name: com.android.vending
,V/Finsky  (12472): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid (12472): Untagging socket 47
,I/qtaguid (12472): Failed write_ctrl(u 47) res=-1 errno=22
,I/qtaguid (12472): Untagging socket 47 failed errno=-22
W/NetworkManagementSocketTagger(12472): untagSocket(47) failed with errno -22
,I/System.out(12472): Thread-1673 calls detatch()
,D/Finsky  (12472): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.googlequicksearchbox to true
,D/Finsky  (12472): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.googlequicksearchbox from  to d_AAAAAAADF8w=
,D/ResourcesManager(12472): creating new AssetManager and set to /system/framework/framework-res.apk
,D/ResourcesManager(12472): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(12472): creating new AssetManager and set to /system/app/ANTRadioService/ANTRadioService.apk
,D/ResourcesManager(12472): creating new AssetManager and set to /system/app/AntHalService/AntHalService.apk
,W/ResourcesManager(12472): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(12472): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12472): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12472): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GAV3    (11932): Thread[GAThread,5,main]: No campaign data found.
,D/ResourcesManager(12472): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(12472): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(12472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  (12472): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 3517): waitForAlarm result :4
,D/Finsky  (12472): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/DeviceConnectionService( 4247): client connected with version: 8296000
,D/Finsky  (12472): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,D/Finsky  (12472): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  (12472): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/Finsky  (12472): [1697] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12472): (HTTPLog)-Static: isSBSettingEnabled false
,I/ActivityManager( 3517): Killing 11015:com.android.email/u0a178 (adj 13): bgCount ##31
,I/ActivityManager( 3517): Killing 11845:com.samsung.android.sconnect/u0a150 (adj 13): bgCount ##32
,I/ActivityManager( 3517): Killing 11079:tv.peel.smartremote/u0a186 (adj 13): bgCount ##31
,E/Watchdog( 3517): !@Sync 10
,D/WearableClient(12357): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12357): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12357): WearableClientImpl.onPostInitHandler: done
,I/MusicLeanback(12357): Conditions not met for autocaching.
I/MusicLeanback(12357): Stop autocaching.
,E/GmsUtils(12357): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient(12357): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12357): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dhcpcd  (11222): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11222): wlan0: no IPv6 Routers available
,I/ActivityManager( 3517): Killing 11876:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,D/PackageManager( 3517): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager( 3517): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 3997): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,W/ResourcesManager( 3997): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/PageBuddyNotiSvc( 4655): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/InputReader( 3517): Reconfiguring input devices.  changes=0x00000010
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/LocationWidgetApplication(12392): Intent.ACTION_PACKAGE_CHANGED has been called for com.google.android.talk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/LWLocationManager(12392): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12392): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Books/Books.apk
,I/InputReader( 3517): Reconfiguring input devices.  changes=0x00000010
,W/ResourceType( 4948): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,W/ResourceType( 4948): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PageBuddyNotiSvc( 4655): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,I/LocationWidgetApplication(12392): Intent.ACTION_PACKAGE_CHANGED has been called for com.google.android.videos
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Launcher.Workspace( 3997): isBadgeUpdate : false
,D/ResourcesManager( 3997): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/InputReader( 3517): Reconfiguring input devices.  changes=0x00000010
,I/PageBuddyNotiSvc( 4655): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,I/LocationWidgetApplication(12392): Intent.ACTION_PACKAGE_CHANGED has been called for com.google.android.gms
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/SecContentProvider2( 3517): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3517): mCursor = null
,E/Zygote  (12712): MountEmulatedStorage()
E/Zygote  (12712): v2
I/libpersona(12712): KNOX_SDCARD checking this for 10035
I/libpersona(12712): KNOX_SDCARD not a persona
,I/SELinux (12712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12712): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3517): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12712 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/RegisteredServicesCache( 3965): empty dynamic service
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/RegisteredServicesCache( 3965): empty dynamic service
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/Launcher.Workspace( 3997): isBadgeUpdate : false
,D/TimaKeyStoreProvider(12712): TimaSignature is unavailable
,D/ActivityThread(12712): Added TimaKeyStore provider
,D/ResourcesManager( 3997): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,W/ResourceType( 4948): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4948): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/RegisteredServicesCache( 3965): empty dynamic service
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(12712): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(12392): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/FeatureConfig(12712): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/SecContentProvider2( 3517): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3517): mCursor = null
D/ResourcesManager(12392): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12392): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12392): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12392): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,W/ResourceType( 4948): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4948): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/ActivityManager( 3517): Killing 11467:com.sec.android.fotaclient/u0a12 (adj 13): bgCount ##31
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12733): MountEmulatedStorage()
,E/Zygote  (12733): v2
I/libpersona(12733): KNOX_SDCARD checking this for 10050
I/libpersona(12733): KNOX_SDCARD not a persona
,I/SELinux (12733): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ResourceType( 3517): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/SELinux (12733): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3517): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12733 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (12733): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/SecContentProvider2( 3517): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3517): mCursor = null
D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3517): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3517): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3517): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3517): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/TimaKeyStoreProvider(12733): TimaSignature is unavailable
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/ApplicationPolicy( 3517): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
D/ActivityThread(12733): Added TimaKeyStore provider
,D/BackupManagerService( 3517): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 3517): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(12733): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(12712): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourceType( 3517): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/ResourcesManager(12733): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager(12733): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager(12733): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12733): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager(12733): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager(12733): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager(12733): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12712): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager(12733): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(12712): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12712): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager(12712): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
W/ResourceType( 3517): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 3517): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(12712): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ResourcesManager(12712): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager(12712): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager(12712): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(12712): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/BackupManagerService( 3517): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 3517): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GCoreNlp( 4247): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService( 3517): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager(12712): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12712): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Books/Books.apk
,D/SettingsProvider( 3517): name = assisted_gps_enabled
D/SettingsProvider( 3517): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3517): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3517): selectionArgs: false
D/SettingsProvider( 3517): selectionArgs: 10014
D/SecContentProvider( 3517): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3517): ret = -1
,D/LocationProviderProxy( 3517): applying state to connected service
,D/ResourcesManager(12712): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12712): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/LocationProviderProxy( 3517): applying state to connected service
,D/ResourcesManager(12712): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12712): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(12712): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/BackupManagerService( 3517): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 3517): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2ac4a271
D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(12712): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(12712): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager(12712): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager(12712): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager(12712): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourcesManager(12712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/ResourcesManager(12712): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12712): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
D/PackageManager( 3517): findPreferredActivity: No PreferredActivities set
,D/ResourcesManager(12712): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(12712): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
W/ResourcesManager(12712): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/NearbySource(12733): Nearby Source Create!
,D/NearbyContext(12733): Nearby Context Create!
,D/ResourcesManager(12712): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager(12712): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/ResourcesManager(12712): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/ResourcesManager(12712): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(12712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication(12712): system/finder_cp/cpdata.xml file not found
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12733): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12733): Samsung link source created
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/WifiDisplayAdapter( 3517): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider(12733): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3517): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,I/UpdateIcingCorporaServi( 4035): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 3517): Killing 11517:com.samsung.klmsagent/u0a21 (adj 13): bgCount ##31
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12755): MountEmulatedStorage()
E/Zygote  (12755): v2
I/libpersona(12755): KNOX_SDCARD checking this for 10079
I/libpersona(12755): KNOX_SDCARD not a persona
,I/SELinux (12755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=12755 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12755): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12755): TimaSignature is unavailable
,D/ActivityThread(12755): Added TimaKeyStore provider
,D/ResourcesManager( 4035): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 4035): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4035): UpdateCorporaTask done [took 81 ms] updated apps [took 80 ms] 
,D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(12755): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/FileShare-Server(12755): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.talk
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/Zygote  (12770): MountEmulatedStorage()
E/Zygote  (12770): v2
I/libpersona(12770): KNOX_SDCARD checking this for 1000
I/libpersona(12770): KNOX_SDCARD not a persona
,I/SELinux (12770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3517): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=12770 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3517): Killing 11897:com.android.mms/u0a52 (adj 13): bgCount ##31
,E/SELinux (12770): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12770): TimaSignature is unavailable
,D/ActivityThread(12770): Added TimaKeyStore provider
,D/ResourcesManager(12770): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,D/CountryDetector( 3517): No listener is left
,W/ResourcesManager(12770): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/art     ( 3517): Explicit concurrent mark sweep GC freed 50237(2MB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 49MB/65MB, paused 2.416ms total 140.378ms
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
E/Zygote  (12787): MountEmulatedStorage()
E/Zygote  (12787): v2
I/libpersona(12787): KNOX_SDCARD checking this for 1000
I/libpersona(12787): KNOX_SDCARD not a persona
I/SELinux (12787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3517): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=12787 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12787): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Killing 11063:com.samsung.android.securitylogagent/1000 (adj 13): bgCount ##31
,D/ContactProvider(12733): getAllContactInfoList End
,I/syncContacts(12733): thread: 1688, sync time = 295
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/TimaKeyStoreProvider(12787): TimaSignature is unavailable
,D/ActivityThread(12787): Added TimaKeyStore provider
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(12787): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ShortcutReceiver(12787):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(12392): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/PackageBroadcastService( 4466): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/Zygote  (12805): MountEmulatedStorage()
E/Zygote  (12805): v2
I/libpersona(12805): KNOX_SDCARD checking this for 10110
I/libpersona(12805): KNOX_SDCARD not a persona
,I/SELinux (12805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
I/ActivityManager( 3517): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.packages.PackageReceiver: pid=12805 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (12805): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/ResourcesManager(12392): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12392): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12392): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,I/ActivityManager( 3517): Killing 11977:com.sec.android.app.taskmanager/u0a191 (adj 13): bgCount ##31
D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider(12805): TimaSignature is unavailable
,D/ActivityThread(12805): Added TimaKeyStore provider
,D/ResourcesManager(12805): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ACRA    (12805): ACRA is enabled for com.facebook.appmanager, intializing...
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/DexLibLoader(12805): not using cross-dex optimization: ART in use
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,I/art     (12805): Thread[1,tid=12805,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(12805): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(12805): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(12805): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(12805): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(12805): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (12805): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(12805): loading pre-built fallback odex files
V/MultiDexClassLoader(12805): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(12805): released odex store lock
,D/DexLibLoader(12805): DexLibLoader.loadAll took 21 ms
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,W/ca      (12805): Verify
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,W/LightSharedPreferencesImpl(12805): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(12805): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12805): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/LightSharedPreferencesImpl(12805): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(12805): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(12805): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(12805): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(12805): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(12805): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(12805): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(12805): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(12805): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(12805): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(12805): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12805): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(12805): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(12805): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(12805): 	... 10 more
,E/ActivityThread(12805): Failed to find provider info for com.facebook.appmanager.installrecord
W/appmanager(:<default>):b(12805): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12805): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/LocationWidgetApplication(12392): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(12805): Exposure of experiment com.facebook.common.network.l@1df8a0e9 occurred when no user was logged in
,D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/UpdateIcingCorporaServi( 4035): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,W/BroadcastQueue( 3517): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{8319dbc u0 ReceiverList{8b275af 12805 com.facebook.appmanager/10110/u0 remote:3a5eb98e}}
,W/BroadcastQueue( 3517): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{8319dbc u0 ReceiverList{8b275af 12805 com.facebook.appmanager/10110/u0 remote:3a5eb98e}}
,D/FileShare-Server(12755): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.videos
,I/TLC_TIMA_PKM_measure_kernel( 3517): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 3517): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/ShortcutReceiver(12787):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/TimaService( 3517): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3517): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/PackageBroadcastService( 4466): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,E/ActivityThread(12805): Failed to find provider info for com.facebook.appmanager.installrecord
,D/ResourcesManager( 4035): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/BroadcastQueue( 3517): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3932a44a u0 ReceiverList{fbc65b5 12805 com.facebook.appmanager/10110/u0 remote:28f5edec}}
,I/UpdateIcingCorporaServi( 4035): UpdateCorporaTask done [took 128 ms] updated apps [took 127 ms] 
,D/LocationWidgetApplication(12392): getLastUiLocationId() : mLastUiLocationId = -100
,I/ActivityManager( 3517): Killing 12024:com.samsung.android.scloud.sync/u0a69 (adj 13): bgCount ##31
,I/UpdateIcingCorporaServi( 4035): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/FileShare-Server(12755): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ShortcutReceiver(12787):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ResourcesManager( 4466): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/PackageBroadcastService( 4466): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4466): Null package name or gms related package.  Ignoreing.
,E/ActivityThread(12805): Failed to find provider info for com.facebook.appmanager.installrecord
,I/Icing   ( 4466): updateResources: need to parse f{com.google.android.gms}
,D/ResourcesManager( 4035): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/UpdateIcingCorporaServi( 4035): UpdateCorporaTask done [took 316 ms] updated apps [took 316 ms] 
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:-311, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:87
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12805): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12805): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/appmanager(:<default>):QuickExperimentControllerImpl(12805): Exposure of experiment com.facebook.imagepipeline.a.g@3643a3fa occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12805): Exposure of experiment com.facebook.imagepipeline.a.d@2020f987 occurred when no user was logged in
,I/Icing   ( 4466): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,I/art     (12805): Explicit concurrent mark sweep GC freed 49954(2MB) AllocSpace objects, 3(48KB) LOS objects, 22% free, 27MB/35MB, paused 1.874ms total 53.532ms
,W/appmanager(:<default>):m(12805): No feature status reporters found; is this dead code?
,D/ResourcesManager( 4466): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 4466): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/appmanager(:<default>):b(12805): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12805): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12805): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):QuickExperimentControllerImpl(12805): Exposure of experiment com.facebook.http.g.bb@16c29f13 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12805): Exposure of experiment com.facebook.http.g.an@1907b550 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12805): Exposure of experiment com.facebook.http.g.aw@17b7944e occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(12805): Exposure of experiment com.facebook.http.g.aj@aae196f occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(12805): Exposure of experiment com.facebook.http.g.a@32bad67c occurred when no user was logged in
,D/ResourcesManager( 4466): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(12805): Exposure of experiment com.facebook.http.g.k@352cdd8b occurred when no user was logged in
,I/System.out(12805): Thread-1741(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12805): Thread-1741(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12805): Thread-1741(ApacheHTTPLog):isShipBuild true
I/System.out(12805): Thread-1741(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/appmanager(:<default>):QuickExperimentControllerImpl(12805): Exposure of experiment com.facebook.http.g.c@5157914 occurred when no user was logged in
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10110
,D/SSRM:n  ( 3517): SIOP:: AP = 260, PST = 212, CUR = -311
,I/Icing   ( 4466): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,D/CAR.SERVICE(12599): mConnectedToCar = false, abort
,E/ActivityThread(12599): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@7f24b6a that was originally bound here
E/ActivityThread(12599): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@7f24b6a that was originally bound here
E/ActivityThread(12599): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12599): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12599): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12599): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12599): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12599): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12599): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12599): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread(12599): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread(12599): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread(12599): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread(12599): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread(12599): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread(12599): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12599): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12599): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12599): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12599): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12599): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12599): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12599): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12599): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12599): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread(12599): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3fce3a0d that was originally bound here
E/ActivityThread(12599): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3fce3a0d that was originally bound here
E/ActivityThread(12599): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12599): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12599): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12599): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12599): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12599): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread(12599): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread(12599): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread(12599): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread(12599): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread(12599): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread(12599): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread(12599): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3181)
E/ActivityThread(12599): 	at android.app.ActivityThread.access$2000(ActivityThread.java:178)
E/ActivityThread(12599): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1537)
E/ActivityThread(12599): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12599): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12599): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12599): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12599): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12599): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12599): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 3517): Unbind failed: could not find connection for android.os.BinderProxy@200dcf4d
,W/ActivityThread(12805): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out(12805): P[5]_NetworkDispatch1 calls detatch()
,W/appmanager(:<default>):b(12805): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12805): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/Icing   ( 4466): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,I/Icing   ( 4466): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,I/Icing   ( 4466): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,I/Icing   ( 4466): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,D/WVMDrmPlugIn( 2858): WVMDrmPlugin::onTerminate : 3317
,W/IdleConnectionHandler(12805): Removing a connection that never existed!
,I/ActivityManager( 3517): Waited long enough for: ServiceRecord{224d9a53 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,I/PowerManagerService( 3517): [PWL] Off : 275s ago
,I/ActivityManager( 3517): Waited long enough for: ServiceRecord{14d397bd u0 com.google.android.music/.download.artwork.ArtDownloadService}
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10202
,I/System.out( 6500): Thread-643 calls detatch()
,I/System.out( 6500): Thread-643 calls detatch()
,I/System.out( 6500): Thread-643 calls detatch()
,I/System.out( 6500): Thread-643 calls detatch()
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 217, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:-72, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:80
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 240, PST = 216, CUR = -72
,V/AlarmManager( 3517): waitForAlarm result :4
,D/Finsky  (12472): [1685] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (12472): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 3517): waitForAlarm result :4,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:65
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 220, PST = 224, CUR = 16
,W/IcingInternalCorpora( 4466): getNumBytesRead when not calculated.
,W/ProcessCpuTracker( 3517): Skipping unknown process pid 13005
,E/Watchdog( 3517): !@Sync 11
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 220, PST = 224, CUR = 44
,V/AlarmManager( 3517): waitForAlarm result :8
,I/ActivityManager( 3517): Killing 12042:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/SSRM:n  ( 3517): SIOP:: AP = 210, PST = 225, CUR = 52
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:58
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3517): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/ActivityThread( 4466): Failed to find provider info for com.android.contacts.metadata
,D/ChimeraCfgMgr( 4466): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4466): Module APK com.google.android.play.games already loaded
,D/SyncManager( 3517): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 334022, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 3517): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 425102, reason: UserStart
,W/ResourceType( 4948): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4948): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 4466): 0 accounts found with uca feature
I/GamesSyncAdapter( 4466): Starting sync for 3a3529a
,I/GamesSyncAdapter( 4466): Sync duration for 3a3529a: 5
,D/SecContentProvider2( 3517): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3517): mCursor = null
,D/ChimeraCfgMgr( 4466): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4466): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4466): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4466): Module APK com.google.android.play.games already loaded
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 210, PST = 225, CUR = 52
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 12
,I/PowerManagerService( 3517): [PWL] Off : 330s ago
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 210, PST = 226, CUR = 51
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 210, PST = 225, CUR = 48
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3517): waitForAlarm result :4
,D/SSRM:n  ( 3517): SIOP:: AP = 210, PST = 225, CUR = 46,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3517): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 13
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 222, CUR = 43
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3517): waitForAlarm result :8
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 219, CUR = 41
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 215, CUR = 39
,I/ClearcutLoggerApiImpl( 4466): disconnect managed GoogleApiClient
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 14
,I/PowerManagerService( 3517): [PWL] Off : 390s ago
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 214, CUR = 37
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:62
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 212, CUR = 35
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 210, CUR = 34
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 15
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 207, CUR = 34
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,D/BatteryService( 3517): stay LED for fully charged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 207, CUR = 33
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 206, CUR = 31
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 16
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 205, CUR = 32
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
D/BatteryService( 3517): stay LED for fully charged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3517): [PWL] Off : 455s ago,
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 204, CUR = 32
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 203, CUR = 32
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 17
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 202, CUR = 31
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 202, CUR = 29
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 201, CUR = 28
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 18
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 201, CUR = 27
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 201, CUR = 28
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3517): [PWL] Off : 525s ago
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 28
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3517): stay LED for fully charged
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 19
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 29
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 27
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 217, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3517): stay LED for fully charged,
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 26
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3517): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3517): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3517): TIMA: checkEvent, operation: 50000 subject: 10000
,E/Watchdog( 3517): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3517): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3517): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3517): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3517): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 26
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 217, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 26
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 217, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3517): stay LED for fully charged
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 25,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 217, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 21
,I/PowerManagerService( 3517): [PWL] Off : 600s ago
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 25
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 217, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 26
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 217, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4247): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4247): Tagging socket 76 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,I/qtaguid ( 4247): Tagging socket 83 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,I/System.out( 4466): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4466): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 25,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 217, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 22
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 24
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 217, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 26,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 217, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 25
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 23
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 23
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 217, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 23
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3517): [PWL] Off : 680s ago
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 24
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 24
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 23
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 23
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 23,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 25
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 22
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 22
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 21
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 26,
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 200, PST = 200, CUR = 22
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 199, CUR = 22
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3517): stay LED for fully charged
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3517): [PWL] Off : 765s ago
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 199, CUR = 19
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3517): stay LED for fully charged
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 27
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 199, CUR = 20,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 198, CUR = 19
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 198, CUR = 17,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 216, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 28
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 198, CUR = 19
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 197, CUR = 19
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 197, CUR = 19
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 29
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 197, CUR = 19
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 196, CUR = 18
,V/AlarmManager( 3517): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,V/AlarmManager( 3517): waitForAlarm result :8
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 3517): [PWL] Off : 855s ago
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 196, CUR = 18
,V/AlarmManager( 3517): waitForAlarm result :8,
,D/LightsService( 3517): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK,
,I/Sensors ( 3517): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3517): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/Sensors ( 3517): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3517): [SvcLED]  onSensorChanged::light value = 0
,I/Sensors ( 3517): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3517): unregisterListener ::   
,D/LightsService( 3517): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/TimaService( 3517): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3517): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3517): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,W/ProcessCpuTracker( 3517): Skipping unknown process pid 13397
,E/Watchdog( 3517): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3517): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3517): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3517): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3517): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 196, CUR = 18
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 195, CUR = 18
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 195, CUR = 19
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 31
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 195, CUR = 19
,V/AlarmManager( 3517): waitForAlarm result :8
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,D/BatteryService( 3517): stay LED for fully charged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 194, CUR = 16
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 194, CUR = 17,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3517): !@Sync 32
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 194, CUR = 17
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 193, CUR = 16
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3517): [PWL] Off : 950s ago
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 193, CUR = 16
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 215, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 33
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 193, CUR = 18
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 192, CUR = 17
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 192, CUR = 19
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 34
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 192, CUR = 17
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 191, CUR = 15
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 191, CUR = 15
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 35
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 191, CUR = 16
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 17
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 17
,E/Watchdog( 3517): !@Sync 36
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3517): [PWL] Off : 1050s ago
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 17
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 15
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3517): stay LED for fully charged
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 14
,E/Watchdog( 3517): !@Sync 37
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 15
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 14,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 214, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3517): stay LED for fully charged
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 17
,E/Watchdog( 3517): !@Sync 38
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 14
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 14
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 13
,E/Watchdog( 3517): !@Sync 39
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 15
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 14
,I/PowerManagerService( 3517): [PWL] Off : 1155s ago
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 15
,D/TimaService( 3517): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3517): TIMA: checkEvent, operation: 50000 subject: 10000,
D/TimaService( 3517): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService( 3517): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3517): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3517): Updating Usage Statistics in DB @ 1451924602063
,I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
,W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
,W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
,W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
,W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
,W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	,at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3517): ::getAppControlDB: Exception to create DB
W/System.err( 3517): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3517): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3517): Done Updating Usage Statistics in DB @ 1451924602135
,E/Watchdog( 3517): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3517): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3517): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3517): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3517): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 15
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 15
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 14
,E/Watchdog( 3517): !@Sync 41
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 13
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 14
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3517): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 13
,E/Watchdog( 3517): !@Sync 42
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 13
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 13
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 14
,E/Watchdog( 3517): !@Sync 43
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 13
,I/PowerManagerService( 3517): [PWL] Off : 1265s ago
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 13
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 13
,E/Watchdog( 3517): !@Sync 44
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 12
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 12
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 14
,E/Watchdog( 3517): !@Sync 45
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 14
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3517): stay LED for fully charged
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 14
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,D/BatteryService( 3517): stay LED for fully charged
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 12
,E/Watchdog( 3517): !@Sync 46
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 213, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 11
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 13
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 13
,I/art     ( 3517): Background sticky concurrent mark sweep GC freed 106612(9MB) AllocSpace objects, 337(5MB) LOS objects, 13% free, 49MB/57MB, paused 3.111ms total 116.034ms
,E/Watchdog( 3517): !@Sync 47
,I/PowerManagerService( 3517): [PWL] Off : 1380s ago
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 12,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 13
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 12
,E/Watchdog( 3517): !@Sync 48
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 11
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 11
,E/Watchdog( 3517): !@Sync 49
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 11
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 12
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/TimaService( 3517): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3517): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3517): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3517): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 3517): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3517): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3517): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3517): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 11
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 11
,E/Watchdog( 3517): !@Sync 51
,I/PowerManagerService( 3517): [PWL] Off : 1500s ago
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 11
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 11
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,E/Watchdog( 3517): !@Sync 52
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 11
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 11
,E/Watchdog( 3517): !@Sync 53
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 9
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3517): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,E/Watchdog( 3517): !@Sync 54
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 9
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 9
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,E/Watchdog( 3517): !@Sync 55
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24,
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3517): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,I/PowerManagerService( 3517): [PWL] Off : 1625s ago
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged,
I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 12
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,E/Watchdog( 3517): !@Sync 56
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 11
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,E/Watchdog( 3517): !@Sync 57
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
D/BatteryService( 3517): stay LED for fully charged
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 212, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3517): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 11
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 58
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24,
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3517): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 8
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 59
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 8
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 3517): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/LightsService( 3517): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3517): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3517): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,W/ProcessCpuTracker( 3517): Skipping unknown process pid 13895
,D/NetworkStatsFactory( 3517): UpdateStatsForKnox
,I/EventLogService( 4466): Aggregate from 1451923696067 (log), 1451922633007 (data)
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4247): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4247): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,I/Sensors ( 3517): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3517): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3517): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3517): unregisterListener ::   
D/LightsService( 3517): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/PowerManagerService( 3517): [PWL] Off : 1755s ago
,I/System.out( 4247): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4247): Tagging socket 55 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,I/qtaguid ( 4247): Tagging socket 69 with tag 1000040100000000{268436481,0} uid 10014, pid: 4247, getuid(): 10014
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3517): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3517): TIMA: checkEvent, operation: 50000 subject: 10000,
D/TimaService( 3517): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3517): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 3517): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3517): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3517): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3517): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ProcessCpuTracker( 3517): Skipping unknown process pid 13942
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 8
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 61,
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,V/AlarmManager( 3517): waitForAlarm result :8
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 9,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 9
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 62
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 9
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 9
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 8
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 63
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3517): stay LED for fully charged
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 9
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 9
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 64
,I/PowerManagerService( 3517): [PWL] Off : 1890s ago
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 9
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 8
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 8
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 65
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 66
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 8
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 8
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 7
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3517): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-15
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 67
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 8
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 8,
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 8
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 68
,I/MMD     ( 2884): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     ( 3517): Background partial concurrent mark sweep GC freed 56399(5MB) AllocSpace objects, 196(3MB) LOS objects, 24% free, 49MB/65MB, paused 3.150ms total 188.508ms
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 10
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3517): [PWL] Off : 2030s ago
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 7
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3517): !@Sync 69
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 9
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-14
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/BatteryService( 3517): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3517): SIOP:: AP = 190, PST = 190, CUR = 6
,D/BatteryService( 3517): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3517): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 211, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3517): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3517): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3517): stay LED for fully charged
,I/MotionRecognitionService( 3517): Plugged
,I/MotionRecognitionService( 3517): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10982): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10982): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1800000ms)
```
