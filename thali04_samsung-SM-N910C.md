#### Test 56672827039a409_thali04_samsung-SM-N910C Logs


```
--------- beginning of main
,I/MMD     ( 2876): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
D/AndroidRuntime(10608): 
D/AndroidRuntime(10608): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10608): CheckJNI is OFF
D/AndroidRuntime(10608): readGMSProperty: start
D/AndroidRuntime(10608): readGMSProperty: already setted!!
D/AndroidRuntime(10608): readGMSProperty: end
D/AndroidRuntime(10608): addProductProperty: start
E/AffinityControl(10608): AffinityControl: registerfunction enter
D/AndroidRuntime(10608): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3514): inState():  stateMachine is null !!
I/PersonaManagerService( 3514): PersonaId don't exist
I/ActivityManager( 3514): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3514): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager( 3514): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3514): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3514): mDVFSHelper.acquire()
D/FocusedStackFrame( 3514): Set to : 0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/Zygote  (10626): MountEmulatedStorage()
I/libpersona(10626): KNOX_SDCARD checking this for 10596
E/Zygote  (10626): v2
I/libpersona(10626): KNOX_SDCARD not a persona
I/SELinux (10626): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10626): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3514): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=10626 uid=10596 gids={50596, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (10626): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10608): Shutting down VM
D/PointerIcon( 3514): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3514): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3514): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3514): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(10626): TimaSignature is unavailable
D/ActivityThread(10626): Added TimaKeyStore provider
V/WindowOrientationListener( 3514): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3514): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3514): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3514): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3514): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(10626): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2855): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2855): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 3999): updateVisibility : ActivityRecord{663fc6c token=android.os.BinderProxy@3e724bff {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3999): onTrimMemory. Level: 20
I/WebViewFactory(10626): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10626): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10626): Loading: webviewchromium
I/LibraryLoader(10626): Time to load native libraries: 3 ms (timestamps 6850-6853)
I/LibraryLoader(10626): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10626): Binding Chromium to main looper Looper (main, tid 1) {2fce486d}
,I/LibraryLoader(10626): Expected native library version number "",actual native library version number ""
I/chromium(10626): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10626): Initializing chromium process, renderers=0
,W/art     (10626): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10626): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10626): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10626): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10626): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothAdapter(10626): 640957602: getState() :  mService = null. Returning STATE_OFF
,W/chromium(10626): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10626): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10626): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10626): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(10626): CordovaWebView is running on device made by: samsung
,W/art     (10626): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10626): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(10626): performCreate Call secproduct feature valuefalse
D/Activity(10626): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(10626): Render dirty regions requested: true
,D/ActivityManager( 3514): post active user change for 0
D/KnoxTimeoutHandler( 3514): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3514): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2855): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3514): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3514): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3514): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3514): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3514): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3514): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(10626): Initialized EGL, version 1.4
,I/OpenGLRenderer(10626): HWUI protection enabled for context ,  &this =0xaf845060 ,&mEglDisplay = 1 , &mEglConfig = -1278635760 
,D/OpenGLRenderer(10626): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10626): Enabling debug mode 0
,D/mali_winsys(10626): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(10626): updateVisibility : ActivityRecord{36891252 token=android.os.BinderProxy@295796d8 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3514): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3514): mDVFSHelper.release()
I/Timeline( 3514): Timeline: Activity_windows_visible id: ActivityRecord{300e0fe1 u0 com.test.thalitest/.MainActivity t25} time:137226
,W/IInputConnectionWrapper(10626): showStatusIcon on inactive InputConnection
,I/Timeline(10626): Timeline: Activity_idle id: android.os.BinderProxy@295796d8 time:137231
,D/JsMessageQueue(10626): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(10626): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10626): 
,D/jxcore_app_log(10626): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358473472
,I/chromium(10626): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(10626): Initializing JXcore engine
W/jxcore-log(10626): JXcore engine is ready
E/auditd  ( 4538): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService( 3514): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService( 3514): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
W/jxcore-log(10626): Starting JXcore engine
W/jxcore-log(10626): Platform android
W/jxcore-log(10626): 
W/jxcore-log(10626): Process ARCH arm
W/jxcore-log(10626): 
,I/jxcore-log(10626): JXcore Cordova bridge is ready!
I/jxcore-log(10626): 
W/jxcore-log(10626): JXcore engine is started
,I/jxcore-log(10626): Toggling radios to true
I/jxcore-log(10626): 
,D/BluetoothAdapter(10626): enable()
,W/ActivityManager( 3514): Permission Denial: getCurrentUser() from pid=10626, uid=10596 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 3514): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 3514): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10626, uid=10596 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 3514): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/BluetoothManagerService( 3514): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2160)
W/BluetoothManagerService( 3514): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService( 3514): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 3514): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService( 3514): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3514): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 3514): name = bluetooth_on
,E/DevicePolicyManagerService( 3514): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3514): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,I/WifiManager(10626): packageName : com.test.thalitest
,D/WifiService( 3514): New client listening to asynchronous messages
D/SecContentProvider( 3514): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3514): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3514): mCursor = null
,D/WifiService( 3514): setWifiEnabled: true pid=10626, uid=10596
E/WifiService( 3514): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3514): Permission Denial: getCurrentUser() from pid=10626, uid=10596 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3514): Failed getting userId using ActivityManagerNative
W/WifiService( 3514): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10626, uid=10596 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3514): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3514): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3514): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3514): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3514): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3514): name = wifi_on
,E/WifiStateMachine( 3514): setting operational mode to 1
,I/WifiService( 3514): disconnect: pid=10626, uid=10596
E/WifiHW  ( 3514): ##################### set firmware type 0 #####################
,I/jxcore-log(10626): Radios toggled
I/jxcore-log(10626): 
,I/jxcore-log(10626): My device name is: samsung-SM-N910C
I/jxcore-log(10626): 
,E/Zygote  (10696): MountEmulatedStorage()
I/libpersona(10696): KNOX_SDCARD checking this for 1002
E/Zygote  (10696): v2
I/libpersona(10696): KNOX_SDCARD not a persona
I/WifiHW  ( 2851): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,I/SELinux (10696): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10696): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10696): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/WifiHW  ( 2851): module is murata
E/WifiHW  ( 2851): ==========[WIFI] MURATA MODULE ===========
I/WifiHW  ( 2851): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_murata
I/ActivityManager( 3514): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=10696 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
E/WifiHW  ( 2851): TEMP_FAILURE_RETRY complete
D/SoftapController( 2851): Softap fwReload - Ok
,D/CommandListener( 2851): Setting iface cfg
D/CommandListener( 2851): Trying to bring down wlan0
,D/CommandListener( 2851): Clearing all IP addresses on wlan0
,D/TimaKeyStoreProvider(10696): TimaSignature is unavailable
,D/ActivityThread(10696): Added TimaKeyStore provider
,D/ResourcesManager(10696): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(10696): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(10696): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni(10696): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig(10696): Adding GattService
,D/BtSettings.ProfileConfig(10696): Adding HeadsetService
D/BtSettings.ProfileConfig(10696): Adding A2dpService
D/BtSettings.ProfileConfig(10696): Adding HidService
D/BtSettings.ProfileConfig(10696): Adding HealthService
,D/BtSettings.ProfileConfig(10696): Adding PanService
D/BtSettings.ProfileConfig(10696): Adding BluetoothMapService
D/BtSettings.ProfileConfig(10696): Adding SapService
D/BtSettings.ProfileConfig(10696): Adding HeadsetClientService
D/BtSettings.ProfileConfig(10696): Adding A2dpSinkService
D/BtSettings.ProfileConfig(10696): Adding SapClientService
D/BtSettings.ProfileConfig(10696): Adding HidDevService
I/BtSettings.ProfileConfig(10696): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3514): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3514): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3514): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3514): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3514): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3514): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3514): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3514): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
E/WifiHW  ( 3514): supplicant_name : p2p_supplicant
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3514): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3514): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3514): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3514): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/wpa_supplicant(10711): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant(10711): Successfully initialized wpa_supplicant
,I/SecureStorage(10711): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage(10711): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage( 2920): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10711
I/SecureStorage( 2920): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
I/SecureStorage(10711): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant(10711): ssSupport state is = 1
,I/wpa_supplicant(10711): >>>>> GET KEY, IV <<<<<
,I/SecureStorage(10711): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage( 2920): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10711
I/SecureStorage( 2920): [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,D/BluetoothAdapterState(10696): make
,I/bluedroid(10696): init
I/BluetoothAdapterState(10696): Entering OffState
,I/bte_conf(10696): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf(10696): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config(10696): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf(10696): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif (10696): btif_fetch_local_ble_random_bdaddr
I/bluedroid(10696): get_profile_interface socket
I/bluedroid(10696): get_profile_interface map_client
D/BluetoothAdapterService(10696): checkAddrForIOP: Loading from conf
D/BluetoothAdapterService(10696): Inband Ring is supported
I/GKI_LINUX(10696): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties(10696): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10696): populateRssiValuesNative
I/bluedroid(10696): getModelRssiValues
E/BluetoothServiceJni(10696): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10696): modelRssiValuesCallback, low, mid, high = -75,-65,127
D/BluetoothAdapterProperties(10696): Name is: Note4-1
D/SettingsProvider( 3514): name = bluetooth_name
,I/bluedroid(10696): config_hci_snoop_log
D/BluetoothManagerService( 3514): Broadcasting onBluetoothServiceUp() to 11 receivers.
,E/DevicePolicyManagerService( 3514): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3514): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 3514): uri = 3 selection = isBluetoothEnabled
E/WifiStateMachine( 3514): setWifiState: enabling
E/WifiStateMachine( 3514): Supplicant start successful
D/WifiMonitor( 3514): startMonitoring(wlan0) with mConnected = false
D/BluetoothAdapterState(10696): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties(10696): Setting state to 11
I/BluetoothAdapterState(10696): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(10696): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10696): updateAdapterState state is 11
D/BluetoothAdapterService(10696): Autoconnection is available 
D/BluetoothAdapterService(10696): updateAdapterState prevState = 10newState = 11
D/SmartBondingService( 3514): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothSecureManager(10696): getInstant: null
D/BluetoothSecureManager(10696): calling getMethod for getService
D/BluetoothSecureManager(10696): calling getService
D/SLocation( 3514): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/SmartBondingService( 3514): getNetworkEnabled : wifi : false mobile : false
D/BluetoothSecureManager(10696): getService return binder: android.os.BinderProxy@10e51825
D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-WifiQuickSettingButton( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3690): Wifi onReceive(2)
D/STATUSBAR-QSTileView( 3690): onStateChanged: Wi-Fi
D/HotspotTile( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 3690): onReceive : 2, 0
D/BluetoothSecureManagerService( 3514): isSecureModeEnabled
D/BluetoothSecureManagerService( 3514): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode(10696): isSecureModeOn:false
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3690): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
W/BluetoothAdapterService(10696): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10696): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10696): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(10696): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
I/SamsungIME( 4459): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService(10696): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10696): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10696): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10696): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
D/StatusBarManagerService( 3514): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
D/StatusBarManagerService( 3514): setIconVisibility slot=bluetooth visible=false
I/Hs20UtilService( 6337): Starting #2
D/PhoneStatusBar( 3690): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
D/STATUSBAR-QSTileView( 3690): onStateChanged: Bluetooth
W/InputMethodManagerService( 3514): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/Hs20UtilService( 6337): Message received 5011
I/InputMethodManagerService( 3514): [BT Setting State] State =11
W/BluetoothAdapterService(10696): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10696): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
W/BluetoothAdapterService(10696): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
W/BluetoothAdapterService(10696): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine(10696): make
W/BluetoothAdapterService(10696): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine(10696): StableState(): Entering Off State
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService(10696): Not skipping com.android.bluetooth.gatt.GattService
V/[CarModeFW](10060): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/Zygote  (10719): MountEmulatedStorage()
E/Zygote  (10719): v2
I/libpersona(10719): KNOX_SDCARD checking this for 10127
I/libpersona(10719): KNOX_SDCARD not a persona
,I/SELinux (10719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=10719 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (10719): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BluetoothAdapterService(10696): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
I/BtGatt.JNI(10696): classInitNative(L900): classInitNative: Success!
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10696): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils(10696): handleDebugAction() action=null
D/BtGatt.GattService(10696): Received start request. Starting profile...
D/BtGatt.GattService(10696): start()
I/bluedroid(10696): get_profile_interface gatt
D/BluetoothAdapterService(10696): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fce486d
D/BtGatt.AdvertiseManager(10696): advertise manager created
,W/BluetoothAdapterService(10696): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10696): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService(10696): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(10696): Not skipping com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService(10696): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fce486d
,W/BluetoothAdapterService(10696): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10696): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService(10696): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10696): Not skipping com.android.bluetooth.pan.PanService
,D/HeadsetService(10696): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni(10696): classInitNative: succeeds
D/HeadsetStateMachine(10696): make
E/HeadsetStateMachine(10696): # of Max HF connection is 2
,D/TimaKeyStoreProvider(10719): TimaSignature is unavailable
D/ActivityThread(10719): Added TimaKeyStore provider
,W/BluetoothAdapterService(10696): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10696): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService(10696): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService(10696): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService(10696): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10696): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10696): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10696): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10696): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10696): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10696): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig(10696): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService(10696): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState(10696): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid(10696): get_profile_interface handsfree
,I/DualScoManager(10696): Instantiating Dual Sco Manager
I/DualScoManager(10696): Set HeadsetServiceHelper
D/ResourcesManager(10719): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/BluetoothAtMessage(10696): createCMTIContentObservers
,D/SettingsProvider( 3514): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine(10696): Enter Disconnected: -2
,E/HeadsetStateMachine(10696): set to mRemoteBrsf = 0
D/KeyguardWallpaperUpdator(10719): cancelUpdateWallpaper
,D/BluetoothAdapterService(10696): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fce486d
,D/KeyguardWallpaperUpdator(10719): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10719): stopCheckCategoryVersion
,D/HeadsetStateMachine(10696): map size, before remove : 0
D/HeadsetStateMachine(10696): map size, after remove: 0
D/BluetoothA2dp( 3514): Proxy object connected
,D/BluetoothA2dp( 4807): Proxy object connected
D/A2dpService(10696): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni(10696): classInitNative: succeeds
V/Avrcp   (10696): make
V/Avrcp   (10696): Avrcp
I/bluedroid(10696): get_profile_interface avrcp
,I/SignOutReceiver( 8845): WIFI_STATE_CHANGED_ACTION
,V/Avrcp   (10696): start
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/RemoteController(10696): Cannot set synchronization mode on an unregistered RemoteController
,E/Zygote  (10741): MountEmulatedStorage()
E/Zygote  (10741): v2
I/libpersona(10741): KNOX_SDCARD checking this for 1000
I/libpersona(10741): KNOX_SDCARD not a persona
,I/SELinux (10741): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10741): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10741): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3514): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=10741 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,V/Avrcp   (10696): ++registerMediaPlayers++
,I/Avrcp   (10696): No of Audio players :: 2
I/Avrcp   (10696): App Package name is com.google.android.music
,D/ResourcesManager(10696): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   (10696): App pkg name is Google Play Music
,I/Avrcp   (10696): Name::Google Play Music
V/Avrcp   (10696): MediaPlayerInfo: mPlayerId=1
I/Avrcp   (10696): App Package name is com.sec.android.app.music
,D/ResourcesManager(10696): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   (10696): App pkg name is Music
,I/Avrcp   (10696): Name::Music
V/Avrcp   (10696): MediaPlayerInfo: mPlayerId=2
,I/Avrcp   (10696): No of Video players :: 1
I/Avrcp   (10696): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager(10696): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   (10696): Video App pkg name is Video Player
,I/Avrcp   (10696): Name::Video Player
V/Avrcp   (10696): MediaPlayerInfo: mPlayerId=3
I/Avrcp   (10696): Add tempPlayer
V/Avrcp   (10696): MediaPlayerInfo: mPlayerId=4
I/Avrcp   (10696): Total no of players: 4
V/Avrcp   (10696): swapping the samsung player with 1st player
I/Avrcp   (10696):  Updating now playing list upon AVRCP Start
V/Avrcp   (10696): handleMessage, msg=207
D/BluetoothMediaBrowser(10696):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,V/Avrcp   (10696): CurrentAudioFocusPackageName is null
I/Avrcp   (10696): There is no currently selected player ,setting Samsung Music Player ID
I/Avrcp   (10696):  set player publishabilty with player id::1 toBePublished ::true
,I/BluetoothA2dpServiceJni(10696): classInitNative: succeeds
D/A2dpStateMachine(10696): make
,I/bluedroid(10696): get_profile_interface a2dp
I/GKI_LINUX(10696): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif (10696): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService(10696): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fce486d
,E/BluetoothAdapterService(802048109)(10696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
D/A2dpStateMachine(10696): Enter Disconnected: -2
I/BluetoothHidServiceJni(10696): classInitNative: succeeds
,D/HidService(10696): Received start request. Starting profile...
I/bluedroid(10696): get_profile_interface hidhost
D/HidService(10696): setHidService(): set to: null
D/BluetoothAdapterService(10696): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fce486d
,I/BluetoothHealthServiceJni(10696): classInitNative: succeeds
,D/HealthService(10696): Received start request. Starting profile...
,I/bluedroid(10696): get_profile_interface health
D/BluetoothAdapterService(10696): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fce486d
,I/BluetoothPanServiceJni(10696): classInitNative(L105): succeeds
,D/BluetoothPan( 3514): BluetoothPAN Proxy object connected
,D/PanService(10696): Received start request. Starting profile...
D/BluetoothPanServiceJni(10696): initializeNative(L110): pan
I/bluedroid(10696): get_profile_interface pan
,D/BluetoothAdapterService(10696): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fce486d
,D/TimaKeyStoreProvider(10741): TimaSignature is unavailable
,D/ActivityThread(10741): Added TimaKeyStore provider
,D/BluetoothMediaBrowser(10696): no now playing list
D/BluetoothMapService(10696): Received start request. Starting profile...
D/BluetoothMediaBrowser(10696):  getNowPlayingId now playing id : -1
D/Avrcp   (10696):  checkNowPlayingList start
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10741): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,E/Zygote  (10761): MountEmulatedStorage()
E/Zygote  (10761): v2
I/libpersona(10761): KNOX_SDCARD checking this for 10178
I/libpersona(10761): KNOX_SDCARD not a persona
,I/SELinux (10761): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10761): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10761): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=10761 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 472us total 10.233ms
,D/TimaKeyStoreProvider(10761): TimaSignature is unavailable
D/ActivityThread(10761): Added TimaKeyStore provider
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 457us total 8.493ms
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10761): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(10761): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(10761): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10761): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10761): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10761): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10761): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 279us total 8.688ms
,E/Zygote  (10777): MountEmulatedStorage()
E/Zygote  (10777): v2
I/libpersona(10777): KNOX_SDCARD checking this for 10186
I/libpersona(10777): KNOX_SDCARD not a persona
,I/SELinux (10777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3514): Start proc tv.peel.smartremote for broadcast tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver: pid=10777 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/SELinux (10777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10777): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Killing 9899:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10777): TimaSignature is unavailable
,D/ActivityThread(10777): Added TimaKeyStore provider
,D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,D/ResourcesManager(10777): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,W/ResourcesManager(10777): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/BluetoothAdapterService(10696): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fce486d
,I/BluetoothSAPServiceJni(10696): classInitNative(L204): succeeds
,E/Zygote  (10800): MountEmulatedStorage()
E/Zygote  (10800): v2
I/libpersona(10800): KNOX_SDCARD checking this for 10082
I/libpersona(10800): KNOX_SDCARD not a persona
,I/SELinux (10800): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10800): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=10800 uid=10082 gids={50082, 9997} abi=armeabi-v7a
E/SELinux (10800): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SapService(10696): Received start request. Starting profile...
D/BluetoothSAPServiceJni(10696): initializeNative(L209): sap
I/bluedroid(10696): get_profile_interface sap
D/BluetoothAdapterService(10696): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fce486d
D/HeadsetStateMachine(10696): Try to query the phonestate on bind
,I/Telecom ( 3951): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 3951): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 3951): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 3951): Proxy not attached to service
,D/HeadsetStateMachine(10696): Proxy object connected
D/HeadsetPhoneState(10696): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState(10696): sendDeviceDataStateChanged
D/HeadsetPhoneState(10696): Signal level : previous=0 curr=0
D/HeadsetStateMachine(10696): Disconnected process message: 11
E/BluetoothAdapterService(802048109)(10696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10696): Disconnected process message: 18
D/BluetoothA2dp(10696): Proxy object connected
D/BluetoothAdapterService(10696): Bluetooth A2dp source service connected
D/HeadsetStateMachine(10696): Disconnected process message: 10
E/BluetoothAdapterService(802048109)(10696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(802048109)(10696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(802048109)(10696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(802048109)(10696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/HeadsetPhoneState(10696): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine(10696): Disconnected process message: 11
,I/ActivityManager( 3514): Killing 9931:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/9931/oom_score_adj; errno=22
E/BluetoothAdapterService(802048109)(10696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(802048109)(10696): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState(10696): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid(10696): enable
,I/GKI_LINUX(10696): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid(10696): init
,I/bt_vendor(10696): init
I/bt_vnd_conf(10696): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf(10696): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial(10696): userial_init
D/TimaKeyStoreProvider(10800): TimaSignature is unavailable
,D/ActivityThread(10800): Added TimaKeyStore provider
,I/ActivityManager( 3514): Killing 9175:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/ResourcesManager(10800): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(10800): onCreate
D/BadgeProvider(10800): DatabaseHelper
,D/BadgeProvider(10800): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(10800): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10800): sendNotify, [notify] : null
D/BadgeProvider(10800): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10800): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10800): update, [UpdateCount] : 1
,D/Launcher.Model( 3999): reloadBadges entered.
,I/WebViewFactory(10777): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(10777): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(10777): Loading: webviewchromium
,I/LibraryLoader(10777): Time to load native libraries: 6 ms (timestamps 9215-9221)
I/LibraryLoader(10777): Expected native library version number "",actual native library version number ""
,W/ActivityManager( 3514): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/bt_userial_vendor(10696): userial vendor open: opening /dev/ttySAC3
,I/bt_userial_vendor(10696): userial_vendor_open():UART is setup
I/bt_userial_vendor(10696): device fd = 65 open
E/bt_hwcfg(10696): Start CFG HW, HCI reset
D/bt_userial(10696): Entering userial_read_thread()
,V/WebViewChromiumFactoryProvider(10777): Binding Chromium to main looper Looper (main, tid 1) {1c306e97}
,E/bt_hwcfg(10696): Read Local Name after HCI reset
I/LibraryLoader(10777): Expected native library version number "",actual native library version number ""
,I/chromium(10777): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10777): Initializing chromium process, renderers=0
,W/art     (10777): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10777): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10777): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10777): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
I/chromium(10777): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
,D/bt_hwcfg(10696): Chipset BCM43569A1
D/bt_hwcfg(10696): Target name = [BCM4358A1]
,I/bt_hwcfg(10696): module_type[murata].
I/bt_hwcfg(10696): module_type[murata] is invalid.
E/bt_hwcfg(10696): patchram path ORG . BCM4358A1
E/bt_hwcfg(10696): patchram path ORG .. BCM4358A1
E/bt_hwcfg(10696): patchram path ORG bcm4358A0_V0033.0000.hcd BCM4358A1
E/bt_hwcfg(10696): patchram path ORG bcm4358A1_V0044.0078.hcd BCM4358A1
I/bt_hwcfg(10696): patch(org) : bcm4358A1_V0044.0078.hcd
I/bt_hwcfg(10696): Found patchfile: /vendor/firmware/bcm4358A1_V0044.0078.hcd
E/bt_hwcfg(10696): ORG patchram base 0044
E/bt_hwcfg(10696): ORG patchram minor 0078
E/bt_hwcfg(10696): fw ver (org)44.78
E/bt_hwcfg(10696): Final Patchram is /vendor/firmware/bcm4358A1_V0044.0078.hcd
,I/bt_hwcfg(10696): Axi patch failure or not include AXI patching
,I/bt_hwcfg(10696): bt vendor lib: set UART baud 3000000
,W/chromium(10777): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10777): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10777): Attempt to remove local handle scope entry from IRT, ignoring
,I/SecureStorage(10711): [INFO]: SPID(0x00000005)Processing data has been completed
,W/AwContents(10777): onDetachedFromWindow called when already detached. Ignoring
,I/SecureStorage(10711): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10711): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10711
I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10711): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10711): ssSupport state is = 1
,I/wpa_supplicant(10711): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant(10711): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10711): SIM READ ERROR
I/wpa_supplicant(10711): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10711): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10711): SIM READ ERROR
I/wpa_supplicant(10711): Blacklist: Clear (all) 
I/wpa_supplicant(10711): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10711): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant(10711): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10711): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant(10711): rfkill: Cannot open RFKILL control device
,I/ActivityManager( 3514): Killing 7867:com.android.mms/u0a52 (adj 13): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/7867/oom_score_adj; errno=22
,D/BluetoothNotiBroadcastReceiver( 7620): onReceive
,D/AuthorizationBluetoothService( 4252): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/CountryDetector( 3514): No listener is left
,I/bt_hwcfg(10696): bt vendor lib: set UART baud 115200
I/bt_hwcfg(10696): FW Download delta = 472599
D/bt_hwcfg(10696): Settlement delay -- 100 ms
I/bt_hwcfg(10696): Setting fw settlement delay to 100 
,I/bt_hwcfg(10696): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg(10696): vendor lib fwcfg completed
,I/        (10696): BTE_InitTraceLevels -- TRC_HCI
I/        (10696): BTE_InitTraceLevels -- TRC_L2CAP
I/        (10696): BTE_InitTraceLevels -- TRC_RFCOMM
I/        (10696): BTE_InitTraceLevels -- TRC_AVDT
I/        (10696): BTE_InitTraceLevels -- TRC_AVRC
I/        (10696): BTE_InitTraceLevels -- TRC_A2D
I/        (10696): BTE_InitTraceLevels -- TRC_BNEP
I/        (10696): BTE_InitTraceLevels -- TRC_BTM
I/        (10696): BTE_InitTraceLevels -- TRC_GAP
I/        (10696): BTE_InitTraceLevels -- TRC_PAN
I/        (10696): BTE_InitTraceLevels -- TRC_SAP
I/        (10696): BTE_InitTraceLevels -- TRC_SDP
I/        (10696): BTE_InitTraceLevels -- TRC_GATT
I/        (10696): BTE_InitTraceLevels -- TRC_SMP
I/        (10696): BTE_InitTraceLevels -- TRC_BTAPP
I/        (10696): BTE_InitTraceLevels -- TRC_BTIF
I/        (10696): BTE_InitTraceLevels -- TRC_PROTOCOL
,W/bt-l2cap(10696): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  (10696): BTM_SecRegister:p_cb_info->p_le_callback == 0xb39eb9e1 
E/bt-btm  (10696): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb39eb9e1 
,E/Tethering( 3514): No numeric data
,D/Tethering( 3514): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 3514): forceRefresh() from cache miss
D/HotspotTile( 3690): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3690): updateTetherState():false, false
D/EnterpriseController( 2851): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2851): getNetworkForDns: using netid 0 for uid 1000
D/NtpTrustedTime( 3514): forceRefresh Fail.
V/NetworkStats( 3514): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3514): UpdateStatsForKnox
,V/NetworkStats( 3514): performPollLocked() took 2ms
,D/NtpTrustedTime( 3514): forceRefresh() from cache miss
,D/NtpTrustedTime( 3514): forceRefresh Fail.
,I/wpa_supplicant(10711): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant(10711): wlan0: State: DISCONNECTED -> DISCONNECTED
I/SecureStorage(10711): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10711): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10711
I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10711): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10711): ssSupport state is = 1
,I/SecureStorage(10711): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,D/BluetoothAdapterProperties(10696): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,I/SecureStorage(10711): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10711
I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10711): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10711): ssSupport state is = 1
I/wpa_supplicant(10711): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10711): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10711): SIM READ ERROR
I/wpa_supplicant(10711): rfkill: Cannot open RFKILL control device
E/wpa_supplicant(10711): nl80211: Could not configure driver mode
E/wpa_supplicant(10711): p2p0: Failed to initialize driver interface
I/wpa_supplicant(10711): Blacklist: Clear (all) 
,I/SecureStorage(10711): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,E/bt-btif (10696): Calling BTA_HhEnable
E/bt-btif (10696): btif_storage_get_adapter_property service_mask:0x2120048
,D/BluetoothAdapterProperties(10696): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10696): populateRssiValuesNative
I/bluedroid(10696): getModelRssiValues
E/BluetoothServiceJni(10696): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10696): modelRssiValuesCallback, low, mid, high = -75,-65,127
D/BluetoothAdapterProperties(10696): Name is: Note4-1
,D/BluetoothAdapterProperties(10696): Scan Mode:20
D/BluetoothAdapterProperties(10696): Discoverable Timeout:120
D/BluetoothAdapterProperties(10696): LE Address is:E0:B7:20:28:C5:81
E/bt-btif (10696): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif (10696): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif (10696): btif_sock_init: !radio_req && !rfc_init
D/SettingsProvider( 3514): name = bluetooth_name
E/bt-btif (10696): btif_sock_init: !vhci_init
D/IOP_DB_BT(10696): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT(10696): db_open: db_open : handle 3025498128l, read 14063 bytes onto local cache
D/IOP_DB_BT(10696): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT(10696): db_query: result 1
I/        (10696): iop_db_open: iop_db_open status 0
,D/bte_conf(10696): Device ID record 1 : primary
D/bte_conf(10696):   vendorId            = 0075
D/bte_conf(10696):   vendorIdSource      = 0001
D/bte_conf(10696):   product             = 0100
D/bte_conf(10696):   version             = 0200
D/bte_conf(10696):   clientExecutableURL = 
D/bte_conf(10696):   serviceDescription  = 
D/bte_conf(10696):   documentationURL    = 
D/bte_conf(10696): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState(10696): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties(10696): ScanMode =  20
D/BluetoothPanServiceJni(10696): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties(10696): State =  11
,D/SecContentProvider( 3514): uri = 3 selection = isDiscoverableEnabled
D/BluetoothAdapterProperties(10696): Setting state to 12
I/BluetoothAdapterState(10696): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties(10696): Scan Mode:21
D/BluetoothAdapterProperties(10696): Discoverable Timeout:120
,D/SettingsProvider( 3514): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 1002
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService(10696): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10696): updateAdapterState state is 12
I/SecureStorage(10711): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10711
I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10711): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10711): ssSupport state is = 1
I/SecureStorage(10711): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,D/BluetoothAdapterService(10696): Autoconnection is available 
D/BluetoothAdapterService(10696): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService(10696): starting service from this receiver
,D/BluetoothA2dp( 3514): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 4807): onBluetoothStateChange: up=true
,I/BluetoothAdapterState(10696): Entering On State from state = 11
D/BluetoothA2dp(10696): onBluetoothStateChange: up=true
,W/InputMethodManagerService( 3514): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3514): [BT Setting State] State =12
I/InputMethodManagerService( 3514): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/SecureStorage(10711): [INFO]: SPID(0x00000005)This device supports Secure Storage
I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10711
I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10711): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10711): ssSupport state is = 1
I/wpa_supplicant(10711): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10711): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10711): SIM READ ERROR
I/wpa_supplicant(10711): rfkill: Cannot open RFKILL control device
D/BluetoothHeadset( 3951): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@14360b6f, true
,D/BluetoothHeadset( 3951): registerMessageListener
,I/SamsungIME( 4459): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
E/bt_h4   (10696): vendor lib postload completed
,D/BluetoothTile( 3690):  onBluetoothStateChange:
,I/BluetoothPbapService(10696): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3690): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/HeadsetService(10696): registerMessageListener
,D/HeadsetService(10696): registerMessageListener
,D/HeadsetStateMachine(10696): Disconnected process message: 70
I/Telecom ( 3951): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 3951): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/HeadsetStateMachine(10696): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@256821b2
W/ContextImpl( 7620): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,V/[CarModeFW](10060): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](10060): ConnectivityManager-handleMessage INITIAL_STATE_ON
,D/BluetoothTile( 3690):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 3690): onStateChanged: Bluetooth
,D/HeadsetStateMachine(10696): Disconnected process message: 9
D/HeadsetStateMachine(10696): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/StatusBarManagerService( 3514): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3514): setIconVisibility slot=bluetooth visible=true
,D/PhoneStatusBar( 3690): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,I/AudioHardwareTinyALSA( 2860): setParameters(A2dpSuspended=false)
,E/HeadsetStateMachine(10696): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/LocalBluetoothProfileManager( 7620): Adding local A2DP profile
,I/wpa_supplicant(10711): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant(10711): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant(10711): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant(10711): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant(10711): Skip scan - bUseNetwork false
,E/WifiStateMachine( 3514): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,E/WifiStateMachine( 3514): setSuspendOptimizations: 2 true
E/WifiStateMachine( 3514): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine( 3514): Supplicant connection established
,D/WifiNative-HAL( 3514): callSECApiBoolean - ID [21]
I/wpa_supplicant(10711): HOTSPOT20_ENABLE called
I/wpa_supplicant(10711): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10711): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10711): SIM READ ERROR
I/wpa_supplicant(10711): Blacklist: Clear (all) 
,I/wpa_supplicant(10711): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant(10711): Skip scan - bUseNetwork false
E/WifiStateMachine( 3514): setWifiState: enabled
,D/WifiNative-HAL( 3514): callSECApiInt - ID [210]
,D/WifiConfigStore( 3514): Loading config and enabling all networks 
,D/SmartBondingService( 3514): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3514): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/HotspotTile( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3690): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 3690): onStateChanged: Wi-Fi
,D/HotspotTile( 3690): onReceive : 3, 0
,E/WifiConfigStore( 3514): Not a HS20
,E/WifiConfigStore( 3514): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/art     ( 3514): Explicit concurrent mark sweep GC freed 32635(1934KB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 48MB/64MB, paused 8.857ms total 88.705ms
D/SmartBondingService( 3514): getNetworkEnabled : wifi : true mobile : false
,I/WifiStateMachine( 3514): update LTECoexState:0
D/WifiNative-HAL( 3514): callSECApiInt - ID [65]
,I/BluetoothPbapService(10696): Handler(): got msg=1
D/LocalBluetoothProfileManager( 7620): Adding local HEADSET profile
D/BluetoothManagerService( 3514): Broadcasting onBluetoothServiceUp() to 0 receivers.
D/SecContentProvider( 3514): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,E/BluetoothHeadset( 7620): BTStateChangeCB is registed
,D/WifiNative-HAL( 3514): callSECApiBoolean - ID [13]
I/wpa_supplicant(10711): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant(10711): wlan0: Setting scan request: 8 sec 0 usec
E/BluetoothHeadset( 7620): BluetoothHeadset service is binded
I/wpa_supplicant(10711): reset timer : RESET_TIMER 0
I/wpa_supplicant(10711): P2P: Current p2p state = IDLE
I/wpa_supplicant(10711): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant(10711): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant(10711): First Scan Start
,V/BluetoothPbapService(10696): PBAP Service initSocket try: 0
,I/wpa_supplicant(10711): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL( 3514): Setting external_sim to 1
,D/WifiStateMachine( 3514): Setting OUI to DA-A1-19
I/WifiNative-HAL( 3514): startHal
E/wifi    ( 3514): getStaticLongField sWifiHalHandle 0x8f81485c
D/wifi    ( 3514): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0xa0208e
I/WifiNative-HAL( 3514): Could not start hal
W/BluetoothAdapter(10696): getBluetoothService() called with no BluetoothManagerCallback
,E/WifiStateMachine( 3514): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,D/BluetoothSocket(10696): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket(10696): bindListen(), new LocalSocket 
W/ContextImpl( 7620): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/BluetoothSocket(10696): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10696): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17e6ae5f
,D/BluetoothMapMasInstance(10696): set MAP SDP message type : 1
D/BluetoothSocket(10696): channel: 19
D/BluetoothPbapService(10696): PBAP Socket is BluetoothServerSocket
,E/WifiStateMachine( 3514): Attempting to reconnect to wifi network ..
D/Bluetoothsap( 7620): bindService called to Bluetooth SAP Service
,E/native  ( 3514): do suspend true
,W/BluetoothAdapter(10696): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10696): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket(10696): bindListen(), new LocalSocket 
D/BluetoothSocket(10696): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10696): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32d360ac
D/BluetoothSocket(10696): channel: 5
,E/WifiStateMachine( 3514): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiStateMachine( 3514): updateConfiguredNetworkExpiration - currTime: 1453396607247
D/WifiStateMachine( 3514): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/WifiScanningService( 3514): SCAN_AVAILABLE : 3
D/WifiScanningService( 3514): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 3514): startHal
E/wifi    ( 3514): getStaticLongField sWifiHalHandle 0x8e5cc98c
D/WifiP2pService( 3514): P2pDisabledState{ what=131203 }
D/wifi    ( 3514): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0xc01fca
I/WifiNative-HAL( 3514): Could not start hal
E/WifiScanningService( 3514): could not start HAL
D/LocalBluetoothProfileManager( 7620): PANU : true
D/LocalBluetoothProfileManager( 7620): Adding local MAP profile
D/RttService( 3514): SCAN_AVAILABLE : 3
D/RttService( 3514): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 3514): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3514): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,D/BluetoothMap( 7620): Create BluetoothMap proxy object
E/WifiStateMachine( 3514): set country code pl
,W/LocalBluetoothProfileManager( 7620): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 7620): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 7620): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 7620): onReceive
,D/BluetoothA2dp( 7620): Proxy object connected
D/A2dpProfile( 7620): Bluetooth service connected
,D/BluetoothAdapterService(10696): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fce486d
D/BtConfig.SecureMode(10696): isSecureModeOn:false
,D/HeadsetProfile( 7620): Bluetooth service connected
,D/Bluetoothsap( 7620): BluetoothSAP Proxy object connected
,D/AuthorizationBluetoothService( 4252): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/SapProfile( 7620): Bluetooth service connected
D/Bluetoothsap( 7620): getConnectedDevices()
,D/BluetoothInputDevice( 7620): Proxy object connected
D/HidProfile( 7620): Bluetooth service connected
,I/Hs20UtilService( 6337): Starting #3
I/Hs20UtilService( 6337): Message received 5011
,D/BluetoothPan( 7620): BluetoothPAN Proxy object connected
D/PanProfile( 7620): Bluetooth service connected
I/WifiStateMachine( 3514): callSECApi what=207
,D/CommandListener( 2851): Setting iface cfg
D/CommandListener( 2851): Trying to bring up p2p0
I/wpa_supplicant(10711): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiMonitor( 3514): startMonitoring(p2p0) with mConnected = true
,D/BluetoothMap( 7620): Proxy object connected
D/MapProfile( 7620): Bluetooth service connected
D/BluetoothPbap( 7620): Proxy object connected
D/PbapServerProfile( 7620): Bluetooth service connected
E/WifiStateMachine( 3514): set frequency band 0
D/WifiP2pService( 3514): P2pEnablingState
,D/KeyguardWallpaperUpdator(10719): cancelUpdateWallpaper
D/WifiP2pService( 3514): P2pEnablingState{ what=147457 }
,D/WifiP2pService( 3514): P2p socket connection successful
,D/WifiP2pService( 3514): P2pEnabledState
,D/KeyguardWallpaperUpdator(10719): cancelUpdateCategory
,D/KeyguardWallpaperUpdator(10719): stopCheckCategoryVersion
,D/SecContentProvider( 3514): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/WifiP2pService( 3514): sending p2p connection changed broadcast: IDLE
E/WifiStateMachine( 3514): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 3514): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiDisplayController( 3514): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/SignOutReceiver( 8845): WIFI_STATE_CHANGED_ACTION
D/WifiDisplayController( 3514): disconnect
D/WifiDisplayController( 3514): updateConnection
D/WifiDisplayController( 3514): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService( 3514): create mNetworkAgent
,D/AllShareCastTile( 3690): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayController( 3514): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 3690): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,W/BluetoothAdapter(10696): getBluetoothService() called with no BluetoothManagerCallback
,I/wpa_supplicant(10711): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/WifiStateMachine( 3514): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3514): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine( 3514): setDetailed state send new extra info
,D/ConnectivityService( 3514): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 3514): hsengiv:checkWhatTypeOfNetwork and the value is false
D/BluetoothSocket(10696): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
D/BluetoothSocket(10696): bindListen(), new LocalSocket 
D/BluetoothSocket(10696): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10696): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f6297d6
,D/BluetoothSocket(10696): channel: 12
I/BtOppRfcommListener(10696): Accept thread started.
E/ConnectivityService( 3514): updateNetworkInfo()
D/ConnectivityService( 3514): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/CSLegacyTypeTracker( 3514): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3514): mCursor = null
,E/WifiStateMachine( 3514): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL( 3514): callSECStringApiVoid - ID [215]
E/WifiNative-HAL( 3514): invaild command id : 215
,D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3514): mCursor = null
,D/WifiNative-HAL( 3514): p2pGetDeviceAddress
,D/WifiNative-HAL( 3514): p2pGetDeviceAddress returning 92:b6:86:43:73:1c
,D/NearbySettings( 7620): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 7620): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 7620): MountReceiver.onReceive - Create mPrefHandler
D/WifiP2pService( 3514): DeviceAddress: 92:73:1c
,D/NearbySettings( 7620): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDisplayController( 3514): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note4-1
D/WifiDisplayController( 3514):  deviceAddress: 92:b6:86:43:73:1c
D/WifiDisplayController( 3514):  primary type: 10-0050F204-5
D/WifiDisplayController( 3514):  secondary type: null
D/WifiDisplayController( 3514):  wps: 0
D/WifiDisplayController( 3514):  grpcapab: 0
D/WifiDisplayController( 3514):  devcapab: 0
D/WifiDisplayController( 3514):  status: 3
D/WifiDisplayController( 3514):  wfdInfo: null
D/WifiDisplayController( 3514):  groupownerAddress: null
D/WifiDisplayController( 3514):  GOdeviceName: null
D/WifiDisplayController( 3514):  interfaceAddress: 
D/WifiDisplayController( 3514):  SConnectInfo : null
V/NearbySettings( 7620): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 7620): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3514): New client listening to asynchronous messages
,I/NearbySettings( 7620): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7620): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7620): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7620): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/WifiP2pService( 3514): sending p2p persistent groups changed broadcast
,E/Zygote  (10890): MountEmulatedStorage()
E/Zygote  (10890): v2
I/libpersona(10890): KNOX_SDCARD checking this for 10079
I/libpersona(10890): KNOX_SDCARD not a persona
,I/SELinux (10890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=10890 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (10890): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiP2pService( 3514): InactiveState
D/WifiP2pService( 3514): InactiveState{ what=143376 }
D/WifiP2pService( 3514): P2pEnabledState{ what=143376 }
,I/wpa_supplicant(10711): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService( 3514): updateNetworkInfo()
,D/WifiP2pService( 3514): InactiveState{ what=143376 }
D/WifiP2pService( 3514): P2pEnabledState{ what=143376 }
,D/TimaKeyStoreProvider(10890): TimaSignature is unavailable
,D/ActivityThread(10890): Added TimaKeyStore provider
,D/ResourcesManager(10890): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(10890): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 3514): Killing 9983:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,I/wpa_supplicant(10711): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant(10711): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant(10711): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant(10711): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant(10711): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3514): [1,453,396,607,800 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3514): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2547de75 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3514): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3514): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3514): mCursor = null
,I/wpa_supplicant(10711): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant(10711): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3514): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3514): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3514): setDetailed state send new extra info"NG700"
I/wpa_supplicant(10711): Associated with C0.AA.48
,D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3514): mCursor = null
,I/wpa_supplicant(10711): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant(10711): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3514): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3514): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3514): mCursor = null
,I/wpa_supplicant(10711): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant(10711): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant(10711): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3514): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3514): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant(10711): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(10711): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant(10711): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant(10711): Blacklist: Clear (temp) 
I/wpa_supplicant(10711): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3514): Network connection established
,D/WifiNative-HAL( 3514): callSECApiVoid - ID [50]
E/WifiStateMachine( 3514): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3514): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3514): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3514): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine( 3514): L2ConnectedState "NG700" nid=0
D/ConnectivityService( 3514): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 3514): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore( 3514): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService( 3514): updateNetworkInfo()
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 6337): Starting #4
I/Hs20UtilService( 6337): Message received 5007
,D/NearbySettings( 7620): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 7620): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 7620): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 7620): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7620): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7620): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7620): MountReceiver.mPrefHandler - 7002
,E/WifiStateMachine( 3514): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
,E/WifiStateMachine( 3514): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3514): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3514): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SignOutReceiver( 8845): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2851): Setting iface cfg
,E/WifiStateMachine( 3514): Start Dhcp Watchdog 1
,D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3514): mCursor = null
,E/WifiStateMachine( 3514): Force RSSI Broadcast 1/3
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3514): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3514): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3514): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3514): do suspend false
,D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3514): InactiveState{ what=143375 }
D/SecContentProvider2( 3514): mCursor = null
D/WifiP2pService( 3514): P2pEnabledState{ what=143375 }
,I/jxcore-log(10626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(10626): 
,E/dhcpcd  (10908): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (10908): version 5.5.6 starting
,E/dhcpcd  (10908): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (10908): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (10908): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (10908): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (10908): bssid match
,I/dhcpcd  (10908): wlan0: rebinding lease of 192.168.1.124
,I/jxcore-log(10626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(10626): 
,I/jxcore-log(10626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(10626): 
,I/jxcore-log(10626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(10626): 
,I/jxcore-log(10626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(10626): 
,I/jxcore-log(10626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(10626): 
,I/jxcore-log(10626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(10626): 
,I/jxcore-log(10626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(10626): 
,I/jxcore-log(10626): Test app app.js loaded
I/jxcore-log(10626): 
,I/chromium(10626): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine( 3514): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3514): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/dhcpcd  (10908): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (10908): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3514): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3514): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10626): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(10626): BLE advertisement is supported
I/jxcore-log(10626): 
,E/WifiStateMachine( 3514): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3514): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3514): do suspend true
,D/WifiP2pService( 3514): InactiveState{ what=143375 }
D/WifiP2pService( 3514): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3514): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3514): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3514): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3514): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
D/WifiStateMachine( 3514): Not connected state, yet.
E/WifiStateMachine( 3514): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3514): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3514): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3514): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3514): callSECApiInt - ID [210]
,E/WifiStateMachine( 3514): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3514): updateNetworkInfo(),
,D/ConnectivityService( 3514): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
D/ConnectivityService( 3514): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 3514): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3514): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3514): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3514): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3514): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3514): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3514): Now, connected state.
E/WifiStateMachine( 3514): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3514): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3514): evaluateTrafficStatsPolling
,I/Hs20UtilService( 6337): Starting #5
,I/Hs20UtilService( 6337): Message received 5007
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3514): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3514): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3514): callSECApiVoid - ID [212]
,D/ConnectivityService( 3514): Adding Route [fe80::/64 -> :: wlan0] to network 502
,E/WifiStateMachine( 3514): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService( 3514): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,I/WifiStateMachine( 3514): REQUEST_POWER_SAVE_ON
,D/ConnectivityService( 3514): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
E/ConnectivityService( 3514): Unexpected mtu value: 0, wlan0
,D/StatusBar.NetworkController( 3690): applyOpen
,V/        ( 2851): QcRouteController
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/NearbySettings( 7620): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 7620): MountReceiver.onReceive - Keep current state
,V/        ( 2851): QcRouteController
,I/SignOutReceiver( 8845): NETWORK_STATE_CHANGED_ACTION
W/NetworkManagementService( 3514): route cmd failed: 
W/NetworkManagementService( 3514): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '51 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 51 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3514): '
W/NetworkManagementService( 3514): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3514): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3514): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3514): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3514): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3514): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3514): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3514): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6313)
W/NetworkManagementService( 3514): 	at com.android.server.ConnectivityService.access$2700(ConnectivityService.java:231)
W/NetworkManagementService( 3514): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2449)
W/NetworkManagementService( 3514): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3514): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3514): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/        ( 2851): QcRouteController
I/Hs20UtilService( 6337): Starting #6
V/        ( 2851): QcRouteController
I/Hs20UtilService( 6337): Message received 5007
D/NearbySettings( 7620): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 7620): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 7620): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 7620): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7620): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7620): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7620): MountReceiver.mPrefHandler - 7002
V/        ( 2851): QcRouteController
I/SignOutReceiver( 8845): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2851): QcRouteController
,I/Hs20UtilService( 6337): Starting #7
,D/NearbySettings( 7620): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 6337): Message received 5007
,V/        ( 2851): QcRouteController
I/NearbySettings( 7620): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3514): callSECApi what=220
D/WifiStateMachine( 3514): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        ( 2851): QcRouteController
,V/        ( 2851): QcRouteController
,V/        ( 2851): QcRouteController
,I/SignOutReceiver( 8845): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2851): QcRouteController
,I/SurfaceFlinger( 2855): id=13 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3514): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3514
D/ConnectivityService( 3514): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService( 3514): LTETest block dns file not exists
,D/ConnectivityService( 3514): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,E/ConnectivityService( 3514): updateNetworkInfo()
E/ConnectivityService( 3514): updateNetworkInfo()
,D/ConnectivityService( 3514): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3514): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): Checking http://clients3.google.com/generate_204 on "NG700"
D/mali_winsys( 3690): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/ConnectivityService( 3514): rematching NetworkAgentInfo [WIFI () - 502]
,I/System.out( 3514): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3514): (HTTPLog)-Static: isShipBuild true
I/System.out( 3514): (HTTPLog)-Thread-187-90324901: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3514): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2851): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2851): getNetworkForDns: using netid 502 for uid 1000
,D/ConnectivityService( 3514):    accepting network in place of null
,D/ConnectivityService( 3514): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/TelephonyNetworkFactory( 3978): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3514): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3514): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService( 3514): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3514): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/EntConnectivity( 3514): Not allowed due to - mEnabled false
D/ConnectivityService( 3514): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 7834): CM callback handler got msg 524290
,W/ProcessCpuTracker( 3514): Skipping unknown process pid 10976
W/ProcessCpuTracker( 3514): Skipping unknown process pid 10977
,D/Tethering( 3514): MasterInitialState.processMessage what=3
D/SmartBondingService( 3514): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3514): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3514): forceRefresh() from cache miss
,V/NetworkStats( 3514): updateIfacesLocked()
V/NetworkStats( 3514): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3514): UpdateStatsForKnox
I/System.out( 3514): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SmartBondingService( 3514): getNetworkEnabled : wifi : true mobile : false
,D/EnterpriseController( 2851): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2851): getNetworkForDns: using netid 502 for uid 1000
,V/NetworkStats( 3514): performPollLocked() took 7ms
,D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3690): updateDataNetType()
D/StatusBar.NetworkController( 3690): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3690): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3690): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 17:16:51 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453396611018], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453396611001]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): Validated
D/ConnectivityService( 3514): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3514): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3514): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService( 3514): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524290
,D/ConnectivityService( 3514): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 7834): CM callback handler got msg 524290
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
,D/NtpTrustedTime( 3514): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1453396611595 mCachedNtpElapsedRealtime : 144073 mCachedNtpCertainty : 13
,D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
V/NetworkStats( 3514): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
,D/SSRM:n  ( 3514): SIOP:: AP = 280, PST = 272, CUR = 50
,I/PowerManagerService( 3514): [PWL] Off : 50s ago
I/PowerManagerService( 3514): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3514): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3514): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=10696, ws=null) (elapsedTime=4424)
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:-106, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:78
,D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3514): Plugged
,D/BatteryService( 3514): stay LED for fully charged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/ConnectivityService( 3514): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SmartBondingService( 3514): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3514): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3514): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/SmartBondingService( 3514): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
,D/SmartBondingService( 3514): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
,D/AlarmManagerService( 3514): Setting time of day to sec=1453396611
D/AlarmManagerService( 3514): Trying to open a file
,D/AlarmManagerService( 3514): File Open Success
,D/AlarmManagerService( 3514): File Close Success
I/AlarmManagerService( 3514): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 3514): waitForAlarm result :65536
,I/DBG_DM  ( 5894): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 5894): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 5894): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 5894): [IlIIlIIlIllllIlllIII(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 5894): [IlIlllIlllllIlIllllI(403/llllllIllIlIlllIIlIl)] Check completed.
,D/WifiStateMachine( 3514): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_SET
,D/SettingsProvider( 3514): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 10060
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
I/DBG_DM  ( 5894): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 5894): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/Settings( 3514): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardEffectViewUtil( 3690): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3690): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3690): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3690): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3690): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{25d929d8 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
I/DBG_DM  ( 5894): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
D/VisualEffectParticleEffect( 3690): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{3d46d131 V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3690): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{25d929d8 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3690): clearEffect
D/WallpaperWidget( 3690): setLockScreenWallpaper()
,I/DBG_DM  ( 5894): [IIlIIIlllllIIlIIIlII(72/llllIIIllIlIIIIllllI)] 
,D/KeyguardEffectViewUtil( 3690): getCurrentWallpaper() mWallpaperPath :null
,W/SEC_DRM_PLUGIN_Playready( 2859): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1453396611 after conversion: 1453396611
W/SEC_DRM_PLUGIN_Playready( 2859): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1453396612 after conversion: 1453396612
,I/DBG_DM  ( 5894): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 5894): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
,I/DBG_DM  ( 5894): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 5894): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,E/Zygote  (11005): MountEmulatedStorage()
E/Zygote  (11005): v2
I/libpersona(11005): KNOX_SDCARD checking this for 1000
I/libpersona(11005): KNOX_SDCARD not a persona
,I/SELinux (11005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/DBG_DM  ( 5894): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,I/SELinux (11005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11005 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11005): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5894): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
,I/DBG_DM  ( 5894): [IlIIlIIlIllllIlllIII(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 5894): [IlIIlIIlIllllIlllIII(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 5894): [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 5894): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 5894): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 5894): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(502/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11005): TimaSignature is unavailable
,E/Zygote  (11022): MountEmulatedStorage()
E/Zygote  (11022): v2
I/libpersona(11022): KNOX_SDCARD checking this for 10090
I/libpersona(11022): KNOX_SDCARD not a persona
,D/ActivityThread(11005): Added TimaKeyStore provider
I/SELinux (11022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=11022 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11022): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5894): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5894): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,D/TimaKeyStoreProvider(11022): TimaSignature is unavailable
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(11022): Added TimaKeyStore provider
,I/DBG_DM  ( 5894): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 5894): [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
I/DBG_DM  ( 5894): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 5894): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 5894): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@571d17b
,D/ResourcesManager(11005): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/ActivityManager( 3514): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=11038 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/Zygote  (11038): MountEmulatedStorage()
E/Zygote  (11038): v2
I/libpersona(11038): KNOX_SDCARD checking this for 10050
I/libpersona(11038): KNOX_SDCARD not a persona
,I/SELinux (11038): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11038): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11038): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/GpsLocationProvider( 3514): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 5894): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,I/PCWCLIENTTRACE_LOG(11005): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11005): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11005): new DMDBOpenHelper instance
,D/ResourcesManager(11022): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/PCWCLIENTTRACE_PushUtil(11005): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11005): sales region : global
I/PCWCLIENTTRACE_PushUtil(11005): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11005): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11054): MountEmulatedStorage()
I/libpersona(11054): KNOX_SDCARD checking this for 10135
E/Zygote  (11054): v2
I/libpersona(11054): KNOX_SDCARD not a persona
,I/SELinux (11054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11054 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11054): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11038): TimaSignature is unavailable
,D/ActivityThread(11038): Added TimaKeyStore provider
,E/ActivityThread( 7834): Failed to find provider info for com.android.contacts.metadata
,I/KeyguardEffectViewUtil( 3690): set current wallpaper info
,D/SettingsProvider( 3514): name = keyguard_current_wallpaper_type
,D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 10060
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3514): ret = -1
,D/TimaKeyStoreProvider(11054): TimaSignature is unavailable
,D/ActivityThread(11054): Added TimaKeyStore provider
,D/ResourcesManager(11038): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/SyncManager( 3514): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 15764, reason: UserStart, SyncResult: databaseError: true stats []
,W/ResourcesManager(11038): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/SyncManager( 3514): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 175137, reason: UserStart
W/ResourcesManager(11038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11038): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11038): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11038): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(11038): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(11038): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11038): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/DBG_DM  ( 5894): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/VacuumService( 4252): Vacuum at: now=1453396612331 tag=VacuumService
,I/DBG_DM  ( 5894): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,W/ResourceType( 4948): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4948): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager(11054): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/SecContentProvider2( 3514): uri = 14 selection = getSealedState
D/SecContentProvider2( 3514): mCursor = null
,V/GLSActivity( 4252): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ApplicationPolicy( 3514): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3514): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 3514): showStatusBarByNotification() mOpenByNotification=false
,D/ResourcesManager( 3690): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,I/DBG_DM  ( 5894): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 5894): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3514): name = keyguard_current_wallpaper_file_path
,D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 10060
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,D/SecContentProvider2( 3514): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3514): mCursor = null
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,I/DBG_DM  ( 5894): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 5894): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 5894): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
D/SettingsProvider( 3514): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 10060
,D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,W/BackupManagerService( 3514): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/StatusBar-DoNotDistrub( 3690): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 3690): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/MusicStore(11054): Database version: 104
,D/StatusBar-DoNotDistrub( 3690): sendBroadcast android.intent.action.DORMANT_MODE_OFF
V/AudioPolicyManager( 2860): getOutputsForDevice device 0002 -> 0002
I/AudioService( 3514): getStreamVolume 5 index 110
,D/StatusBar-DoNotDistrub( 3690): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService( 3514): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,I/System.out( 6599): Thread-662(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6599): Thread-662(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6599): Thread-662(ApacheHTTPLog):isShipBuild true
I/System.out( 6599): Thread-662(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/EnterpriseController( 2851): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2851): getNetworkForDns: using netid 502 for uid 10202
,D/PackageManager( 3514): findPreferredActivity: No PreferredActivities set
,D/NearbySource(11038): Nearby Source Create!
,D/NearbyContext(11038): Nearby Context Create!
,D/ResourcesManager(11054): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/DelayedSyncController(11022): Delaying sync.
,W/ResourcesManager(11054): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11054): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/KnoxNotification( 3690): ----- inflateViews : modified publicViewLocal -----
,V/GLSActivity( 4252): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4252): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/KnoxNotification( 3690): ----- inflateViews : modified KnoxViewLocal -----
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
D/PersonaManager( 3690): PersonaID is invalid or persona doesn't exists. : 0
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
D/PhoneStatusBar( 3690): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@1ae599a8
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
W/ContextImpl(11038): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/SLinkSource(11038): Samsung link source created
,I/PhoneStatusBar( 3690): Icon Only
,I/StatusBar( 3690): Icon Only
,D/PanelView( 3690): There is/are notification(s) 
D/PanelView( 3690): There is/are notification(s) 
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
,E/Auth.Api.Credentials( 7834): [CredentialSyncAdapter] Unknown sync event.
,V/JNIHelp (11054): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider(11038): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/KeyguardEffectViewUtil( 3690): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3690): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3690): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3690): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3690): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{25d929d8 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3690): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{3d46d131 V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3690): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{25d929d8 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3690): clearEffect
,V/GLSActivity( 4252): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityThread(11054): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11054): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d64fff1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11054): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11054): GMSCore installation verified
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/ActivityManager( 3514): Killing 10002:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/ContactProvider(11038): getAllContactInfoList End
,I/syncContacts(11038): thread: 1468, sync time = 82
,I/ConfigStore(11054): Config Database version: 1
,D/PicasaService(11038): start picasa sync
,D/PicasaService(11038): end picasa sync
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11054): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11054): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11054): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3514): getStreamVolume 3 index 0
,I/MediaRouter(11054): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/DelayedSyncController(11022): Delaying sync.
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor(11054): type=WIFI subType= reason=null isConnected=true
,E/Zygote  (11105): MountEmulatedStorage()
E/Zygote  (11105): v2
I/libpersona(11105): KNOX_SDCARD checking this for 10002
I/libpersona(11105): KNOX_SDCARD not a persona
,I/SELinux (11105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11105 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11105): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11054): type=WIFI subType= reason=null isConnected=true
,D/TimaKeyStoreProvider(11105): TimaSignature is unavailable
,D/ActivityThread(11105): Added TimaKeyStore provider
,I/ActivityManager( 3514): Killing 10024:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,D/ResourcesManager(11105): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/art     (10219): Attempt to remove local handle scope entry from IRT, ignoring
,W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  (10908): wlan0: sending IPv6 Router Solicitation
,I/ActivityManager( 3514): Killing 10040:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController( 2851): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2851): getNetworkForDns: using netid 502 for uid 10147
,E/Zygote  (11132): MountEmulatedStorage()
E/Zygote  (11132): v2
I/libpersona(11132): KNOX_SDCARD checking this for 1000
I/libpersona(11132): KNOX_SDCARD not a persona
,I/SELinux (11132): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11132): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3514): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11132 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11132): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11132): TimaSignature is unavailable
,D/ActivityThread(11132): Added TimaKeyStore provider
,D/ResourcesManager(11132): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/art     ( 3514): Explicit concurrent mark sweep GC freed 83650(4MB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 48MB/64MB, paused 2.013ms total 159.779ms
,I/DIAGMON_AGENT(11132): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11132): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11132): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11132): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11132): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/ActivityManager( 3514): Killing 10082:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,I/qtaguid ( 6599): Tagging socket 26 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6599, getuid(): 10202
,D/EnterpriseController( 2851): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2851): getNetworkForDns: using netid 502 for uid 10147
,E/Zygote  (11150): MountEmulatedStorage()
,E/Zygote  (11150): v2
I/libpersona(11150): KNOX_SDCARD checking this for 10012
I/libpersona(11150): KNOX_SDCARD not a persona
,I/SELinux (11150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3514): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11150 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11150): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11150): TimaSignature is unavailable
,D/ActivityThread(11150): Added TimaKeyStore provider
,D/ResourcesManager(11150): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3514): Killing 10131:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/FOTA_Client(11150): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11150): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/qtaguid ( 6599): Untagging socket 26
,I/System.out( 6599): Thread-662 calls detatch()
,I/FOTA_Client(11150): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11166): MountEmulatedStorage()
E/Zygote  (11166): v2
I/libpersona(11166): KNOX_SDCARD checking this for 10021
I/libpersona(11166): KNOX_SDCARD not a persona
,I/SELinux (11166): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11166): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3514): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11166 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,E/SELinux (11166): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Killing 10151:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 857us total 24.500ms
,D/TimaKeyStoreProvider(11166): TimaSignature is unavailable
,D/ActivityThread(11166): Added TimaKeyStore provider
,D/ResourcesManager(11166): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 798us total 17.858ms
,I/KLMS-2.4.521: (11166): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 21 18:16:53 GMT+01:00 2016
,I/KLMS-2.4.521: (11166): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11166): KLMSIntentService(): onCreate()
I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.168ms total 20.516ms
,I/KLMS-2.4.521: (11166): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11166): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11166): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11166): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11166): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11166): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11166): NetworkChangeOperations(): uploadRequestLog().START 
,E/Zygote  (11182): MountEmulatedStorage()
I/libpersona(11182): KNOX_SDCARD checking this for 10038
E/Zygote  (11182): v2
I/libpersona(11182): KNOX_SDCARD not a persona
,D/btif_config_util(10696): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/SELinux (11182): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11182): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11182): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11182 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11166): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11166): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11166): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider(11182): TimaSignature is unavailable
,D/ActivityThread(11182): Added TimaKeyStore provider
,I/ActivityManager( 3514): Killing 10167:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/ResourcesManager(11182): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11182): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11202): MountEmulatedStorage()
E/Zygote  (11202): v2
I/libpersona(11202): KNOX_SDCARD checking this for 1000
I/libpersona(11202): KNOX_SDCARD not a persona
,I/SELinux (11202): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11202): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11202 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11202): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3514): Killing 10182:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11202): TimaSignature is unavailable
,D/ActivityThread(11202): Added TimaKeyStore provider
,D/ResourcesManager(11202): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11222): MountEmulatedStorage()
I/libpersona(11222): KNOX_SDCARD checking this for 10039
E/Zygote  (11222): v2
I/libpersona(11222): KNOX_SDCARD not a persona
,I/SELinux (11222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11222): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11222 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3514): Killing 10279:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11222): TimaSignature is unavailable
,D/ActivityThread(11222): Added TimaKeyStore provider
,D/ResourcesManager(11222): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(11222): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11222): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService(11222): PushLog.txt file is not deleted.
D/SPPClientService(11222): PushLog.txt file is not deleted.
D/SPPClientService(11222): ============PushLog. stop!
,E/SPPClientService(11222): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11240): MountEmulatedStorage()
E/Zygote  (11240): v2
I/libpersona(11240): KNOX_SDCARD checking this for 10045
I/libpersona(11240): KNOX_SDCARD not a persona
,I/SELinux (11240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3514): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=11240 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Killing 10296:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
E/SELinux (11240): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11240): TimaSignature is unavailable
,D/ActivityThread(11240): Added TimaKeyStore provider
,D/ResourcesManager(11240): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/WifiStateMachine( 3514): updateConfiguredNetworkExpiration - currTime: 1453396613974
D/WifiStateMachine( 3514): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,I/SA      (11240): [SSP] onCreated
,I/SA      (11240): [TPM] There is no property file
,I/SA      (11240): [SCU] isHaveSA() - false
,I/SA      (11240): [TPM] getModelProperty : null
I/SA      (11240): [TPM] getCSCProperty : null
,I/SA      (11240): [DM] init START
,I/SA      (11240): [DM] This device is not a Vodafone
,I/SA      (11240): checkReactivationActive for LOLLIPOP
I/SA      (11240): checkReactivationActive for reactiveActive
I/SA      (11240): setSupportRL : true
,I/SA      (11240): [SCU] isHaveSA() - false
I/SA      (11240): support phone number id : false
,I/SA      (11240): [DM] init END
I/SA      (11240): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11240): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11240): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11240): [SLFUCHKMGR] constructor called
,I/SA      (11240): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11240): [OR] == isSIMCardReady false ==
,I/SA      (11240): [SCU] == networkStateCheck == true
I/SA      (11240): [DM] getCountryCodeFromCSC : PL
,I/SA      (11240): isChinaCountryCode : false
I/SA      (11240): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11240): [OR] == networkStateCheck true ==
,I/SA      (11240): [OR] GetMyCountryZoneTask
,I/SA      (11240): [OR] onReceive END
,I/SA      (11240): [SRS] prepareGetMyCountryZone
,I/ActivityManager( 3514): Killing 10312:com.facebook.system/u0a10 (adj 13): bgCount ##31
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11240): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11240): [SSP] query invoked
,I/SA      (11240): [TPMU] GetMccFromDB : null
I/SA      (11240): [SCU] getMccFromPreferece mcc = 260
I/SA      (11240): [TPM] isNoProxy(default) : true
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11262): MountEmulatedStorage()
,E/Zygote  (11262): v2
I/libpersona(11262): KNOX_SDCARD checking this for 10067
I/libpersona(11262): KNOX_SDCARD not a persona
,I/SELinux (11262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11262): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11262 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11262): TimaSignature is unavailable
,D/ActivityThread(11262): Added TimaKeyStore provider
,D/ResourcesManager(11262): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,D/PackageManager( 3514): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/sCloudBackupApp(11262): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11262): Other Intent
,I/ActivityManager( 3514): Killing 10419:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,D/accuweather( 5233): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5233): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5233): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5233): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5233): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5233): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5233): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11279): MountEmulatedStorage()
E/Zygote  (11279): v2
I/libpersona(11279): KNOX_SDCARD checking this for 1000
I/libpersona(11279): KNOX_SDCARD not a persona
,I/SELinux (11279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3514): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11279 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11279): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11279): TimaSignature is unavailable
,D/ActivityThread(11279): Added TimaKeyStore provider
,E/AclDataUtils(10219): Circle ID not found for type: 9
,D/ResourcesManager(11279): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11279): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(11279): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(11279): premStatus:2
,I/KnoxUsageLogPro(11279): isEulaShown : false
I/KnoxUsageLogPro(11279): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(10719): cancelUpdateWallpaper
I/ActivityManager( 3514): Killing 10455:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/ActivityManager( 3514): Killing 10116:com.android.providers.calendar/u0a47 (adj 13): bgCount ##32
,D/KeyguardWallpaperUpdator(10719): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10719): stopCheckCategoryVersion
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11294): MountEmulatedStorage()
I/libpersona(11294): KNOX_SDCARD checking this for 10136
E/Zygote  (11294): v2
I/libpersona(11294): KNOX_SDCARD not a persona
,I/SELinux (11294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11294): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11294 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11294): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Killing 10470:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11294): TimaSignature is unavailable
,D/ActivityThread(11294): Added TimaKeyStore provider
,D/ResourcesManager(11294): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/WifiStateMachine( 3514): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3514): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11294): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11294): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11294): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11294): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/SA      (11240): [RC New] Execute method=[GET] start
,I/SA      (11240): [RC New] Security=[true]
,I/System.out(11240): Thread-1515(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11240): Thread-1515(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11240): Thread-1515(ApacheHTTPLog):isShipBuild true
I/System.out(11240): Thread-1515(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController( 2851): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2851): getNetworkForDns: using netid 502 for uid 10045
,I/WebViewFactory(11294): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11294): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11294): Loading: webviewchromium
,I/LibraryLoader(11294): Time to load native libraries: 2 ms (timestamps 7155-7157)
I/LibraryLoader(11294): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11294): Binding Chromium to main looper Looper (main, tid 1) {3272f4f3}
,I/LibraryLoader(11294): Expected native library version number "",actual native library version number ""
I/chromium(11294): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11294): Initializing chromium process, renderers=0
,W/art     (11294): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11294): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid(11294): Requires BLUETOOTH permission
I/chromium(11294): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(11294): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(11294): Starting up...
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11363): MountEmulatedStorage()
E/Zygote  (11363): v2
I/libpersona(11363): KNOX_SDCARD checking this for 10150
I/libpersona(11363): KNOX_SDCARD not a persona
,I/SELinux (11363): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3514): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=11363 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux (11363): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11363): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Killing 9741:com.android.defcontainer/u0a5 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11363): TimaSignature is unavailable
,D/ActivityThread(11363): Added TimaKeyStore provider
,D/ResourcesManager(11363): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(11363): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11363): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(11363): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/SurfaceFlinger( 2855): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger( 2855): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 3514): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3514) eventTime = 147332
,D/PowerManagerService( 3514): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3514 (0x0)
D/PowerManagerService( 3514): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3514, ws=WorkSource{10060}) (elapsedTime=3487)
,D/OpenGLRenderer( 5894): Render dirty regions requested: true
,I/SurfaceFlinger( 2855): id=14 createSurf (1x1),1 flag=4, Uoast
,D/QuickConnect(11363): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(11363): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(11363): PeriphStartReceiver.onReceive - no need to start
,D/PowerManagerService( 3514): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3514
,D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,I/OpenGLRenderer( 5894): Initialized EGL, version 1.4
,I/ActivityManager( 3514): Killing 10365:com.android.vending/u0a31 (adj 13): bgCount ##31
,I/OpenGLRenderer( 5894): HWUI protection enabled for context ,  &this =0xaf722088 ,&mEglDisplay = 1 , &mEglConfig = -1351229168 
,D/OpenGLRenderer( 5894): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 5894): Enabling debug mode 0
,D/mali_winsys( 5894): new_window_surface returns 0x3000,  [616x201]-format:1
,I/iu.SyncManager( 7834): SYNC; picasa accounts
,D/NetworkLogImpl( 7834): Loaded NetworkSpeedPredictor
,I/iu.Environment( 7834): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 7834): num queued entries: 0
,I/iu.UploadsManager( 7834): num updated entries: 0
,I/iu.SyncManager( 7834): NEXT; no task
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController( 2851): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2851): getNetworkForDns: using netid 502 for uid 10014
,E/Zygote  (11399): MountEmulatedStorage()
E/Zygote  (11399): v2
I/libpersona(11399): KNOX_SDCARD checking this for 10013
I/libpersona(11399): KNOX_SDCARD not a persona
,I/SELinux (11399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=11399 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11399): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11399): TimaSignature is unavailable
,D/ActivityThread(11399): Added TimaKeyStore provider
,D/ResourcesManager(11399): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/ResourcesManager( 4252): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/WaitQueueForNetworkActivate(11399): notifyNetworkActivated
,I/GCM     ( 4252): GCM config loaded
,W/ContextImpl(11399): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3514): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/AlarmManager( 3514):  next == MAX_VALUE
,V/AlarmManager( 3514):  next == MAX_VALUE
,D/hcjo    (11399): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(11399): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(11399): exit::IDLE
D/InitializeManagerStateMachine(11399): entry::NETWORK_CHECK
,I/SA      (11240): [RC New] [v2liruge] api execute + 653
,I/SA      (11240): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11240): AsyncTask #1 calls detatch()
,D/InitializeManagerStateMachine(11399): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(11399): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(11399): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11399): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(11399): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11399): entry::SUCCESS
D/hcjo    (11399): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/FOTA_Client(11150): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/hcjo    (11399): AutoUpdateTriggerManager:IDLE:setInterval:345600000
I/splitIntent( 3514): Split this intent : android.intent.action.TIME_SET !!   mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=17 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 3514): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,I/SA      (11240): [TPMU] getNetworkMcc : 
,I/SA      (11240): [SCU] saveMccToPreferece Start
I/SA      (11240): [SCU] RegionMCC : 260
I/SA      (11240): [SSP] query invoked
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,I/SA      (11240): [TPMU] GetMccFromDB : null
I/SA      (11240): [SCU] getMccFromPreferece mcc = 260
I/SA      (11240): [SCU] saveMccToPreferece End
,I/SA      (11240): [RC New] executeRequest [v2liruge] end. 693
I/SA      (11240): [RC New] Execute end
,I/SA      (11240): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11240): [OR] GetMyCountryZoneTask Success
I/FOTA_Client(11150): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,E/Zygote  (11425): MountEmulatedStorage()
E/Zygote  (11425): v2
I/libpersona(11425): KNOX_SDCARD checking this for 10052
I/libpersona(11425): KNOX_SDCARD not a persona
,I/SELinux (11425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=11425 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/SELinux (11425): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/hcjo    (11399): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (11399): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(11399): exit::SUCCESS
D/InitializeManagerStateMachine(11399): entry::IDLE
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11166): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Jan 21 18:16:55 GMT+01:00 2016
,E/Zygote  (11440): MountEmulatedStorage()
E/Zygote  (11440): v2
I/libpersona(11440): KNOX_SDCARD checking this for 10164
I/libpersona(11440): KNOX_SDCARD not a persona
,I/SELinux (11440): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/TimaKeyStoreProvider(11425): TimaSignature is unavailable
,I/SELinux (11440): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ActivityThread(11425): Added TimaKeyStore provider
,E/SELinux (11440): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=11440 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8749(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 916us total 22.160ms
,I/KLMS-2.4.521: (11166): KLMSAbstractReciever(): onReceive().END.
,D/TimaKeyStoreProvider(11440): TimaSignature is unavailable
,D/ActivityThread(11440): Added TimaKeyStore provider
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.4.521: (11166): KLMSIntentService(): onCreate()
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11166): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 623us total 20.520ms
,I/KLMS-2.4.521: (11166): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11166): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,D/ResourcesManager(11425): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/KLMS-2.4.521: (11166): KLMSIntentService(): TIME_CHANGED
,D/ResourcesManager(11440): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/KLMS-2.4.521: (11166): StateImplV2(): dateTimeChanged().START : Thu Jan 21 18:16:55 GMT+01:00 2016
D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 3777): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3777): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
D/comsamsunglog( 3777): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3777): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ResourcesManager(11425): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(11425): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11425): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11425): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11440): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11425): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(11425): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager(11440): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11440): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(11440): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 437us total 16.671ms
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/KLMS-2.4.521: (11166): StateImplV2(): dateTimeChanged().END
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 3777): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,E/Zygote  (11456): MountEmulatedStorage()
E/Zygote  (11456): v2
I/libpersona(11456): KNOX_SDCARD checking this for 10036
I/libpersona(11456): KNOX_SDCARD not a persona
,I/SELinux (11456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/com.cigna.mobile.coach.CoachBroadcastReceiver: pid=11456 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/SELinux (11456): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11166): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3514): Killing 10800:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11456): TimaSignature is unavailable
,D/ActivityThread(11456): Added TimaKeyStore provider
,D/comdaemonstockapp( 3777): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 3777): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/ResourcesManager(11456): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/Mms/MmsApp(11425): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(11425): init before art
,D/Mms/ArtClassLoader(11425): init [DONE] art
,D/Mms/TelephonyPermission(11425): start operation mode monitor
,D/ResourcesManager(11425): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11425): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/TelephonyPermission(11425): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(11425): isDefault true
,D/Mms/MmsApp(11425): onCreate() com.android.mms
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsApp(11425): [start]    initCountryIso consume time = 38.97425
,D/CountryDetector( 3514): The first listener is added
,D/Mms/MmsApp(11425): [end]    initCountryIso consume time = 6.201584
D/Mms/MmsConfig(11425): [start]    MmsConfig.init() consume time = 0.075583
,E/Zygote  (11479): MountEmulatedStorage()
E/Zygote  (11479): v2
I/libpersona(11479): KNOX_SDCARD checking this for 10047
I/libpersona(11479): KNOX_SDCARD not a persona
,D/Mms/MmsConfig(11425): before partial update
,I/SELinux (11479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3514): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=11479 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11479): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/Mms/MmsConfig(11425): Load Resize quality : 80
,D/Mms/MmsConfig(11425):  enable multiwindow = true
,I/CheckinService( 7834): Checkin interval check for package: unspecified last checkin: 1453082886478 min interval config: 0 actual interval: 313729071
,D/SecurityLogAgent(10741): KnoxConfiguration : Current State = 0
,D/SecurityLogAgent(10741): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent(10741): StateMachine : Initialized
,D/SecurityLogAgent(10741): StateMachine : Changed Current State = 0
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/SecurityLogAgent(10741): StateMachine : Current State = 0
,E/Mms/MessageUtils(11425): setCountryDetector : update country detector info 
E/Mms/MessageUtils(11425): updateCountryIso : update country iso info 
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(11479): TimaSignature is unavailable
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(11479): Added TimaKeyStore provider
,D/Mms/PackageInfo(11425): com.sec.imsservice is not installed
D/Mms/MmsConfig(11425): [end]    init() consume time = 47.363958
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): checkState() : APP TYPE = Full
,D/Mms/Contact(11425): [start]    init() consume time = 1.248
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,E/Zygote  (11504): MountEmulatedStorage()
E/Zygote  (11504): v2
I/libpersona(11504): KNOX_SDCARD checking this for 10191
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
I/libpersona(11504): KNOX_SDCARD not a persona
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/SELinux (11504): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/SELinux (11504): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11504): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=11504 uid=10191 gids={50191, 9997} abi=armeabi-v7a
,D/Mms/Contact(11425): [end]    init consume time = 15.986042
,D/Mms/DraftCache(11425): [start]    rebuildCache consume time = 2.318667
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11504): TimaSignature is unavailable
,D/ActivityThread(11504): Added TimaKeyStore provider
,E/Zygote  (11521): MountEmulatedStorage()
E/Zygote  (11521): v2
I/libpersona(11521): KNOX_SDCARD checking this for 10019
I/libpersona(11521): KNOX_SDCARD not a persona
,I/SELinux (11521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11521): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=11521 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (11521): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/MmsSmsProvider( 3978): query,matched:13, calling pid = 11425
,D/Mms/TelephonyUtils(11425): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(11425): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11425): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11425): auto download without roaming -> true
D/Mms/DownloadManager(11425): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,E/Mms/TelephonyUtils(11425): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(11425): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(11425): roaming -> false (slotId = 1)
D/Mms/DownloadManager(11425): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(11425): auto download without roaming -> true
D/Mms/DownloadManager(11425): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(11425): auto download during roaming secondary -> false
D/Mms/DownloadManager(11425): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 3978): query,matched:12, calling pid = 11425
,D/Mms/MmsApp(11425): [end]    onCreate() consume time = 49.046333
,D/Mms/Conversation(11425): [start]    init() consume time = 0.959917
,D/TP/MmsSmsProvider( 3978): deleteConversation threadId: 9223372036854775807
D/TimaKeyStoreProvider(11521): TimaSignature is unavailable
,D/ActivityThread(11521): Added TimaKeyStore provider
,D/Mms/DownloadManager(11425): Service state changed: Bundle[mParcelledData.dataSize=692]
,D/Mms/DownloadManager(11425): roaming ------> false, mSimSlot = 0
D/TP/MmsSmsProvider( 3978): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,D/Mms/TelephonyUtils(11425): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(11425): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11425): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11425): auto download without roaming -> true
D/Mms/DownloadManager(11425): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(11425): mAutoDownload ------> true
,E/SQLiteLog( 3978): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3978): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3978): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3978): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3978): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3978): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 3978): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 3978): need read changed broadcast:false
,D/Mms/Conversation(11425): [end]    init consume time = 21.461833
D/Mms/MessagingNotification(11425): [start]    init() consume time = 0.096208
,I/art     ( 3514): Explicit concurrent mark sweep GC freed 26150(1677KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 48MB/64MB, paused 2.075ms total 143.962ms,
,D/TP/MmsSmsProvider( 3978): match 13:Elapsed time : 107.700 ms
D/TP/MmsSmsProvider( 3978): match 12:Elapsed time : 107.844 ms
,D/ResourcesManager(11479): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager(11479): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/ResourcesManager(11504): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,W/ResourcesManager(11504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11521): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/Zygote  (11537): MountEmulatedStorage()
I/libpersona(11537): KNOX_SDCARD checking this for 10069
E/Zygote  (11537): v2
I/libpersona(11537): KNOX_SDCARD not a persona
I/SELinux (11537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3514): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=11537 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/MessagingNotification(11425): [end]    init consume time = 137.488834
,D/Mms/Synchronizer(11425): [start]    doSync consume time = 3.800875
,D/Mms/SpamFilter(11425): [start]    SpamFilter fill() begin consume time = 1.846083
,D/Mms/DraftCache(11425): [end]    rebuildCache consume time = 5.239458
,D/TP/MmsSmsProvider( 3978): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 3978): syncDBData start
,D/TP/MmsSmsProvider( 3978): query,matched:0, calling pid = 11425
V/TP/MmsSmsProvider( 3978): getSimpleConversations entered.
,V/TP/MmsSmsProvider( 3978): syncDBData sms end
,V/TP/MmsSmsProvider( 3978): syncDBData mms end
D/TP/MmsSmsProvider( 3978): match 0:Elapsed time : 2.094 ms
,V/TP/MmsSmsProvider( 3978): syncDBData end
,D/TP/MmsSmsProvider( 3978): query,matched:400, calling pid = 11425
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/TimaKeyStoreProvider(11537): TimaSignature is unavailable
I/CalendarProvider2(11479): CalendarProvider2.onCreate() called
D/Mms/SpamFilter(11425): [end]    SpamFilter fill() finished consume time = 14.698375
,D/ActivityThread(11537): Added TimaKeyStore provider
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/com.sec.android.service.health.keyManager.KeyManager(11456): Current encrypted state : -1
,I/SecSQLiteOpenHelper(11456): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper(11456): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11456): Open platform.db in secure mode
D/SecSQLiteDatabase(11456): Android Version: 5.0.1
D/SecSQLiteDatabase(11456): Load library secsqlite.so for Android 5.0.1
,I/SecSQLiteDatabase(11456): openSecureDatabase...
E/Zygote  (11554): MountEmulatedStorage()
I/libpersona(11554): KNOX_SDCARD checking this for 10082
E/Zygote  (11554): v2
I/libpersona(11554): KNOX_SDCARD not a persona
,I/SELinux (11554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SecSQLiteDatabase(11456): private openSecureDatabase...
,I/SecSQLiteConnectionPool(11456): OpenSecure
I/SecSQLiteConnectionPool(11456): OpenSecure with password
I/SecSQLiteConnectionPool(11456): openSecureConnectionLocked
,I/SecSQLiteDatabase(11456): ...private openSecureDatabase
I/SecSQLiteDatabase(11456): ...openSecureDatabase
I/SELinux (11554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=11554 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/Mms/Synchronizer(11425): [end]    doSync consume time = 23.228459
E/SELinux (11554): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11537): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,D/TimaKeyStoreProvider(11554): TimaSignature is unavailable
,D/ActivityThread(11554): Added TimaKeyStore provider
,I/ActivityManager( 3514): Killing 10060:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/ResourcesManager(11554): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,E/SQLiteLog(11456): (26) statement aborts at 0: [PRAGMA user_version;] file is encrypted or is not a database
,E/SecDefaultDatabaseErrorHandler(11456): Corruption reported by sqlite on database: /data/data/com.sec.android.app.shealth/databases/platform.db
E/SecDefaultDatabaseErrorHandler(11456): backup the database file: /data/data/com.sec.android.app.shealth/databases/platform.db
,D/SecSQLiteOpenHelper(11456): ...getDatabaseLocked(b,b,pwd)
,I/ActivityManager( 3514): Killing 10438:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/BadgeProvider(11554): onCreate
,D/BadgeProvider(11554): DatabaseHelper
,I/PhenotypeConfigurator( 4252): Scheduling Phenotype for one-off execution 12313 seconds from now (1453396615941)
,I/SecureStorage(11521): [INFO]: SPID(0x00000000)Processing data
,I/ActivityManager( 3514): Killing 10890:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31
,I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Credentials: uid 10019, gid 10019, pid 11521
I/SecureStorage( 2920): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,D/accuweather( 5233): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 5233): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ Time Manager (11537): Time Difference not stored. TIME_DIFFERENCE
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/GetConfigurationSnapshotOperation( 4252): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/Zygote  (11580): MountEmulatedStorage()
E/Zygote  (11580): v2
I/libpersona(11580): KNOX_SDCARD checking this for 10094
I/libpersona(11580): KNOX_SDCARD not a persona
,I/SELinux (11580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11580): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=11580 uid=10094 gids={50094, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Mms/MessagingNotification(11425): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 3978): query,matched:26, calling pid = 11425
,D/TP/SmsProvider( 3978): match 26:Elapsed time : 2.435 ms
,D/TimaKeyStoreProvider(11580): TimaSignature is unavailable
,D/ActivityThread(11580): Added TimaKeyStore provider
,I/ActivityManager( 3514): Killing 7620:com.android.settings/1000 (adj 13): bgCount ##31
,I/PhenotypeFlagCommitter( 4252): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4252): Using platform SSLCertificateSocketFactory
,D/TP/MmsSmsProvider( 3978): query,matched:6, calling pid = 11425
,D/TP/MmsSmsProvider( 3978): match 6:Elapsed time : 2.378 ms
,D/ResourcesManager(11580): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,I/Mms/ReservationManager(11425): ReservationManager()
,I/Mms/ReservationManager(11425): resetAfterConnected()
,W/ResourcesManager(11580): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager(11580): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 3978): query,matched:7, calling pid = 11425
W/ResourcesManager(11580): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11580): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11580): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11580): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 3978): match 7:Elapsed time : 3.050 ms
,I/Mms/ReservationManager(11425): getReservedSendMessageCount(): retMessageCount=0
,D/WifiService( 3514): Client connection lost with reason: 4
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11599): MountEmulatedStorage()
,E/Zygote  (11599): v2
I/libpersona(11599): KNOX_SDCARD checking this for 10028
I/libpersona(11599): KNOX_SDCARD not a persona
,I/SELinux (11599): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11599): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=11599 uid=10028 gids={50028, 9997} abi=armeabi-v7a
,E/SELinux (11599): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Killing 8845:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11599): TimaSignature is unavailable
,D/ActivityThread(11599): Added TimaKeyStore provider
,D/ResourcesManager(11599): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
I/ActivityManager( 3514): Killing 10336:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
,W/ResourcesManager(11599): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/SettingsProvider( 3514): name = next_alarm_formatted
D/SettingsProvider( 3514): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3514): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3514): selectionArgs: false
D/SettingsProvider( 3514): selectionArgs: 10094
D/SecContentProvider( 3514): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3514): ret = -1
,D/LocationManagerService( 3514): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/OMACP   (11599): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp(11425): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/Mms/ArtClassLoader(11425): init before art
D/Mms/ArtClassLoader(11425): init [DONE] art
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
D/Mms/PerformanceUtils(11425): link cahcing start
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   (11599): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/Mms/PerformanceUtils(11425): link cahcing done
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11616): MountEmulatedStorage()
I/libpersona(11616): KNOX_SDCARD checking this for 10106
E/Zygote  (11616): v2
I/libpersona(11616): KNOX_SDCARD not a persona
,I/SELinux (11616): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11616): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11616 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (11616): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Killing 11005:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11616): TimaSignature is unavailable
,D/ActivityThread(11616): Added TimaKeyStore provider
,I/System.out( 4252): (HTTPLog)-Static: isSBSettingEnabled false
,D/ResourcesManager(11616): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/EnterpriseController( 2851): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2851): getNetworkForDns: using netid 502 for uid 10014
,D/elm:14491(11616): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491(11616): ELMEngine.ELMEngine( context ).
,D/elm:14491(11616): MDMBridge.setEnterpriseBridge()
,D/elm:14491(11616): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/elm:14491(11616): ElmAgentService : onCreate()
,D/elm:14491(11616): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14491(11616): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491(11616): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491(11616): ModuleBase.ModifySetAlarm()
D/elm:14491(11616): MDMBridge.getInstance()
D/elm:14491(11616): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (11634): MountEmulatedStorage()
E/Zygote  (11634): v2
I/libpersona(11634): KNOX_SDCARD checking this for 10163
I/libpersona(11634): KNOX_SDCARD not a persona
,I/SELinux (11634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3514): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=11634 uid=10163 gids={50163, 9997} abi=armeabi-v7a
,I/SELinux (11634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11634): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/System.out( 4252): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4252): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 4252, getuid(): 10014
,D/elm:14491(11616): ElmAgentService : onDestroy().
,I/ActivityManager( 3514): Killing 11038:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,W/ProcessCpuTracker( 3514): Skipping unknown process pid 11005
,D/TimaKeyStoreProvider(11634): TimaSignature is unavailable
,D/ActivityThread(11634): Added TimaKeyStore provider
,D/ResourcesManager(11634): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,I/qtaguid ( 4252): Tagging socket 82 with tag 1000120100000000{268440065,0} uid -1, pid: 4252, getuid(): 10014
,W/ResourcesManager(11634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11634): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/ActivityManager( 3514): Killing 11054:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,I/SecureStorage( 2920): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
,D/LocationManagerService( 3514): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4252): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4252): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 4252, getuid(): 10014
,I/SecureStorage(11521): [INFO]: SPID(0x00000006)Processing data has been completed
,I/SecureStorage(11521): [INFO]: SPID(0x00000006)Skip using SecureStorageExceptionJNI
,I/SecSQLiteOpenHelper(11456): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11456): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11456): Open platform.db in secure mode
I/SecSQLiteDatabase(11456): openSecureDatabase...
I/SecSQLiteDatabase(11456): private openSecureDatabase...
I/SecSQLiteConnectionPool(11456): OpenSecure
I/SecSQLiteConnectionPool(11456): OpenSecure with password
I/SecSQLiteConnectionPool(11456): openSecureConnectionLocked
I/SecSQLiteDatabase(11456): ...private openSecureDatabase
I/SecSQLiteDatabase(11456): ...openSecureDatabase
,I/SecSQLiteOpenHelper(11456): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11456): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/-----SIC-----(11456): ------------------skip TGH
,I/SecSQLiteOpenHelper(11456): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11456): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11456): Open platform.db in secure mode
I/SecSQLiteDatabase(11456): openSecureDatabase...
I/SecSQLiteDatabase(11456): private openSecureDatabase...
I/SecSQLiteConnectionPool(11456): OpenSecure
I/SecSQLiteConnectionPool(11456): OpenSecure with password
I/SecSQLiteConnectionPool(11456): openSecureConnectionLocked
I/SecSQLiteDatabase(11456): ...private openSecureDatabase
I/SecSQLiteDatabase(11456): ...openSecureDatabase
,V/AlarmManager( 3514): waitForAlarm result :4
,I/CalendarProvider2(11479): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager( 3514): Killing 11105:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,D/LocationManagerService( 3514): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/SecSQLiteOpenHelper(11456): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11456): ...getDatabaseLocked(b,b,pwd)
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11456): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,I/dhcpcd  (10908): wlan0: sending IPv6 Router Solicitation
,I/System.out( 4252): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4252): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 4252, getuid(): 10014
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11456): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer(11456): decode(33, 20909908, 4230)
,V/MediaPlayerService( 2860): decode(24, 20909908, 4230)
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
V/StagefrightPlayer( 2860): setDataSource(24, 20909908, 4230)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 8, 0, 0)
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
,V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
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
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/SO_AGENT(11182): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
,I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
,V/MediaPlayerService( 2860): wait for playback complete
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
,V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer(11456): decode(37, 20763080, 15440)
V/MediaPlayerService( 2860): decode(24, 20763080, 15440)
,I/SA      (11240): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
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
V/StagefrightPlayer( 2860): setDataSource(24, 20763080, 15440)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
,I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
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
,V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder',
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
,V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port,
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 200, 973, 0),
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 2860): notify(0xb020d330, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
,V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7,
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
,I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
V/MediaPlayerService( 2860): wait for playback complete
,D/LocationManagerService( 3514): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 2860): wait - success
V/AwesomePlayer( 2860): addBatteryData
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer(11456): decode(38, 20807608, 9226)
V/MediaPlayerService( 2860): decode(24, 20807608, 9226)
,V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/AwesomePlayer( 2860): setDefault
,V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
,V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(24, 20807608, 9226)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
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
,V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
,I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 200, 973, 0)
V/AudioCache( 2860): ignored
,V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
,V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
V/MediaPlayerService( 2860): wait for playback complete
,I/AudioPlayer( 2860): First fillBuffer call!!
,I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
,V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): addBatteryData
V/AwesomePlayer( 2860): reset_l()
,V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1,
I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/AudioPlayer( 2860): reset out
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2860): SecVideoCapture destructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): mSecCapture clear
,I/SecMediaClock( 2860): SecMediaClock destructor
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
I/System.out( 4252): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4252): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 4252, getuid(): 10014
I/ActivityManager( 3514): Killing 11132:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/MediaPlayer(11456): decode(39, 20914220, 4890)
,V/MediaPlayerService( 2860): decode(24, 20914220, 4890)
,V/MediaPlayerService( 2860): player type = 3
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthServiceInstalled() : HealthService is Installed.
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
,V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
,D/AdaptiveEventManager( 3690): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3690): M updateContainers()
D/AdaptiveEventContainerSmall( 3690): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3690): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3690): pedoEvent == null
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(24, 20914220, 4890)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,I/ActivityManager( 3514): Killing 11202:com.policydm/1000 (adj 13): bgCount ##31
,D/AdaptiveEventManager( 3690): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3690): M updateContainers()
D/AdaptiveEventContainerSmall( 3690): C updatePedoContainer()
V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
D/AdaptiveEventContainerSmall( 3690): handlePedoUpdate()
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
D/AdaptiveEventContainerSmall( 3690): pedoEvent == null
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
W/System.err(11456): java.lang.NumberFormatException: Invalid int: "null"
V/MediaPlayerService( 2860): wait for prepare
W/System.err(11456): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err(11456): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err(11456): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err(11456): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:498)
W/System.err(11456): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1242)
W/System.err(11456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11456): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/AwesomePlayer( 2860): onPrepareAsyncEvent
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
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
W/System.err( 9958): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
W/System.err( 9958): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err( 9958): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err( 9958): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err( 9958): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err( 9958): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
W/System.err( 9958): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
W/System.err( 9958): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
W/System.err( 9958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9958): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9958): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9958): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9958): 	at java.lang.reflect.Method.invoke(Method.java:372)
I/splitIntent( 3514): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
W/System.err( 9958): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9958): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DatabaseUtils( 3514): Writing exception to parcel
E/DatabaseUtils( 3514): java.lang.NullPointerException: key == null
E/DatabaseUtils( 3514): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils( 3514): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils( 3514): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils( 3514): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:376)
E/DatabaseUtils( 3514): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils( 3514): 	at android.os.Binder.execTransact(Binder.java:446)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 6, 0, 0)
I/AudioPlayer( 2860): First fillBuffer call!!
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
V/MediaPlayerService( 2860): wait for playback complete
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
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
V/MediaPlayer(11456): decode(40, 20840384, 17329)
V/MediaPlayerService( 2860): decode(29, 20840384, 17329)
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
V/StagefrightPlayer( 2860): setDataSource(29, 20840384, 17329)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
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
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
V/MediaPlayerService( 2860): wait for playback complete
V/AlarmManager( 3514):  next == MAX_VALUE
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
,V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
,I/OggExtractor( 2860): ~OggExtractor --
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
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
,E/SQLiteLog(11479): (284) automatic index on view_events(_id)
,V/MediaPlayer(11456): decode(36, 20740576, 6644)
,V/MediaPlayerService( 2860): decode(29, 20740576, 6644)
V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
E/Zygote  (11693): MountEmulatedStorage()
E/Zygote  (11693): v2
I/libpersona(11693): KNOX_SDCARD checking this for 10022
I/libpersona(11693): KNOX_SDCARD not a persona
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AlarmManager( 3514):  next == MAX_VALUE
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
I/ActivityManager( 3514): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=11693 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
I/SELinux (11693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(29, 20740576, 6644)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
I/SELinux (11693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11693): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
,V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
,I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
V/MediaPlayerService( 2860): wait for playback complete
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8712(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 850us total 29.188ms
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
,V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache( 2860): notify(0xaec1f6f0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
,V/AwesomePlayer( 2860): reset_l()
,V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 952us total 20.047ms
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
D/TimaKeyStoreProvider(11693): TimaSignature is unavailable
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
D/ActivityThread(11693): Added TimaKeyStore provider
D/CalendarAlarmManager(11479): sys current time:1453396617281
,V/MediaPlayer(11456): decode(41, 20816916, 23389)
V/MediaPlayerService( 2860): decode(24, 20816916, 23389)
,D/CalendarAlarmManager(11479): reminder amount:0
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
V/StagefrightPlayer( 2860): setDataSource(24, 20816916, 23389)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 8, 0, 0)
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
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 772us total 17.308ms
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 1, 0, 0)
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
V/AudioCache( 2860): notify(0xb020d330, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
V/MediaPlayerService( 2860): wait for playback complete
,D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(11693): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11693): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11693): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
,V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 8, 0, 0)
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
,V/MediaPlayer(11456): decode(42, 20706272, 8154)
V/MediaPlayerService( 2860): decode(24, 20706272, 8154)
,V/MediaPlayerService( 2860): player type = 3
,V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
,V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(24, 20706272, 8154)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
,I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
,I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 5, 0, 0)
,V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7,
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
V/MediaPlayerService( 2860): wait for playback complete
,I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,I/LocationWidgetApplication(11693): onCreate() : start
,D/LocationWidgetApplication(11693): countryCode = POLAND
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
,V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
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
V/AwesomePlayer( 2860): mSecCapture clear
I/SecMediaClock( 2860): SecMediaClock destructor
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/StagefrightPlayer( 2860): ~StagefrightPlayer
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
,V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/MediaPlayer(11456): decode(43, 20679752, 4804)
,V/MediaPlayerService( 2860): decode(24, 20679752, 4804)
V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
,V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(24, 20679752, 4804)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2860): notify(0xb0009150, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
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
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/LocationWidgetUtils(11693): getUpcommingInstances() start: 1453396617441, end: 1453935599999
,D/LocationWidgetUtils(11693): getUpcommingInstances() DB begin time >= start:1453396617441, DB begin time <= end:1453935599999
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 1, 0, 0)
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
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer( 2860): First fillBuffer call!!
,I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
V/AudioCache( 2860): notify(0xb0009150, 6, 0, 0)
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
,V/MediaPlayerService( 2860): wait for playback complete
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 8, 0, 0)
V/AudioCache( 2860): ignored
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
V/MediaPlayer(11456): decode(44, 20649204, 9400)
V/MediaPlayerService( 2860): decode(24, 20649204, 9400)
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
V/StagefrightPlayer( 2860): setDataSource(24, 20649204, 9400)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/MediaPlayer(11456): decode(50, 20722624, 4112)
,V/MediaPlayerService( 2860): decode(34, 20722624, 4112)
V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
V/AwesomePlayer( 2860): onPrepareAsyncEvent
V/AwesomePlayer( 2860): setDefault
I/SecMediaClock( 2860): SecMediaClock constructor
V/AwesomePlayer( 2860): reset_l()
I/SecMediaClock( 2860): reset
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(34, 20722624, 4112)
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
V/AudioCache( 2860): notify(0xaec1f6f0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
,V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
,V/MediaPlayerService( 2860): wait for prepare
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
,I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 5, 0, 0)
,V/AudioCache( 2860): ignored
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/AudioCache( 2860): notify(0xb040f3d0, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
,V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2860): notify(0xaec1f6f0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 2860): notify(0xaec1f6f0, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AudioCache( 2860): notify(0xb040f3d0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2860): open(44100, 1, 0x0, 1, 0)
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/MediaPlayerService( 2860): wait for playback complete
V/AudioCache( 2860): notify(0xaec1f6f0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
,I/AudioPlayer( 2860): First fillBuffer call!!
V/MediaPlayerService( 2860): wait for playback complete
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 8, 0, 0)
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
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/AudioPlayer( 2860): reset out
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
,V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): destructor
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2860): mAudioTrackVector clear
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
V/AudioCache( 2860): notify(0xb040f3d0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 8, 0, 0)
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
V/MediaPlayer(11456): decode(45, 20857804, 52024)
V/MediaPlayerService( 2860): decode(24, 20857804, 52024)
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
,V/AwesomePlayer( 2860): mSecMediaClock clear
V/StagefrightPlayer( 2860): StagefrightPlayer
V/AwesomePlayer( 2860): setListener
V/StagefrightPlayer( 2860): initCheck
V/AwesomePlayer( 2860): setAudioSink
V/StagefrightPlayer( 2860): setDataSource(24, 20857804, 52024)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 8, 0, 0)
,V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
,V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
,V/AudioPolicyManager( 2860): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
,V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 200, 973, 0)
V/AudioCache( 2860): ignored
,V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
,V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants(11456): RegionGroup for  is null
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
I/AudioPlayer( 2860): First fillBuffer call!!
,I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2860): wait for playback complete
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11456): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/LocationManagerService( 3514): getProviders()=[]
D/LocationManagerService( 3514): getProviders()=[passive]
D/LocationManagerService( 3514): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(11693): mPrivacy is null
,W/ContextImpl(11693): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,D/ContextFramework:PrivacyManager(11693): Service for PrivacyManager is connected
,D/LWLocationManager(11693): Privacy service : STATUS_PLACE
D/LWLocationManager(11693): updateLocationStatus()
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
,V/AudioCache( 2860): wait - success
V/AwesomePlayer( 2860): addBatteryData
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x87, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
,I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
D/BluetoothManager(11456): getConnectedDevices
D/BluetoothManager(11456): getConnectedDevices
D/BluetoothManager(11456): getConnectedDevices
,I/LocationWidgetFuctionData(11693): readDB
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
V/MediaPlayer(11456): decode(46, 20722624, 4112)
V/MediaPlayerService( 2860): decode(24, 20722624, 4112)
,V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
,I/LocationWidgetFuctionData(11693): selectedAppSize: 3
I/LocationWidgetFuctionData(11693): configPlaceList aroundMeItems
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
V/StagefrightPlayer( 2860): setDataSource(24, 20722624, 4112)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 8, 0, 0)
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
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 200, 973, 0)
V/AudioCache( 2860): ignored
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
V/AudioCache( 2860): notify(0xafffd970, 5, 0, 0)
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
V/AudioCache( 2860): ignored
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 1, 0, 0)
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
V/AudioCache( 2860): notify(0xafffd970, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
,V/MediaPlayerService( 2860): wait for playback complete
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xafffd970, 8, 0, 0)
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
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/MediaPlayer(11456): decode(47, 20785700, 21825)
,V/MediaPlayerService( 2860): decode(24, 20785700, 21825)
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
V/StagefrightPlayer( 2860): setDataSource(24, 20785700, 21825)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
I/libpersona(11753): KNOX_SDCARD checking this for 10003
V/MediaPlayerService( 2860): prepare
I/libpersona(11753): KNOX_SDCARD not a persona
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
E/Zygote  (11753): MountEmulatedStorage()
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
E/Zygote  (11753): v2
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/SELinux (11753): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/Mms/MmsApp(11425):  start initViewCache mms
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/SELinux (11753): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 1, 0, 0)
I/ActivityManager( 3514): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=11753 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
E/SELinux (11753): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(44100, 2, 0x0, 1, 0)
,D/BluetoothManager(11456): getConnectedDevices
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
V/MediaPlayerService( 2860): wait for playback complete
,D/Mms/ComposeMessageFragment(11425): [start]    fillCache consume time = 1803.311875
D/Mms/ComposeMessageFragment(11425): fillCache, easy = false
,I/AudioPlayer( 2860): First fillBuffer call!!
,I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,D/BluetoothManager(11456): getConnectedDevices
,D/BluetoothManager(11456): getConnectedDevices
,D/TimaKeyStoreProvider(11753): TimaSignature is unavailable
,D/ActivityThread(11753): Added TimaKeyStore provider
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 7, 0, 0)
I/ActivityManager( 3514): Killing 11262:com.samsung.android.scloud.backup/u0a67 (adj 13): bgCount ##31
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
,V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb0009150, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x89, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor( 2860): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2860): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2860): ~OggSource --
,I/OggExtractor( 2860): ~OggExtractor ++
I/OggExtractor( 2860): ~MyVorbisExtractor ++ 
I/OggExtractor( 2860): ~MyVorbisExtractor --
I/OggExtractor( 2860): ~OggExtractor --
,I/AudioPlayer( 2860): reset out
,V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
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
,V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/MediaPlayer(11456): decode(48, 20684636, 21552)
,V/MediaPlayerService( 2860): decode(24, 20684636, 21552)
,V/MediaPlayerService( 2860): player type = 3
V/AwesomePlayer( 2860): setDefault
V/AwesomePlayer( 2860): constructor
D/ResourcesManager(11753): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
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
V/StagefrightPlayer( 2860): setDataSource(24, 20684636, 21552)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
V/AwesomePlayer( 2860): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2860): mSecCapture clear
V/AwesomePlayer( 2860): mSecMediaClock clear
,V/AwesomePlayer( 2860): track of type 'audio/vorbis' does not publish bitrate,
V/AwesomePlayer( 2860): mBitrate = -1 bits/sec
I/OggExtractor( 2860): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer( 2860): current audio track index (0) is added to vector
V/AwesomePlayer( 2860): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer( 2860): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2860): prepare
V/AwesomePlayer( 2860): prepareAsync
V/MediaPlayerService( 2860): wait for prepare
V/AwesomePlayer( 2860): onPrepareAsyncEvent
I/SecMediaClock( 2860): SecMediaClock constructor
,I/SecMediaClock( 2860): reset
I/SecVideoCapture( 2860): SecVideoCapture constructor
I/SecVideoCapture( 2860): reset
V/AwesomePlayer( 2860): initAudioDecoder
V/AwesomePlayer( 2860): checkOffloadExceptions is true
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2860): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2860): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2860): Could not offload audio decode, try pcm offload
I/ActivityManager( 3514): Killing 11279:com.sec.knox.bridge/1000 (adj 13): bgCount ##31
V/AudioPolicyManager( 2860): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2860): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2860): finishAsyncPrepare_l
V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 1, 0, 0)
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
V/AudioCache( 2860): notify(0xaec1f6f0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
,I/AudioPlayer( 2860): First fillBuffer call!!
V/MediaPlayerService( 2860): wait for playback complete
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
,D/UserAnalysis.PlaceProvider(11753): PlaceProvider onCreate()
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
,V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xaec1f6f0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x8a, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer(11456): decode(49, 20778600, 7017)
,V/MediaPlayerService( 2860): decode(24, 20778600, 7017)
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
V/StagefrightPlayer( 2860): setDataSource(24, 20778600, 7017)
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 8, 0, 0)
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
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2860): finishAsyncPrepare_l
,V/AwesomePlayer( 2860): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 200, 973, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 2860): notify(0xb040f3d0, 5, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 1, 0, 0)
V/AudioCache( 2860): prepared
V/AudioCache( 2860): wait - success
V/MediaPlayerService( 2860): start
V/StagefrightPlayer( 2860): start
V/AwesomePlayer( 2860): play
V/AwesomePlayer( 2860): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2860): startAudioPlayer_l, sendErrorNotification (0)
D/UserAnalysis.SecureDbManager(11753): Key for secure DB is newly created
,D/AbsListView(11425): Get MotionRecognitionManager
D/UserAnalysis.SecurePlaceDbHelper(11753): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(11753): Create SecureDbHelper
,D/MotionRecognitionService( 3514):  ssp status : true
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2860): >>>UHQA initOutputFormat 16
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/Mms/ComposeMessageFragment(11425): [end]    fillCache consume time = 127.196
,D/IntelligenceServiceApplication(11753): onCreate()
,I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2860): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2860): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2860): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer( 2860): First fillBuffer call!!
I/AudioPlayer( 2860): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2860): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,V/AudioCache( 2860): notify(0xb040f3d0, 6, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): addBatteryData
,V/MediaPlayerService( 2860): wait for playback complete
,I/OMXCodec( 2860): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2860): postAudioEOS delayUs (0)
V/AwesomePlayer( 2860): onCheckAudioStatus
V/AwesomePlayer( 2860): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2860): onStreamDone
V/AwesomePlayer( 2860): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2860): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 2, 0, 0)
V/AudioCache( 2860): playback complete - thread will wake up later
V/AwesomePlayer( 2860): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 7, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2860): addBatteryData
V/AudioCache( 2860): wait - success
V/StagefrightPlayer( 2860): reset
V/AwesomePlayer( 2860): reset_l()
V/AwesomePlayer( 2860): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2860): notify(0xb040f3d0, 8, 0, 0)
V/AudioCache( 2860): ignored
V/AwesomePlayer( 2860): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2860): mAudioTrackVector clear
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2860): [OMX.google.vorbis.decoder] stop() sendCommand(0x8b, OMX_CommandStateSet, OMX_StateIdle)
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
,I/LocationWidgetFuctionData(11693): selectedAppSize: 3
,I/LocationWidgetFuctionData(11693): selectedAppSize: 3
,I/LocationWidgetFuctionData(11693): selectedAppSize: 3
,I/LocationWidgetFuctionData(11693): selectedAppSize: 3
,E/LWLocationManager(11693): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(11693): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(11693): setShouldUpdateLocationId
D/LWLocationManager(11693): setShouldUpdateLocationId return false
D/LWLocationManager(11693): setShouldUpdateLocationId
D/LWLocationManager(11693): setShouldUpdateLocationId return false
D/LWLocationManager(11693): setShouldUpdateLocationId
D/LWLocationManager(11693): setShouldUpdateLocationId return false
D/LWLocationManager(11693): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,D/Mms/BubbleViewCache(11425): fillCache bubble = 8
,I/SurfaceFlinger( 2855): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2855): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3514): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3514) eventTime = 150836
,D/PowerManagerService( 3514): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3514 (0x0)
,D/PowerManagerService( 3514): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3514, ws=WorkSource{1000}) (elapsedTime=3469)
,I/System.out( 3514): Thread-148(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3514): Thread-148(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3514): Thread-148(ApacheHTTPLog):isShipBuild true
I/System.out( 3514): Thread-148(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2851): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2851): getNetworkForDns: using netid 502 for uid 1000
,I/System.out( 3514): AsyncTask #3 calls detatch()
,W/System.err( 3514): java.io.IOException: Not Found
,W/System.err( 3514): 	at a.d.b(Unknown Source)
,W/System.err( 3514): 	at a.d.doInBackground(Unknown Source)
,W/System.err( 3514): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 3514): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 3514): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 3514): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 3514): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 3514): 	at java.lang.Thread.run(Thread.java:818)
,I/GAV4    (11294): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 3514): waitForAlarm result :8
,I/dhcpcd  (10908): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (10908): wlan0: no IPv6 Routers available
,D/SSRM:n  ( 3514): SIOP:: AP = 280, PST = 268, CUR = -106
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:-30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:75
,D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/BatteryService( 3514): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3514): Skipping unknown process pid 11842
,I/GAV3    (11456): Thread[GAThread,5,main]: No campaign data found.
,D/PreloadUpdateManagerStateMachine(11399): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(11399): exit::IDLE
D/PreloadUpdateManagerStateMachine(11399): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (11399): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (11399): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(11399): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(11399): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(11399): entry::IDLE
,E/Watchdog( 3514): !@Sync 5
,D/SSRM:n  ( 3514): SIOP:: AP = 260, PST = 268, CUR = -30,
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/BatteryService( 3514): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3514): [PWL] Off : 75s ago
,D/SSRM:n  ( 3514): SIOP:: AP = 250, PST = 265, CUR = 29
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/BatteryService( 3514): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3514): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ClearcutLoggerApiImpl( 4252): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3514): SIOP:: AP = 250, PST = 264, CUR = 49
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3514): stay LED for fully charged
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3514): !@Sync 6
,D/SSRM:n  ( 3514): SIOP:: AP = 250, PST = 263, CUR = 53
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/BatteryService( 3514): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2876): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3514): [PWL] Off : 105s ago
,D/SSRM:n  ( 3514): SIOP:: AP = 240, PST = 260, CUR = 52
,V/AlarmManager( 3514): waitForAlarm result :4
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3514): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3514): stay LED for fully charged
,I/MotionRecognitionService( 3514): Plugged
I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/ActivityThread( 7834): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3514): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 175137, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager( 3514): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 266128, reason: UserStart
,W/ResourceType( 4948): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4948): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SecContentProvider2( 3514): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3514): mCursor = null
,V/AlarmManager( 3514): waitForAlarm result :8
,D/SSRM:n  ( 3514): SIOP:: AP = 240, PST = 255, CUR = 49
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
,D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/BatteryService( 3514): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3514): !@Sync 7
,V/AlarmManager( 3514): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3514): SIOP:: AP = 240, PST = 253, CUR = 48
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3514): stay LED for fully charged
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3514): [PWL] Off : 140s ago
,D/SSRM:n  ( 3514): SIOP:: AP = 240, PST = 253, CUR = 46
,V/AlarmManager( 3514): waitForAlarm result :4
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/BatteryService( 3514): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3514): SIOP:: AP = 240, PST = 250, CUR = 43
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/BatteryService( 3514): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3514): !@Sync 8
,D/SSRM:n  ( 3514): SIOP:: AP = 240, PST = 247, CUR = 41
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/BatteryService( 3514): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2876): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3514): SIOP:: AP = 240, PST = 246, CUR = 40
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3514): stay LED for fully charged
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3514): waitForAlarm result :8
,I/PowerManagerService( 3514): [PWL] Off : 180s ago
,D/SSRM:n  ( 3514): SIOP:: AP = 240, PST = 245, CUR = 39,
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3514): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/BatteryService( 3514): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10696): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10696): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(10626): --= Surplus to requirements =--
I/jxcore-log(10626): 
I/jxcore-log(10626): ****TEST TOOK:  ms ****
I/jxcore-log(10626): 
I/jxcore-log(10626): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10626): 
,E/Watchdog( 3514): !@Sync 9
,D/AndroidRuntime(12052): 
D/AndroidRuntime(12052): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12052): CheckJNI is OFF
,D/AndroidRuntime(12052): readGMSProperty: start
D/AndroidRuntime(12052): readGMSProperty: already setted!!
,D/AndroidRuntime(12052): readGMSProperty: end
D/AndroidRuntime(12052): addProductProperty: start
,E/AffinityControl(12052): AffinityControl: registerfunction enter
,D/AndroidRuntime(12052): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3514): START PACKAGE DELETE: observer{178152463}
D/PackageManager( 3514): pkg{<packageName>}
D/PackageManager( 3514): user{0}
D/PackageManager( 3514): caller{2000},
D/PackageManager( 3514): flags{3}
D/PersonaManagerService( 3514): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3514): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3514): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3514): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 3514): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3514): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3514): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3514): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3514): getApplicationUninstallationEnabled
,D/ApplicationPolicy( 3514): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3514): !@killApplicatoin: 10596, uninstall pkg
I/ActivityManager( 3514): Force stopping com.test.thalitest appid=10596 user=-1: uninstall pkg
I/ActivityManager( 3514): Killing 10626:com.test.thalitest/u0a596 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3514):   Force finishing activity ActivityRecord{300e0fe1 u0 com.test.thalitest/.MainActivity t25}
,I/SurfaceFlinger( 2855): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2855): id=12 Removed NainActivit (-2/8)
,D/PointerIcon( 3514): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3514): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3514): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3514): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3514): Skipping PackageSetting{651af69 com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3514): Force stopping com.test.thalitest appid=10596 user=0: pkg removed
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/WifiService( 3514): Client connection lost with reason: 4
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 8047): Explicit concurrent mark sweep GC freed 31561(1738KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.152ms total 49.278ms
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 1377(68KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.393ms total 46.611ms
,I/art     ( 7834): Explicit concurrent mark sweep GC freed 10518(806KB) AllocSpace objects, 29(464KB) LOS objects, 20% free, 31MB/39MB, paused 2.572ms total 65.477ms
,W/GeofencerStateMachine( 4252): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4459): mOCRHelper is null
,D/LWLocationManager(11693): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11693): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/InputReader( 3514): Reconfiguring input devices.  changes=0x00000010
,E/Zygote  (12063): MountEmulatedStorage()
E/Zygote  (12063): v2
I/libpersona(12063): KNOX_SDCARD checking this for 10063
I/libpersona(12063): KNOX_SDCARD not a persona
,I/SELinux (12063): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12063): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3514): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12063 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/SELinux (12063): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 4948): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4948): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/EnterpriseDeviceManagerService( 3514): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3514): Admin package name: com.google.android.gms
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/TimaKeyStoreProvider(12063): TimaSignature is unavailable
D/ActivityThread(12063): Added TimaKeyStore provider
,D/ResourcesManager(12063): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12063): onReceive()
,D/VRSetupWizardStub/PackageIntentReceiver(12063): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12063): packagename:com.test.thalitest
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/KLMS-2.4.521: (11166): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 21 18:19:11 GMT+01:00 2016
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/KLMS-2.4.521: (11166): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3514): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3514): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/art     ( 3514): Explicit concurrent mark sweep GC freed 60740(4MB) AllocSpace objects, 55(3MB) LOS objects, 24% free, 49MB/65MB, paused 2.294ms total 196.784ms
,D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3514): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/KLMS-2.4.521: (11166): KLMSIntentService(): onCreate()
,I/art     ( 3514): WaitForGcToComplete blocked for 190.533ms for cause Explicit
,D/elm:14491(11616): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/KLMS-2.4.521: (11166): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11166): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11166): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/Zygote  (12082): MountEmulatedStorage()
E/Zygote  (12082): v2
I/libpersona(12082): KNOX_SDCARD checking this for 1000
I/libpersona(12082): KNOX_SDCARD not a persona
,I/SELinux (12082): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (11166): KLMSIntentService(): PACKAGE_REMOVED
,I/ActivityManager( 3514): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=12082 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12082): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/SELinux (12082): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/KLMS-2.4.521: (11166): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (11166): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/elm:14491(11616): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/elm:14491(11616): ElmAgentService : onCreate()
,D/elm:14491(11616): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(11616): MainReceiver.listeningToPackageRemoved()
D/elm:14491(11616): MDMBridge.getInstance()
D/elm:14491(11616): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
D/elm:14491(11616): MDMBridge.getAllLicenseInfoFromSDK()
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/TimaKeyStoreProvider(12082): TimaSignature is unavailable
,D/ActivityThread(12082): Added TimaKeyStore provider
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  (12099): MountEmulatedStorage()
E/Zygote  (12099): v2
I/libpersona(12099): KNOX_SDCARD checking this for 10160
D/ResourcesManager(11693): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
I/libpersona(12099): KNOX_SDCARD not a persona
,I/SELinux (12099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3514): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=12099 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,I/SELinux (12099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12099): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/SecContentProvider2( 3514): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3514): mCursor = null
,E/Zygote  (12113): MountEmulatedStorage()
E/Zygote  (12113): v2
I/libpersona(12113): KNOX_SDCARD checking this for 10050
I/libpersona(12113): KNOX_SDCARD not a persona
,I/SELinux (12113): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12113): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12113 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (12113): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12099): TimaSignature is unavailable
,D/ActivityThread(12099): Added TimaKeyStore provider
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/elm:14491(11616): ElmAgentService : onDestroy().
,W/ResourcesManager(11693): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12113): TimaSignature is unavailable
,D/ActivityThread(12113): Added TimaKeyStore provider
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(12082): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12082): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager(12099): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(12099): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12099): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/RCPManager(12082):  in createShortcut() for packageName: com.test.thalitest userId0
D/ResourcesManager(12113): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/RCPManagerService( 3514):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3514): queryAllProviders():  providerCallBack is not register for 0
,W/ResourcesManager(12113): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12113): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/com.sec.android.service.health.upgrade.UninstallReceiver(11521): onReceive()
W/ResourcesManager(12113): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/com.sec.android.service.health.upgrade.UninstallReceiver(11521): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
W/ResourcesManager(12113): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/com.sec.android.service.health.upgrade.UninstallReceiver(11521): onReceive() : package name is not s health. Return !!!
W/ResourcesManager(12113): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12113): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12113): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12113): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RegisteredServicesCache( 3966): empty dynamic service
I/art     ( 3514): Explicit concurrent mark sweep GC freed 8595(428KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.312ms total 146.830ms
I/art     ( 3514): WaitForGcToComplete blocked for 211.527ms for cause Explicit
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/Zygote  (12129): MountEmulatedStorage()
I/libpersona(12129): KNOX_SDCARD checking this for 10101
E/Zygote  (12129): v2
I/libpersona(12129): KNOX_SDCARD not a persona
,I/SELinux (12129): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (11166): KLMSIntentService(): listeningToPackageRemoved().END
I/ActivityManager( 3514): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12129 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12129): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12129): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/LocationWidgetApplication(11693): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/KLMS-2.4.521: (11166): KLMSIntentService(): onDestroy()
,W/ResourcesManager(11693): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11693): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11693): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11693): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/ActivityManager( 3514): Killing 11022:com.android.chrome/u0a90 (adj 13): bgCount ##31
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 3514): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/TimaKeyStoreProvider(12129): TimaSignature is unavailable
,D/ActivityThread(12129): Added TimaKeyStore provider
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/Zygote  (12145): MountEmulatedStorage()
E/Zygote  (12145): v2
,I/libpersona(12145): KNOX_SDCARD checking this for 1000
I/libpersona(12145): KNOX_SDCARD not a persona
,I/SELinux (12145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3514): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12145 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/Videos/Videos.apk
,V/Common  (12099): getScreenSize 1440 2560
,E/SELinux (12145): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Killing 10719:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 13): bgCount ##31
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12129): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,E/Zygote  (12162): MountEmulatedStorage()
,E/Zygote  (12162): v2
I/libpersona(12162): KNOX_SDCARD checking this for 10160
I/libpersona(12162): KNOX_SDCARD not a persona
,I/JAM     (12099): Load The ApaService JNI
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux (12162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/JAM     (12099): version: ProfessionalAudio_v1.0.b5
I/JAM     (12099): Try v1.0.b3 ...
I/art     ( 3514): Explicit concurrent mark sweep GC freed 2696(158KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.159ms total 100.178ms
D/Spen    (12099): SpenSdk version level = 55
D/Spen    (12099): SpenSdk jar version = 3.0.243
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/ActivityManager( 3514): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=12162 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
I/SELinux (12162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12162): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Spen    (12099): SpenSdk apk version = 3.0.235
D/Spen    (12099): Server UPDATE Check
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/linker  (12099): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/SPenError(12099): JNI_OnLoad
,D/JNI_Bitmap(12099): Init .. Done
D/SPenSpiDecoder(12099): JNI_OnLoad .. Done
D/SPenError(12099): JNI_OnLoad Success
,D/PluginManager(12099): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(12099): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(12099): JNI_OnLoad
,D/Init_SPenSdk_Jni(12099): AndroidSDK: 21
D/Init_SPenSdk_Jni(12099): JNI_OnLoad .. Done
,D/PackageManager( 3514): findPreferredActivity: No PreferredActivities set
,D/Model_ObjectBase_Jni(12099): JNI_OnLoad .. Done
D/Model_ObjectStroke_Jni(12099): JNI_OnLoad .. Done
,D/Model_ObjectImage_Jni(12099): JNI_OnLoad .. Done
D/Model_ObjectText_Jni(12099): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(12099): JNI_OnLoad .. Done
,D/TimaKeyStoreProvider(12145): TimaSignature is unavailable
D/Model_PageDoc_Jni(12099): JNI_OnLoad .. Done
,D/Model_NoteDoc_Jni(12099): check build type eng[0]
D/ActivityThread(12145): Added TimaKeyStore provider
D/Model_NoteDoc_Jni(12099): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(12099): JNI_OnLoad .. Done
,D/Model_ObjectUtil_Jni(12099): JNI_OnLoad .. Done
D/Model   (12099): OnLoad class Done
,D/ResourcesManager(11693): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/spe_log (12099): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library(12099): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(12099): Canvas JNI_OnLoad enter!!
,D/SPen_Library(12099): Canvas JNI_OnLoad Success
D/SPen_Library(12099): TextView JNI_OnLoad enter!!
,D/SPen_Library(12099): TextView JNI_OnLoad Success
D/SPen_Library(12099): Text JNI_OnLoad enter!!
D/SPen_Library(12099): Text JNI_OnLoad Success
D/SPen_Library(12099): FontManager JNI_OnLoad enter!!
D/SPen_Library(12099): FontManager JNI_OnLoad Success
D/SPen_Library(12099): CapturePage JNI_OnLoad enter!!
D/SPen_Library(12099): CapturePage JNI_OnLoad Success
D/SPen_Library(12099): Multi JNI_OnLoad enter!!
D/SPen_Library(12099): Multi JNI_OnLoad Success
D/SPen_Library(12099): Draw Engine JNI_OnLoad Success
,D/SPen_Library(12099): Brush JNI_OnLoad enter!!
,D/SPen_Library(12099): Brush JNI_OnLoad Success
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/SPen_Library(12099): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(12099): ChineseBrush JNI_OnLoad Success
,D/SPen_Library(12099): InkPen JNI_OnLoad enter!!
,D/SPen_Library(12099): InkPen JNI_OnLoad Success
,D/SPen_Library(12099): Marker JNI_OnLoad enter!!
,D/SPen_Library(12099): Marker JNI_OnLoad Success
,D/SPen_Library(12099): Pencil JNI_OnLoad enter!!
D/SPen_Library(12099): Pencil JNI_OnLoad Success
,D/DocsApplication(12129): Installing DEX configuration.
D/SPen_Library(12099): NativePen JNI_OnLoad enter!!
,D/SPen_Library(12099): NativePen JNI_OnLoad Success
D/ResourcesManager(11693): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
D/SPen_Library(12099): MontblancFountainPen JNI_OnLoad enter!!
D/NearbySource(12113): Nearby Source Create!
D/SPen_Library(12099): MontblancFountainPen JNI_OnLoad Success
D/NearbyContext(12113): Nearby Context Create!
,D/DexInstaller(12129): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,D/SPen_Library(12099): MontblancCalligraphyPen JNI_OnLoad enter!!
D/SPen_Library(12099): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library(12099): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(12099): MagicPen JNI_OnLoad Success
,D/SPen_Library(12099): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library(12099): ObliquePen JNI_OnLoad Success
I/PackageInfoHelper(12129): Provided clientMode=RELEASE, packageInfo=PackageInfo{155c2e4a com.google.android.apps.docs}
,D/SPen_Library(12099): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(12099): FountainPen JNI_OnLoad Success
D/Spen    (12099): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(12099): SPenSdk_init2
D/Init_SPenSdk(12099): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(12099): Total S Pen SDK Directory Size = 0
D/Spen    (12099): initialize complete
D/TAG     (12129): onCreate()
,W/linker  (12099): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/CrossAppStateProvider(12129): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/TimaKeyStoreProvider(12162): TimaSignature is unavailable
,D/ActivityThread(12162): Added TimaKeyStore provider
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
D/ResourcesManager(12145): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ContextImpl(12113): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12113): Samsung link source created
,D/PackageManager( 3514): delete codoeFile: 
,D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/AASAUninstall( 3514):  com.test.thalitest not target!
,D/PackageManager( 3514): result of delete: 1{178152463}
,D/AndroidRuntime(12052): Shutting down VM
,E/Zygote  (12182): MountEmulatedStorage()
E/Zygote  (12182): v2
I/libpersona(12182): KNOX_SDCARD checking this for 10183
I/libpersona(12182): KNOX_SDCARD not a persona
I/SELinux (12182): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12182): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12182): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/ActivityManager( 3514): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12182 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,I/PCWCLIENTTRACE_LOG(12145): DEFAULT_LOGON : true
I/ActivityManager( 3514): Killing 11294:com.google.android.apps.magazines/u0a136 (adj 13): bgCount ##31
I/PCWCLIENTTRACE_LOG(12145): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12145): new DMDBOpenHelper instance
,D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/TimaKeyStoreProvider(12182): TimaSignature is unavailable
,D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityThread(12182): Added TimaKeyStore provider
,I/ActivityManager( 3514): Killing 10219:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,I/PCWCLIENTTRACE_PushUtil(12145): SPPPushClient is installed : true
D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/PCWCLIENTTRACE_PushUtil(12145): sales region : global
I/PCWCLIENTTRACE_PushUtil(12145): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12145): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/Zygote  (12199): MountEmulatedStorage()
I/libpersona(12199): KNOX_SDCARD checking this for 10035
E/Zygote  (12199): v2
I/libpersona(12199): KNOX_SDCARD not a persona
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/SELinux (12199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(11693): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
I/SELinux (12199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3514): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12199 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux (12199): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 3514): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3514): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3514): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/ActivityManager( 3514): Killing 11363:com.samsung.android.sconnect/u0a150 (adj 13): bgCount ##31
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ContactProvider(12113): getAllContactInfoList Start
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/ResourcesManager(12162): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(12182): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/TimaKeyStoreProvider(12199): TimaSignature is unavailable
,W/ResourcesManager(12162): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12162): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12162): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ActivityThread(12199): Added TimaKeyStore provider
,D/Mms/FreeMessageStatusReceiver(11425): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3514): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/SQLiteLog(12182): (284) automatic index on shooting_modes(title_id)
D/ResourcesManager(12199): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/RCPManagerService( 3514): PackageReceiver onReceive()
I/HarmonyEASService( 3514): onReceive : android.intent.action.PACKAGE_REMOVED for 0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 3514): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/JobSchedulerService( 3514): Receieved: android.intent.action.PACKAGE_REMOVED
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/KnoxMUMContainerPolicy( 3514): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3514): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3514): uID is 10596
V/EnterpriseBillingPolicy( 3514): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3514): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3514): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3514): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3514): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3514): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3514): getBillingProfileForVpnEngine - end - null
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/FreeMessageReceiverService(11425): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(11425): onHandleIntent: ACTION_PACKAGE_REMOVED
,E/Zygote  (12217): MountEmulatedStorage()
,D/SNoteProvider(12162): onCreate enableSnoteSync = true
E/Zygote  (12217): v2
I/libpersona(12217): KNOX_SDCARD checking this for 1000
I/libpersona(12217): KNOX_SDCARD not a persona
,I/SELinux (12217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,I/SELinux (12217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.android.settings for broadcast com.android.settings/.TactileAssistBroadcastReceiver: pid=12217 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
I/CrashAnrDetector( 3514): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 3514): clearDefaults: com.test.thalitest
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8768(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 877us total 22.316ms
,D/TaskPersister( 3514): removeObsoleteFile: deleting file=25_task.xml
I/FeatureConfig(12199): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager(12199): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12199): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 474us total 18.219ms
,V/Common  (12162): getScreenSize 1440 2560
,D/SNoteProvider(12162): ===query=== 
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12217): TimaSignature is unavailable
D/ResourcesManager(11693): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(12199): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ActivityThread(12217): Added TimaKeyStore provider
,W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 350us total 13.124ms
,D/ResourcesManager(12199): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(12199): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(12199): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/Zygote  (12237): MountEmulatedStorage()
E/Zygote  (12237): v2
I/libpersona(12237): KNOX_SDCARD checking this for 10190
I/libpersona(12237): KNOX_SDCARD not a persona
,I/SELinux (12237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12237): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3514): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12237 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,D/ResourcesManager(12199): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12199): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/ActivityManager( 3514): Killing 10761:com.android.email/u0a178 (adj 13): bgCount ##31
,D/ResourcesManager(12199): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/TimaKeyStoreProvider(12237): TimaSignature is unavailable
,D/ActivityThread(12237): Added TimaKeyStore provider
W/ResourcesManager(12199): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,I/ActivityManager( 3514): Killing 10777:tv.peel.smartremote/u0a186 (adj 13): bgCount ##31
,D/ResourcesManager(12199): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12199): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12199): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12217): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager(12237): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/ResourcesManager(12199): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(12199): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(12199): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12237): onReceive()
W/ResourcesManager(12199): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/TapandpayWidget:TanpandpayAppWidgetProvider(12237): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/TapandpayWidget:Utils(12237): Clear T&P info.
W/ResourcesManager(12217): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager(12217): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
D/ResourcesManager(11693): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
D/ResourcesManager(12199): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
W/ResourcesManager(12217): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager(12217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12217): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12237): Widget is not attached.
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(12199): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12199): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ContactProvider(12113): getAllContactInfoList End
W/ResourcesManager(12199): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/SQLiteLog(11222): (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11693): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/SQLiteDatabase(11222): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase(11222): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11222): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(11222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(11222): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11222): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(11222): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(11222): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(11222): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(11222): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11222): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(11222): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(11222): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase(11222): 	at com.sec.spp.push.i.c.d(Unknown Source)
E/SQLiteDatabase(11222): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase(11222): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase(11222): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase(11222): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11222): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(11222): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(11222): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(11222): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(11222): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(11222): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/syncContacts(12113): thread: 1628, sync time = 307
,E/SPPClientService(11222): [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
,D/ResourcesManager(12199): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/Zygote  (12255): MountEmulatedStorage()
I/libpersona(12255): KNOX_SDCARD checking this for 10039
E/Zygote  (12255): v2
I/libpersona(12255): KNOX_SDCARD not a persona
D/ResourcesManager(11693): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(12199): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/ActivityManager( 3514): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=12255 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager(12199): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/SELinux (12255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/SQLiteLog(11456): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog(11456): (3850) statement aborts at 19: [delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"] disk I/O error
E/SQLiteQuery(11456): exception: disk I/O error (code 3850); query: delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"
,D/ResourcesManager(12199): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/SELinux (12255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/ResourcesManager(12199): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
E/SELinux (12255): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ResourcesManager(12199): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/System.err(12217): java.io.FileNotFoundException: /data/log/settingsprovider.txt: open failed: EROFS (Read-only file system)
,D/PackageBroadcastService( 7834): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 7834): Clearing selected account for com.test.thalitest
,D/ResourcesManager(12199): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/ResourcesManager(12199): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager(11693): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,W/System.err(12217): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(12217): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/System.err(12217): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:149)
W/System.err(12217): 	at com.android.settings.favorite.LogMsg.writeLog(LogMsg.java:51)
W/System.err(12217): 	at com.android.settings.favorite.LogMsg.out(LogMsg.java:29)
W/System.err(12217): 	at com.android.settings.favorite.MySettingsProvider$DatabaseHelper.<init>(MySettingsProvider.java:167)
W/System.err(12217): 	at com.android.settings.favorite.MySettingsProvider.onCreate(MySettingsProvider.java:345)
W/System.err(12217): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
W/System.err(12217): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
W/System.err(12217): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
W/System.err(12217): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
W/System.err(12217): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
W/System.err(12217): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(12217): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(12217): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12217): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(12217): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(12217): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(12217): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(12217): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(12217): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err(12217): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(12217): 	at libcore.io.Posix.open(Native Method)
W/System.err(12217): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(12217): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(12217): 	... 20 more
D/MySettingsProvider(12217): DatabaseHelper(Context context):DATABASE_VERSION=1
E/SQLiteLog(12217): (28) failed to open "/data/data/com.android.settings/databases/mysettings.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(12217): Failed to open database '/data/data/com.android.settings/databases/mysettings.db'.
E/SQLiteDatabase(12217): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12217): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12217): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12217): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12217): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12217): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12217): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12217): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12217): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12217): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12217): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12217): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12217): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12217): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDa,tabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12217): 	at com.android.settings.favorite.MySettingsProvider.onCreate(MySettingsProvider.java:346)
E/SQLiteDatabase(12217): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(12217): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(12217): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12217): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12217): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12217): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12217): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12217): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12217): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12217): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12217): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12217): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12217): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12217): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12217): Shutting down VM
E/AndroidRuntime(12217): FATAL EXCEPTION: main
E/AndroidRuntime(12217): Process: com.android.settings, PID: 12217
E/AndroidRuntime(12217): java.lang.RuntimeException: Unable to get provider com.android.settings.favorite.MySettingsProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12217): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(12217): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(12217): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(12217): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(12217): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(12217): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12217): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12217): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12217): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12217): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12217): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12217): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12217): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12217): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12217): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12217): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12217): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12217): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12217): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12217): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12217): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12217): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12217): 	a,t android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12217): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12217): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12217): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12217): 	at com.android.settings.favorite.MySettingsProvider.onCreate(MySettingsProvider.java:346)
E/AndroidRuntime(12217): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(12217): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(12217): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(12217): 	... 11 more
W/GalaxyFinderApplication(12199): system/finder_cp/cpdata.xml file not found
E/SQLiteLog( 7834): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 7834): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AndroidRuntime(11456): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime(11456): Process: com.sec.android.app.shealth, PID: 11456
E/AndroidRuntime(11456): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime(11456): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForCursorWindow(Native Method)
E/AndroidRuntime(11456): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:1015)
E/AndroidRuntime(11456): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
E/AndroidRuntime(11456): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
E/AndroidRuntime(11456): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:147)
E/AndroidRuntime(11456): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:136)
E/AndroidRuntime(11456): 	at android.content.ContentResolver.query(ContentResolver.java:503)
E/AndroidRuntime(11456): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime(11456): 	at com.sec.android.app.shealth.framework.ui.data.AppRegistryDbManagerWithProvider.deleteAppRegistryData(Unknown Source)
E/AndroidRuntime(11456): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:66)
E/AndroidRuntime(11456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(11456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11456): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(11456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DriveAsyncService( 7834): disk I/O error (code 3850)
E/DriveAsyncService( 7834): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 7834): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 7834): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 7834): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 7834): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 7834): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 7834): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 7834): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 7834): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 7834): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 7834): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 7834): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 7834): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 7834): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 7834): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 7834): 	at java.lang.Thread.run(Thread.java:818)
I/LocationSettingsChecker( 7834): Removing dialog suppression flag for package com.test.thalitest
V/ApplicationPolicy( 3514): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/SNoteProvider(12162): ===query=== 
D/TimaKeyStoreProvider(12255): TimaSignature is unavailable
D/ActivityThread(12255): Added TimaKeyStore provider
D/ChimeraCfgMgr( 7834): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7834): Module APK com.google.android.play.games already loaded
V/ApplicationPolicy( 3514): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
D/UsbHostManager( 3514): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3514): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3514): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3514): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3514): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3514): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3514): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3514): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3514): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3514): displayNotification : [09h,00h,00h]
D/UsbHostManager( 3514): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3514): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3514): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/DropBoxManagerService( 3514): Can't write: system_app_crash
E/DropBoxManagerService( 3514): java.io.FileNotFoundException: /data/system/dropbox/drop192.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3514): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3514): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3514): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3514): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3514): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3514): 	... 5 more
E/DropBoxManagerService( 3514): Can't write: system_app_crash
E/DropBoxManagerService( 3514): java.io.FileNotFoundException: /data/system/dropbox/drop193.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3514): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3514): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3514): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3514): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3514): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3514): 	... 5 more
D/ResourcesManager(11693): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
D/ResourcesManager(12255): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
D/ChimeraCfgMgr( 7834): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7834): Module APK com.google.android.play.games already loaded
D/UsbHostManager( 3514): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3514): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
E/SQLiteLog( 7834): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 7834): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 7834): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7834): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 7834): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7834): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 7834): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 7834): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 7834): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 7834): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7834): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 7834): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 7834): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7834): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7834): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7834): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 7834): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7834): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7834): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 7834): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7834): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7834): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7834): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 7834): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 7834): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 7834): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 7834): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 7834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7834): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 7834): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 7834): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 7834): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/EventHub( 3514): Removing device '/dev/input/event10' due to inotify event
E/SQLiteLog( 7834): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 7834): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 7834): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 7834): Process: com.google.android.gms, PID: 7834
E/AndroidRuntime( 7834): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 7834): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 7834): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 7834): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7834): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 7834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/MtpClient(12113): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
E/SQLiteLog(12129): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
D/MtpClient(12113): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,E/SQLiteDatabase(12129): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12129): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12129): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12129): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12129): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12129): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12129): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12129): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12129): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12129): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12129): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12129): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12129): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12129): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12129): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12129): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12129): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12129): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12129): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12129): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12129): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12129): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12129): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12129): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12129): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12129): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12129): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12129): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12129): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12129): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12129): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12129): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12129): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12129): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(12129): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12129): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12129): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12129): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12129): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12129): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12129): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12129): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12129): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12129): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12129): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12129): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12129): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12129): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12129): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12129): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12129): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12129): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12129): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12129): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12129): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12129): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12129): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12129): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12129): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12129): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12129): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12129): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12129): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12129): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12129): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12129): 	at aEV.a(Gelly,InjectorStore.java:130)
E/SQLiteOpenHelper(12129): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12129): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12129): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12129): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12129): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12129): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12129): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12129): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12129): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12129): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12129): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12129): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12129): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12129): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12129): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12129): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12129): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12129): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12129): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12129): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12129): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12129): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12129): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12129): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12129): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12129): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12129): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12129): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12129): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12129): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12129): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12129): Opened ClientFlag.db in read-only mode
E/SQLiteLog( 4252): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4252): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 4252): Shutting down VM
E/AndroidRuntime( 4252): FATAL EXCEPTION: main
E/AndroidRuntime( 4252): Process: com.google.android.gms.persistent, PID: 4252
E/AndroidRuntime( 4252): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4252): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4252): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4252): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4252): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4252): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4252): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4252): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4252): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4252): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4252): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4252): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4252): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4252): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4252): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4252): 	... 9 more
I/EventHub( 3514): Removing device '/dev/input/event7' due to inotify event
,E/SQLiteLog(12129): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(12129): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12129): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12129): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12129): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12129): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12129): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12129): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12129): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12129): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/AndroidRuntime(12129): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12129): Process: com.google.android.apps.docs, PID: 12129
E/AndroidRuntime(12129): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12129): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12129): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12129): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12129): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12129): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12129): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12129): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12129): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12129): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12129): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12129): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12129): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12129): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12129): 	at aFp.run(AbstractDatabaseInstance.java:471)
V/ApplicationPolicy( 3514): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
I/Process (11456): Sending signal. PID: 11456 SIG: 9
V/ApplicationPolicy( 3514): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
I/EventHub( 3514): Removing device '/dev/input/event8' due to inotify event
I/Process (12217): Sending signal. PID: 12217 SIG: 9
V/ApplicationPolicy( 3514): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
,E/DropBoxManagerService( 3514): Can't write: system_app_crash
E/DropBoxManagerService( 3514): java.io.FileNotFoundException: /data/system/dropbox/drop194.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3514): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3514): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3514): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3514): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3514): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3514): 	... 5 more
,E/SQLiteLog( 7834): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3514): Removing device '/dev/input/event9' due to inotify event
,E/SPPClientService(12255): ============PushLog. commonIsShipBuild. stop!
E/SQLiteLog(12255): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7834): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 7834): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7834): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 7834): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7834): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7834): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 7834): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7834): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PhenotypeInitializer( 7834): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 7834): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 7834): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 7834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 7834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 7834): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 7834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 7834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 7834): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 7834): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 7834): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 7834): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 7834): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 7834): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 7834): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 7834): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 7834): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 7834): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 7834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 7834): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 7834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase(12255): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase(12255): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12255): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12255): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12255): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12255): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12255): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12255): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12255): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12255): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12255): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12255): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12255): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12255): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12255): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12255): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase(12255): 	at com.sec.spp.push.notisvc.a,.b.a(Unknown Source)
E/SQLiteDatabase(12255): 	at com.sec.spp.push.notisvc.registration.n.b(Unknown Source)
E/SQLiteDatabase(12255): 	at com.sec.spp.push.notisvc.registration.n.a(Unknown Source)
E/SQLiteDatabase(12255): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase(12255): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase(12255): 	at com.sec.spp.push.notisvc.registration.i.handleMessage(Unknown Source)
E/SQLiteDatabase(12255): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12255): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12255): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12255): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12255): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12255): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12255): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/LNoti   (12255): [b] open fail. SQLException occured
E/DropBoxManagerService( 3514): Can't write: system_app_crash
E/DropBoxManagerService( 3514): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3514): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3514): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3514): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3514): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3514): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3514): 	... 5 more
E/SPPClientService(12255): [PushClientApplication] Push log off : This is Ship build version
,E/SQLiteLog(12129): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12129): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12129): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12129): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12129): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12129): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12129): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12129): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(12129): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(12129): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12129): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12129): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12129): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12129): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12129): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12129): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12129): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12129): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12129): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12129): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12129): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12129): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12129): 	at android.database.sql,ite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12129): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12129): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12129): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12129): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12129): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(12129): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(12129): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12129): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12129): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12129): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12129): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12129): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12129): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12129): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12129): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12129): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12129): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
W/SQLiteOpenHelper(12129): Opened ClientFlag.db in read-only mode
,D/SPPClientService(12255): PushLog.txt file is not deleted.
D/SPPClientService(12255): PushLog.txt file is not deleted.
D/SPPClientService(12255): ============PushLog. stop!
,E/SQLiteLog( 7834): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 7834): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 7834): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
I/EventHub( 3514): Removing device '/dev/input/event11' due to inotify event
,E/SharedPreferencesImpl( 7834): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/Zygote  (12293): MountEmulatedStorage()
E/Zygote  (12293): v2
I/libpersona(12293): KNOX_SDCARD checking this for 1000
I/libpersona(12293): KNOX_SDCARD not a persona
,I/SELinux (12293): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12293): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12293): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=12293 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/EventHub( 3514): Removing device '/dev/input/event12' due to inotify event
,I/Process ( 7834): Sending signal. PID: 7834 SIG: 9
,I/EventHub( 3514): Removing device '/dev/input/event13' due to inotify event
,W/ActivityManager( 3514): Process com.google.android.gms has crashed too many times: killing!
,I/ActivityManager( 3514): Killing 4252:com.google.android.gms.persistent/u0a14 (adj 0): crash
,E/DropBoxManagerService( 3514): Can't write: system_app_crash
E/DropBoxManagerService( 3514): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3514): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3514): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3514): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3514): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3514): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3514): 	... 5 more
,V/BackupManagerService( 3514): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService( 3514): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
,I/Process (12129): Sending signal. PID: 12129 SIG: 9
,D/TimaKeyStoreProvider(12293): TimaSignature is unavailable
,D/ActivityThread(12293): Added TimaKeyStore provider
,I/EventHub( 3514): Removing device '/dev/input/event14' due to inotify event
W/BroadcastQueue( 3514): Skipping deliver [background] BroadcastRecord{33a62a7c u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{425c950 12129 com.google.android.apps.docs/10101/u0 remote:29fc8313}: process crashing
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12310): MountEmulatedStorage()
I/libpersona(12310): KNOX_SDCARD checking this for 10042
E/Zygote  (12310): v2
I/libpersona(12310): KNOX_SDCARD not a persona
,I/SELinux (12310): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12310): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12310): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ConnectivityService( 3514): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@369a0f05)
,I/ActivityManager( 3514): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=12310 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,D/GpsStatusListenerHelper( 3514): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@130a1b5a
D/LocationManagerService( 3514): Location listener died
I/LocationManagerService( 3514): remove 2f4e8dbf by com.google.android.gms
,E/lowmemorykiller( 2829): Error writing /proc/12129/oom_score_adj; errno=22
D/LocationManagerService( 3514): Location listener died
D/WifiService( 3514): Client connection lost with reason: 4
,I/ActivityManager( 3514): Killing 11150:com.sec.android.fotaclient/u0a12 (adj 15): bgCount ##31
,D/LocationManagerService( 3514): provider request: passive ProviderRequest[ON interval=0],
D/ConnectivityService( 3514): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/LocationManagerService( 3514): remove 3d98ff44 by com.google.android.gms
E/ConnectivityService( 3514): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocationManagerService( 3514): provider request: passive ProviderRequest[ON interval=0]
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0

```
