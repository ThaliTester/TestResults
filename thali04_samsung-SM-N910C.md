#### Test 5497026140aeaf4_thali04_samsung-SM-N910C Logs


```
--------- beginning of system,
D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 263, CUR = 32
D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:65
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3525): stay LED for fully charged
I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(10586): 
D/AndroidRuntime(10586): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10586): CheckJNI is OFF
D/AndroidRuntime(10586): readGMSProperty: start
D/AndroidRuntime(10586): readGMSProperty: already setted!!
D/AndroidRuntime(10586): readGMSProperty: end
D/AndroidRuntime(10586): addProductProperty: start
E/AffinityControl(10586): AffinityControl: registerfunction enter
D/AndroidRuntime(10586): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3525): inState():  stateMachine is null !!
I/PersonaManagerService( 3525): PersonaId don't exist
I/ActivityManager( 3525): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3525): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3525): mDVFSHelper.acquire()
D/FocusedStackFrame( 3525): Set to : 0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/Zygote  (10605): MountEmulatedStorage()
E/Zygote  (10605): v2
I/libpersona(10605): KNOX_SDCARD checking this for 10550
I/libpersona(10605): KNOX_SDCARD not a persona
I/SELinux (10605): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10605): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=10605 uid=10550 gids={50550, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (10605): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10586): Shutting down VM
D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(10605): TimaSignature is unavailable
D/ActivityThread(10605): Added TimaKeyStore provider
V/WindowOrientationListener( 3525): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager( 3525): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3525): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener( 3525): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3525): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(10605): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2851): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2851): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 4004): updateVisibility : ActivityRecord{35774e70 token=android.os.BinderProxy@223dd93 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4004): onTrimMemory. Level: 20
I/WebViewFactory(10605): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10605): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10605): Loading: webviewchromium
I/LibraryLoader(10605): Time to load native libraries: 4 ms (timestamps 4814-4818)
I/LibraryLoader(10605): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10605): Binding Chromium to main looper Looper (main, tid 1) {35d97f08}
,I/LibraryLoader(10605): Expected native library version number "",actual native library version number ""
I/chromium(10605): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10605): Initializing chromium process, renderers=0
,W/art     (10605): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10605): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10605): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10605): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10605): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothAdapter(10605): 981448353: getState() :  mService = null. Returning STATE_OFF
,W/chromium(10605): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10605): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10605): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10605): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(10605): CordovaWebView is running on device made by: samsung
,W/art     (10605): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10605): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(10605): performCreate Call secproduct feature valuefalse
D/Activity(10605): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(10605): Render dirty regions requested: true
,D/ActivityManager( 3525): post active user change for 0
D/KnoxTimeoutHandler( 3525): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3525): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2851): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
I/OpenGLRenderer(10605): Initialized EGL, version 1.4
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(10605): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1278639856 
,D/OpenGLRenderer(10605): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10605): Enabling debug mode 0
,D/mali_winsys(10605): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(10605): updateVisibility : ActivityRecord{1a328a11 token=android.os.BinderProxy@940a68f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3525): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3525): mDVFSHelper.release()
,I/Timeline( 3525): Timeline: Activity_windows_visible id: ActivityRecord{2538b8af u0 com.test.thalitest/.MainActivity t25} time:135156
,W/IInputConnectionWrapper(10605): showStatusIcon on inactive InputConnection
,I/Timeline(10605): Timeline: Activity_idle id: android.os.BinderProxy@940a68f time:135161
,I/chromium(10605): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10605): 
,D/JsMessageQueue(10605): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(10605): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357424896
D/JX-Cordova(10605): jxcore cordova android initializing
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/jxcore-log(10605): Initializing JXcore engine
W/jxcore-log(10605): JXcore engine is ready
,W/jxcore-log(10605): Starting JXcore engine
,E/auditd  ( 4537): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3525): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3525): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10605): Platform android
W/jxcore-log(10605): 
W/jxcore-log(10605): Process ARCH arm
W/jxcore-log(10605): 
,I/jxcore-log(10605): JXcore Cordova bridge is ready!
I/jxcore-log(10605): 
W/jxcore-log(10605): JXcore engine is started
,I/jxcore-log(10605): Toggling radios to true
I/jxcore-log(10605): 
,D/BluetoothAdapter(10605): enable()
,W/ActivityManager( 3525): Permission Denial: getCurrentUser() from pid=10605, uid=10550 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 3525): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 3525): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10605, uid=10550 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 3525): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/BluetoothManagerService( 3525): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2160)
W/BluetoothManagerService( 3525): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService( 3525): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 3525): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService( 3525): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3525): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 3525): name = bluetooth_on
,E/DevicePolicyManagerService( 3525): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3525): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/WifiManager(10605): packageName : com.test.thalitest
,D/SecContentProvider( 3525): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3525): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3525): mCursor = null
D/WifiService( 3525): New client listening to asynchronous messages
,D/WifiService( 3525): setWifiEnabled: true pid=10605, uid=10550
E/WifiService( 3525): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3525): Permission Denial: getCurrentUser() from pid=10605, uid=10550 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3525): Failed getting userId using ActivityManagerNative
W/WifiService( 3525): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10605, uid=10550 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3525): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3525): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3525): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3525): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3525): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3525): name = wifi_on
,E/WifiStateMachine( 3525): setting operational mode to 1
,I/WifiService( 3525): disconnect: pid=10605, uid=10550
E/WifiHW  ( 3525): ##################### set firmware type 0 #####################
,I/jxcore-log(10605): Radios toggled
I/jxcore-log(10605): 
E/Zygote  (10688): MountEmulatedStorage()
I/libpersona(10688): KNOX_SDCARD checking this for 1002
E/Zygote  (10688): v2
I/libpersona(10688): KNOX_SDCARD not a persona
,I/SELinux (10688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/WifiHW  ( 2847): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,I/WifiHW  ( 2847): module is murata
E/WifiHW  ( 2847): ==========[WIFI] MURATA MODULE ===========
I/WifiHW  ( 2847): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_murata
I/SELinux (10688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/WifiHW  ( 2847): TEMP_FAILURE_RETRY complete
D/SoftapController( 2847): Softap fwReload - Ok
E/SELinux (10688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=10688 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/CommandListener( 2847): Setting iface cfg
D/CommandListener( 2847): Trying to bring down wlan0
D/CommandListener( 2847): Clearing all IP addresses on wlan0
,D/TimaKeyStoreProvider(10688): TimaSignature is unavailable
,D/ActivityThread(10688): Added TimaKeyStore provider
,D/ResourcesManager(10688): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(10688): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(10688): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni(10688): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig(10688): Adding GattService
,D/BtSettings.ProfileConfig(10688): Adding HeadsetService
D/BtSettings.ProfileConfig(10688): Adding A2dpService
D/BtSettings.ProfileConfig(10688): Adding HidService
D/BtSettings.ProfileConfig(10688): Adding HealthService
,D/BtSettings.ProfileConfig(10688): Adding PanService
D/BtSettings.ProfileConfig(10688): Adding BluetoothMapService
D/BtSettings.ProfileConfig(10688): Adding SapService
D/BtSettings.ProfileConfig(10688): Adding HeadsetClientService
D/BtSettings.ProfileConfig(10688): Adding A2dpSinkService
D/BtSettings.ProfileConfig(10688): Adding SapClientService
D/BtSettings.ProfileConfig(10688): Adding HidDevService
I/BtSettings.ProfileConfig(10688): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3525): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3525): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
,D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3525): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3525): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,E/WifiHW  ( 3525): supplicant_name : p2p_supplicant
W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider( 3525): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3525): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3525): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3525): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3525): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3525): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3525): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/SettingsProvider( 3525): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterState(10688): make
,I/bluedroid(10688): init
I/BluetoothAdapterState(10688): Entering OffState
,I/wpa_supplicant(10703): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant(10703): Successfully initialized wpa_supplicant
,I/SecureStorage(10703): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/bte_conf(10688): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf(10688): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config(10688): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf(10688): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif (10688): btif_fetch_local_ble_random_bdaddr
I/bluedroid(10688): get_profile_interface socket
I/bluedroid(10688): get_profile_interface map_client
D/BluetoothAdapterService(10688): checkAddrForIOP: Loading from conf
D/BluetoothAdapterService(10688): Inband Ring is supported
,I/GKI_LINUX(10688): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties(10688): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10688): populateRssiValuesNative
I/bluedroid(10688): getModelRssiValues
E/BluetoothServiceJni(10688): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10688): modelRssiValuesCallback, low, mid, high = -75,-65,127
,I/SecureStorage(10703): [INFO]: SPID(0x00000000)This device supports Secure Storage
,D/BluetoothAdapterProperties(10688): Name is: Note4-1
I/SecureStorage( 2921): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10703
I/SecureStorage( 2921): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
I/SecureStorage(10703): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant(10703): ssSupport state is = 1
I/wpa_supplicant(10703): >>>>> GET KEY, IV <<<<<
D/SettingsProvider( 3525): name = bluetooth_name
I/SecureStorage(10703): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 2921): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10703
I/SecureStorage( 2921): [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,I/bluedroid(10688): config_hci_snoop_log
,D/BluetoothManagerService( 3525): Broadcasting onBluetoothServiceUp() to 11 receivers.
,E/DevicePolicyManagerService( 3525): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3525): getAllowBluetoothMode - value retunrs : 2
D/SecContentProvider( 3525): uri = 3 selection = isBluetoothEnabled
D/BluetoothAdapterState(10688): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties(10688): Setting state to 11
I/BluetoothAdapterState(10688): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(10688): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10688): updateAdapterState state is 11
D/BluetoothAdapterService(10688): Autoconnection is available 
D/BluetoothAdapterService(10688): updateAdapterState prevState = 10newState = 11
D/BluetoothSecureManager(10688): getInstant: null
D/BluetoothSecureManager(10688): calling getMethod for getService
D/BluetoothSecureManager(10688): calling getService
D/BluetoothSecureManager(10688): getService return binder: android.os.BinderProxy@15b72720
W/InputMethodManagerService( 3525): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 3695): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 3695):  onBluetoothPairedDevicesChanged:
I/InputMethodManagerService( 3525): [BT Setting State] State =11
I/SamsungIME( 4460): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
D/STATUSBAR-QSTileView( 3695): onStateChanged: Bluetooth
D/BluetoothSecureManagerService( 3525): isSecureModeEnabled
D/BluetoothSecureManagerService( 3525): getSecureModeSetting, name: secure_mode_enable
D/StatusBarManagerService( 3525): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
E/WifiStateMachine( 3525): setWifiState: enabling
D/BtConfig.SecureMode(10688): isSecureModeOn:false
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
E/WifiStateMachine( 3525): Supplicant start successful
D/WifiMonitor( 3525): startMonitoring(wlan0) with mConnected = false
D/StatusBarManagerService( 3525): setIconVisibility slot=bluetooth visible=false
W/BluetoothAdapterService(10688): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/PhoneStatusBar( 3695): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
W/BluetoothAdapterService(10688): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10688): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(10688): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10688): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10688): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10688): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10688): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=false enabledDesc:null
D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
W/BluetoothAdapterService(10688): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
V/[CarModeFW](10056): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
D/SLocation( 3525): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/STATUSBAR-WifiQuickSettingButton( 3695): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3695): Wifi onReceive(2)
D/HotspotTile( 3695): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 3695): onStateChanged: Wi-Fi
D/HotspotTile( 3695): onReceive : 2, 0
W/BluetoothAdapterService(10688): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10688): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService(10688): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine(10688): make
I/BluetoothBondStateMachine(10688): StableState(): Entering Off State
W/BluetoothAdapterService(10688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService(10688): Not skipping com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService(10688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/SmartBondingService( 3525): getNetworkEnabled : wifi : false mobile : false
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10688): Not skipping com.android.bluetooth.hfp.HeadsetService
I/BtGatt.JNI(10688): classInitNative(L900): classInitNative: Success!
,D/BtGatt.DebugUtils(10688): handleDebugAction() action=null
,D/BtGatt.GattService(10688): Received start request. Starting profile...
D/BtGatt.GattService(10688): start()
I/bluedroid(10688): get_profile_interface gatt
D/BluetoothAdapterService(10688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d97f08
D/BtGatt.AdvertiseManager(10688): advertise manager created
W/BluetoothAdapterService(10688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10688): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService(10688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(10688): Not skipping com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(10688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10688): Not skipping com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService(10688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d97f08
,D/BluetoothNotiBroadcastReceiver( 7628): onReceive
,D/HeadsetService(10688): Received start request. Starting profile...
,W/BluetoothAdapterService(10688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10688): Not skipping com.android.bluetooth.pan.PanService
,I/BluetoothHeadsetServiceJni(10688): classInitNative: succeeds
D/HeadsetStateMachine(10688): make
,E/HeadsetStateMachine(10688): # of Max HF connection is 2
,W/BluetoothAdapterService(10688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10688): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService(10688): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10688): Not skipping com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10688): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10688): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10688): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig(10688): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService(10688): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState(10688): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/bluedroid(10688): get_profile_interface handsfree
I/DualScoManager(10688): Instantiating Dual Sco Manager
I/DualScoManager(10688): Set HeadsetServiceHelper
,D/BluetoothAtMessage(10688): createCMTIContentObservers
,D/SettingsProvider( 3525): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine(10688): Enter Disconnected: -2
,E/HeadsetStateMachine(10688): set to mRemoteBrsf = 0
,D/BluetoothAdapterService(10688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d97f08
,D/HeadsetStateMachine(10688): map size, before remove : 0
D/HeadsetStateMachine(10688): map size, after remove: 0
,D/BluetoothA2dp( 4800): Proxy object connected
D/BluetoothA2dp( 3525): Proxy object connected
,D/A2dpService(10688): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni(10688): classInitNative: succeeds
V/Avrcp   (10688): make
V/Avrcp   (10688): Avrcp
I/bluedroid(10688): get_profile_interface avrcp
,V/Avrcp   (10688): start
,E/RemoteController(10688): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   (10688): ++registerMediaPlayers++
,I/Avrcp   (10688): No of Audio players :: 2
I/Avrcp   (10688): App Package name is com.google.android.music
,D/ResourcesManager(10688): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   (10688): App pkg name is Google Play Music
,I/Avrcp   (10688): Name::Google Play Music
V/Avrcp   (10688): MediaPlayerInfo: mPlayerId=1
I/Avrcp   (10688): App Package name is com.sec.android.app.music
,D/ResourcesManager(10688): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   (10688): App pkg name is Music
,I/Avrcp   (10688): Name::Music
V/Avrcp   (10688): MediaPlayerInfo: mPlayerId=2
,I/Avrcp   (10688): No of Video players :: 1
I/Avrcp   (10688): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager(10688): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   (10688): Video App pkg name is Video Player
,I/Avrcp   (10688): Name::Video Player
V/Avrcp   (10688): MediaPlayerInfo: mPlayerId=3
I/Avrcp   (10688): Add tempPlayer
V/Avrcp   (10688): MediaPlayerInfo: mPlayerId=4
I/Avrcp   (10688): Total no of players: 4
V/Avrcp   (10688): swapping the samsung player with 1st player
I/Avrcp   (10688):  Updating now playing list upon AVRCP Start
V/Avrcp   (10688): handleMessage, msg=207
D/BluetoothMediaBrowser(10688):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,V/Avrcp   (10688): CurrentAudioFocusPackageName is null
I/Avrcp   (10688): There is no currently selected player ,setting Samsung Music Player ID
I/Avrcp   (10688):  set player publishabilty with player id::1 toBePublished ::true
,I/BluetoothA2dpServiceJni(10688): classInitNative: succeeds
D/A2dpStateMachine(10688): make
,I/bluedroid(10688): get_profile_interface a2dp
I/GKI_LINUX(10688): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif (10688): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService(10688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d97f08
D/A2dpStateMachine(10688): Enter Disconnected: -2
,I/BluetoothHidServiceJni(10688): classInitNative: succeeds
,D/HidService(10688): Received start request. Starting profile...
I/bluedroid(10688): get_profile_interface hidhost
D/HidService(10688): setHidService(): set to: null
D/BluetoothAdapterService(10688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d97f08
E/BluetoothAdapterService(903446280)(10688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,I/BluetoothHealthServiceJni(10688): classInitNative: succeeds
,D/HealthService(10688): Received start request. Starting profile...
,I/bluedroid(10688): get_profile_interface health
D/BluetoothAdapterService(10688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d97f08
,I/BluetoothPanServiceJni(10688): classInitNative(L105): succeeds
,D/AuthorizationBluetoothService( 4237): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPan( 3525): BluetoothPAN Proxy object connected
D/PanService(10688): Received start request. Starting profile...
D/BluetoothPanServiceJni(10688): initializeNative(L110): pan
I/bluedroid(10688): get_profile_interface pan
,D/BluetoothAdapterService(10688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d97f08
,I/Hs20UtilService( 6356): Starting #2
,I/Hs20UtilService( 6356): Message received 5011
D/BluetoothMapService(10688): Received start request. Starting profile...
,D/BluetoothMediaBrowser(10688): no now playing list
D/BluetoothMediaBrowser(10688):  getNowPlayingId now playing id : -1
D/Avrcp   (10688):  checkNowPlayingList start
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10721): MountEmulatedStorage()
I/libpersona(10721): KNOX_SDCARD checking this for 10127
E/Zygote  (10721): v2
I/libpersona(10721): KNOX_SDCARD not a persona
,I/SELinux (10721): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10721): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=10721 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (10721): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10721): TimaSignature is unavailable
,D/ActivityThread(10721): Added TimaKeyStore provider
,E/Zygote  (10735): MountEmulatedStorage()
E/Zygote  (10735): v2
I/libpersona(10735): KNOX_SDCARD checking this for 10178
I/libpersona(10735): KNOX_SDCARD not a persona
,I/SELinux (10735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10735): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=10735 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux (10735): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8740(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 423us total 10.537ms
,D/ResourcesManager(10721): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/TimaKeyStoreProvider(10735): TimaSignature is unavailable
,D/ActivityThread(10735): Added TimaKeyStore provider
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 381us total 8.884ms
,D/ResourcesManager(10735): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(10735): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(10735): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10735): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10735): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10735): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10735): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 526us total 8.756ms
,D/KeyguardWallpaperUpdator(10721): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(10721): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10721): stopCheckCategoryVersion
,I/SignOutReceiver( 8286): WIFI_STATE_CHANGED_ACTION
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10752): MountEmulatedStorage()
I/libpersona(10752): KNOX_SDCARD checking this for 1000
E/Zygote  (10752): v2
I/libpersona(10752): KNOX_SDCARD not a persona
,I/SELinux (10752): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3525): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=10752 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (10752): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10752): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10752): TimaSignature is unavailable
,D/ActivityThread(10752): Added TimaKeyStore provider
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/ResourcesManager(10752): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/BluetoothAdapterService(10688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d97f08
,I/BluetoothSAPServiceJni(10688): classInitNative(L204): succeeds
,D/SapService(10688): Received start request. Starting profile...
D/BluetoothSAPServiceJni(10688): initializeNative(L209): sap
I/bluedroid(10688): get_profile_interface sap
D/BluetoothAdapterService(10688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d97f08
,D/HeadsetStateMachine(10688): Try to query the phonestate on bind
,E/Zygote  (10775): MountEmulatedStorage()
I/libpersona(10775): KNOX_SDCARD checking this for 10082
E/Zygote  (10775): v2
I/libpersona(10775): KNOX_SDCARD not a persona
I/SELinux (10775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=10775 uid=10082 gids={50082, 9997} abi=armeabi-v7a
E/SELinux (10775): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/Telecom ( 3954): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 3954): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 3954): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 3954): Proxy not attached to service
,D/HeadsetStateMachine(10688): Proxy object connected
D/HeadsetPhoneState(10688): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState(10688): sendDeviceDataStateChanged
D/HeadsetStateMachine(10688): Disconnected process message: 11
D/HeadsetStateMachine(10688): Disconnected process message: 18
D/HeadsetPhoneState(10688): Signal level : previous=0 curr=0
E/BluetoothAdapterService(903446280)(10688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp(10688): Proxy object connected
D/BluetoothAdapterService(10688): Bluetooth A2dp source service connected
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/BluetoothAdapterService(903446280)(10688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/HeadsetStateMachine(10688): Disconnected process message: 10
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/BluetoothAdapterService(903446280)(10688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/BluetoothAdapterService(903446280)(10688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(903446280)(10688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/HeadsetPhoneState(10688): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine(10688): Disconnected process message: 11
,D/TimaKeyStoreProvider(10775): TimaSignature is unavailable
D/ActivityThread(10775): Added TimaKeyStore provider
E/Zygote  (10791): MountEmulatedStorage()
I/libpersona(10791): KNOX_SDCARD checking this for 10186
E/Zygote  (10791): v2
I/libpersona(10791): KNOX_SDCARD not a persona
I/SELinux (10791): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10791): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10791): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc tv.peel.smartremote for broadcast tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver: pid=10791 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
E/lowmemorykiller( 2829): Error writing /proc/9866/oom_score_adj; errno=22
I/ActivityManager( 3525): Killing 9866:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
D/ResourcesManager(10775): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
I/ActivityManager( 3525): Killing 9917:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
I/ActivityManager( 3525): Killing 9883:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##32
D/TimaKeyStoreProvider(10791): TimaSignature is unavailable
D/ActivityThread(10791): Added TimaKeyStore provider
E/BluetoothAdapterService(903446280)(10688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(903446280)(10688): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState(10688): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid(10688): enable
I/GKI_LINUX(10688): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid(10688): init
I/bt_vendor(10688): init
I/bt_vnd_conf(10688): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf(10688): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial(10688): userial_init
,D/ResourcesManager(10791): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
W/ResourcesManager(10791): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/BadgeProvider(10775): onCreate
D/BadgeProvider(10775): DatabaseHelper
D/BadgeProvider(10775): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/BadgeProvider(10775): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10775): sendNotify, [notify] : null
D/BadgeProvider(10775): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10775): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10775): update, [UpdateCount] : 1
D/Launcher.Model( 4004): reloadBadges entered.
,W/ActivityManager( 3525): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/bt_userial_vendor(10688): userial vendor open: opening /dev/ttySAC3
,I/bt_userial_vendor(10688): userial_vendor_open():UART is setup
I/bt_userial_vendor(10688): device fd = 65 open
E/bt_hwcfg(10688): Start CFG HW, HCI reset
D/bt_userial(10688): Entering userial_read_thread()
,E/bt_hwcfg(10688): Read Local Name after HCI reset
,I/WebViewFactory(10791): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(10791): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(10791): Loading: webviewchromium
,I/LibraryLoader(10791): Time to load native libraries: 3 ms (timestamps 7327-7330)
I/LibraryLoader(10791): Expected native library version number "",actual native library version number ""
,D/bt_hwcfg(10688): Chipset BCM43569A1
D/bt_hwcfg(10688): Target name = [BCM4358A1]
,I/bt_hwcfg(10688): module_type[murata].
I/bt_hwcfg(10688): module_type[murata] is invalid.
E/bt_hwcfg(10688): patchram path ORG . BCM4358A1
E/bt_hwcfg(10688): patchram path ORG .. BCM4358A1
E/bt_hwcfg(10688): patchram path ORG bcm4358A0_V0033.0000.hcd BCM4358A1
E/bt_hwcfg(10688): patchram path ORG bcm4358A1_V0044.0078.hcd BCM4358A1
I/bt_hwcfg(10688): patch(org) : bcm4358A1_V0044.0078.hcd
I/bt_hwcfg(10688): Found patchfile: /vendor/firmware/bcm4358A1_V0044.0078.hcd
E/bt_hwcfg(10688): ORG patchram base 0044
E/bt_hwcfg(10688): ORG patchram minor 0078
E/bt_hwcfg(10688): fw ver (org)44.78
E/bt_hwcfg(10688): Final Patchram is /vendor/firmware/bcm4358A1_V0044.0078.hcd
,V/WebViewChromiumFactoryProvider(10791): Binding Chromium to main looper Looper (main, tid 1) {3fddeefa}
,I/LibraryLoader(10791): Expected native library version number "",actual native library version number ""
,I/chromium(10791): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/bt_hwcfg(10688): Axi patch failure or not include AXI patching
,I/bt_hwcfg(10688): bt vendor lib: set UART baud 3000000
,I/BrowserStartupController(10791): Initializing chromium process, renderers=0
,W/art     (10791): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10791): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10791): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10791): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
I/chromium(10791): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
,I/SecureStorage(10703): [INFO]: SPID(0x00000005)Processing data has been completed
,I/SecureStorage(10703): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10703): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10703
I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10703): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10703): ssSupport state is = 1
,I/wpa_supplicant(10703): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant(10703): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10703): SIM READ ERROR
I/wpa_supplicant(10703): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10703): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10703): SIM READ ERROR
I/wpa_supplicant(10703): Blacklist: Clear (all) 
I/wpa_supplicant(10703): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10703): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant(10703): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10703): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
I/wpa_supplicant(10703): rfkill: Cannot open RFKILL control device
,W/chromium(10791): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10791): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10791): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10791): onDetachedFromWindow called when already detached. Ignoring
,I/ActivityManager( 3525): Killing 9156:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,I/bt_hwcfg(10688): bt vendor lib: set UART baud 115200
,I/bt_hwcfg(10688): FW Download delta = 466472
D/bt_hwcfg(10688): Settlement delay -- 100 ms
I/bt_hwcfg(10688): Setting fw settlement delay to 100 
,I/bt_hwcfg(10688): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg(10688): vendor lib fwcfg completed
,I/        (10688): BTE_InitTraceLevels -- TRC_HCI
I/        (10688): BTE_InitTraceLevels -- TRC_L2CAP
I/        (10688): BTE_InitTraceLevels -- TRC_RFCOMM
I/        (10688): BTE_InitTraceLevels -- TRC_AVDT
I/        (10688): BTE_InitTraceLevels -- TRC_AVRC
I/        (10688): BTE_InitTraceLevels -- TRC_A2D
I/        (10688): BTE_InitTraceLevels -- TRC_BNEP
I/        (10688): BTE_InitTraceLevels -- TRC_BTM
I/        (10688): BTE_InitTraceLevels -- TRC_GAP
I/        (10688): BTE_InitTraceLevels -- TRC_PAN
I/        (10688): BTE_InitTraceLevels -- TRC_SAP
I/        (10688): BTE_InitTraceLevels -- TRC_SDP
I/        (10688): BTE_InitTraceLevels -- TRC_GATT
I/        (10688): BTE_InitTraceLevels -- TRC_SMP
I/        (10688): BTE_InitTraceLevels -- TRC_BTAPP
I/        (10688): BTE_InitTraceLevels -- TRC_BTIF
I/        (10688): BTE_InitTraceLevels -- TRC_PROTOCOL
,E/Tethering( 3525): No numeric data
,D/Tethering( 3525): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 3525): forceRefresh() from cache miss
,D/HotspotTile( 3695): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3695): updateTetherState():false, false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 3525): forceRefresh Fail.
,V/NetworkStats( 3525): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3525): UpdateStatsForKnox
,V/NetworkStats( 3525): performPollLocked() took 3ms
,D/NtpTrustedTime( 3525): forceRefresh() from cache miss
,D/NtpTrustedTime( 3525): forceRefresh Fail.
,W/bt-l2cap(10688): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  (10688): BTM_SecRegister:p_cb_info->p_le_callback == 0xb39eb9e1 
E/bt-btm  (10688): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb39eb9e1 
,I/wpa_supplicant(10703): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant(10703): wlan0: State: DISCONNECTED -> DISCONNECTED
I/SecureStorage(10703): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10703): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10703
I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10703): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10703): ssSupport state is = 1
,I/SecureStorage(10703): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10703): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10703
I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10703): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10703): ssSupport state is = 1
I/wpa_supplicant(10703): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10703): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10703): SIM READ ERROR
I/wpa_supplicant(10703): rfkill: Cannot open RFKILL control device
E/wpa_supplicant(10703): nl80211: Could not configure driver mode
E/wpa_supplicant(10703): p2p0: Failed to initialize driver interface
I/wpa_supplicant(10703): Blacklist: Clear (all) 
,I/SecureStorage(10703): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10703): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10703
I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10703): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10703): ssSupport state is = 1
I/SecureStorage(10703): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10703): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10703
I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10703): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10703): ssSupport state is = 1
I/wpa_supplicant(10703): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10703): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10703): SIM READ ERROR
I/wpa_supplicant(10703): rfkill: Cannot open RFKILL control device
,D/BluetoothAdapterProperties(10688): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif (10688): Calling BTA_HhEnable
,E/bt-btif (10688): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties(10688): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10688): populateRssiValuesNative
I/bluedroid(10688): getModelRssiValues
E/BluetoothServiceJni(10688): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10688): modelRssiValuesCallback, low, mid, high = -75,-65,127
,D/BluetoothAdapterProperties(10688): Name is: Note4-1
,D/SettingsProvider( 3525): name = bluetooth_name
D/BluetoothAdapterProperties(10688): Scan Mode:20
D/BluetoothAdapterProperties(10688): Discoverable Timeout:120
D/BluetoothAdapterProperties(10688): LE Address is:E0:B7:20:28:C5:81
E/bt-btif (10688): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif (10688): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif (10688): btif_sock_init: !radio_req && !rfc_init
E/bt-btif (10688): btif_sock_init: !vhci_init
D/IOP_DB_BT(10688): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT(10688): db_open: db_open : handle 3025489936l, read 14063 bytes onto local cache
D/IOP_DB_BT(10688): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT(10688): db_query: result 1
I/        (10688): iop_db_open: iop_db_open status 0
,D/bte_conf(10688): Device ID record 1 : primary
D/bte_conf(10688):   vendorId            = 0075
D/bte_conf(10688):   vendorIdSource      = 0001
D/bte_conf(10688):   product             = 0100
D/bte_conf(10688):   version             = 0200
D/bte_conf(10688):   clientExecutableURL = 
,D/bte_conf(10688):   serviceDescription  = 
D/bte_conf(10688):   documentationURL    = 
D/bte_conf(10688): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni(10688): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState(10688): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties(10688): ScanMode =  20
D/BluetoothAdapterProperties(10688): State =  11
D/SecContentProvider( 3525): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties(10688): Setting state to 12
I/BluetoothAdapterState(10688): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties(10688): Scan Mode:21
D/BluetoothAdapterProperties(10688): Discoverable Timeout:120
D/SettingsProvider( 3525): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService(10688): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10688): updateAdapterState state is 12
,D/BluetoothAdapterService(10688): Autoconnection is available 
D/BluetoothAdapterService(10688): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService(10688): starting service from this receiver
,I/BluetoothAdapterState(10688): Entering On State from state = 11
,D/BluetoothA2dp(10688): onBluetoothStateChange: up=true
D/BluetoothA2dp( 3525): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 4800): onBluetoothStateChange: up=true
,W/InputMethodManagerService( 3525): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3525): [BT Setting State] State =12
I/InputMethodManagerService( 3525): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothTile( 3695):  onBluetoothStateChange:
,I/BluetoothPbapService(10688): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothHeadset( 3954): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@212f2b2, true
,I/SamsungIME( 4460): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
E/bt_h4   (10688): vendor lib postload completed
D/BluetoothHeadset( 3954): registerMessageListener
,D/BluetoothTile( 3695):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3695): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 3695):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 3695): onStateChanged: Bluetooth
,D/StatusBarManagerService( 3525): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3525): setIconVisibility slot=bluetooth visible=true
,D/PhoneStatusBar( 3695): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,W/ContextImpl( 7628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/HeadsetService(10688): registerMessageListener
I/wpa_supplicant(10703): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant(10703): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
D/HeadsetService(10688): registerMessageListener
D/HeadsetStateMachine(10688): Disconnected process message: 70
D/HeadsetStateMachine(10688): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@64498d6
I/Telecom ( 3954): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 3954): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,V/[CarModeFW](10056): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
D/[CarModeFW](10056): ConnectivityManager-handleMessage INITIAL_STATE_ON
,D/HeadsetStateMachine(10688): Disconnected process message: 9
,D/HeadsetStateMachine(10688): mNumActive: 0 mNumHeld: 0 mCallState: 6
,I/AudioHardwareTinyALSA( 2856): setParameters(A2dpSuspended=false)
,E/HeadsetStateMachine(10688): terminateScoUsingVirtualVoiceCall:No present call to terminate
,I/BluetoothPbapService(10688): Handler(): got msg=1
D/BluetoothManagerService( 3525): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/SecContentProvider( 3525): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/LocalBluetoothProfileManager( 7628): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 7628): Adding local HEADSET profile
,V/BluetoothPbapService(10688): PBAP Service initSocket try: 0
,E/BluetoothHeadset( 7628): BTStateChangeCB is registed
,W/BluetoothAdapter(10688): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothHeadset( 7628): BluetoothHeadset service is binded
,D/BluetoothMapMasInstance(10688): set MAP SDP message type : 1
,D/BluetoothSocket(10688): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket(10688): bindListen(), new LocalSocket 
D/BluetoothSocket(10688): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10688): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11c96c62
D/BluetoothSocket(10688): channel: 19
D/BluetoothPbapService(10688): PBAP Socket is BluetoothServerSocket
,I/wpa_supplicant(10703): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant(10703): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant(10703): Skip scan - bUseNetwork false
,W/BluetoothAdapter(10688): getBluetoothService() called with no BluetoothManagerCallback
W/ContextImpl( 7628): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,E/WifiStateMachine( 3525): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,E/WifiStateMachine( 3525): setSuspendOptimizations: 2 true
E/WifiStateMachine( 3525): mSuspendOptNeedsDisabled 0
D/Bluetoothsap( 7628): bindService called to Bluetooth SAP Service
D/BluetoothSocket(10688): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket(10688): bindListen(), new LocalSocket 
D/BluetoothSocket(10688): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10688): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@279531f3
,E/WifiStateMachine( 3525): Supplicant connection established
D/BluetoothSocket(10688): channel: 5
D/WifiNative-HAL( 3525): callSECApiBoolean - ID [21]
I/wpa_supplicant(10703): HOTSPOT20_ENABLE called
I/wpa_supplicant(10703): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10703): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10703): SIM READ ERROR
I/wpa_supplicant(10703): Blacklist: Clear (all) 
,D/LocalBluetoothProfileManager( 7628): PANU : true
D/LocalBluetoothProfileManager( 7628): Adding local MAP profile
,D/BluetoothMap( 7628): Create BluetoothMap proxy object
,I/wpa_supplicant(10703): wlan0: Setting scan request: 0 sec 0 usec
,W/LocalBluetoothProfileManager( 7628): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 7628): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 7628): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 7628): onReceive
,D/BluetoothA2dp( 7628): Proxy object connected
D/A2dpProfile( 7628): Bluetooth service connected
I/wpa_supplicant(10703): Skip scan - bUseNetwork false
E/WifiStateMachine( 3525): setWifiState: enabled
,D/BluetoothAdapterService(10688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d97f08
D/BtConfig.SecureMode(10688): isSecureModeOn:false
,D/HeadsetProfile( 7628): Bluetooth service connected
,D/WifiNative-HAL( 3525): callSECApiInt - ID [210]
,D/WifiConfigStore( 3525): Loading config and enabling all networks 
,D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3525): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,D/Bluetoothsap( 7628): BluetoothSAP Proxy object connected
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/SapProfile( 7628): Bluetooth service connected
D/StatusBar.NetworkController( 3695): applyOpen
D/Bluetoothsap( 7628): getConnectedDevices()
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3695): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 3695): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3695): Wifi onReceive(3)
,D/HotspotTile( 3695): onReceive : 3, 0
D/STATUSBAR-QSTileView( 3695): onStateChanged: Wi-Fi
,D/AuthorizationBluetoothService( 4237): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/WifiConfigStore( 3525): Not a HS20
,E/WifiConfigStore( 3525): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/SecContentProvider( 3525): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/WifiStateMachine( 3525): update LTECoexState:0
D/WifiNative-HAL( 3525): callSECApiInt - ID [65]
,I/Hs20UtilService( 6356): Starting #3
I/Hs20UtilService( 6356): Message received 5011
,I/WifiStateMachine( 3525): callSECApi what=207
,D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant(10703): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant(10703): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant(10703): reset timer : RESET_TIMER 0
I/wpa_supplicant(10703): P2P: Current p2p state = IDLE
I/wpa_supplicant(10703): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant(10703): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant(10703): First Scan Start
,I/wpa_supplicant(10703): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL( 3525): Setting external_sim to 1
,D/WifiStateMachine( 3525): Setting OUI to DA-A1-19
I/WifiNative-HAL( 3525): startHal
E/wifi    ( 3525): getStaticLongField sWifiHalHandle 0x8f66785c
D/wifi    ( 3525): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x302286
I/WifiNative-HAL( 3525): Could not start hal
W/BluetoothAdapter(10688): getBluetoothService() called with no BluetoothManagerCallback
E/WifiStateMachine( 3525): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,E/WifiStateMachine( 3525): Attempting to reconnect to wifi network ..
D/KeyguardWallpaperUpdator(10721): cancelUpdateWallpaper
,D/BluetoothSocket(10688): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
D/BluetoothSocket(10688): bindListen(), new LocalSocket 
D/BluetoothSocket(10688): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10688): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c0a46e5
E/native  ( 3525): do suspend true
,D/BluetoothSocket(10688): channel: 12
I/BtOppRfcommListener(10688): Accept thread started.
D/KeyguardWallpaperUpdator(10721): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10721): stopCheckCategoryVersion
,D/BluetoothInputDevice( 7628): Proxy object connected
D/HidProfile( 7628): Bluetooth service connected
,I/SignOutReceiver( 8286): WIFI_STATE_CHANGED_ACTION
D/WifiP2pService( 3525): P2pDisabledState{ what=131203 }
,E/WifiStateMachine( 3525): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiStateMachine( 3525): updateConfiguredNetworkExpiration - currTime: 1452278388242
D/WifiStateMachine( 3525): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/WifiScanningService( 3525): SCAN_AVAILABLE : 3
D/WifiScanningService( 3525): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 3525): startHal
E/wifi    ( 3525): getStaticLongField sWifiHalHandle 0x8e41f98c
D/CommandListener( 2847): Setting iface cfg
D/wifi    ( 3525): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x20228e
I/WifiNative-HAL( 3525): Could not start hal
D/CommandListener( 2847): Trying to bring up p2p0
E/WifiScanningService( 3525): could not start HAL
,D/RttService( 3525): SCAN_AVAILABLE : 3
D/WifiMonitor( 3525): startMonitoring(p2p0) with mConnected = true
D/RttService( 3525): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 3525): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiP2pService( 3525): P2pEnablingState
D/WifiNative-HAL( 3525): callSECStringApiVoid - ID [215]
E/WifiNative-HAL( 3525): invaild command id : 215
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/WifiP2pService( 3525): P2pEnablingState{ what=147457 }
E/WifiStateMachine( 3525): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/WifiP2pService( 3525): P2p socket connection successful
D/WifiP2pService( 3525): P2pEnabledState
E/WifiStateMachine( 3525): set country code pl
,D/WifiP2pService( 3525): sending p2p connection changed broadcast: IDLE
,D/BluetoothPan( 7628): BluetoothPAN Proxy object connected
D/PanProfile( 7628): Bluetooth service connected
E/WifiStateMachine( 3525): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 3525): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiP2pService( 3525): create mNetworkAgent
,D/WifiDisplayController( 3525): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3525): disconnect
D/WifiDisplayController( 3525): updateConnection
D/WifiDisplayController( 3525): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/BluetoothMap( 7628): Proxy object connected
D/MapProfile( 7628): Bluetooth service connected
,D/BluetoothPbap( 7628): Proxy object connected
D/PbapServerProfile( 7628): Bluetooth service connected
,D/WifiDisplayController( 3525): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AllShareCastTile( 3695): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3695): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/NearbySettings( 7628): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 7628): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 7628): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 7628): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 7628): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 7628): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/wpa_supplicant(10703): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/ConnectivityService( 3525): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3525): set frequency band 0
D/ConnectivityService( 3525): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 3525): updateNetworkInfo()
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/CSLegacyTypeTracker( 3525): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
I/NearbySettings( 7628): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7628): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7628): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 7628): MountReceiver.mPrefHandler - 7002
,I/wpa_supplicant(10703): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine( 3525): setDetailed state send new extra info
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,D/WifiNative-HAL( 3525): p2pGetDeviceAddress
,D/WifiNative-HAL( 3525): p2pGetDeviceAddress returning 92:b6:86:43:73:1c
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
D/WifiP2pService( 3525): DeviceAddress: 92:73:1c
,D/WifiDisplayController( 3525): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note4-1
D/WifiDisplayController( 3525):  deviceAddress: 92:b6:86:43:73:1c
D/WifiDisplayController( 3525):  primary type: 10-0050F204-5
D/WifiDisplayController( 3525):  secondary type: null
D/WifiDisplayController( 3525):  wps: 0
D/WifiDisplayController( 3525):  grpcapab: 0
D/WifiDisplayController( 3525):  devcapab: 0
D/WifiDisplayController( 3525):  status: 3
D/WifiDisplayController( 3525):  wfdInfo: null
D/WifiDisplayController( 3525):  groupownerAddress: null
D/WifiDisplayController( 3525):  GOdeviceName: null
D/WifiDisplayController( 3525):  interfaceAddress: 
D/WifiDisplayController( 3525):  SConnectInfo : null
,D/WifiP2pService( 3525): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 3525): InactiveState
D/WifiP2pService( 3525): InactiveState{ what=143376 }
D/WifiP2pService( 3525): P2pEnabledState{ what=143376 }
,I/wpa_supplicant(10703): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService( 3525): updateNetworkInfo()
D/WifiP2pService( 3525): InactiveState{ what=143376 }
D/WifiP2pService( 3525): P2pEnabledState{ what=143376 }
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 41156(2MB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 48MB/64MB, paused 1.290ms total 85.736ms
,D/WifiService( 3525): New client listening to asynchronous messages
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10885): MountEmulatedStorage()
I/libpersona(10885): KNOX_SDCARD checking this for 10079
E/Zygote  (10885): v2
I/libpersona(10885): KNOX_SDCARD not a persona
,I/SELinux (10885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=10885 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (10885): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10885): TimaSignature is unavailable
,D/ActivityThread(10885): Added TimaKeyStore provider
,D/ResourcesManager(10885): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(10885): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 3525): Killing 7820:com.android.mms/u0a52 (adj 13): bgCount ##31
,D/CountryDetector( 3525): No listener is left
,I/wpa_supplicant(10703): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant(10703): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant(10703): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant(10703): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant(10703): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3525): [1,452,278,388,797 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3525): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1d16d574 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,I/wpa_supplicant(10703): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant(10703): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3525): setDetailed state send new extra info"NG700"
I/wpa_supplicant(10703): Associated with C0.AA.48
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,I/wpa_supplicant(10703): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant(10703): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,I/wpa_supplicant(10703): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant(10703): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant(10703): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant(10703): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(10703): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant(10703): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant(10703): Blacklist: Clear (temp) 
I/wpa_supplicant(10703): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3525): Network connection established
,D/WifiNative-HAL( 3525): callSECApiVoid - ID [50]
E/WifiStateMachine( 3525): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3525): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3525): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3525): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine( 3525): L2ConnectedState "NG700" nid=0
D/ConnectivityService( 3525): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3525): updateNetworkInfo()
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 6356): Starting #4
,I/Hs20UtilService( 6356): Message received 5007
,D/NearbySettings( 7628): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 7628): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 7628): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 7628): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7628): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7628): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7628): MountReceiver.mPrefHandler - 7002
,E/WifiStateMachine( 3525): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine( 3525): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3525): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SignOutReceiver( 8286): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2847): Setting iface cfg
,E/WifiStateMachine( 3525): Start Dhcp Watchdog 1
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,E/WifiStateMachine( 3525): Force RSSI Broadcast 1/3
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3525): do suspend false
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
D/WifiP2pService( 3525): InactiveState{ what=143375 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
,E/dhcpcd  (10904): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (10904): version 5.5.6 starting
,E/dhcpcd  (10904): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (10904): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (10904): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (10904): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (10904): bssid match
,I/dhcpcd  (10904): wlan0: rebinding lease of 192.168.1.124
,I/dhcpcd  (10904): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
I/dhcpcd  (10904): wlan0: leased 192.168.1.124 for 86400 seconds
E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine( 3525): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3525): do suspend true
D/WifiP2pService( 3525): InactiveState{ what=143375 }
D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
E/WifiStateMachine( 3525): WifiStateMachine DHCP successful
E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3525): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3525): Not connected state, yet.
E/WifiStateMachine( 3525): VerifyingLinkState enter
D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3525): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3525): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3525): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3525): callSECApiInt - ID [210]
E/WifiStateMachine( 3525): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3525): updateNetworkInfo()
D/ConnectivityService( 3525): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3525): Adding iface wlan0 to network 502
D/WifiWatchdogStateMachine( 3525): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
E/WifiStateMachine( 3525): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
I/Hs20UtilService( 6356): Starting #5
I/Hs20UtilService( 6356): Message received 5007
D/WifiStateMachine( 3525): Now, connected state.
E/WifiStateMachine( 3525): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
D/NearbySettings( 7628): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3525): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
I/NearbySettings( 7628): MountReceiver.onReceive - Keep current state
D/ConnectivityService( 3525): Adding Route [fe80::/64 -> :: wlan0] to network 502
D/ConnectivityService( 3525): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService( 3525): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
E/WifiStateMachine( 3525): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService( 3525): Unexpected mtu value: 0, wlan0
I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
E/WifiStateMachine( 3525): ConnectedState Enter  mScreenOn=false scanperiod=20000
V/        ( 2847): QcRouteController
D/WifiNative-HAL( 3525): callSECApiVoid - ID [212]
I/WifiStateMachine( 3525): REQUEST_POWER_SAVE_ON
D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
V/        ( 2847): QcRouteController
V/        ( 2847): QcRouteController
V/        ( 2847): QcRouteController
V/        ( 2847): QcRouteController
I/SignOutReceiver( 8286): NETWORK_STATE_CHANGED_ACTION
I/Hs20UtilService( 6356): Starting #6
I/Hs20UtilService( 6356): Message received 5007
V/        ( 2847): QcRouteController
D/NearbySettings( 7628): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 7628): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 7628): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 7628): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7628): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7628): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7628): MountReceiver.mPrefHandler - 7002
V/        ( 2847): QcRouteController
V/        ( 2847): QcRouteController
I/SignOutReceiver( 8286): NETWORK_STATE_CHANGED_ACTION
I/Hs20UtilService( 6356): Starting #7
I/Hs20UtilService( 6356): Message received 5007
D/NearbySettings( 7628): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/        ( 2847): QcRouteController
I/NearbySettings( 7628): MountReceiver.onReceive - Keep current state
I/WifiStateMachine( 3525): callSECApi what=220
D/WifiStateMachine( 3525): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
V/        ( 2847): QcRouteController
V/        ( 2847): QcRouteController
W/NetworkManagementService( 3525): route cmd failed: 
W/NetworkManagementService( 3525): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '52 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 52 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3525): '
W/NetworkManagementService( 3525): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3525): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3525): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3525): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3525): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6313)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService.access$2700(ConnectivityService.java:231)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2449)
W/NetworkManagementService( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3525): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 3525): LTETest block dns file not exists
I/SignOutReceiver( 8286): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 3525): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
E/ConnectivityService( 3525): updateNetworkInfo()
E/ConnectivityService( 3525): updateNetworkInfo()
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3525): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3525): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Checking http://clients3.google.com/generate_204 on "NG700"
I/System.out( 3525): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3525): (HTTPLog)-Static: isShipBuild true
I/System.out( 3525): (HTTPLog)-Thread-187-934161869: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3525): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService( 3525):    accepting network in place of null
D/ConnectivityService( 3525): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 1000
E/CSLegacyTypeTracker( 3525): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3525): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/TelephonyNetworkFactory( 3984): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 3525): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering( 3525): MasterInitialState.processMessage what=3
D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity( 3525): Not allowed due to - mEnabled false
D/ConnectivityService( 3525): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Validated
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
V/NetworkStats( 3525): updateIfacesLocked()
D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
V/NetworkStats( 3525): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3525): UpdateStatsForKnox
D/NtpTrustedTime( 3525): forceRefresh() from cache miss
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 1000
D/ConnectivityService( 3525): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3525): rematching NetworkAgentInfo [WIFI () - 502]
V/NetworkStats( 3525): performPollLocked() took 2ms
D/ConnectivityService( 3525): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 3525): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524290
D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 4478): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 4478): CM callback handler got msg 524290
I/SurfaceFlinger( 2851): id=13 createSurf (1x1),1 flag=4, Uoast
D/PowerManagerService( 3525): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3525
D/mali_winsys( 3695): new_window_surface returns 0x3000,  [1120x201]-format:1
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3695): updateDataNetType()
D/StatusBar.NetworkController( 3695): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3695): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 3695): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3695): updateDataNetType()
D/StatusBar.NetworkController( 3695): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3695): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 3695): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/NtpTrustedTime( 3525): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1452278391221 mCachedNtpElapsedRealtime : 140889 mCachedNtpCertainty : 17
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
V/NetworkStats( 3525): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3525): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3525): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 5904): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
D/AlarmManagerService( 3525): Setting time of day to sec=1452278391
D/AlarmManagerService( 3525): Trying to open a file
I/DBG_DM  ( 5904): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/AlarmManagerService( 3525): File Open Success
D/AlarmManagerService( 3525): File Close Success
I/AlarmManagerService( 3525): DRM_TIME_PATH CHMOD 666 for resetState done 
,I/DBG_DM  ( 5904): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,V/AlarmManager( 3525): waitForAlarm result :65536
I/DBG_DM  ( 5904): [IlIIlIIlIllllIlllIII(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 5904): [IlIlllIlllllIlIllllI(403/llllllIllIlIlllIIlIl)] Check completed.
,I/DBG_DM  ( 5904): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 5904): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/WifiStateMachine( 3525): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.TIME_SET
,D/KeyguardEffectViewController( 3695): onReceive action : android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 3695): handleTimeUpdate
,D/SettingsProvider( 3525): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10060
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/KeyguardEffectViewUtil( 3695): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3695): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3695): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3695): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3695): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{3874758f G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/VisualEffectParticleEffect( 3695): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{101d01c V.E..... ......I. 0,0-0,0}
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/VisualEffectParticleEffect( 3695): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{3874758f G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/VisualEffectParticleEffect( 3695): clearEffect
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/WallpaperWidget( 3695): setLockScreenWallpaper()
,D/KeyguardEffectViewUtil( 3695): getCurrentWallpaper() mWallpaperPath :null
,E/Zygote  (10964): MountEmulatedStorage()
E/Zygote  (10964): v2
I/libpersona(10964): KNOX_SDCARD checking this for 1000
I/libpersona(10964): KNOX_SDCARD not a persona
,I/SELinux (10964): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10964): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10964): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10964 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/DBG_DM  ( 5904): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5904): [IIlIIIlllllIIlIIIlII(72/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 5904): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,W/Settings( 3525): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TimaKeyStoreProvider(10964): TimaSignature is unavailable
,D/ActivityThread(10964): Added TimaKeyStore provider
,I/DBG_DM  ( 5904): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,W/SEC_DRM_PLUGIN_Playready( 2855): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1452278391 after conversion: 1452278391
W/SEC_DRM_PLUGIN_Playready( 2855): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1452278391 after conversion: 1452278391
,I/DBG_DM  ( 5904): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 5904): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
D/ResourcesManager(10964): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/DBG_DM  ( 5904): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 5904): [IlIIlIIlIllllIlllIII(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_LOG(10964): DEFAULT_LOGON : true
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_LOG(10964): DEFAULT_LOGLEVEL : 3
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_DMDBOpenHelper(10964): new DMDBOpenHelper instance
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 5904): [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 5904): [IlIIlIIlIllllIlllIII(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 5904): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,E/Zygote  (10983): MountEmulatedStorage()
E/Zygote  (10983): v2
I/libpersona(10983): KNOX_SDCARD checking this for 10090
I/libpersona(10983): KNOX_SDCARD not a persona
,I/DBG_DM  ( 5904): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
I/SELinux (10983): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3525): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=10983 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 5904): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(502/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
I/SELinux (10983): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10983): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5904): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_PushUtil(10964): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(10964): sales region : global
I/PCWCLIENTTRACE_PushUtil(10964): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(10964): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 5904): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,E/Zygote  (10998): MountEmulatedStorage()
E/Zygote  (10998): v2
I/libpersona(10998): KNOX_SDCARD checking this for 10050
I/libpersona(10998): KNOX_SDCARD not a persona
,I/SELinux (10998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10998): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5904): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 5904): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 5904): [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,E/DBG_DM  ( 5904): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
D/TimaKeyStoreProvider(10983): TimaSignature is unavailable
,I/ActivityManager( 3525): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=10998 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/ActivityThread(10983): Added TimaKeyStore provider
E/DBG_DM  ( 5904): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@11c96c62
,D/GpsLocationProvider( 3525): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11007): MountEmulatedStorage()
I/libpersona(11007): KNOX_SDCARD checking this for 10135
E/Zygote  (11007): v2
I/libpersona(11007): KNOX_SDCARD not a persona
,I/SELinux (11007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11007): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11007 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 5904): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,D/TimaKeyStoreProvider(10998): TimaSignature is unavailable
,D/ActivityThread(10998): Added TimaKeyStore provider
,D/ResourcesManager(10983): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/TimaKeyStoreProvider(11007): TimaSignature is unavailable
,D/ActivityThread(11007): Added TimaKeyStore provider
,I/KeyguardEffectViewUtil( 3695): set current wallpaper info
,D/SettingsProvider( 3525): name = keyguard_current_wallpaper_type
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10060
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/ResourcesManager(10998): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(10998): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(10998): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10998): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10998): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10998): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(10998): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10998): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10998): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SettingsProvider( 3525): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10060
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,I/ActivityManager( 3525): Killing 9960:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/ResourcesManager(11007): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/DBG_DM  ( 5904): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/SettingsProvider( 3525): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10060
,D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/StatusBar-DoNotDistrub( 3695): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 3695): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar-DoNotDistrub( 3695): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager( 2856): getOutputsForDevice device 0002 -> 0002
I/AudioService( 3525): getStreamVolume 5 index 110
,D/StatusBar-DoNotDistrub( 3695): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,E/ActivityThread( 4478): Failed to find provider info for com.android.contacts.metadata
,D/DateView( 3695): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3695): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DBG_DM  ( 5904): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/KeyguardEffectViewUtil( 3695): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3695): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3695): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3695): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3695): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{3874758f G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3695): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{101d01c V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3695): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{3874758f G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3695): clearEffect
,D/SecContentProvider2( 3525): uri = 14 selection = getSealedState
D/SecContentProvider2( 3525): mCursor = null
,D/ApplicationPolicy( 3525): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 3525): showStatusBarByNotification() mOpenByNotification=false
,D/ResourcesManager( 3695): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,I/MusicStore(11007): Database version: 104
,I/jxcore-log(10605): Test app app.js loaded
I/jxcore-log(10605): 
,D/KnoxNotification( 3695): ----- inflateViews : modified publicViewLocal -----
I/Choreographer(10605): Skipped 292 frames!  The application may be doing too much work on its main thread.
,D/KnoxNotification( 3695): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 3695): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 3695): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2bbcb59f
D/PersonaManager( 3695): isKioskContainerExistOnDevice
D/PersonaManager( 3695): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3695): Icon Only
,I/chromium(10605): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ResourcesManager(11007): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/StatusBar( 3695): Icon Only
D/PanelView( 3695): There is/are notification(s) 
D/PanelView( 3695): There is/are notification(s) 
D/PersonaManager( 3695): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3695): Icon Only
I/StatusBar( 3695): Icon Only
D/PanelView( 3695): There is/are notification(s) 
,I/chromium(10605): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ResourcesManager(11007): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11007): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/DBG_DM  ( 5904): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 5904): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,V/JNIHelp (11007): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/GLSActivity( 4237): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_DM  ( 5904): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 5904): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
I/VacuumService( 4237): Vacuum at: now=1452278392006 tag=VacuumService
,I/DBG_DM  ( 5904): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,W/ActivityThread(11007): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11007): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d16d5dc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11007): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11007): GMSCore installation verified
,D/PackageManager( 3525): findPreferredActivity: No PreferredActivities set
,I/ConfigStore(11007): Config Database version: 1
,E/Auth.Api.Credentials( 4478): [CredentialSyncAdapter] Unknown sync event.
,D/SyncManager( 3525): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 15681, reason: UserStart, SyncResult: databaseError: true stats []
D/PanelView( 3695): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
D/SyncManager( 3525): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 173025, reason: UserStart
,D/NearbySource(10998): Nearby Source Create!
D/NearbyContext(10998): Nearby Context Create!
,D/DelayedSyncController(10983): Delaying sync.
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10998): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(10998): Samsung link source created
W/ResourceType( 4962): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4962): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider(10998): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11007): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/SecContentProvider2( 3525): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3525): mCursor = null
,D/ContactProvider(10998): getAllContactInfoList End
I/syncContacts(10998): thread: 1473, sync time = 47
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11007): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11007): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,V/GLSActivity( 4237): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 3525): Killing 9980:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3525): getStreamVolume 3 index 0
,I/MediaRouter(11007): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PicasaService(10998): start picasa sync
,D/PicasaService(10998): end picasa sync
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
I/NetworkMonitor(11007): type=WIFI subType= reason=null isConnected=true
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11059): MountEmulatedStorage()
,E/Zygote  (11059): v2
I/libpersona(11059): KNOX_SDCARD checking this for 10002
I/libpersona(11059): KNOX_SDCARD not a persona
I/SELinux (11059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11059): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11059 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/ActivityManager( 3525): Killing 10003:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11059): TimaSignature is unavailable
,D/ActivityThread(11059): Added TimaKeyStore provider
,I/NetworkMonitor(11007): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 3525): Killing 10023:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,D/ResourcesManager(11059): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/DelayedSyncController(10983): Delaying sync.
,I/ActivityManager( 3525): Killing 10087:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11079): MountEmulatedStorage()
I/libpersona(11079): KNOX_SDCARD checking this for 1000
E/Zygote  (11079): v2
I/libpersona(11079): KNOX_SDCARD not a persona
I/SELinux (11079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11079): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11079 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 67231(3MB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 48MB/64MB, paused 1.693ms total 83.446ms
,D/TimaKeyStoreProvider(11079): TimaSignature is unavailable
,D/ActivityThread(11079): Added TimaKeyStore provider
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11079): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11079): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11079): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11079): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11079): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11096): MountEmulatedStorage()
E/Zygote  (11096): v2
I/libpersona(11096): KNOX_SDCARD checking this for 10012
I/libpersona(11096): KNOX_SDCARD not a persona
,I/SELinux (11096): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11096): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11096): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11096 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 328us total 9.970ms
,D/TimaKeyStoreProvider(11096): TimaSignature is unavailable
,D/ActivityThread(11096): Added TimaKeyStore provider
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 373us total 8.580ms
,D/ResourcesManager(11096): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 337us total 12.418ms
,I/ActivityManager( 3525): Killing 10139:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/FOTA_Client(11096): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11096): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11096): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11112): MountEmulatedStorage()
I/libpersona(11112): KNOX_SDCARD checking this for 10021
E/Zygote  (11112): v2
I/libpersona(11112): KNOX_SDCARD not a persona
,I/SELinux (11112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11112): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11112 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 10124:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11112): TimaSignature is unavailable
,D/ActivityThread(11112): Added TimaKeyStore provider
,D/ResourcesManager(11112): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11112): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 19:39:52 GMT+01:00 2016
,I/KLMS-2.4.521: (11112): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11112): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11112): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11112): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11112): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11112): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11112): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11112): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11112): NetworkChangeOperations(): uploadRequestLog().START 
,E/Zygote  (11129): MountEmulatedStorage()
I/libpersona(11129): KNOX_SDCARD checking this for 10038
E/Zygote  (11129): v2
I/libpersona(11129): KNOX_SDCARD not a persona
,I/SELinux (11129): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11129): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11129): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11129 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11112): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11112): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11112): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3525): Killing 10158:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11129): TimaSignature is unavailable
,D/ActivityThread(11129): Added TimaKeyStore provider
,D/ResourcesManager(11129): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11129): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11149): MountEmulatedStorage()
I/libpersona(11149): KNOX_SDCARD checking this for 1000
E/Zygote  (11149): v2
I/libpersona(11149): KNOX_SDCARD not a persona
,I/SELinux (11149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11149 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11149): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 10174:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11149): TimaSignature is unavailable
,D/ActivityThread(11149): Added TimaKeyStore provider
,D/ResourcesManager(11149): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11169): MountEmulatedStorage()
I/libpersona(11169): KNOX_SDCARD checking this for 10039
E/Zygote  (11169): v2
I/libpersona(11169): KNOX_SDCARD not a persona
,I/SELinux (11169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11169): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11169 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 10191:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11169): TimaSignature is unavailable
,D/ActivityThread(11169): Added TimaKeyStore provider
,D/ResourcesManager(11169): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(11169): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11169): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService(11169): PushLog.txt file is not deleted.
D/SPPClientService(11169): PushLog.txt file is not deleted.
D/SPPClientService(11169): ============PushLog. stop!
,E/SPPClientService(11169): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11187): MountEmulatedStorage()
E/Zygote  (11187): v2
I/libpersona(11187): KNOX_SDCARD checking this for 10045
I/libpersona(11187): KNOX_SDCARD not a persona
,I/SELinux (11187): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11187): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11187): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=11187 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3525): Killing 10223:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11187): TimaSignature is unavailable
,D/ActivityThread(11187): Added TimaKeyStore provider
,D/ResourcesManager(11187): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (11187): [SSP] onCreated
,I/SA      (11187): [TPM] There is no property file
,I/SA      (11187): [SCU] isHaveSA() - false
,I/SA      (11187): [TPM] getModelProperty : null
I/SA      (11187): [TPM] getCSCProperty : null
,I/SA      (11187): [DM] init START
,I/SA      (11187): [DM] This device is not a Vodafone
,I/SA      (11187): checkReactivationActive for LOLLIPOP
,I/SA      (11187): checkReactivationActive for reactiveActive
I/SA      (11187): setSupportRL : true
,I/SA      (11187): [SCU] isHaveSA() - false
I/SA      (11187): support phone number id : false
,I/SA      (11187): [DM] init END
I/SA      (11187): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11187): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11187): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11187): [SLFUCHKMGR] constructor called
,I/SA      (11187): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11187): [OR] == isSIMCardReady false ==
,I/SA      (11187): [SCU] == networkStateCheck == true
I/SA      (11187): [DM] getCountryCodeFromCSC : PL
I/SA      (11187): isChinaCountryCode : false
I/SA      (11187): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11187): [OR] == networkStateCheck true ==
,I/SA      (11187): [OR] GetMyCountryZoneTask
,I/SA      (11187): [OR] onReceive END
,I/ActivityManager( 3525): Killing 10276:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,I/SA      (11187): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5434): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11187): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11187): [SSP] query invoked
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/SA      (11187): [TPMU] GetMccFromDB : null
I/SA      (11187): [SCU] getMccFromPreferece mcc = 260
I/SA      (11187): [TPM] isNoProxy(default) : true
,E/Zygote  (11209): MountEmulatedStorage()
E/Zygote  (11209): v2
I/libpersona(11209): KNOX_SDCARD checking this for 10067
I/libpersona(11209): KNOX_SDCARD not a persona
,I/SELinux (11209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11209): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11209 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11209): TimaSignature is unavailable
,D/ActivityThread(11209): Added TimaKeyStore provider
,D/ResourcesManager(11209): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(11209): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11209): Other Intent
,I/ActivityManager( 3525): Killing 10293:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/accuweather( 5178): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3781): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 5178): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5178): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5178): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5178): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5178): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5178): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11225): MountEmulatedStorage()
I/libpersona(11225): KNOX_SDCARD checking this for 1000
E/Zygote  (11225): v2
I/libpersona(11225): KNOX_SDCARD not a persona
,I/SELinux (11225): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11225): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11225 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11225): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11225): TimaSignature is unavailable
,D/ActivityThread(11225): Added TimaKeyStore provider
,D/ResourcesManager(11225): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11225): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(11225): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(11225): premStatus:2
,I/KnoxUsageLogPro(11225): isEulaShown : false
I/KnoxUsageLogPro(11225): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(10721): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(10721): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10721): stopCheckCategoryVersion
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11240): MountEmulatedStorage()
I/libpersona(11240): KNOX_SDCARD checking this for 10136
E/Zygote  (11240): v2
I/libpersona(11240): KNOX_SDCARD not a persona
,I/SELinux (11240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11240 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11240): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Killing 10309:com.facebook.system/u0a10 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11240): TimaSignature is unavailable
,D/ActivityThread(11240): Added TimaKeyStore provider
,D/ResourcesManager(11240): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11240): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11240): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11240): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11240): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/SA      (11187): [RC New] Execute method=[GET] start
,I/SA      (11187): [RC New] Security=[true]
,I/System.out(11187): Thread-1520(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11187): Thread-1520(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11187): Thread-1520(ApacheHTTPLog):isShipBuild true
I/System.out(11187): Thread-1520(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10045
,I/WebViewFactory(11240): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11240): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11240): Loading: webviewchromium
,I/LibraryLoader(11240): Time to load native libraries: 3 ms (timestamps 2906-2909)
,I/LibraryLoader(11240): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11240): Binding Chromium to main looper Looper (main, tid 1) {3d12e386}
,I/LibraryLoader(11240): Expected native library version number "",actual native library version number ""
,I/chromium(11240): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11240): Initializing chromium process, renderers=0
,W/art     (11240): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11240): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/AudioManagerAndroid(11240): Requires BLUETOOTH permission
,I/chromium(11240): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(11240): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(11240): Starting up...
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11308): MountEmulatedStorage()
E/Zygote  (11308): v2
I/libpersona(11308): KNOX_SDCARD checking this for 10147
I/libpersona(11308): KNOX_SDCARD not a persona
,I/SELinux (11308): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11308): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=11308 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11308): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 10414:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11308): TimaSignature is unavailable
,D/ActivityThread(11308): Added TimaKeyStore provider
,D/ResourcesManager(11308): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(11308): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/GLSActivity( 4237): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4237): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11336): MountEmulatedStorage()
E/Zygote  (11336): v2
I/libpersona(11336): KNOX_SDCARD checking this for 10150
I/libpersona(11336): KNOX_SDCARD not a persona
,I/SELinux (11336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11336): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=11336 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11336): TimaSignature is unavailable
,D/ActivityThread(11336): Added TimaKeyStore provider
,D/ResourcesManager(11336): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(11336): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11336): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11336): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(11336): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(11336): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(11336): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,I/ActivityManager( 3525): Killing 10451:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/iu.SyncManager( 4478): SYNC; picasa accounts
,D/NetworkLogImpl( 4478): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4478): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4478): num queued entries: 0
,I/iu.UploadsManager( 4478): num updated entries: 0
,I/iu.SyncManager( 4478): NEXT; no task
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,E/Zygote  (11361): MountEmulatedStorage()
E/Zygote  (11361): v2
I/libpersona(11361): KNOX_SDCARD checking this for 10013
I/libpersona(11361): KNOX_SDCARD not a persona
,I/SELinux (11361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=11361 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (11361): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 269us total 9.823ms
,D/TimaKeyStoreProvider(11361): TimaSignature is unavailable
,D/ActivityThread(11361): Added TimaKeyStore provider
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 360us total 8.433ms
,D/ResourcesManager(11361): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 312us total 8.389ms
,D/WifiStateMachine( 3525): updateConfiguredNetworkExpiration - currTime: 1452278393658
D/WifiStateMachine( 3525): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/WaitQueueForNetworkActivate(11361): notifyNetworkActivated
,W/ContextImpl(11361): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3525): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ResourcesManager( 4237): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GCM     ( 4237): GCM config loaded
,I/dhcpcd  (10904): wlan0: sending IPv6 Router Solicitation
,D/hcjo    (11361): AutoUpdateManager:IDLE:execute
,I/FOTA_Client(11096): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/InitializeManagerStateMachine(11361): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(11361): exit::IDLE
D/InitializeManagerStateMachine(11361): entry::NETWORK_CHECK
,I/splitIntent( 3525): Split this intent : android.intent.action.TIME_SET !!   mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=17 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 3525): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
D/InitializeManagerStateMachine(11361): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(11361): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(11361): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11361): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(11361): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11361): entry::SUCCESS
D/hcjo    (11361): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (11361): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client(11096): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,E/Zygote  (11385): MountEmulatedStorage()
I/libpersona(11385): KNOX_SDCARD checking this for 10052
E/Zygote  (11385): v2
I/libpersona(11385): KNOX_SDCARD not a persona
,I/SELinux (11385): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11385): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11385): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=11385 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/hcjo    (11361): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (11361): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(11361): exit::SUCCESS
D/InitializeManagerStateMachine(11361): entry::IDLE
,I/KLMS-2.4.521: (11112): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Fri Jan 08 19:39:53 GMT+01:00 2016
,I/KLMS-2.4.521: (11112): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11112): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11112): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (11112): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11112): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.4.521: (11112): KLMSIntentService(): TIME_CHANGED
I/KLMS-2.4.521: (11112): StateImplV2(): dateTimeChanged().START : Fri Jan 08 19:39:53 GMT+01:00 2016
,D/TimaKeyStoreProvider(11385): TimaSignature is unavailable
,D/ActivityThread(11385): Added TimaKeyStore provider
,D/daemonapp( 3781): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 3781): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3781): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11112): StateImplV2(): dateTimeChanged().END
,D/daemonapp( 3781): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3781): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 3781): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 3781): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3781): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
D/comsamsunglog( 3781): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3781): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 3781): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 3781): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3781): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,E/Zygote  (11403): MountEmulatedStorage()
E/Zygote  (11403): v2
I/libpersona(11403): KNOX_SDCARD checking this for 10047
I/libpersona(11403): KNOX_SDCARD not a persona
,D/daemonapp( 3781): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
I/SELinux (11403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/daemonapp( 3781): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3781): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 3781): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/SELinux (11403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11403): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=11403 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/daemonapp( 3781): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/TimaKeyStoreProvider(11403): TimaSignature is unavailable
,D/ActivityThread(11403): Added TimaKeyStore provider
,I/KLMS-2.4.521: (11112): KLMSIntentService(): onDestroy()
,D/ResourcesManager(11385): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(11385): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(11385): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11385): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11385): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(11385): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/SA      (11187): [RC New] [v2liruge] api execute + 622
I/SA      (11187): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11187): AsyncTask #1 calls detatch()
,D/ResourcesManager(11403): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager(11403): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/Zygote  (11420): MountEmulatedStorage()
E/Zygote  (11420): v2
I/libpersona(11420): KNOX_SDCARD checking this for 10036
I/libpersona(11420): KNOX_SDCARD not a persona
,I/SELinux (11420): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3525): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/com.cigna.mobile.coach.CoachBroadcastReceiver: pid=11420 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/SELinux (11420): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11420): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/SA      (11187): [TPMU] getNetworkMcc : 
,I/SA      (11187): [SCU] saveMccToPreferece Start
I/SA      (11187): [SCU] RegionMCC : 260
,I/SA      (11187): [SSP] query invoked
,I/CalendarProvider2(11403): CalendarProvider2.onCreate() called
,D/comdaemonstockapp( 3781): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 3781): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/TimaKeyStoreProvider(11420): TimaSignature is unavailable
,D/ActivityThread(11420): Added TimaKeyStore provider
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 23698(1482KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 48MB/64MB, paused 1.364ms total 81.842ms
,I/SA      (11187): [TPMU] GetMccFromDB : null
I/SA      (11187): [SCU] getMccFromPreferece mcc = 260
I/SA      (11187): [SCU] saveMccToPreferece End
,I/SA      (11187): [RC New] executeRequest [v2liruge] end. 742
I/SA      (11187): [RC New] Execute end
I/SA      (11187): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11187): [OR] GetMyCountryZoneTask Success
,D/SecurityLogAgent(10752): KnoxConfiguration : Current State = 0
D/Mms/MmsApp(11385): [start]    onCreate() consume time = 0.0
,D/SecurityLogAgent(10752): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent(10752): StateMachine : Initialized
,D/SecurityLogAgent(10752): StateMachine : Changed Current State = 0
D/SecurityLogAgent(10752): StateMachine : Current State = 0
,D/Mms/ArtClassLoader(11385): init before art
,D/Mms/ArtClassLoader(11385): init [DONE] art
D/Mms/TelephonyPermission(11385): start operation mode monitor
D/ResourcesManager(11420): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(11385): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11385): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11438): MountEmulatedStorage()
I/libpersona(11438): KNOX_SDCARD checking this for 10191
E/Zygote  (11438): v2
I/libpersona(11438): KNOX_SDCARD not a persona
,I/SELinux (11438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=11438 uid=10191 gids={50191, 9997} abi=armeabi-v7a
,D/Mms/TelephonyPermission(11385): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(11385): isDefault true
,D/Mms/MmsApp(11385): onCreate() com.android.mms
,D/TimaKeyStoreProvider(11438): TimaSignature is unavailable
,D/ActivityThread(11438): Added TimaKeyStore provider
,D/Mms/MmsApp(11385): [start]    initCountryIso consume time = 48.9915
,D/CountryDetector( 3525): The first listener is added
,I/CheckinService( 4478): Checkin interval check for package: unspecified last checkin: 1451923699574 min interval config: 0 actual interval: 354694420
,D/Mms/MmsApp(11385): [end]    initCountryIso consume time = 10.492791
D/Mms/MmsConfig(11385): [start]    MmsConfig.init() consume time = 0.060542
,D/ResourcesManager(11438): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,W/ResourcesManager(11438): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Mms/MmsConfig(11385): before partial update
,D/Mms/MmsConfig(11385): Load Resize quality : 80
,D/Mms/MmsConfig(11385):  enable multiwindow = true
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthServiceInstalled() : HealthService is Installed.
,E/Mms/MessageUtils(11385): setCountryDetector : update country detector info 
E/Mms/MessageUtils(11385): updateCountryIso : update country iso info 
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/Mms/PackageInfo(11385): com.sec.imsservice is not installed
D/Mms/MmsConfig(11385): [end]    init() consume time = 31.533333
,D/Mms/Contact(11385): [start]    init() consume time = 0.408375
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): checkState() : APP TYPE = Full
,D/Mms/Contact(11385): [end]    init consume time = 5.8385
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/Mms/DraftCache(11385): [start]    rebuildCache consume time = 1.590875
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/TP/MmsSmsProvider( 3984): query,matched:13, calling pid = 11385
,D/TP/MmsSmsProvider( 3984): match 13:Elapsed time : 1.692 ms
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/TP/MmsSmsProvider( 3984): query,matched:12, calling pid = 11385
,I/ActivityManager( 3525): Killing 9711:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/TP/MmsSmsProvider( 3984): match 12:Elapsed time : 4.316 ms
,D/Mms/TelephonyUtils(11385): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(11385): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11385): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11385): auto download without roaming -> true
D/Mms/DownloadManager(11385): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Mms/TelephonyUtils(11385): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(11385): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(11385): roaming -> false (slotId = 1)
D/Mms/DownloadManager(11385): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(11385): auto download without roaming -> true
D/Mms/DownloadManager(11385): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(11385): auto download during roaming secondary -> false
D/Mms/DownloadManager(11385): mAutoDownload ------> true
,E/Zygote  (11473): MountEmulatedStorage()
E/Zygote  (11473): v2
I/libpersona(11473): KNOX_SDCARD checking this for 10019
I/libpersona(11473): KNOX_SDCARD not a persona
,I/SELinux (11473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11473): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=11473 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/Mms/DraftCache(11385): [end]    rebuildCache consume time = 31.903167
,D/Mms/Conversation(11385): [start]    init() consume time = 2.3255
,D/Mms/MmsApp(11385): [end]    onCreate() consume time = 0.300042
,D/Mms/DownloadManager(11385): Service state changed: Bundle[mParcelledData.dataSize=692]
,D/Mms/DownloadManager(11385): roaming ------> false, mSimSlot = 0
D/Mms/TelephonyUtils(11385): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(11385): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11385): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11385): auto download without roaming -> true
D/Mms/DownloadManager(11385): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(11385): mAutoDownload ------> true
D/TP/MmsSmsProvider( 3984): deleteConversation threadId: 9223372036854775807
,D/TimaKeyStoreProvider(11473): TimaSignature is unavailable
,I/ActivityManager( 3525): Killing 10360:com.android.vending/u0a31 (adj 13): bgCount ##31
D/ActivityThread(11473): Added TimaKeyStore provider
,I/PhenotypeConfigurator( 4237): Scheduling Phenotype for one-off execution 7963 seconds from now (1452278394076)
,D/TP/MmsSmsProvider( 3984): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,E/SQLiteLog( 3984): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3984): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3984): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3984): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3984): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3984): (284) automatic index on im_threads(normal_thread_id)
,I/ActivityManager( 3525): Killing 10775:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/TP/MmsSmsProvider( 3984): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 3984): need read changed broadcast:false
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11473): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/Zygote  (11489): MountEmulatedStorage()
I/libpersona(11489): KNOX_SDCARD checking this for 10069
E/Zygote  (11489): v2
I/libpersona(11489): KNOX_SDCARD not a persona
,I/SELinux (11489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11489): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=11489 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Mms/Conversation(11385): [end]    init consume time = 28.130708
D/Mms/MessagingNotification(11385): [start]    init() consume time = 0.059208
,I/ActivityManager( 3525): Killing 10056:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthServiceInstalled() : HealthService is Installed.
,D/GetConfigurationSnapshotOperation( 4237): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/com.sec.android.service.health.keyManager.KeyManager(11420): Current encrypted state : -1
,I/SecSQLiteOpenHelper(11420): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11420): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11420): Open platform.db in secure mode
D/SecSQLiteDatabase(11420): Android Version: 5.0.1
D/SecSQLiteDatabase(11420): Load library secsqlite.so for Android 5.0.1
,D/Mms/MessagingNotification(11385): [end]    init consume time = 13.726084
I/SecSQLiteDatabase(11420): openSecureDatabase...
,I/SecSQLiteDatabase(11420): private openSecureDatabase...
I/SecSQLiteConnectionPool(11420): OpenSecure
I/SecSQLiteConnectionPool(11420): OpenSecure with password
I/SecSQLiteConnectionPool(11420): openSecureConnectionLocked
I/SecSQLiteDatabase(11420): ...private openSecureDatabase
I/SecSQLiteDatabase(11420): ...openSecureDatabase
,D/Mms/SpamFilter(11385): [start]    SpamFilter fill() begin consume time = 1.814791
,D/Mms/Synchronizer(11385): [start]    doSync consume time = 0.815042
,D/TimaKeyStoreProvider(11489): TimaSignature is unavailable
,D/ActivityThread(11489): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 3984): query,matched:0, calling pid = 11385
V/TP/MmsSmsProvider( 3984): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3984): match 0:Elapsed time : 1.389 ms
,D/TP/MmsSmsProvider( 3984): query,matched:400, calling pid = 11385
,D/TP/MmsSmsProvider( 3984): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 3984): syncDBData start
,V/TP/MmsSmsProvider( 3984): syncDBData sms end
,V/TP/MmsSmsProvider( 3984): syncDBData mms end
,V/TP/MmsSmsProvider( 3984): syncDBData end
,D/Mms/Synchronizer(11385): [end]    doSync consume time = 13.761292
D/ResourcesManager(11489): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,I/PhenotypeFlagCommitter( 4237): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4237): Using platform SSLCertificateSocketFactory
D/Mms/SpamFilter(11385): [end]    SpamFilter fill() finished consume time = 2.16025
,I/ActivityThread(11385): Removing dead content provider:android.content.ContentProviderProxy@2fa798d9
E/SQLiteLog(11420): (26) statement aborts at 0: [PRAGMA user_version;] file is encrypted or is not a database
,E/SecDefaultDatabaseErrorHandler(11420): Corruption reported by sqlite on database: /data/data/com.sec.android.app.shealth/databases/platform.db
E/SecDefaultDatabaseErrorHandler(11420): backup the database file: /data/data/com.sec.android.app.shealth/databases/platform.db
D/SecSQLiteOpenHelper(11420): ...getDatabaseLocked(b,b,pwd)
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11508): MountEmulatedStorage()
I/libpersona(11508): KNOX_SDCARD checking this for 10082
E/Zygote  (11508): v2
I/libpersona(11508): KNOX_SDCARD not a persona
,I/SELinux (11508): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11508): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11508): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=11508 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11508): TimaSignature is unavailable
,D/ActivityThread(11508): Added TimaKeyStore provider
,I/SecureStorage(11473): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Credentials: uid 10019, gid 10019, pid 11473
I/SecureStorage( 2921): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,I/ActivityManager( 3525): Killing 10431:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/accuweather( 5178): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 5178): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/ Time Manager (11489): Time Difference not stored. TIME_DIFFERENCE
,D/ResourcesManager(11508): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(11508): onCreate
D/BadgeProvider(11508): DatabaseHelper
,E/Zygote  (11527): MountEmulatedStorage()
E/Zygote  (11527): v2
I/libpersona(11527): KNOX_SDCARD checking this for 10094
I/libpersona(11527): KNOX_SDCARD not a persona
,I/SELinux (11527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=11527 uid=10094 gids={50094, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11527): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 10885:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31
,D/Mms/MessagingNotification(11385): checkBadgeCount unreadCount=0 badgeCount=0
,D/TimaKeyStoreProvider(11527): TimaSignature is unavailable
,D/ActivityThread(11527): Added TimaKeyStore provider
,D/TP/SmsProvider( 3984): query,matched:26, calling pid = 11385
,D/TP/SmsProvider( 3984): match 26:Elapsed time : 0.871 ms
,D/ResourcesManager(11527): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/TP/MmsSmsProvider( 3984): query,matched:6, calling pid = 11385
,W/ResourcesManager(11527): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 3984): match 6:Elapsed time : 1.239 ms
W/ResourcesManager(11527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11527): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/Mms/ReservationManager(11385): ReservationManager()
,I/Mms/ReservationManager(11385): resetAfterConnected()
,D/TP/MmsSmsProvider( 3984): query,matched:7, calling pid = 11385
,D/TP/MmsSmsProvider( 3984): match 7:Elapsed time : 1.598 ms
,I/Mms/ReservationManager(11385): getReservedSendMessageCount(): retMessageCount=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11542): MountEmulatedStorage()
E/Zygote  (11542): v2
I/libpersona(11542): KNOX_SDCARD checking this for 10028
I/libpersona(11542): KNOX_SDCARD not a persona
,I/SELinux (11542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11542): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=11542 uid=10028 gids={50028, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11542): TimaSignature is unavailable
,D/ActivityThread(11542): Added TimaKeyStore provider
,I/ActivityManager( 3525): Killing 7628:com.android.settings/1000 (adj 13): bgCount ##31
,D/SettingsProvider( 3525): name = next_alarm_formatted
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10094
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/LocationManagerService( 3525): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,W/ResourcesManager(11542): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/SSRM:n  ( 3525): SIOP:: AP = 280, PST = 260, CUR = 51
,I/OMACP   (11542): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/WifiService( 3525): Client connection lost with reason: 4
,D/Mms/Omacp(11385): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/System.out( 4237): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4237): (HTTPLog)-Static: isShipBuild true
I/System.out( 4237): (HTTPLog)-Thread-267-318900173: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4237): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 10014
,D/Mms/ArtClassLoader(11385): init before art
D/Mms/ArtClassLoader(11385): init [DONE] art
,D/Mms/PerformanceUtils(11385): link cahcing start
,I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   (11542): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/Mms/PerformanceUtils(11385): link cahcing done
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11561): MountEmulatedStorage()
,E/Zygote  (11561): v2
I/libpersona(11561): KNOX_SDCARD checking this for 10106
I/libpersona(11561): KNOX_SDCARD not a persona
,I/SELinux (11561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11561 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
E/SELinux (11561): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Killing 8286:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
,I/WifiStateMachine( 3525): REQUEST_POWER_SAVE_ON
,I/System.out( 4237): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4237): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 4237, getuid(): 10014
,D/TimaKeyStoreProvider(11561): TimaSignature is unavailable
,D/ActivityThread(11561): Added TimaKeyStore provider
,D/ResourcesManager(11561): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/elm:14491(11561): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491(11561): ELMEngine.ELMEngine( context ).
D/elm:14491(11561): MDMBridge.setEnterpriseBridge()
,D/elm:14491(11561): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,I/qtaguid ( 4237): Tagging socket 82 with tag 1000120100000000{268440065,0} uid -1, pid: 4237, getuid(): 10014
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/elm:14491(11561): ElmAgentService : onCreate()
,D/elm:14491(11561): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14491(11561): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491(11561): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14491(11561): ModuleBase.ModifySetAlarm()
D/elm:14491(11561): MDMBridge.getInstance()
D/elm:14491(11561): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (11578): MountEmulatedStorage()
E/Zygote  (11578): v2
I/libpersona(11578): KNOX_SDCARD checking this for 10163
I/libpersona(11578): KNOX_SDCARD not a persona
,I/SELinux (11578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=11578 uid=10163 gids={50163, 9997} abi=armeabi-v7a
E/SELinux (11578): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/elm:14491(11561): ElmAgentService : onDestroy().
,E/WifiStateMachine( 3525): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ActivityManager( 3525): Killing 10333:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8717(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 460us total 10.401ms
,D/TimaKeyStoreProvider(11578): TimaSignature is unavailable
,D/ActivityThread(11578): Added TimaKeyStore provider
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 250us total 9.642ms
,D/ResourcesManager(11578): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(11578): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11578): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 522us total 8.737ms
,I/ActivityManager( 3525): Killing 10964:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,D/btif_config_util(10688): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/PowerManagerService( 3525): [PWL] Off : 50s ago
I/PowerManagerService( 3525): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3525): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3525): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10014, pid=4237, ws=WorkSource{10014 com.google.android.gms}) (elapsedTime=757)
I/PowerManagerService( 3525): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10094, pid=11527, ws=null) (elapsedTime=267)
,D/LocationManagerService( 3525): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4237): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4237): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 4237, getuid(): 10014
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4217, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:-370, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-992
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10688): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/LocationManagerService( 3525): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4237): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4237): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 4237, getuid(): 10014
,I/SurfaceFlinger( 2851): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger( 2851): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 3525): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3525) eventTime = 144288
,D/PowerManagerService( 3525): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3525 (0x0)
D/PowerManagerService( 3525): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3525, ws=WorkSource{10060}) (elapsedTime=3475)
,D/OpenGLRenderer( 5904): Render dirty regions requested: true
,I/SurfaceFlinger( 2851): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3525): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3525
,I/OpenGLRenderer( 5904): Initialized EGL, version 1.4
,I/OpenGLRenderer( 5904): HWUI protection enabled for context ,  &this =0xaf822088 ,&mEglDisplay = 1 , &mEglConfig = -1350180592 
,D/OpenGLRenderer( 5904): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 5904): Enabling debug mode 0
,D/mali_winsys( 5904): new_window_surface returns 0x3000,  [616x201]-format:1
,I/SecureStorage( 2921): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
,D/PackageManager( 3525): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/CalendarProvider2(11403): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager( 3525): Killing 11007:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,I/SecureStorage(11473): [INFO]: SPID(0x00000006)Processing data has been completed
,I/SecureStorage(11473): [INFO]: SPID(0x00000006)Skip using SecureStorageExceptionJNI
,I/SecSQLiteOpenHelper(11420): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11420): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11420): Open platform.db in secure mode
I/SecSQLiteDatabase(11420): openSecureDatabase...
I/SecSQLiteDatabase(11420): private openSecureDatabase...
I/SecSQLiteConnectionPool(11420): OpenSecure
I/SecSQLiteConnectionPool(11420): OpenSecure with password
I/SecSQLiteConnectionPool(11420): openSecureConnectionLocked
,I/SecSQLiteDatabase(11420): ...private openSecureDatabase
I/SecSQLiteDatabase(11420): ...openSecureDatabase
,I/SecSQLiteOpenHelper(11420): ...getDatabaseLocked(b,b,pwd)
,D/SecSQLiteOpenHelper(11420): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/-----SIC-----(11420): ------------------skip TGH
,I/SecSQLiteOpenHelper(11420): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11420): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11420): Open platform.db in secure mode
I/SecSQLiteDatabase(11420): openSecureDatabase...
I/SecSQLiteDatabase(11420): private openSecureDatabase...
I/SecSQLiteConnectionPool(11420): OpenSecure
I/SecSQLiteConnectionPool(11420): OpenSecure with password
I/SecSQLiteConnectionPool(11420): openSecureConnectionLocked
I/SecSQLiteDatabase(11420): ...private openSecureDatabase
I/SecSQLiteDatabase(11420): ...openSecureDatabase
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11420): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11420): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,I/SecSQLiteOpenHelper(11420): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11420): ...getDatabaseLocked(b,b,pwd)
,V/MediaPlayer(11420): decode(36, 20909908, 4230)
,V/MediaPlayerService( 2856): decode(26, 20909908, 4230)
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
V/StagefrightPlayer( 2856): setDataSource(26, 20909908, 4230)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 8, 0, 0)
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
,V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
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
I/SO_AGENT(11129): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 1, 0, 0)
V/AudioCache( 2856): prepared
,V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/SA      (11187): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2856): wait for playback complete
V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
,I/OggExtractor( 2856): ~MyVorbisExtractor --
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
,V/MediaPlayer(11420): decode(35, 20763080, 15440)
V/MediaPlayerService( 2856): decode(26, 20763080, 15440)
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
V/StagefrightPlayer( 2856): setDataSource(26, 20763080, 15440)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 8, 0, 0)
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
,V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
,V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
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
V/AudioCache( 2856): notify(0xb040f100, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
,V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,V/AudioCache( 2856): notify(0xb040f100, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
,V/MediaPlayerService( 2856): wait for playback complete
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 2856): wait - success
V/AwesomePlayer( 2856): addBatteryData
V/StagefrightPlayer( 2856): reset
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer(11420): decode(37, 20807608, 9226)
,V/MediaPlayerService( 2856): decode(31, 20807608, 9226)
,V/MediaPlayerService( 2856): player type = 3
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
,I/ActivityManager( 3525): Killing 10998:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
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
V/StagefrightPlayer( 2856): setDataSource(31, 20807608, 9226)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
,V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
,V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthServiceInstalled() : HealthService is Installed.
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/AdaptiveEventManager( 3695): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService,
D/AdaptiveEventManager( 3695): M updateContainers()
,D/AdaptiveEventContainerSmall( 3695): C updatePedoContainer()
D/AdaptiveEventManager( 3695): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
,D/AdaptiveEventManager( 3695): M updateContainers()
D/AdaptiveEventContainerSmall( 3695): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3695): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3695): pedoEvent == null
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
,V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
,V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 1, 0, 0)
,V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
,V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
,I/ActivityManager( 3525): Killing 11059:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1733175209, value : 485677307
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1733175209, value : 485677307
V/MediaPlayerService( 2856): wait for playback complete
,W/System.err(11420): java.lang.NumberFormatException: Invalid int: "null"
W/System.err(11420): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err(11420): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err(11420): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err(11420): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:498)
W/System.err(11420): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1242)
W/System.err(11420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11420): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DatabaseUtils( 3525): Writing exception to parcel
E/DatabaseUtils( 3525): java.lang.NullPointerException: key == null
E/DatabaseUtils( 3525): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils( 3525): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils( 3525): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils( 3525): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:376)
E/DatabaseUtils( 3525): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils( 3525): 	at android.os.Binder.execTransact(Binder.java:446)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 8, 0, 0)
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
W/System.err( 9942): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(11420): decode(38, 20914220, 4890)
V/MediaPlayerService( 2856): decode(26, 20914220, 4890)
,V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20914220, 4890)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 8, 0, 0)
,V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
I/splitIntent( 3525): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
W/System.err( 9942): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err( 9942): 	at android.provider.Settings$System.getLong(Settings.java:1669)
,W/System.err( 9942): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err( 9942): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err( 9942): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
W/System.err( 9942): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
W/System.err( 9942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
W/System.err( 9942): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9942): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9942): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9942): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 9942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,W/System.err( 9942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
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
,V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
,V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 2856): notify(0xb0009060, 1, 0, 0)
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
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 6, 0, 0)
,V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
V/MediaPlayerService( 2856): wait for playback complete
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream,
V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1),
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
,I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
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
,V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
,V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(11420): decode(39, 20840384, 17329)
V/MediaPlayerService( 2856): decode(26, 20840384, 17329)
V/MediaPlayerService( 2856): player type = 3
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
,V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20840384, 17329)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 8, 0, 0)
V/AudioCache( 2856): ignored
,V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
,V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
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
,V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
,I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
,V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 5, 0, 0)
V/AudioCache( 2856): ignored
,V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 6, 0, 0)
,V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2856): wait for playback complete
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,E/Zygote  (11664): MountEmulatedStorage()
E/Zygote  (11664): v2
I/libpersona(11664): KNOX_SDCARD checking this for 10022
I/libpersona(11664): KNOX_SDCARD not a persona
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
I/SELinux (11664): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11664): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=11664 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
E/SELinux (11664): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/MediaPlayer(11420): decode(41, 20740576, 6644)
V/MediaPlayerService( 2856): decode(26, 20740576, 6644)
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
V/StagefrightPlayer( 2856): setDataSource(26, 20740576, 6644)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 8, 0, 0)
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
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
,V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 1, 0, 0)
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
V/AudioCache( 2856): notify(0xb040f100, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
V/MediaPlayerService( 2856): wait for playback complete
,I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
,I/OggExtractor( 2856): ~OggExtractor --
I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
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
,V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
D/TimaKeyStoreProvider(11664): TimaSignature is unavailable
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
D/ActivityThread(11664): Added TimaKeyStore provider
,V/MediaPlayer(11420): decode(40, 20816916, 23389)
V/MediaPlayerService( 2856): decode(26, 20816916, 23389)
V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
,V/AwesomePlayer( 2856): constructor
V/AwesomePlayer( 2856): setDefault
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
,V/StagefrightPlayer( 2856): setDataSource(26, 20816916, 23389)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
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
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 200, 973, 0)
V/AudioCache( 2856): ignored
,V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
,V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
,E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2856): wait for playback complete
,D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(11664): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11664): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(11664): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 8, 0, 0)
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
,I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
,V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(11420): decode(42, 20706272, 8154)
V/MediaPlayerService( 2856): decode(26, 20706272, 8154)
V/MediaPlayerService( 2856): player type = 3
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
,V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20706272, 8154)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
,I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
,I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 5, 0, 0)
V/AudioCache( 2856): ignored
,V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
V/MediaPlayerService( 2856): wait for playback complete
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
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
,V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(11420): decode(43, 20679752, 4804)
V/MediaPlayerService( 2856): decode(26, 20679752, 4804)
,V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20679752, 4804)
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 8, 0, 0)
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
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
,I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/LocationWidgetApplication(11664): onCreate() : start
,D/LocationWidgetApplication(11664): countryCode = POLAND
I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 5, 0, 0)
,V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 6, 0, 0)
V/AudioCache( 2856): ignored
,V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
V/MediaPlayerService( 2856): wait for playback complete
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
,V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x84, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1,
I/OggExtractor( 2856): ~OggSource --,
,I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
D/LocationWidgetUtils(11664): getUpcommingInstances() start: 1452278395738, end: 1452812399999
D/LocationWidgetUtils(11664): getUpcommingInstances() DB begin time >= start:1452278395738, DB begin time <= end:1452812399999
V/MediaPlayer(11420): decode(44, 20649204, 9400)
V/MediaPlayerService( 2856): decode(26, 20649204, 9400)
V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
,V/AwesomePlayer( 2856): constructor
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
,V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20649204, 9400),
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(11420): decode(50, 20722624, 4112)
V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent,
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
,I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 200, 973, 0)
,V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 1, 0, 0)
V/AudioCache( 2856): prepared
V/MediaPlayerService( 2856): decode(38, 20722624, 4112)
V/MediaPlayerService( 2856): player type = 3
,V/AwesomePlayer( 2856): setDefault
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
,V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(38, 20722624, 4112)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2856): mSecCapture clear
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
,V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/AudioCache( 2856): wait - success
,V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 5, 0, 0)
V/AudioCache( 2856): ignored
,V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 1, 0, 0)
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
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
,E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
V/MediaPlayerService( 2856): wait for playback complete
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
,I/AudioPlayer( 2856): First fillBuffer call!!
,I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
,E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2856): wait for playback complete
V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
,V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 8, 0, 0)
,V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x86, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
,I/AudioPlayer( 2856): reset out
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
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
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
,V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 8, 0, 0)
,V/AudioCache( 2856): ignored
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
,V/MediaPlayer(11420): decode(45, 20857804, 52024)
V/MediaPlayerService( 2856): decode(26, 20857804, 52024)
,V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
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
,V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20857804, 52024)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
,I/SecMediaClock( 2856): reset
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
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 2856): notify(0xb0009060, 1, 0, 0)
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
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 6, 0, 0)
,V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2856): wait for playback complete
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11420): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants(11420): RegionGroup for  is null
,D/LocationManagerService( 3525): getProviders()=[]
D/LocationManagerService( 3525): getProviders()=[passive]
D/LocationManagerService( 3525): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2856): addBatteryData
,V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x87, OMX_CommandStateSet, OMX_StateIdle)
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
D/LWLocationManager(11664): mPrivacy is null
V/MediaPlayer(11420): decode(46, 20722624, 4112),
V/MediaPlayerService( 2856): decode(26, 20722624, 4112)
W/ContextImpl(11664): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,V/MediaPlayerService( 2856): player type = 3
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0),
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
,V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20722624, 4112)
V/AwesomePlayer( 2856): reset_l()
,V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
,V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
,I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2856): notify(0xb040f1a0, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 1, 0, 0)
,V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
D/ContextFramework:PrivacyManager(11664): Service for PrivacyManager is connected
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:1, 1, 0,
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2856): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 6, 0, 0)
,V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
,V/MediaPlayerService( 2856): wait for playback complete
,V/AwesomePlayer( 2856): onCheckAudioStatus,
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
,V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f1a0, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x88, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
,I/OggExtractor( 2856): ~MyVorbisExtractor --
I/OggExtractor( 2856): ~OggExtractor --
I/AudioPlayer( 2856): reset out
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
,I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
,V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
D/LWLocationManager(11664): Privacy service : STATUS_PLACE
D/LWLocationManager(11664): updateLocationStatus()
V/AwesomePlayer( 2856): reset_l()
,V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/MediaPlayer(11420): decode(47, 20785700, 21825)
V/MediaPlayerService( 2856): decode(26, 20785700, 21825)
V/MediaPlayerService( 2856): player type = 3
,V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): constructor
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20785700, 21825)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 8, 0, 0)
V/AudioCache( 2856): ignored
,V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
,V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
,V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/LocationWidgetFuctionData(11664): readDB
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/BluetoothManager(11420): getConnectedDevices
,I/LocationWidgetFuctionData(11664): selectedAppSize: 3
,I/LocationWidgetFuctionData(11664): configPlaceList aroundMeItems
D/BluetoothManager(11420): getConnectedDevices
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l,
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 5, 0, 0)
,V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
V/AudioCache( 2856): notify(0xb236c6f0, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
,V/MediaPlayerService( 2856): wait for playback complete
,D/BluetoothManager(11420): getConnectedDevices
,E/Zygote  (11728): MountEmulatedStorage()
E/Zygote  (11728): v2
I/libpersona(11728): KNOX_SDCARD checking this for 10003
I/libpersona(11728): KNOX_SDCARD not a persona
,I/SELinux (11728): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3525): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=11728 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
I/SELinux (11728): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11728): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
,V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb236c6f0, 8, 0, 0)
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
,V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,V/MediaPlayer(11420): decode(48, 20684636, 21552)
V/MediaPlayerService( 2856): decode(26, 20684636, 21552)
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
V/StagefrightPlayer( 2856): setDataSource(26, 20684636, 21552)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 8, 0, 0)
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
,V/AwesomePlayer( 2856): onPrepareAsyncEvent
,D/BluetoothManager(11420): getConnectedDevices
,I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): initAudioDecoder
,V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/BluetoothManager(11420): getConnectedDevices
,I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/TimaKeyStoreProvider(11728): TimaSignature is unavailable
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,D/ActivityThread(11728): Added TimaKeyStore provider
V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 200, 973, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 5, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 1, 0, 0)
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
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
I/AudioPlayer( 2856): First fillBuffer call!!
I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
V/MediaPlayerService( 2856): wait for playback complete
,I/ActivityManager( 3525): Killing 11079:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,D/BluetoothManager(11420): getConnectedDevices
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0)
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2856): addBatteryData
V/AudioCache( 2856): wait - success
,V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb040f100, 8, 0, 0)
,V/AudioCache( 2856): ignored
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
V/MediaPlayer(11420): decode(49, 20778600, 7017)
V/MediaPlayerService( 2856): decode(26, 20778600, 7017)
,V/MediaPlayerService( 2856): player type = 3
,V/AwesomePlayer( 2856): setDefault
,V/AwesomePlayer( 2856): constructor
V/AwesomePlayer( 2856): setDefault
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): StagefrightPlayer
V/AwesomePlayer( 2856): setListener
V/StagefrightPlayer( 2856): initCheck
,V/AwesomePlayer( 2856): setAudioSink
V/StagefrightPlayer( 2856): setDataSource(26, 20778600, 7017)
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 8, 0, 0)
V/AudioCache( 2856): ignored
,V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
,V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2856): mBitrate = -1 bits/sec
I/OggExtractor( 2856): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2856): current audio track index (0) is added to vector
V/AwesomePlayer( 2856): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2856): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService( 2856): prepare
V/AwesomePlayer( 2856): prepareAsync
V/MediaPlayerService( 2856): wait for prepare
V/AwesomePlayer( 2856): onPrepareAsyncEvent
I/SecMediaClock( 2856): SecMediaClock constructor
I/SecMediaClock( 2856): reset
I/SecVideoCapture( 2856): SecVideoCapture constructor
I/SecVideoCapture( 2856): reset
,V/AwesomePlayer( 2856): initAudioDecoder
V/AwesomePlayer( 2856): checkOffloadExceptions is true
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
,I/AwesomePlayer( 2856): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2856): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2856): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2856): finishAsyncPrepare_l
V/AwesomePlayer( 2856): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 200, 973, 0)
V/AudioCache( 2856): ignored
,V/AwesomePlayer( 2856): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 5, 0, 0)
V/AudioCache( 2856): ignored
,V/AwesomePlayer( 2856): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 1, 0, 0)
V/AudioCache( 2856): prepared
V/AudioCache( 2856): wait - success
V/MediaPlayerService( 2856): start
V/StagefrightPlayer( 2856): start
V/AwesomePlayer( 2856): play
,V/AwesomePlayer( 2856): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2856): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2856): >>>UHQA initOutputFormat 16
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2856): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 2856): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2856): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 6, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): addBatteryData
V/MediaPlayerService( 2856): wait for playback complete
,I/AudioPlayer( 2856): First fillBuffer call!!
,I/AudioPlayer( 2856): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2856): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,I/OMXCodec( 2856): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2856): postAudioEOS delayUs (0),
V/AwesomePlayer( 2856): onCheckAudioStatus
V/AwesomePlayer( 2856): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2856): onStreamDone
V/AwesomePlayer( 2856): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2856): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 2, 0, 0)
V/AudioCache( 2856): playback complete - thread will wake up later
V/AwesomePlayer( 2856): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache( 2856): notify(0xb0009060, 7, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 2856): wait - success
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): addBatteryData
V/AwesomePlayer( 2856): reset_l()
,V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2856): notify(0xb0009060, 8, 0, 0)
V/AudioCache( 2856): ignored
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stop() sendCommand(0x8b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event ,
I/OMXCodec( 2856): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2856): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2856): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2856): ~OggSource --
I/OggExtractor( 2856): ~OggExtractor ++
I/OggExtractor( 2856): ~MyVorbisExtractor ++ 
I/OggExtractor( 2856): ~MyVorbisExtractor --
,I/OggExtractor( 2856): ~OggExtractor --
I/AudioPlayer( 2856): reset out
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2856): SecVideoCapture destructor
I/SecVideoCapture( 2856): reset
V/AwesomePlayer( 2856): mSecCapture clear
I/SecMediaClock( 2856): SecMediaClock destructor
,V/AwesomePlayer( 2856): mSecMediaClock clear
V/StagefrightPlayer( 2856): ~StagefrightPlayer
V/StagefrightPlayer( 2856): reset
V/AwesomePlayer( 2856): reset_l()
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2856): mAudioTrackVector clear
V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
V/AwesomePlayer( 2856): destructor
,V/AwesomePlayer( 2856): reset_l(),
V/AwesomePlayer( 2856): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2856): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2856): mAudioTrackVector clear
,V/AwesomePlayer( 2856): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2856): mSecCapture clear
V/AwesomePlayer( 2856): mSecMediaClock clear
,I/Mms/MmsApp(11385):  start initViewCache mms
,D/Mms/ComposeMessageFragment(11385): [start]    fillCache consume time = 1943.805958
,D/Mms/ComposeMessageFragment(11385): fillCache, easy = false
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 23613(1553KB) AllocSpace objects, 15(2MB) LOS objects, 24% free, 48MB/64MB, paused 2.113ms total 145.786ms
,I/ActivityManager( 3525): Killing 11149:com.policydm/1000 (adj 13): bgCount ##31
,D/ResourcesManager(11728): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/UserAnalysis.PlaceProvider(11728): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager(11728): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(11728): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(11728): Create SecureDbHelper
,D/IntelligenceServiceApplication(11728): onCreate()
,D/AbsListView(11385): Get MotionRecognitionManager
,D/MotionRecognitionService( 3525):  ssp status : true
,D/Mms/ComposeMessageFragment(11385): [end]    fillCache consume time = 215.267709
,I/LocationWidgetFuctionData(11664): selectedAppSize: 3
,I/LocationWidgetFuctionData(11664): selectedAppSize: 3
,I/LocationWidgetFuctionData(11664): selectedAppSize: 3
,I/LocationWidgetFuctionData(11664): selectedAppSize: 3
,E/LWLocationManager(11664): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(11664): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(11664): setShouldUpdateLocationId
D/LWLocationManager(11664): setShouldUpdateLocationId return false
D/LWLocationManager(11664): setShouldUpdateLocationId
D/LWLocationManager(11664): setShouldUpdateLocationId return false
D/LWLocationManager(11664): setShouldUpdateLocationId
D/LWLocationManager(11664): setShouldUpdateLocationId return false
D/LWLocationManager(11664): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/Mms/BubbleViewCache(11385): fillCache bubble = 8
,V/AlarmManager( 3525): waitForAlarm result :4
,E/SQLiteLog(11403): (284) automatic index on view_events(_id)
,D/CalendarAlarmManager(11403): sys current time:1452278396751
,D/CalendarAlarmManager(11403): reminder amount:0
,W/ProcessCpuTracker( 3525): Skipping unknown process pid 11770
,I/dhcpcd  (10904): wlan0: sending IPv6 Router Solicitation
,I/SurfaceFlinger( 2851): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2851): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3525): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3525) eventTime = 147801
,D/PowerManagerService( 3525): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3525 (0x0)
,D/PowerManagerService( 3525): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3525, ws=WorkSource{1000}) (elapsedTime=3478)
,I/GAV4    (11240): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    (11308): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 3525): Killing 11209:com.samsung.android.scloud.backup/u0a67 (adj 13): bgCount ##31
,V/AlarmManager( 3525): waitForAlarm result :8
,I/System.out( 3525): Thread-147(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3525): Thread-147(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 3525): Thread-147(ApacheHTTPLog):isShipBuild true
,I/System.out( 3525): Thread-147(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 502 for uid 1000
,I/System.out( 3525): AsyncTask #3 calls detatch()
,W/System.err( 3525): java.io.IOException: Not Found
,W/System.err( 3525): 	at a.d.b(Unknown Source)
,W/System.err( 3525): 	at a.d.doInBackground(Unknown Source)
,W/System.err( 3525): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 3525): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 3525): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 3525): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 3525): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 3525): 	at java.lang.Thread.run(Thread.java:818)
,I/GAV3    (11420): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  (10904): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (10904): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(11361): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(11361): exit::IDLE
,D/PreloadUpdateManagerStateMachine(11361): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (11361): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (11361): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(11361): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(11361): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(11361): entry::IDLE
,D/SSRM:n  ( 3525): SIOP:: AP = 270, PST = 256, CUR = -370
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:-93, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:94
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10688): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 5
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 256, CUR = -93
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:81
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10688): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 3525): [PWL] Off : 75s ago
,V/AlarmManager( 3525): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3695): handleTimeUpdate
,D/KeyguardEffectViewController( 3695): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3695): *** don't update sliding image ***
,D/DateView( 3695): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3695): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 253, CUR = 12
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:79
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10688): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4237): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 253, CUR = 48
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10688): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3525): !@Sync 6
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 252, CUR = 57
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10688): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3525): [PWL] Off : 105s ago
,V/AlarmManager( 3525): waitForAlarm result :4
,E/ActivityThread( 4478): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3525): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 173025, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager( 3525): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 264995, reason: UserStart
,W/ResourceType( 4962): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4962): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3525): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3525): mCursor = null
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 250, CUR = 60,
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10688): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3525): waitForAlarm result :8
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 245, CUR = 57
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10688): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3525): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3695): handleTimeUpdate
,D/KeyguardEffectViewController( 3695): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3695): *** don't update sliding image ***
,D/DateView( 3695): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3695): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3525): !@Sync 7
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 244, CUR = 54
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10688): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3525): waitForAlarm result :4
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 243, CUR = 50
,I/PowerManagerService( 3525): [PWL] Off : 140s ago
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10688): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 240, CUR = 48
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10688): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3525): !@Sync 8
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 237, CUR = 44
,I/jxcore-log(10605): --= Surplus to requirements =--
I/jxcore-log(10605): 
I/jxcore-log(10605): ****TEST TOOK:  ms ****
I/jxcore-log(10605): 
I/jxcore-log(10605): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10605): 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
D/BatteryService( 3525): stay LED for fully charged
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10688): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime(11983): 
D/AndroidRuntime(11983): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(11983): CheckJNI is OFF
,D/AndroidRuntime(11983): readGMSProperty: start
D/AndroidRuntime(11983): readGMSProperty: already setted!!
,D/AndroidRuntime(11983): readGMSProperty: end
D/AndroidRuntime(11983): addProductProperty: start
,E/AffinityControl(11983): AffinityControl: registerfunction enter
,D/AndroidRuntime(11983): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3525): START PACKAGE DELETE: observer{466320293}
D/PackageManager( 3525): pkg{<packageName>}
D/PackageManager( 3525): user{0}
D/PackageManager( 3525): caller{2000}
D/PackageManager( 3525): flags{3}
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3525): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3525): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3525): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3525): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3525): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3525): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3525): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3525): !@killApplicatoin: 10550, uninstall pkg
,I/ActivityManager( 3525): Force stopping com.test.thalitest appid=10550 user=-1: uninstall pkg
I/ActivityManager( 3525): Killing 10605:com.test.thalitest/u0a550 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3525):   Force finishing activity ActivityRecord{2538b8af u0 com.test.thalitest/.MainActivity t25}
,I/SurfaceFlinger( 2851): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2851): id=12 Removed NainActivit (-2/8)
,D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3525): Skipping PackageSetting{8296f38 com.example.hello/10549} due to missing metadata
,I/ActivityManager( 3525): Force stopping com.test.thalitest appid=10550 user=0: pkg removed
,D/WifiService( 3525): Client connection lost with reason: 4
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader( 3525): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 7976): Explicit concurrent mark sweep GC freed 27564(1568KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.144ms total 50.439ms
,W/GeofencerStateMachine( 4237): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4460): mOCRHelper is null
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
I/art     ( 4051): Explicit concurrent mark sweep GC freed 1460(75KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 945us total 67.274ms
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,E/Zygote  (12008): MountEmulatedStorage()
I/libpersona(12008): KNOX_SDCARD checking this for 10063
E/Zygote  (12008): v2
I/libpersona(12008): KNOX_SDCARD not a persona
I/SELinux (12008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3525): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12008 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LWLocationManager(11664): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11664): getLastUiLocationId() : mLastUiLocationId = -100
I/SELinux (12008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12008): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/EnterpriseDeviceManagerService( 3525): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3525): Admin package name: com.google.android.gms
,W/ResourceType( 4962): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourceType( 4962): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/TimaKeyStoreProvider(12008): TimaSignature is unavailable
,D/ActivityThread(12008): Added TimaKeyStore provider
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(12008): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 43694(3MB) AllocSpace objects, 38(631KB) LOS objects, 24% free, 48MB/64MB, paused 5.448ms total 192.141ms
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     ( 3525): WaitForGcToComplete blocked for 96.989ms for cause Explicit
,D/VRSetupWizardStub/PackageIntentReceiver(12008): onReceive()
,D/VRSetupWizardStub/PackageIntentReceiver(12008): Action Package Remove
,D/VRSetupWizardStub/PackageIntentReceiver(12008): packagename:com.test.thalitest
,I/KLMS-2.4.521: (11112): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 19:41:46 GMT+01:00 2016
,I/KLMS-2.4.521: (11112): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3525): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
,I/splitIntent( 3525): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/elm:14491(11561): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/KLMS-2.4.521: (11112): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11112): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/KLMS-2.4.521: (11112): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11112): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/KLMS-2.4.521: (11112): KLMSIntentService(): PACKAGE_REMOVED
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/SecContentProvider2( 3525): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3525): mCursor = null
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11112): KLMSIntentService(): listeningToPackageRemoved().START
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/RCPManager(11225):  in createShortcut() for packageName: com.test.thalitest userId0
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/RCPManagerService( 3525):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3525): queryAllProviders():  providerCallBack is not register for 0
,I/KLMS-2.4.521: (11112): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  (12026): MountEmulatedStorage()
E/Zygote  (12026): v2
I/libpersona(12026): KNOX_SDCARD checking this for 10160
I/libpersona(12026): KNOX_SDCARD not a persona
,I/SELinux (12026): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12026): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=12026 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
E/SELinux (12026): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491(11561): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/RegisteredServicesCache( 3964): empty dynamic service
,D/elm:14491(11561): ElmAgentService : onCreate()
,D/elm:14491(11561): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(11561): MainReceiver.listeningToPackageRemoved()
,D/elm:14491(11561): MDMBridge.getInstance()
D/elm:14491(11561): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(11561): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/Zygote  (12042): MountEmulatedStorage()
,E/Zygote  (12042): v2
I/libpersona(12042): KNOX_SDCARD checking this for 10050
I/libpersona(12042): KNOX_SDCARD not a persona
,I/SELinux (12042): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3525): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12042 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux (12042): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12042): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12026): TimaSignature is unavailable
,D/ActivityThread(12026): Added TimaKeyStore provider
,D/elm:14491(11561): ElmAgentService : onDestroy().
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/Zygote  (12055): MountEmulatedStorage()
,E/Zygote  (12055): v2
I/libpersona(12055): KNOX_SDCARD checking this for 10101
I/libpersona(12055): KNOX_SDCARD not a persona
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,I/SELinux (12055): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12055): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12055 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12055): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (11112): KLMSIntentService(): listeningToPackageRemoved().END
D/TimaKeyStoreProvider(12042): TimaSignature is unavailable
,D/ActivityThread(12042): Added TimaKeyStore provider
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11664): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver(11473): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(11473): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(11473): onReceive() : package name is not s health. Return !!!
,W/ResourceType( 3525): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(12026): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(12042): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12026): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12026): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12026): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ResourcesManager(12042): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager(12042): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12042): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12042): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12042): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12042): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12042): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12042): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.4.521: (11112): KLMSIntentService(): onDestroy()
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/TimaKeyStoreProvider(12055): TimaSignature is unavailable
,D/ActivityThread(12055): Added TimaKeyStore provider
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/LocationWidgetApplication(11664): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11664): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11664): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11664): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11664): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 9027(446KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.886ms total 247.025ms
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(12055): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,E/Zygote  (12074): MountEmulatedStorage()
I/libpersona(12074): KNOX_SDCARD checking this for 1000
E/Zygote  (12074): v2
I/libpersona(12074): KNOX_SDCARD not a persona
,I/SELinux (12074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12074 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12074): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 10983:com.android.chrome/u0a90 (adj 13): bgCount ##31
,V/Common  (12026): getScreenSize 1440 2560
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/PackageManager( 3525): delete codoeFile: 
,I/AASAUninstall( 3525):  com.test.thalitest not target!
,D/PackageManager( 3525): result of delete: 1{466320293}
,I/JAM     (12026): Load The ApaService JNI
,I/JAM     (12026): version: ProfessionalAudio_v1.0.b5
I/JAM     (12026): Try v1.0.b3 ...
D/Spen    (12026): SpenSdk version level = 55
D/Spen    (12026): SpenSdk jar version = 3.0.243
,D/Spen    (12026): SpenSdk apk version = 3.0.235
D/Spen    (12026): Server UPDATE Check
,W/linker  (12026): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/SPenError(12026): JNI_OnLoad
D/AndroidRuntime(11983): Shutting down VM
D/JNI_Bitmap(12026): Init .. Done
D/SPenSpiDecoder(12026): JNI_OnLoad .. Done
D/SPenError(12026): JNI_OnLoad Success
,D/PluginManager(12026): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PackageManager( 3525): findPreferredActivity: No PreferredActivities set
D/PluginManager(12026): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(12026): JNI_OnLoad
D/Init_SPenSdk_Jni(12026): AndroidSDK: 21
D/Init_SPenSdk_Jni(12026): JNI_OnLoad .. Done
,D/ResourcesManager(11664): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/Model_ObjectBase_Jni(12026): JNI_OnLoad .. Done
D/Model_ObjectStroke_Jni(12026): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(12026): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni(12026): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(12026): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni(12026): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni(12026): check build type eng[0]
,D/Model_NoteDoc_Jni(12026): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(12026): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(12026): JNI_OnLoad .. Done
D/Model   (12026): OnLoad class Done
E/Zygote  (12093): MountEmulatedStorage()
,E/Zygote  (12093): v2
I/libpersona(12093): KNOX_SDCARD checking this for 10160
I/libpersona(12093): KNOX_SDCARD not a persona
,I/SELinux (12093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/spe_log (12026): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
D/SPen_Library(12026): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(12026): Canvas JNI_OnLoad enter!!
,I/ActivityManager( 3525): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=12093 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,I/SELinux (12093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/SPen_Library(12026): Canvas JNI_OnLoad Success
D/SPen_Library(12026): TextView JNI_OnLoad enter!!
D/SPen_Library(12026): TextView JNI_OnLoad Success
D/SPen_Library(12026): Text JNI_OnLoad enter!!
D/SPen_Library(12026): Text JNI_OnLoad Success
D/SPen_Library(12026): FontManager JNI_OnLoad enter!!
D/SPen_Library(12026): FontManager JNI_OnLoad Success
D/SPen_Library(12026): CapturePage JNI_OnLoad enter!!
D/SPen_Library(12026): CapturePage JNI_OnLoad Success
D/SPen_Library(12026): Multi JNI_OnLoad enter!!
E/SELinux (12093): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SPen_Library(12026): Multi JNI_OnLoad Success
D/SPen_Library(12026): Draw Engine JNI_OnLoad Success
D/TimaKeyStoreProvider(12074): TimaSignature is unavailable
D/DocsApplication(12055): Installing DEX configuration.
D/SPen_Library(12026): Brush JNI_OnLoad enter!!
,D/SPen_Library(12026): Brush JNI_OnLoad Success
D/ActivityThread(12074): Added TimaKeyStore provider
,D/SPen_Library(12026): ChineseBrush JNI_OnLoad enter!!
D/SPen_Library(12026): ChineseBrush JNI_OnLoad Success
,D/DexInstaller(12055): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
D/SPen_Library(12026): InkPen JNI_OnLoad enter!!
D/SPen_Library(12026): InkPen JNI_OnLoad Success
,D/SPen_Library(12026): Marker JNI_OnLoad enter!!
,D/SPen_Library(12026): Marker JNI_OnLoad Success
I/PackageInfoHelper(12055): Provided clientMode=RELEASE, packageInfo=PackageInfo{2d440369 com.google.android.apps.docs}
,D/SPen_Library(12026): Pencil JNI_OnLoad enter!!
D/SPen_Library(12026): Pencil JNI_OnLoad Success
,D/TAG     (12055): onCreate()
D/SPen_Library(12026): NativePen JNI_OnLoad enter!!
D/SPen_Library(12026): NativePen JNI_OnLoad Success
,D/SPen_Library(12026): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library(12026): MontblancFountainPen JNI_OnLoad Success
D/CrossAppStateProvider(12055): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/SPen_Library(12026): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library(12026): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library(12026): MagicPen JNI_OnLoad enter!!
D/SPen_Library(12026): MagicPen JNI_OnLoad Success
,D/SPen_Library(12026): ObliquePen JNI_OnLoad enter!!
D/SPen_Library(12026): ObliquePen JNI_OnLoad Success
,D/SPen_Library(12026): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(12026): FountainPen JNI_OnLoad Success
D/Spen    (12026): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(12026): SPenSdk_init2
D/Init_SPenSdk(12026): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(12026): Total S Pen SDK Directory Size = 0
D/Spen    (12026): initialize complete
W/linker  (12026): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/ResourcesManager(11664): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/NearbySource(12042): Nearby Source Create!
D/NearbyContext(12042): Nearby Context Create!
,D/TimaKeyStoreProvider(12093): TimaSignature is unavailable
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12093): Added TimaKeyStore provider
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(12074): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3525): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3525): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3525): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3525): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
W/ContextImpl(12042): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12042): Samsung link source created
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,E/Zygote  (12112): MountEmulatedStorage()
I/libpersona(12112): KNOX_SDCARD checking this for 10183
E/Zygote  (12112): v2
I/libpersona(12112): KNOX_SDCARD not a persona
,I/SELinux (12112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12112 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
E/SELinux (12112): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 10721:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 13): bgCount ##31
,I/PCWCLIENTTRACE_LOG(12074): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12074): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12074): new DMDBOpenHelper instance
D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/ActivityManager( 3525): Killing 11240:com.google.android.apps.magazines/u0a136 (adj 13): bgCount ##31
D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/PCWCLIENTTRACE_PushUtil(12074): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12074): sales region : global
I/PCWCLIENTTRACE_PushUtil(12074): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12074): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/TimaKeyStoreProvider(12112): TimaSignature is unavailable
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ActivityThread(12112): Added TimaKeyStore provider
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3525): PackageReceiver onReceive()
I/HarmonyEASService( 3525): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/KnoxMUMContainerPolicy( 3525): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3525): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3525): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3525): uID is 10550
V/EnterpriseBillingPolicy( 3525): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3525): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3525): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3525): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3525): getBillingProfileForVpnEngine - end - null
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ResourcesManager(12093): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  (12128): MountEmulatedStorage()
E/Zygote  (12128): v2
I/libpersona(12128): KNOX_SDCARD checking this for 10035
I/libpersona(12128): KNOX_SDCARD not a persona
,I/SELinux (12128): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12128): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12128): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager(12093): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12093): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 3525): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12128 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,I/ActivityManager( 3525): Killing 11336:com.samsung.android.sconnect/u0a150 (adj 13): bgCount ##31
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/Books/Books.apk
,W/ResourcesManager(12093): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/UsbSettingsManager( 3525): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3525): onPackageRemoved : com.test.thalitest
,D/TaskPersister( 3525): removeObsoleteFile: deleting file=25_task.xml
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ContactProvider(12042): getAllContactInfoList Start
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(12112): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/TimaKeyStoreProvider(12128): TimaSignature is unavailable
,D/ActivityThread(12128): Added TimaKeyStore provider
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/Mms/FreeMessageStatusReceiver(11385): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/SNoteProvider(12093): onCreate enableSnoteSync = true
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11664): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager(12128): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/SQLiteLog(12112): (284) automatic index on shooting_modes(title_id)
,D/Mms/FreeMessageReceiverService(11385): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(11385): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,E/Zygote  (12148): MountEmulatedStorage()
E/Zygote  (12148): v2
I/libpersona(12148): KNOX_SDCARD checking this for 1000
I/libpersona(12148): KNOX_SDCARD not a persona
,I/SELinux (12148): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12148): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12148): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.android.settings for broadcast com.android.settings/.TactileAssistBroadcastReceiver: pid=12148 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/SNoteProvider(12093): ===query=== 
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8758(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 778us total 19.437ms
,I/FeatureConfig(12128): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(11664): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 259us total 8.639ms
,I/ActivityManager( 3525): Killing 10735:com.android.email/u0a178 (adj 13): bgCount ##31
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12148): TimaSignature is unavailable
,D/ActivityThread(12148): Added TimaKeyStore provider
D/ResourcesManager(12128): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 262us total 8.923ms
,V/Common  (12093): getScreenSize 1440 2560
W/ResourcesManager(12128): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12128): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (12168): MountEmulatedStorage()
I/libpersona(12168): KNOX_SDCARD checking this for 10190
E/Zygote  (12168): v2
I/libpersona(12168): KNOX_SDCARD not a persona
,I/SELinux (12168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12168 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,E/SELinux (12168): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12128): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(12128): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager(11664): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(12128): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/TimaKeyStoreProvider(12168): TimaSignature is unavailable
,D/ActivityThread(12168): Added TimaKeyStore provider
,I/ActivityManager( 3525): Killing 10791:tv.peel.smartremote/u0a186 (adj 13): bgCount ##31
,D/ResourcesManager(12148): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(12148): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12148): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12148): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
D/ResourcesManager(12128): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(12148): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12148): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12148): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12148): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager(12128): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11664): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(12168): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/ResourcesManager(12128): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12128): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12128): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12128): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(12128): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ContactProvider(12042): getAllContactInfoList End
,I/syncContacts(12042): thread: 1628, sync time = 246
,D/SNoteProvider(12093): ===query=== 
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12128): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SQLiteLog(11169): (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12168): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12168): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,E/SQLiteDatabase(11169): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase(11169): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11169): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11169): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(11169): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(11169): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11169): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11169): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11169): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(11169): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(11169): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(11169): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(11169): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11169): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(11169): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(11169): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase(11169): 	at com.sec.spp.push.i.c.d(Unknown Source)
E/SQLiteDatabase(11169): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase(11169): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase(11169): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase(11169): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11169): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(11169): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(11169): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(11169): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(11169): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(11169): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/libpersona(12183): KNOX_SDCARD checking this for 10039
E/Zygote  (12183): MountEmulatedStorage()
I/libpersona(12183): KNOX_SDCARD not a persona
E/Zygote  (12183): v2
E/SPPClientService(11169): [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
,D/ResourcesManager(12128): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/ActivityManager( 3525): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=12183 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager(12128): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/TapandpayWidget:Utils(12168): Clear T&P info.
W/System.err(12148): java.io.FileNotFoundException: /data/log/settingsprovider.txt: open failed: EROFS (Read-only file system)
D/ResourcesManager(12128): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager(12128): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TapandpayWidget:TanpandpayAppWidgetProvider(12168): Widget is not attached.
D/ResourcesManager(12128): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/ActivityManager( 3525): Killing 11308:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
W/ResourcesManager(12128): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SELinux (12183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
E/SQLiteLog(11420): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog(11420): (3850) statement aborts at 19: [delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"] disk I/O error
E/SQLiteQuery(11420): exception: disk I/O error (code 3850); query: delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"
I/SELinux (12183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12183): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/System.err(12148): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(12148): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/System.err(12148): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:149)
W/System.err(12148): 	at com.android.settings.favorite.LogMsg.writeLog(LogMsg.java:51)
W/System.err(12148): 	at com.android.settings.favorite.LogMsg.out(LogMsg.java:29)
W/System.err(12148): 	at com.android.settings.favorite.MySettingsProvider$DatabaseHelper.<init>(MySettingsProvider.java:167)
W/System.err(12148): 	at com.android.settings.favorite.MySettingsProvider.onCreate(MySettingsProvider.java:345)
W/System.err(12148): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
W/System.err(12148): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
W/System.err(12148): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
W/System.err(12148): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
W/System.err(12148): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
W/System.err(12148): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(12148): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(12148): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12148): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(12148): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(12148): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(12148): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(12148): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(12148): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err(12148): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(12148): 	at libcore.io.Posix.open(Native Method)
W/System.err(12148): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(12148): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(12148): 	... 20 more
D/MySettingsProvider(12148): DatabaseHelper(Context context):DATABASE_VERSION=1
E/SQLiteLog(12148): (28) failed to open "/data/data/com.android.settings/databases/mysettings.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(12148): Failed to open database '/data/data/com.android.settings/databases/mysettings.db'.
E/SQLiteDatabase(12148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12148): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12148): 	at com.android.settings.favorite.MySettingsProvider.onCreate(MySettingsProvider.java:346)
E/SQLiteDatabase(12148): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(12148): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(12148): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12148): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12148): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12148): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12148): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12148): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12148): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12148): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12148): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12148): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12148): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12148): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12148): Shutting down VM
E/AndroidRuntime(12148): FATAL EXCEPTION: main
E/AndroidRuntime(12148): Process: com.android.settings, PID: 12148
E/AndroidRuntime(12148): java.lang.RuntimeException: Unable to get provider com.android.settings.favorite.MySettingsProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12148): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(12148): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(12148): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(12148): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(12148): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(12148): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12148): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12148): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12148): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12148): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12148): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12148): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12148): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12148): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12148): 	at com.android.settings.favorite.MySettingsProvider.onCreate(MySettingsProvider.java:346)
E/AndroidRuntime(12148): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(12148): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(12148): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(12148): 	... 11 more
D/ResourcesManager(12128): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/AndroidRuntime(11420): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime(11420): Process: com.sec.android.app.shealth, PID: 11420
E/AndroidRuntime(11420): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime(11420): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForCursorWindow(Native Method)
E/AndroidRuntime(11420): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:1015)
E/AndroidRuntime(11420): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
E/AndroidRuntime(11420): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
E/AndroidRuntime(11420): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:147)
E/AndroidRuntime(11420): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:136)
E/AndroidRuntime(11420): 	at android.content.ContentResolver.query(ContentResolver.java:503)
E/AndroidRuntime(11420): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime(11420): 	at com.sec.android.app.shealth.framework.ui.data.AppRegistryDbManagerWithProvider.deleteAppRegistryData(Unknown Source)
E/AndroidRuntime(11420): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:66)
E/AndroidRuntime(11420): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(11420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11420): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(11420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
W/ResourcesManager(12128): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider(12183): TimaSignature is unavailable
D/ActivityThread(12183): Added TimaKeyStore provider
D/ResourcesManager(11664): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3525): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3525): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3525): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3525): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3525): displayNotification : [09h,00h,00h]
D/ResourcesManager(12128): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/SQLiteLog(12055): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
D/UsbHostManager( 3525): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3525): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3525): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
D/PackageBroadcastService( 4478): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4478): Clearing selected account for com.test.thalitest
E/SQLiteDatabase(12055): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12055): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12055): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12055): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12055): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12055): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12055): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12055): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12055): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12055): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12055): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12055): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12055): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12055): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12055): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12055): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12055): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12055): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12055): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12055): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12055): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12055): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12055): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12055): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12055): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12055): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12055): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12055): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12055): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12055): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12055): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12055): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12055): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12055): 	at brQ.a(GellyInjector.java:119)
E/SQLiteDatabase(12055): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12055): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12055): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12055): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12055): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12055): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12055): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12055): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12055): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12055): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12055): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12055): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12055): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12055): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12055): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12055): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12055): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12055): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12055): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12055): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12055): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12055): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12055): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12055): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12055): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12055): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12055): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12055): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12055): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12055): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12055): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12055): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteOpenHelper(12055): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12055): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12055): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12055): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12055): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12055): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12055): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12055): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12055): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12055): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12055): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12055): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12055): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12055): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12055): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12055): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12055): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12055): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12055): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12055): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12055): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12055): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12055): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12055): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12055): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12055): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12055): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12055): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12055): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12055): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12055): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12055): Opened ClientFlag.db in read-only mode
D/ResourcesManager(12128): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/DropBoxManagerService( 3525): Can't write: system_app_crash
E/DropBoxManagerService( 3525): java.io.FileNotFoundException: /data/system/dropbox/drop193.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3525): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3525): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3525): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3525): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3525): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3525): 	... 5 more
E/DropBoxManagerService( 3525): Can't write: system_app_crash
E/DropBoxManagerService( 3525): java.io.FileNotFoundException: /data/system/dropbox/drop192.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3525): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3525): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3525): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3525): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3525): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3525): 	... 5 more
D/ResourcesManager(12183): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
W/ResourcesManager(12128): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
E/SQLiteLog(12055): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(12055): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12055): android.database.sqlite.SQLiteException: not an error ,(code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12055): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12055): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12055): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12055): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12055): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12055): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12055): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/AndroidRuntime(12055): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12055): Process: com.google.android.apps.docs, PID: 12055
E/AndroidRuntime(12055): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12055): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12055): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12055): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12055): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12055): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12055): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12055): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12055): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12055): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12055): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12055): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12055): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12055): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12055): 	at aFp.run(AbstractDatabaseInstance.java:471)
D/ResourcesManager(12128): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/ResourcesManager(12128): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12128): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/SQLiteLog( 4478): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4478): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process (11420): Sending signal. PID: 11420 SIG: 9
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
D/ResourcesManager(12128): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
E/DriveAsyncService( 4478): disk I/O error (code 3850)
E/DriveAsyncService( 4478): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4478): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4478): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 4478): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4478): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4478): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 4478): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 4478): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4478): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4478): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4478): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4478): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4478): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4478): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4478): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4478): 	at java.lang.Thread.run(Thread.java:818)
D/MtpClient(12042): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
W/ResourcesManager(12128): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
D/MtpClient(12042): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
W/ResourcesManager(12128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/LocationSettingsChecker( 4478): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 4478): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4478): Module APK com.google.android.play.games already loaded
W/GalaxyFinderApplication(12128): system/finder_cp/cpdata.xml file not found
D/UsbHostManager( 3525): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3525): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
E/DropBoxManagerService( 3525): Can't write: system_app_crash
E/DropBoxManagerService( 3525): java.io.FileNotFoundException: /data/system/dropbox/drop194.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3525): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3525): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3525): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3525): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3525): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3525): 	... 5 more
I/Process (12148): Sending signal. PID: 12148 SIG: 9
E/SQLiteLog(12055): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12055): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12055): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12055): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12055): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12055): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12055): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12055): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(12055): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(12055): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12055): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12055): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12055): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12055): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12055): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12055): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12055): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12055): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12055): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12055): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12055): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12055): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12055): 	at android.database.sql,ite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12055): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12055): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12055): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12055): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12055): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(12055): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(12055): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12055): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12055): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12055): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12055): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12055): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12055): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12055): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12055): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12055): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12055): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ChimeraCfgMgr( 4478): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4478): Module APK com.google.android.play.games already loaded
I/EventHub( 3525): Removing device '/dev/input/event10' due to inotify event
,W/SQLiteOpenHelper(12055): Opened ClientFlag.db in read-only mode
,E/SPPClientService(12183): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12183): [PushClientApplication] Push log off : This is Ship build version
E/SQLiteLog( 4478): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 4478): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 4478): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4478): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4478): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4478): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 4478): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 4478): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 4478): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 4478): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4478): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4478): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4478): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4478): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 4478): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4478): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4478): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 4478): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 4478): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 4478): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 4478): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 4478): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 4478): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 4478): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 4478): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 4478): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4478): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4478): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4478): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 4478): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 4478): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 4478): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 4478): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4478): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4478): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 4478): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4478): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 4478): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4478): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 4478): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
E/SQLiteLog( 4237): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4237): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/gH_CompatibleDatabase( 4478): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/AndroidRuntime( 4237): Shutting down VM
,E/AndroidRuntime( 4478): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 4478): Process: com.google.android.gms, PID: 4478
E/AndroidRuntime( 4478): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4478): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4478): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4478): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4478): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4478): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4478): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 4478): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 4478): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4478): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4478): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4478): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4237): FATAL EXCEPTION: main
E/AndroidRuntime( 4237): Process: com.google.android.gms.persistent, PID: 4237
E/AndroidRuntime( 4237): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4237): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4237): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4237): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4237): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4237): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4237): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4237): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4237): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4237): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4237): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4237): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4237): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4237): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4237): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4237): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4237): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4237): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4237): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4237): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4237): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4237): 	... 9 more
,D/SPPClientService(12183): PushLog.txt file is not deleted.
D/SPPClientService(12183): PushLog.txt file is not deleted.
D/SPPClientService(12183): ============PushLog. stop!
,E/SQLiteLog(12183): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12183): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase(12183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12183): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12183): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase(12183): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase(12183): 	at com.sec.spp.push.notisvc.registration.n.b(Unknown Source)
E/SQLiteDatabase(12183): 	at com.sec.spp.push.notisvc.registration.n.a(Unknown Source)
E/SQLiteDatabase(12183): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase(12183): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase(12183): 	at com.sec.spp.push.notisvc.registration.i.handleMessage(Unknown Source)
E/SQLiteDatabase(12183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12183): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12183): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12183): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12183): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12183): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12183): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/LNoti   (12183): [b] open fail. SQLException occured
,E/SQLiteLog( 4478): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4478): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11664): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/EventHub( 3525): Removing device '/dev/input/event7' due to inotify event
,I/EventHub( 3525): Removing device '/dev/input/event8' due to inotify event
,E/Zygote  (12222): MountEmulatedStorage()
E/Zygote  (12222): v2
I/libpersona(12222): KNOX_SDCARD checking this for 1000
I/libpersona(12222): KNOX_SDCARD not a persona
,I/SELinux (12222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=12222 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12222): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3525): Removing device '/dev/input/event9' due to inotify event
,E/Zygote  (12237): MountEmulatedStorage()
E/Zygote  (12237): v2
I/libpersona(12237): KNOX_SDCARD checking this for 10042
I/libpersona(12237): KNOX_SDCARD not a persona
,I/SELinux (12237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12237): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=12237 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11096:com.sec.android.fotaclient/u0a12 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12222): TimaSignature is unavailable
,D/ActivityThread(12222): Added TimaKeyStore provider
,I/ActivityManager( 3525): Process com.android.settings (pid 12148)(adj 0) has died(353,1129)
,I/EventHub( 3525): Removing device '/dev/input/event11' due to inotify event
,D/TimaKeyStoreProvider(12237): TimaSignature is unavailable
D/ActivityThread(12237): Added TimaKeyStore provider
,V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/DropBoxManagerService( 3525): Can't write: system_app_crash
E/DropBoxManagerService( 3525): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3525): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3525): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3525): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3525): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3525): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3525): 	... 5 more
,E/SQLiteLog( 4478): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3525): Removing device '/dev/input/event12' due to inotify event
,E/SQLiteDatabase( 4478): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 4478): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4478): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4478): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4478): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4478): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4478): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 4478): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4478): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4478): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4478): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 3525): Process com.sec.android.app.shealth (pid 11420)(adj 5) has died(355,1129)
I/Process ( 4478): Sending signal. PID: 4478 SIG: 9
W/ActivityManager( 3525): Scheduling restart of crashed service com.sec.android.app.shealth/.service.HandleAppDataService in 1000ms
,I/EventHub( 3525): Removing device '/dev/input/event13' due to inotify event
,E/DropBoxManagerService( 3525): Can't write: system_app_crash
E/DropBoxManagerService( 3525): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3525): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3525): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3525): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3525): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3525): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3525): 	... 5 more
,D/ResourcesManager(12237): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,I/Process (12055): Sending signal. PID: 12055 SIG: 9
,W/ResourcesManager(12237): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
W/ResourcesManager(12237): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/EventHub( 3525): Removing device '/dev/input/event14' due to inotify event
,D/ConnectivityService( 3525): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2f19e8b)
,D/ConnectivityService( 3525): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ResourcesManager(12222): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,E/ConnectivityService( 3525): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ActivityManager( 3525): Process com.google.android.gms has crashed too many times: killing!
,I/ActivityManager( 3525): Killing 4478:com.google.android.gms/u0a14 (adj 0): crash
,W/BroadcastQueue( 3525): Skipping deliver [background] BroadcastRecord{9b10b68 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{22144013 12055 com.google.android.apps.docs/10101/u0 remote:3d015f02}: process crashing
,W/ActivityManager( 3525): Spurious death for ProcessRecord{1b144342 4478:com.google.android.gms/u0a14}, curProc for 4478: null
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,W/ContextImpl(12222): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,E/Zygote  (12259): MountEmulatedStorage()
E/Zygote  (12259): v2
I/libpersona(12259): KNOX_SDCARD checking this for 10059
I/libpersona(12259): KNOX_SDCARD not a persona
,I/SELinux (12259): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12259): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12259): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=12259 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a

```
